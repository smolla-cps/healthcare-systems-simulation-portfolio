# Healthcare Patient Workflows and Dashboards — FlexSim Models

This folder groups four FlexSim Healthcare models that address dashboard visualization, patient relocation, and laboratory workflows. The two laboratory examples approach the topic through different Process Flow structures: a general process flow and a patient process flow.

## Models Covered

### 1. Healthcare Dashboard Visualization

**File:** `healthcare-dashboard-visualization.fsm`

Introduces dashboard-based visualization within a healthcare simulation. Dashboards can be used to review model-generated information and examine operations during or after a run. The specific charts and measured values should be checked in FlexSim before drawing conclusions.

**Focus:** Dashboard setup and visualization of simulated healthcare operations.

### 2. Patient Relocation Workflow

**File:** `patient-relocation-workflow.fsm`

Demonstrates patient relocation in a FlexSim Healthcare model. The example provides a basis for examining how patient movement is represented and coordinated with simulation logic.

**Focus:** Patient movement between healthcare locations and relocation-related process logic.

### 3. Patient Laboratory — General Process Flow

**File:** `patient-laboratory-general-process-flow.fsm`

Presents a patient laboratory example using a **general process flow** to organize the relevant modeling activities. General process flows can coordinate activities outside an individual patient's dedicated flow.

**Focus:** Modeling laboratory operations using general-purpose Process Flow logic.

### 4. Patient Laboratory — Patient Process Flow

**File:** `patient-laboratory-patient-process-flow.fsm`

Presents the patient laboratory topic through a **patient process flow**, where activities are organized around the patient-specific flow.

**Focus:** Modeling laboratory operations within a patient-oriented workflow.

## Comparing the Laboratory Models

| Model | Process Flow approach | What to examine |
| --- | --- | --- |
| Patient Laboratory — General Process Flow | General process flow | How laboratory-related activities are coordinated in the general flow |
| Patient Laboratory — Patient Process Flow | Patient process flow | How laboratory-related activities are organized around the patient |

These are two examples of process-flow organization. Their specific activities, parameters, and outcomes should be compared in the FlexSim application rather than assumed to be identical.

## Recommended Folder Structure

```text
02-healthcare-patient-workflows-and-dashboards/
├── README.md
├── REQUIREMENTS.md
├── healthcare-dashboard-visualization.fsm
├── patient-relocation-workflow.fsm
├── patient-laboratory-general-process-flow.fsm
└── patient-laboratory-patient-process-flow.fsm
```

## Opening and Exploring the Models

1. Open the selected `.fsm` file in a compatible FlexSim version.
2. Inspect its 3D view, model objects, and relevant Process Flow tabs.
3. Review patient movement and resource interactions where applicable.
4. Reset and run the model to observe its behavior.
5. Inspect the dashboard or compare the two laboratory flows as appropriate.

For software and compatibility information, see [REQUIREMENTS.md](REQUIREMENTS.md).

## Source and Scope

The original model files are associated with the **FlexSim Healthcare Instructional Video Series**. This folder presents the examples by topic. Numerical performance findings are not included because they have not been verified from executed simulation runs.
