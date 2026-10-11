# Healthcare Clinic Simulation Models

This folder contains two FlexSim Healthcare (HC) models centered on clinic simulation: a healthcare clinic demonstration and a second healthcare clinic simulation model. Both are provided as native FlexSim (`.fsm`) files.

## Models

### 1. Healthcare Clinic Demonstration

**File:** `clinic-simulation-demonstration.fsm`

A FlexSim Healthcare clinic demonstration model. It can be used to examine how a clinic is represented in a 3D simulation environment and to explore the model's configured objects and process logic.

**Suggested inspection in FlexSim:** Review the patient flow, location resources, staff assignments, and any data outputs actually configured in the model. The precise settings and performance results should be verified in FlexSim before documenting them.

### 2. Healthcare Clinic Simulation

**File:** `healthcare-clinic-simulation.fsm`

A second FlexSim Healthcare clinic model. It is kept separately from the six numbered fundamentals models so that its configuration can be explored and compared with those incremental examples.

**Suggested inspection in FlexSim:** Open the model, identify its patient and general process flows, inspect configured clinic resources, and compare its contents against the step-by-step models in `01-flexsim-healthcare-fundamentals`.

**Compatibility note:** Both supplied files have a FlexSim **26.0** saved-version header; successful execution has not been verified.

## Folder Contents

```text
03-healthcare-clinic-simulation-models/
├── README.md
├── REQUIREMENTS.md
├── clinic-simulation-demonstration.fsm
└── healthcare-clinic-simulation.fsm
```

## How to Use the Models

1. Install FlexSim with access to its Healthcare modeling objects and Process Flow tools.
2. Open either `.fsm` file in FlexSim.
3. Inspect the 3D layout, Process Flow tabs, resource groups, and configured logic.
4. Reset and run the model; check for missing external assets, errors, or unexpected behavior.
5. Review available statistics and dashboards, if present. Do not treat any output as a validated result without reviewing model assumptions and settings.

See [REQUIREMENTS.md](REQUIREMENTS.md) for software and compatibility notes.

## Scope

These files provide clinic simulation examples. Their detailed process logic and quantitative results should be confirmed by opening and running them in FlexSim.
