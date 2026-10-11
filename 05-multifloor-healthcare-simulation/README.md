# Multifloor Healthcare Simulation with Patient Companion

## Overview

This FlexSim Healthcare demonstration represents a **two-floor healthcare facility** connected by an elevator. Patients move between rooms and floors on a **gurney**, and each patient has a **companion** who follows throughout the care process. A dashboard includes two checkboxes for showing or hiding the visual representation of each floor.

The model illustrates how a healthcare simulation can represent inter-floor movement, patient transportation, and people accompanying patients.

## Simulation Features

### 1. Two-Floor Healthcare Layout

The facility has two floors connected by an elevator. The model provides a setting for observing patient movement within and between floors.

### 2. Patient Transport with a Gurney

Patients are moved on a gurney between different rooms and across floors. This demonstrates patient transportation as part of a healthcare workflow.

### 3. Patient Companion

Each patient has a constant companion who follows the patient throughout their care process. This feature demonstrates how additional people can be associated with individual patients in a healthcare model.

### 4. Floor Visibility Dashboard

The dashboard has two checkboxes that control the visibility of the different floors. This helps with inspecting the model visually while the simulation is running.

## Model File

| File | Description |
| --- | --- |
| `multifloor-healthcare-with-companion.fsm` | Two-floor healthcare demonstration with elevator, gurney transport, companions, and floor visibility controls. |

## Recommended Folder Structure

```text
05-multifloor-healthcare-simulation/
├── README.md
├── REQUIREMENTS.md
└── multifloor-healthcare-with-companion.fsm
```

## Opening and Exploring the Model

1. Open the `.fsm` file in a compatible version of FlexSim with Healthcare modeling functionality.
2. Inspect the 3D layout to identify the two floors and the elevator.
3. Reset and run the simulation.
4. Observe patients moving between rooms and floors using a gurney, together with their companions.
5. Use the dashboard's two checkboxes to change which floor visuals are displayed.
6. Explore the model's logic and resource configurations in FlexSim if you want to understand how its movements and companion behavior are implemented.

See [`REQUIREMENTS.md`](REQUIREMENTS.md) for software and compatibility notes.

## Scope and Model Notes

This is an existing FlexSim Healthcare **community demonstration model**. Its documented features concern the layout, patient transport, patient companions, and visualization controls. No measured throughput, waiting-time improvements, or validated operational performance are claimed here.

The model file reports a **FlexSim 27.0** saved-version header. The `2023` label in the originally distributed filename should not be taken as its current saved version.

## Reference

Autodesk Community, FlexSim Knowledge Base, *Multi-floor HC Demo Model w/ Companion* (community-contributed demonstration):

https://forums.autodesk.com/t5/flexsim-knowledge-base/multi-floor-hc-demo-model-w-companion/ta-p/13552433
