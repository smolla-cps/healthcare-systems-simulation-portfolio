# Requirements — Healthcare Laboratory Simulation and Dashboard Visualization

## Software Requirements

- **FlexSim**, including its **Healthcare / People** modeling objects and **Process Flow** functionality.
- **Saved model version:** FlexSim **26.0**, as indicated by the headers of all three supplied `.fsm` files.
- **Recommended version for opening:** FlexSim 26.0. Opening the files in another version may require compatibility checks.
- **Operating system and hardware:** Follow the requirements for the FlexSim version you install.

These are native FlexSim simulation files. **No Python installation or Python packages are required.**

## Required Files

```text
02-healthcare-laboratory-simulation-and-dashboard-visualization/
├── README.md
├── REQUIREMENTS.md
├── healthcare-dashboard-visualization.fsm
├── patient-laboratory-general-process-flow.fsm
└── patient-laboratory-patient-process-flow.fsm
```

Each `.fsm` file is opened as a separate model. No additional CAD or external data file has been confirmed as a required dependency; check for missing file references if FlexSim reports any when a model opens.

## How to Open and Run

1. Install and launch a compatible version of FlexSim.
2. Use **File → Open** and select one of the `.fsm` files.
3. Inspect the healthcare objects, Process Flow activities, and any dashboard views.
4. Select **Reset** and then **Run**; adjust the run stop time only if needed for your review.
5. For the laboratory examples, compare their general and patient process-flow structures.
6. For the dashboard example, view the charts and indicators supplied by the model.

## Compatibility and Verification

- Preserve the original model files before saving them in a newer FlexSim release.
- The saved model version was read from the file headers; **the models have not been executed or tested in FlexSim** as part of preparing this documentation.
- Specific charts, numerical results, and operational outcomes should be verified from actual simulation runs before reporting them.
- GitHub can host `.fsm` files, but it cannot run or preview a FlexSim simulation directly.
