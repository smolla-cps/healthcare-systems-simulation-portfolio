# Healthcare Systems Simulation Portfolio

A collection of **discrete-event simulation models built in FlexSim Healthcare** that illustrate patient flow, clinic operations, laboratory activities, healthcare resources, transportation, and multilevel facility movement. The repository includes guided examples, instructional models, and demonstration models organized by healthcare simulation topic.

## Portfolio Contents

| Folder | Models | Description |
|---|---:|---|
| [01 — FlexSim Healthcare Basic Guided Models](01-flexsim-healthcare-basic-guided-models/) | 6 | Progressive clinic models covering patient arrivals, healthcare activity sets, staff and treatment, medical equipment, A* navigation, staff tasks, and custom locations. |
| [02 — Healthcare Laboratory Simulation and Dashboard Visualization](02-healthcare-laboratory-simulation-and-dashboard-visualization/) | 3 | Patient laboratory workflows using general and patient process flows, plus a healthcare dashboard visualization example. |
| [03 — Healthcare Clinic Simulation Models](03-healthcare-clinic-simulation-models/) | 2 | Two healthcare clinic models for examining facility layout, resources, and configured simulation logic. |
| [04 — Healthcare Patient Relocation Simulation](04-healthcare-patient-relocation-simulation/) | 1 | Patient relocation workflow demonstrating ambulance use in a healthcare simulation. |
| [05 — Multifloor Healthcare Simulation](05-multifloor-healthcare-simulation/) | 1 | Two-floor healthcare facility with elevator travel, gurney transport, a patient companion, and floor-visibility controls. |

**Total:** 13 native FlexSim (`.fsm`) models across five topics.

## Simulation Topics

- **Patient flow:** Patient arrivals, registration, waiting, care pathways, and movement between locations.
- **Clinical resources:** Nurses, physicians, technicians, exam rooms, medical equipment, and transportation resources.
- **Process Flow:** Healthcare activity sets, general process flows, patient process flows, and staff tasks.
- **Facility navigation:** A* pathfinding, barriers, patient transport, ambulances, and movement between floors.
- **Operational visualization:** Simulation dashboards and model-data displays.

## Repository Structure

```text
healthcare-systems-simulation-portfolio/
├── 01-flexsim-healthcare-basic-guided-models/
├── 02-healthcare-laboratory-simulation-and-dashboard-visualization/
├── 03-healthcare-clinic-simulation-models/
├── 04-healthcare-patient-relocation-simulation/
├── 05-multifloor-healthcare-simulation/
└── README.md
```

Each topic folder contains the relevant `.fsm` file(s), its own `README.md`, and a `REQUIREMENTS.md` file with software and usage notes. The guided models folder also includes the `ER_small.dwg` floor plan.

## Software and How to Explore the Models

The models require **FlexSim** with access to **FlexSim Healthcare** objects and Process Flow features. The uploaded files contain saved-version identifiers from FlexSim **25.2, 26.0, and 27.0**, depending on the model. See each folder's `REQUIREMENTS.md` for its version information and any supporting files.

1. Open the topic folder and review its `README.md` and `REQUIREMENTS.md`.
2. Download the relevant `.fsm` model and any supporting floor-plan file in that folder.
3. Open the model in a compatible version of FlexSim.
4. Inspect the 3D layout, process flows, resource settings, and dashboards where provided.
5. Reset and run the simulation to explore the configured behavior.

**Note:** These files illustrate modeling approaches and workflows. Results and performance comparisons should only be reported after checking model inputs and running suitable simulation experiments.

## Sources and Model Context

Several models follow FlexSim Healthcare tutorials or instructional demonstrations. The multifloor companion model is based on an Autodesk Community example. Original instructional sources include:

- [FlexSim Healthcare Tutorial — Autodesk/FlexSim Documentation](https://docs.flexsim.com/en/26.0/Tutorials/FlexSimHC/OverviewFlexSimHC/OverviewFlexSimHC.html)
- [Multi-floor HC Demo Model with Companion — Autodesk Community](https://forums.autodesk.com/t5/flexsim-knowledge-base/multi-floor-hc-demo-model-w-companion/ta-p/13552433)

The folder documentation describes what each model illustrates; it does not imply that every demonstration originated as an independent research project.
