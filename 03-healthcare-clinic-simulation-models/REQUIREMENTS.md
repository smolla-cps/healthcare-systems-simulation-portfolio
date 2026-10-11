# Requirements — Healthcare Clinic Simulation Models

## Software

- **FlexSim**, with the Healthcare (HC) objects and Process Flow tools available.
- **Saved model version:** Both provided `.fsm` files contain a **FlexSim 26.0** header. FlexSim 26.0 is the safest first version to try. Operation in older or newer versions has not been verified.
- **Operating system:** A computer able to run the selected FlexSim version; consult its official system requirements for supported Windows versions and graphics requirements.
- **Python packages:** None required to open these native `.fsm` files.

## Required Files

Keep these files directly in the same folder:

```text
03-healthcare-clinic-simulation-models/
├── README.md
├── REQUIREMENTS.md
├── clinic-simulation-demonstration.fsm
└── healthcare-clinic-simulation.fsm
```

| File | Purpose |
| --- | --- |
| `clinic-simulation-demonstration.fsm` | Healthcare clinic demonstration model |
| `healthcare-clinic-simulation.fsm` | Healthcare clinic simulation model |

No additional external dependencies have been confirmed from the available model metadata. If FlexSim reports a missing floor plan, image, or other linked asset, locate and provide the original asset before using the model.

## Opening and Running

1. Start FlexSim and open the intended `.fsm` file.
2. Switch to the Healthcare environment if it is not already selected.
3. Verify that the 3D model, Process Flow logic, and any linked resources load correctly.
4. Reset the simulation and run it, observing its behavior.
5. Inspect model statistics, charts, and dashboards if configured.
6. Save changes to a separate working copy to preserve the original model.

## Compatibility and Validation

- A saved-version header indicates the FlexSim version written in the model file; it is **not** proof that the model has been successfully executed or validated in that version.
- Verify model logic, input assumptions, simulation settings, and results inside FlexSim before citing quantitative performance claims.
- The `.fsm` files are binary FlexSim models and cannot be executed directly in GitHub or Google Colab.
