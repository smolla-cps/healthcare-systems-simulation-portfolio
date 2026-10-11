# FlexSim Healthcare Fundamentals

This tutorial series introduces healthcare discrete-event simulation using **FlexSim Healthcare (HC)**. The models represent a walk-in healthcare clinic in which patients arrive, register, wait, receive clinical care, and leave. Six progressively developed models demonstrate patient-flow logic, healthcare staff and resource allocation, equipment and transport, navigation, staff scheduling, and custom locations.

## Learning Objectives

- Model patient arrivals and movement through a healthcare facility using FlexSim Healthcare 3D objects and Process Flow activities.
- Build patient workflows using reusable healthcare activity sets.
- Assign and manage nurses, physicians, technicians, examination rooms, and other resources through object groups.
- Represent clinical treatment alternatives, medical equipment, and wheelchair-assisted patient transport.
- Configure A* navigation so patients and staff move around barriers and obstacles.
- Add independent staff activities, room maintenance, resource priorities, and work schedules.
- Create and configure a custom meeting location for staff consultation.

## Tutorial Models

### 1.1 — Use an Activity Set

**File:** `1.1-use-an-activity-set.fsm`

Introduces the FlexSim Healthcare environment, clinic floor plan, healthcare locations, and patient process flows. Patients are created through an arrivals flow, enter the clinic, sign in at a kiosk, and proceed to the waiting area. The model uses **Walk then Process** activity sets to control patient movement and location use.

**Topics:** Healthcare 3D objects, clinic entrance, kiosk registration, waiting-room multi-locations, Arrivals flow, Patient Flow, activity sets.

### 1.2 — Add Staff

**File:** `1.2-add-staff.fsm`

Extends the patient journey by adding examination tables, a scale, a nurse station, nurses (RNs), and physicians (MDs). Staff and locations are organized into resource groups. Patients are escorted for weighing and placement in examination rooms, examined by a physician, and guided toward departure. The workflow also includes consultation between staff members.

**Topics:** Staff groups, examination-room groups, resource acquisition and release, **Escort then Process**, **Process with Staff**, **Two Staff Meet**, and **Escort to Exit** activity sets.

### 1.3 — Add Transport and Equipment Objects

**File:** `1.3-add-transport-and-equipment.fsm`

Adds two alternative treatment tracks: an **EKG** procedure using portable equipment brought to the patient, and an **X-ray** procedure involving wheelchair transport to and from the radiology location. The model introduces technicians, transport and equipment groups, treatment-selection logic, a revised patient arrival schedule, and charts.

**Topics:** Medical equipment, wheelchairs, technicians, treatment routing, equipment movement and return, patient transport, scheduled arrivals, and simulation charts.

### 1.4 — Add A* Navigation

**File:** `1.4-add-astar-navigation.fsm`

Adds A* navigation grids and dividers to represent travel boundaries, walls, and obstacles. Healthcare objects and staff are connected to the navigation system, and travel thresholds are adjusted to help prevent unrealistic travel through walls or equipment.

**Topics:** A* grids, dividers, navigation members, travel paths, and travel thresholds.

### 1.5 — Create Independent Staff Tasks

**File:** `1.5-independent-staff-tasks.fsm`

Extends the model beyond patient-related activities by representing tasks that consume staff time independently of a particular patient. Examples include cleaning examination rooms after use and responding to phone calls. The model also demonstrates resource-task priorities, shift schedules, off-duty periods, and breaks.

**Topics:** Examination-room maintenance, independent Process Flow tasks, task priorities and preemption, resource availability, and staff timetables.

### 1.6 — Add a Custom Location Object

**File:** `1.6-custom-location-object.fsm`

Introduces a custom staff meeting location for clinical consultation. The tutorial builds a **MeetingPlace** object and defines role-specific entry instructions, positions, orientations, and animations for two staff members meeting at that location.

**Topics:** Custom healthcare locations, enter instructions, staff roles, animation, and consultation behavior.

## Patient Workflow

The tutorial develops a clinic workflow broadly organized as follows:

```text
Patient arrival
      ↓
Kiosk sign-in
      ↓
Waiting room
      ↓
RN-assisted weighing
      ↓
Examination-room placement
      ↓
Physician examination
      ↓
Treatment pathway (EKG or X-ray)
      ↓
Staff consultation
      ↓
Escort to exit
```

Later models add navigation, staff tasks, scheduling, and a custom consultation location. The workflow is a conceptual summary of the progressively developed tutorial rather than a claim that each earlier model includes every stage.

## Model Files and Floor Plan

The six `.fsm` files are saved at successive stages of the tutorial. Open the file matching the task you want to explore; the later stages build upon concepts introduced earlier.

The supplied `ER_small.dwg` file is a clinic floor-plan asset used in the tutorial. If FlexSim cannot locate the drawing after the model is moved to a different computer, update the floor-plan file reference in the model.

See [REQUIREMENTS.md](REQUIREMENTS.md) for software requirements and run instructions.

## Reference

**FlexSim Healthcare Tutorial — Official Documentation:**
https://docs.flexsim.com/en/26.0/Tutorials/FlexSimHC/OverviewFlexSimHC/OverviewFlexSimHC.html

The model sequence follows the six tasks in this tutorial. Tutorial documentation and model files should be distinguished from any separately developed healthcare simulation research or experiments.
