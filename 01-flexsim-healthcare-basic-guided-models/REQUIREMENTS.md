# Requirements — FlexSim Healthcare Fundamentals

## Software

- **FlexSim simulation software** with access to the Healthcare (HC) / People modeling objects and Process Flow tools.
- **Model file version:** The six supplied `.fsm` files contain FlexSim version **25.2** in their file headers.
- **Recommended:** Use FlexSim 25.2 to open these saved models, or test them in a newer compatible release. Compatibility with other versions has not been verified.
- **Operating system:** A computer capable of running the chosen FlexSim release. Check Autodesk/FlexSim documentation for the version-specific supported operating system and hardware requirements.

No Python environment, Python packages, or `pip` installation is required for these native FlexSim `.fsm` models.

## Required Files

Keep the following files accessible:

```text
01-flexsim-healthcare-fundamentals/
├── README.md
├── REQUIREMENTS.md
├── ER_small.dwg
├── 1.1-use-an-activity-set.fsm
├── 1.2-add-staff.fsm
├── 1.3-add-transport-and-equipment.fsm
├── 1.4-add-astar-navigation.fsm
├── 1.5-independent-staff-tasks.fsm
└── 1.6-custom-location-object.fsm
```

`ER_small.dwg` is the clinic floor-plan drawing supplied with the tutorial. The `.fsm` files contain the FlexSim simulation models. You only need to open the particular `.fsm` file you want to inspect or run.

## How to Open and Run

1. Install and launch a compatible version of FlexSim.
2. Open one of the `.fsm` models through **File → Open**.
3. If the floor plan is missing, locate the model's floor-plan/background properties and reconnect the reference to `ER_small.dwg`.
4. Inspect the **3D model** and its associated **Process Flow** views.
5. **Reset** the model before a new run, set the desired run duration, and click **Run**.
6. Review the 3D animation and any available model charts or statistics.

## Notes

- The six tutorial models represent successive development stages, not six separate healthcare facilities.
- Model logic, distributions, and activity settings can differ between tutorial stages.
- These files have not been executed or functionally tested in FlexSim as part of preparing this documentation; results and compatibility should be verified in the application.

## Documentation

FlexSim Healthcare official tutorial:
https://docs.flexsim.com/en/26.0/Tutorials/FlexSimHC/OverviewFlexSimHC/OverviewFlexSimHC.html
