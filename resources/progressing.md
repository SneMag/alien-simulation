---
title: Progressing the Simulation
layout: page
parent: Resources
nav_order: 4
---

# Progressing the Simulation

## Populating the Map
To move the simulation forward to the next phase, copy the contents of the appropriate YAML file from the `_data/Yaml_phases` folder and overwrite the `_data/map.yaml` file. Commit the changes and reload the website. This will remove the previous phase's events and populate the map with the events from the next phase. It might take the new events a few moments to load.

## Current Phase in Scenarios
To update the current phase, modify line 10 of `scenarios` > `index.md` to reflect the correct phase number. Once the simulation progresses forward, uncomment the new phase's description (also in `index.md`). To uncomment, remove the comment characters on either end of the paragraph, like so:
```
    Commented (hidden):
    <!--- ### Phase 1: Initial Infection 
    Description text. --!>
    
    Uncommented (showing):
    ### Phase 1: Initial Infection 
    Description text.
```
