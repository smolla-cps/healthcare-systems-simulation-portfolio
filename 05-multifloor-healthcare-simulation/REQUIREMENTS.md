# Requirements — Multifloor Healthcare Simulation

## Software

- **FlexSim** with access to its Healthcare modeling objects and process flows.
- **Saved model version:** FlexSim **27.0**, as indicated by the uploaded `.fsm` file header.
- Use FlexSim 27.0 to open the model when available. Compatibility with other versions has not been verified.
- A Windows system capable of running the chosen FlexSim version, according to FlexSim's installation requirements.

No Python environment or Python package installation is needed to open the native FlexSim model.

## Required File

| File | Purpose |
| --- | --- |
| `multifloor-healthcare-with-companion.fsm` | Main two-floor healthcare simulation model. |

Keep the `.fsm` file alongside `README.md` and `REQUIREMENTS.md` in `05-multifloor-healthcare-simulation/`.

The supplied Autodesk Community documentation does **not** identify any required external CAD, dataset, or other input file for this model. This does not independently establish that all assets are embedded; check for missing-resource prompts when opening the model.

## How to Open and Run

1. Install and launch a compatible FlexSim version.
2. Open `multifloor-healthcare-with-companion.fsm`.
3. Check whether FlexSim reports any missing dependencies or conversion warnings.
4. Inspect the two-floor 3D layout and the elevator.
5. Reset and run the model.
6. Observe gurney movement and companions following patients.
7. Find the dashboard and use its two checkboxes to show or hide the floor visuals.

## Verification Checklist

- [ ] Model opens without missing-file or conversion errors.
- [ ] Both floors and the elevator are visible.
- [ ] Patient movement between rooms and across floors can be observed.
- [ ] Companions follow their associated patients.
- [ ] Both floor-visibility dashboard checkboxes work.

The uploaded file's saved version was inspected, but the simulation was **not executed or behaviorally validated** in this environment. The checklist is intended for verification within FlexSim.

## Source

Autodesk Community, *Multi-floor HC Demo Model w/ Companion*:

https://forums.autodesk.com/t5/flexsim-knowledge-base/multi-floor-hc-demo-model-w-companion/ta-p/13552433
