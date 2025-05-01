# Progressing the simulation

To move the simulation forward to the next phase, copy the contents of the appropriate YAML file from the `_data/Yaml_phases` folder and overwrite the `_data/map.yaml` file. Commit the changes and reload the website. This will remove the previous phase's events and populate the map with the events from the next phase. It might take the new events a few moments to load.

# Red Team injected scenarios

The Red Team should also create two or more pop-up events during each phase. The participants on the Blue Team should include responses to these injections in their reports for each phase.

To create a pop-up event and display it on the map, edit the `_data/map.yaml` file by pasting an event at the bottom using the following template:
   ```
   - name: "EVENT NAME"
    description: EVENT DESCRIPTION
    latitude: LATITUDE AS A FLOAT
    longitude: LONGITUTE AS A FLOAT
    url: "EVENT URL"
   ```
Here is an example:
   ```
   - name: "My Simulation Event"
    description: This is a description of the event.
    latitude: 37.229572
    longitude: -80.413940
    url: "https://zombo.com/"
   ```

# Reports through giscus comments

## Phase Reports
To submit an individual report summarizing your response to a new phase, use the comments section at the bottom of the phase's page in the Scenarios tab. This will require you to create a GitHub account. Once you have an account, click in the text box to start writing.
Give your report a title using the '#' markdown character. For example:
   ```
   # Title of my Report

   Text of my report.
   ```
When you click on the Preview tab in the comment box, your title should be bolded.
Phase reports should be titled using the following format: `MY POSITION: Response to Phase PHASE NUMBER`. For example, `University President: Response to Phase 1`.
## Red Team injection reports
To submit a report in response to a Red Team event, create your report as a comment using the same format as above. This should also be a comment on the page for the phase the event is part of. To differentiate the Red Team injection reports from the phase reports, title them as follows: `MY POSITION: Response to INJECTION NAME`. For example, `University President: Response to Industrial Accident at the Water Treatment Plant`.
