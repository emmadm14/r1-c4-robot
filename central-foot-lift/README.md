# Central-Foot Lift System

The central-foot lift is one of the main mechanical subsystems of R1-C4 and plays an essential role in the 2-3-2 transformation.

Its purpose is to vertically deploy and retract the central foot, allowing the robot to transition between its upright configuration and its three-wheel driving configuration.

## System Principle

The lift mechanism moves the central foot vertically inside the robot chassis.

During the transition to the three-wheel configuration, the central foot is lowered until it reaches the ground. When the robot returns to its upright configuration, the foot is retracted inside the body.

The system therefore had to provide:

- Controlled vertical motion
- Sufficient mechanical stability
- Compact integration inside the chassis
- Reliable guidance of the moving assembly
- Support for the loads transmitted through the central foot

## First Development Phase

The first functional version of the lift used a belt-driven transmission to generate the vertical movement of the central foot.

This prototype successfully demonstrated that the foot could be extended and retracted in both directions.

However, testing also highlighted several limitations.

The initial guiding solution had been adapted to reduce the space occupied inside the robot, but this resulted in insufficient mechanical stability.

The mechanism was also relatively bulky compared with the available space inside R1-C4.

These observations led to a complete redesign of the central-foot lift.

Images and demonstration videos of this first functional prototype are available in the corresponding development folders.

## Redesigned Lift System

The redesigned system was developed to improve compactness, guidance and mechanical stability.

The current architecture uses two linear guides to control the vertical motion of the lift carriage and reduce unwanted movement.

The central foot is attached to this moving carriage, which travels vertically inside the chassis.

The redesign also required the development of several dedicated mechanical components, including:

- Central-foot lift carriage
- Front linear-guide assembly
- Rear linear-guide assembly
- Lift motor mounting bracket
- Linear-motion stop
- Central foot
- Structural supports and interfaces

## Mechanical Design Choices

Several parts of the redesigned lift were reinforced using ribs.

The objective was to increase stiffness and resistance to deformation in mechanically loaded areas while avoiding unnecessary material and mass.

This approach was particularly useful for the 3D-printed structural components supporting the lift and guiding systems.

The geometry of the different parts was also designed to remain compact enough for integration within the limited internal volume of R1-C4.

## Central-Foot Mobility

The central foot is equipped with flanged-mount ball transfer units underneath its base.

These allow the foot to remain in contact with the ground while rolling freely as the robot moves in its three-wheel configuration.

This provides multidirectional ground support without requiring a dedicated steering mechanism for the central foot.

## CAD Assembly

The complete lift mechanism was modelled in Fusion 360.

Mechanical joints were added to the assembly to reproduce the vertical movement of the central foot and verify the motion of the mechanism before physical integration.

Two STEP assemblies are provided to represent the extreme positions of the system:

- `R1-C4 - Central-foot-assembly-retracted.step`
- `R1-C4 - Central-foot-assembly-extended.step`

The STEP files contain the mechanical geometry of the system, while the CAD animation demonstrates the continuous motion between these two positions.

The motor mounting bracket is included in the assembly, although the motor itself is not represented in the CAD model.

## CAD Files

The `mechanical/cad-parts/` folder contains the individual components designed for the redesigned central-foot lift.

The CAD models are provided in STEP format to allow easy visualisation and compatibility with different CAD software.

## CAD Animations

The `mechanical/cad-animation/` folder contains animations generated from the Fusion 360 assembly.

These animations show:

- The vertical motion of the central-foot lift
- The integration of the mechanism within the robot chassis

They complement the STEP models by illustrating the actual kinematic behaviour of the assembly.

## Prototype Tests

Videos of the first development phase demonstrate the extension and retraction of the original central-foot mechanism.

These tests confirmed the operating principle of the lift before the system was redesigned to improve its compactness and mechanical stability.

## Manufacturing

The structural components of the redesigned lift are manufactured primarily using FDM 3D printing in PETG.

The parts are produced using Prusa MK4 and Prusa XL printers depending on their dimensions.

Specific printing parameters are adapted according to the geometry and mechanical function of each component.