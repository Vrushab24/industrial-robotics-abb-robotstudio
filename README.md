# Industrial Robotics Simulation Using ABB RobotStudio

## Overview

This project was completed as a group assignment as part of the MSc Robotics programme at Cranfield University during the 2023–2024 academic year.

The project involved the design, programming and simulation of two industrial robotic systems using ABB RobotStudio 2023:

1. An automotive engine block deburring system
2. An aeroengine case assembly system

The project explored industrial robot selection, machine vision, end-effector design, workstation development, robot programming and robotic process simulation.

---

## Project Objectives

The main objectives of the project were:

- Select suitable industrial robots for the proposed manufacturing applications.
- Design and integrate suitable end-effectors and workstation components.
- Investigate machine vision for quality inspection in the deburring process.
- Develop the proposed robotic workcells in ABB RobotStudio.
- Create robot targets, paths and programming for the required operations.
- Simulate the proposed manufacturing workflows.

---

## Project 1 – Automotive Engine Deburring

An ABB IRB 2400 was selected for the automotive engine deburring application.

The simulated workstation consisted of:

- ABB IRB 2400 industrial robot
- Automotive engine block and stand
- Deburring end-effector
- Machine vision camera
- Robot controller and workstation components

The CAD model of the end-effector was integrated into ABB RobotStudio and configured as a robot tool.

### Workflow

The proposed workflow involved:

1. Positioning the robot and engine block within the workstation.
2. Creating the required robot targets and paths.
3. Performing the simulated deburring operation.
4. Using machine vision as a quality-control step after deburring.
5. Repeating the deburring and inspection process if additional burrs were identified.

---

## Machine Vision System

Machine vision was investigated as a quality-control method for checking whether burrs remained after the deburring process.

Several Cognex vision systems were compared based on factors including:

- Scan rate
- Weight
- Resolution
- Integration with the robotic system
- Software requirements

The project selected the **COGNEX-DS1100** for the proposed deburring application based on the comparison carried out in the report.

---

## Project 2 – Aeroengine Case Assembly

The second robotic system focused on the assembly of an aeroengine casing.

Two ABB robots were selected:

- **ABB IRB 6640** – handling the upper and lower engine cases
- **ABB IRB 120** – nut and bolt assembly

The simulated workstation included:

- Upper and lower engine cases
- Rotating base
- Gripper
- Nut and bolt sorter
- Nut conveyor
- Bolt conveyor
- ABB IRB 6640
- ABB IRB 120

### Workflow

The proposed assembly process involved:

1. Picking and placing the upper and lower engine cases.
2. Positioning the cases on the rotating base.
3. Supplying nuts and bolts through the sorting and conveyor system.
4. Using the ABB IRB 120 for nut and bolt pick-and-place operations.
5. Creating robot targets and paths for the assembly process.
6. Repeating the operation for the required assembly positions.

---

## End-Effector and CAD Design

The project included CAD-based design and integration of components required for the robotic workcells.

The design work included:

- Deburring end-effector
- Machine vision camera mount
- Aeroengine case gripper
- Rotating base
- Nut and bolt end-effector
- Conveyor components
- Supporting workstation components

CAD models were integrated into ABB RobotStudio to evaluate their positioning and interaction with the robotic workcells.

---

## Robot Programming and Simulation

The robotic systems were programmed and simulated using **ABB RobotStudio 2023**.

The project involved:

- Robot target creation
- Path creation
- Tool configuration
- Robot movement
- Pick-and-place operations
- RAPID programming
- Workstation configuration
- Simulation of the proposed manufacturing processes

The RAPID program contained information relating to targets, paths, zones, speeds and instruction templates for the simulated tasks.

---

## Results

The project successfully produced simulated robotic workcells for both proposed applications.

### Automotive Deburring

The simulation demonstrated the proposed deburring workflow together with a machine-vision inspection process.

### Aeroengine Assembly

The simulation demonstrated robotic handling of the engine cases and nut-and-bolt assembly.

For the aeroengine assembly task, the report documented that **46 of the required 48 nuts and bolts were successfully configured for placement**. The remaining two could not be configured correctly due to constraints within the program.

---

## Potential Implementation Challenges

The project also considered issues that could arise when moving from simulation toward a real industrial implementation.

These included:

- Robot path accuracy
- Workpiece positioning
- Tool positioning
- Robot singularities
- Workstation interference
- End-effector design
- Robot programming limitations
- Error handling
- Differences between simulated and real-world robot behaviour

These considerations highlighted the importance of further debugging, testing and validation before physical implementation.

---

## Technologies and Tools

- **ABB RobotStudio 2023**
- **RAPID Programming**
- **SolidWorks 2020**
- **Machine Vision**
- **Industrial Robotics**
- **CAD**
- **Robotic Process Simulation**
- **End-Effector Design**

---

## My Contribution

This was a group project, and responsibilities were divided among the team members.

My documented contribution included:

- Researching industrial robot selection.
- Researching potential issues during practical implementation.
- Assisting with Part B programming in ABB RobotStudio.
- Contributing to the robot-selection section of the report.
- Contributing to the system-workflow section of the report.
- Contributing to the potential-implementation-issues section of the report.

I was not solely responsible for all components of the project; the different areas were distributed among the group members.

---

## Team

This project was completed as a four-member MSc Robotics group assignment at Cranfield University.

- **Vrushab Sawant**
- **Sarthak Agarwal**
- **Sakshi Chavan**
- **Mohan Shanmugavel**

---

## Project Information

**Programme:** MSc Robotics  
**Institution:** Cranfield University  
**Academic Year:** 2023–2024  
**Project Type:** Group Assignment  
**Primary Simulation Software:** ABB RobotStudio 2023

---

## Documentation

The repository contains a portfolio version of the original academic project documentation.

The original university submission was completed as a group assignment. This repository presents a condensed version of the project for portfolio and learning purposes.

---

## Note

This project was an academic simulation project and was not a physical industrial deployment.

The results described in this repository relate to the simulated robotic systems developed during the assignment.
