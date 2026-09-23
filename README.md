# TARS Digital Twin Robotic System

**Status:** Active Development (Aug 2026–Present)  
**Focus:** Model-Based Systems Engineering (MBSE), SysML, digital twin architecture, multidisciplinary system integration

## Project Overview

TARS is a systems engineering project focused on developing a digital twin architecture for a robotic system. The project uses SysML and MBSE practices to connect requirements, system architecture, behavior, interfaces, analysis, and verification across the robot's major subsystems.

The system model is being developed in Cameo Systems Modeler and incorporates computing, sensing, mobility, controls, power, user interface, and mechanical design considerations.

## Systems Engineering Scope

Current work includes:

- Requirements development and requirements-to-test traceability
- System and subsystem architecture
- Functional decomposition and interface definition
- Behavioral modeling and operational state logic
- Digital twin architecture and simulation
- Parametric analysis for mission energy
- Verification planning and test relationships
- Multidisciplinary hardware/software integration

## Key Modeling Artifacts

The current SysML model includes:

- Block Definition Diagrams (BDD)
- Internal Block Diagrams (IBD)
- Activity Diagrams
- State Machine Diagrams
- Sequence Diagrams
- Parametric Diagrams
- Requirements and verification relationships

The state model includes normal operating behavior, controller pairing, digital twin synchronization, SafeStop behavior, maintenance, and fault-response logic.

### Featured Architecture View

The logical architecture below shows the top-level TARS decomposition and major subsystem relationships.

![TARS Logical Architecture](./diagrams/BDD-LA-01%20TARS%20Logical%20Architecture.jpg)

[Open full-size logical architecture diagram](./diagrams/BDD-LA-01%20TARS%20Logical%20Architecture.jpg)

### Featured Behavioral View

The operational state model below shows how TARS transitions through normal operating modes, synchronization and pairing behavior, SafeStop, maintenance, and fault-response conditions.

![TARS Operational States](./diagrams/STM-01%20TARS%20Operational%20States.jpg)

[Open full-size operational states diagram](./diagrams/STM-01%20TARS%20Operational%20States.jpg)

### Featured Interaction View

The demonstration-mission sequence model shows time-ordered interactions between participating system elements during mission execution.

![Execute Demonstration Mission](./diagrams/SEQ-01%20Execute%20Demonstration%20Mission.jpg)

[Open full-size demonstration mission sequence diagram](./diagrams/SEQ-01%20Execute%20Demonstration%20Mission.jpg)

## Parametric Analysis

A mission-energy model evaluates relationships among:

- Battery voltage
- Battery capacity
- Conversion efficiency
- Average power
- Mission duration
- Usable energy
- Required energy
- Energy margin

This analysis supports design decisions related to power availability and mission-duration requirements.

![Mission Energy Analysis](./diagrams/PAR-01%20Mission%20Energy%20Analysis.jpg)

[Open full-size mission energy analysis diagram](./diagrams/PAR-01%20Mission%20Energy%20Analysis.jpg)

## Verification & Traceability

The verification plan links system requirements to planned verification activities, supporting traceability from requirements through verification.

![TARS Verification Plan](./diagrams/VER-01%20TARS%20Verification%20Plan.jpg)

[Open full-size verification plan](./diagrams/VER-01%20TARS%20Verification%20Plan.jpg)

## Tools & Technologies

- Cameo Systems Modeler / MagicDraw
- SysML
- MATLAB
- Fusion 360
- Git / GitHub

## My Contributions

My work on TARS includes:

- Developing and refining SysML architecture and behavioral models
- Defining requirements, subsystem relationships, and verification traceability
- Building and troubleshooting state-machine simulation behavior
- Developing parametric mission-energy analysis
- Integrating computing, sensing, control, power, user-interface, and mechanical design considerations
- Supporting physical component selection and mechanical integration

## Repository Structure

```text
TARS-Digital-Twin/
├── README.md
├── model/          # Native Cameo source model
├── diagrams/       # Exported SysML diagrams for browser viewing
└── docs/           # Architecture, requirements, verification, and project documentation
```

## Current Development

This repository represents an active work in progress. The model and supporting documentation will continue to evolve as the architecture, verification approach, simulation behavior, and physical design mature.

Current native model:

- [`TARS_SysML_Master.mdzip`](./model/TARS_SysML_Master.mdzip)

Planned repository updates include:

- Exported recruiter-viewable SysML diagrams
- Requirements and verification documentation
- System architecture overview
- Hardware and integration documentation

## Notes

The native Cameo model requires compatible Dassault Systèmes / Cameo software to open. Key engineering artifacts will also be exported to standard formats so the project can be reviewed without Cameo.
