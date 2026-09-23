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
├── model/          # Cameo model files and model notes
├── diagrams/       # Exported SysML diagrams for browser viewing
└── docs/           # Architecture, requirements, verification, and project documentation
```

## Current Development

This repository represents an active work in progress. The model and supporting documentation will continue to evolve as the architecture, verification approach, simulation behavior, and physical design mature.

Planned repository updates include:

- Exported recruiter-viewable SysML diagrams
- Current Cameo `.mdzip` model
- Requirements and verification documentation
- System architecture overview
- Hardware and integration documentation

## Notes

The native Cameo model requires compatible Dassault Systèmes / Cameo software to open. Key engineering artifacts will also be exported to standard formats so the project can be reviewed without Cameo.
