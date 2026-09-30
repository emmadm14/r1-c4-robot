# 2-3-2 Transformation System

The 2-3-2 transformation system is one of the main mechanical subsystems of R1-C4.

Its purpose is to allow the robot to transition between an upright two-leg configuration and a three-wheel configuration by controlling the inclination of the body and coordinating this movement with the deployment of the central foot.

## System Principle

The transformation is based on two complementary mechanical functions:

- Tilting the robot body using a linear actuator and lever mechanism
- Deploying the central foot through the dedicated lift system

During the transition, the body progressively tilts while the central foot moves into position, allowing the robot to adopt a more stable three-wheel configuration for movement.

The 2-3-2 mechanism therefore plays an important role in both the posture and mobility of R1-C4.

## Mechanical Design

The body inclination mechanism uses a linear actuator connected to a lever arm.

The motion of the actuator is converted into a controlled rotation of the robot body, allowing it to move between its upright and inclined positions.

The design had to take into account several constraints:

- Available space inside the chassis
- Required inclination angle (32°)
- Load distribution
- Mechanical stability
- Integration with the central-foot lift system
- Strength of the supporting parts

## Development

The first version of the 2-3-2 mechanism was developed during the first year of the project and validated as part of the initial R1-C4 prototype.

During the second development year, the system is being refined to improve its mechanical integration, reliability and compatibility with the redesigned chassis and central-foot lift.

The current design uses a dedicated linear actuator support and lever arm to control the inclination of the robot body.

## CAD Files

The `mechanical/cad-parts/` folder contains the individual CAD parts designed for the 2-3-2 system.

These files include components such as:

- Linear actuator mount
- Linear actuator lever arm

The CAD models are provided in STEP format to allow easy visualisation, modification and reuse in different CAD software.

## Future Assembly Model

A complete CAD assembly of the 2-3-2 mechanism will be added once the current version of the system has been fully integrated with the linear actuator and surrounding mechanical components.