# Requirements — Healthcare Patient Workflows and Dashboards

## Software

- **FlexSim** with support for **Healthcare (HC) / People objects** and **Process Flow**.
- **Saved file version:** The four supplied models were identified as saved in **FlexSim 26.0**.
- **Recommended starting version:** FlexSim 26.0. Compatibility with other FlexSim releases should be tested before resaving a model.
- **Operating system and computer specifications:** Follow the installation requirements of the selected FlexSim version.

These are native `.fsm` files, so **Python and `pip` packages are not required** to open them.

## Required Model Files

```text
02-healthcare-patient-workflows-and-dashboards/
├── README.md
├── REQUIREMENTS.md
├── healthcare-dashboard-visualization.fsm
├── patient-relocation-workflow.fsm
├── patient-laboratory-general-process-flow.fsm
└── patient-laboratory-patient-process-flow.fsm
```

No external CAD drawing or separate data file has been confirmed as a required dependency from the supplied information. If FlexSim reports missing assets, inspect the affected model's background, object, and file references.

## Opening and Running

1. Open FlexSim and select **File → Open**.
2. Choose one of the `.fsm` files.
3. Review the 3D view and any Process Flow or dashboard tabs.
4. Check the model's settings, objects, and process logic before editing.
5. Use **Reset**, set the appropriate stop time if needed, and select **Run**.
6. Inspect the relevant patient movements, laboratory flows, or dashboard displays.
7. Open the two laboratory models separately when comparing their flow structures.

## Version and Validation Notes

- Keep an unchanged copy before opening and saving models in a newer FlexSim version.
- The original uploads and names were available for review, but the models were **not executed or functionally validated** in FlexSim for this documentation.
- No unverified throughput, utilization, waiting-time, or performance improvement claims are made.
- GitHub may store `.fsm` files, but viewing and running them requires an installed, compatible FlexSim application.
