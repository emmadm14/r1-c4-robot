# Chassis

The chassis is the main structural element of R1-C4 and provides the mechanical support required to integrate the robot's different subsystems.

Its design evolved significantly throughout the project, from an initial wooden prototype to a fully redesigned PETG structure intended to improve rigidity, precision, modularity and ease of manufacturing.

## Design References and Scaling

The initial dimensions of R1-C4 were defined using reference measurements from the R2 Builders community.

These dimensions were adapted to the approximately 3/5 scale selected for the project in order to preserve the general proportions of an R2-D2-inspired robot while remaining compatible with the available manufacturing resources and internal components.

The first chassis was based on wooden construction plans inspired by Mike Senna's R2-D2 designs.

These references provided a useful starting point for establishing the overall geometry and internal organisation of the robot.

## Wooden Prototype

The first chassis was manufactured in wood and used during the initial development phase.

This structure made it possible to validate:

- The general dimensions of the robot
- The integration of the first mechanical subsystems
- The 2-3-2 transformation mechanism
- The first central-foot lift system
- The available internal space for electronics and actuators

Although functional as a prototype, the wooden chassis presented several limitations.

In particular, the structure lacked sufficient dimensional precision and mechanical rigidity for the more advanced stages of the project.

Its construction also made modifications and part replacement more difficult.

These limitations motivated a complete redesign of the chassis.

## PETG Chassis Redesign

The new chassis was fully redesigned in CAD and manufactured using PETG through FDM 3D printing.

The objective was to obtain a structure that was:

- More rigid
- More dimensionally accurate
- Easier to reproduce
- Easier to modify
- Better suited for integrating the different mechanical systems
- More modular for future development

Two main CAD approaches were explored:

- A complete one-piece chassis model
- A modular version divided into several printable sections

The modular version was selected to make manufacturing easier and to allow individual sections to be modified or replaced without reprinting the entire chassis.

## Modular Architecture

The final chassis design is divided into five main sections.

These parts are assembled together to form the complete structure while preserving the overall geometry of the robot.

This modular approach provides several advantages:

- Reduced risk of large-print failure
- Easier manufacturing on available printers
- Easier replacement of damaged parts
- Greater flexibility for future modifications
- Reduced material waste when only one section requires redesign

The complete assembled chassis is available in the `mechanical/assembly/` folder, while the five individual sections are provided in `mechanical/cad-parts/`.

## Manufacturing

The structural chassis parts are manufactured in PETG using Prusa MK4 and Prusa XL 3D printers.

The printer is selected according to the dimensions of each component.

For the main structural parts, reinforced printing parameters were used to improve stiffness and mechanical strength, including:

- 6 perimeters
- 40% gyroid infill
- Reinforced top and bottom layers

The printing parameters were adapted depending on the geometry and mechanical role of each section.

This manufacturing strategy was selected to provide a stronger and more reliable structure than the initial wooden prototype.

## Images

The `images/` folder documents the evolution of the chassis.

It currently includes photographs of the original wooden prototype used during the first development phase.

Additional images of the redesigned PETG chassis will be added as manufacturing and assembly progress.