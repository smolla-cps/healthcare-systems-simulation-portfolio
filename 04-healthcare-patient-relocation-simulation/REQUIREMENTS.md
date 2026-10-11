# Requirements — Healthcare Patient Relocation Simulation

## Software

- **FlexSim** with Healthcare modeling objects and Process Flow capabilities.
- **Saved model version:** FlexSim **26.0** (identified from the uploaded `.fsm` file header).
- A compatible installation capable of opening `.fsm` model files. Opening the model in other versions has not been tested here.

No Python installation or `pip` dependencies are required to open this native FlexSim model.

## Required Files

Keep these files in the same folder:

```text
04-healthcare-patient-relocation-simulation/
├── README.md
├── REQUIREMENTS.md
└── patient-relocation-workflow.fsm
```

The `.fsm` file is the simulation model. The Markdown files provide supporting information; they are not runtime dependencies.

## How to Run

1. Open FlexSim and load `patient-relocation-workflow.fsm`.
2. Check the 3D layout and any Process Flow tabs for missing references or model warnings.
3. Click **Reset** before running a new simulation.
4. Click **Run** and observe the patient relocation workflow and ambulance use.
5. Review the model's own statistics, if configured, before drawing conclusions.

## Compatibility and Verification

- The file header identifies version **26.0**; this does not establish a minimum compatible version.
- The model was not executed in FlexSim as part of preparing these documents, so successful execution and any simulation results are not independently verified.
- If a missing linked asset or external reference warning appears, resolve it in FlexSim before reporting model output.
- If FlexSim prompts you to update the file to a newer version, save a separate copy to preserve the original.
