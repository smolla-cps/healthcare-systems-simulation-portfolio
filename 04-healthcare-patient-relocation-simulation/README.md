# Healthcare Patient Relocation Simulation

## Overview

Patient relocation is an important part of healthcare operations when patients need to move between locations during care. This FlexSim Healthcare model provides a focused example for exploring a patient-relocation workflow and how patient movement can be represented in a discrete-event simulation.

The project uses a native FlexSim model (`.fsm`). The uploaded file identifies FlexSim 26.0 as its saved version.

## Model

### Patient Relocation Workflow

**File:** `patient-relocation-workflow.fsm`

This model focuses on patient relocation within a simulated healthcare setting. It can be opened in FlexSim to inspect the 3D layout and the configured flow logic, observe patient movement, and examine how relocations are represented in the simulation.

The exact movement rules, destination selection, staff assignments, and performance measures should be checked in the running model before being reported as confirmed features or results.

## Modeling Topics

- Patient movement between healthcare locations
- Representation of healthcare operations through discrete-event simulation
- Inspecting patient and resource behavior in FlexSim Healthcare
- Reviewing the relationship between model layout and flow logic

## Folder Structure

```text
04-healthcare-patient-relocation-simulation/
├── README.md
├── REQUIREMENTS.md
└── patient-relocation-workflow.fsm
```

## Opening the Model

1. Install and launch a compatible version of FlexSim with its Healthcare modeling tools.
2. Open `patient-relocation-workflow.fsm` using **File > Open**.
3. Review the 3D model, its process flows, and relevant object properties.
4. Reset the model, run the simulation, and observe the patient relocation workflow.
5. Verify any model statistics or dashboard results directly in FlexSim before publishing them.

See [REQUIREMENTS.md](REQUIREMENTS.md) for software information and compatibility notes.

## Scope

This repository folder contains a healthcare simulation model for demonstration and exploration. It does not include verified experimental comparisons, measured improvements, or a validated clinical case study.
