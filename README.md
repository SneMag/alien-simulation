# Progressing the simulation

To move the simulation forward to the next phase, copy the contents of the appropriate YAML file from the `_data/Yaml_phases` folder and overwrite the `_data/map.yaml` file. Commit the changes and reload the website. This will remove the previous phase's events and populate the map with the events from the next phase. It might take the new events a few moments to load.

# Red Team injected scenarios

The Red Team should also create two or more pop-up events during each phase. The participants on the Blue Team should include responses to these injections in their reports for each phase.

To create a pop-up event and display it on the map, edit the `_data/map.yaml` file by pasting an event at the bottom using the following template:
   `
   - name: "EVENT NAME"
    description: EVENT DESCRIPTION
    latitude: LATITUDE AS A FLOAT
    longitude: LONGITUTE AS A FLOAT
    url: "EVENT URL"
   `
Here is an example:
   `
   - name: "My Simulation Event"
    description: This is a description of the event.
    latitude: 37.229572
    longitude: -80.413940
    url: "(https://zombo.com/)"
   `

# Reports through giscus
