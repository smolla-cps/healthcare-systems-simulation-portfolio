# Requirements — FlexSim Healthcare Specialized Models

## Software

- **FlexSim simulation software** with access to Healthcare (HC) / People objects and the Process Flow tools.
- **Saved model version:** All four uploaded `.fsm` files have **FlexSim 26.0** in their file headers.
- **Recommended version:** FlexSim 26.0. Opening the models in another release may require compatibility checks; other versions have not been tested here.
- **Operating system and hardware:** Follow the requirements for the version of FlexSim being installed.

These are native FlexSim model files. **No Python installation, `requirements.txt`, or `pip` packages are required** simply to open these models.

## Required Files

```text
02-flexsim-healthcare-specialized-models/
├── README.md
├── REQUIREMENTS.md
├── healthcare-dashboards.fsm
├── patient-relocation.fsm
├── patient-labs-general-process-flow.fsm
└── patient-labs-patient-process-flow.fsm
```

No separate CAD floor-plan or other supporting file has been established as a required dependency for these four models from the files supplied. If FlexSim reports a missing external resource, check the model's object, background, or asset references and restore the original source file.

## How to Open and Run

1. Start a compatible release of **FlexSim**.
2. Select **File → Open** and choose an `.fsm` model.
3. Locate the **3D view** and any **Process Flow** tabs associated with the model.
4. Examine model settings, patient/staff resources, activity logic, and routing before modifying the model.
5. Click **Reset**, configure the intended run time, and click **Run**.
6. For the dashboard model, open the available dashboard views and inspect the displayed metrics.
7. For the two laboratory examples, open the files separately and compare the process-flow structure and patient behavior.

## Verification Notes

- The uploaded models were inspected as files to confirm their presence and saved-version header. They have **not** been run or functionally validated in the FlexSim application during documentation preparation.
- Model-specific parameters, resource counts, statistical results, and performance comparisons have not been independently verified.
- If a newer FlexSim version prompts for model conversion, preserve an unchanged copy before saving the converted model.
