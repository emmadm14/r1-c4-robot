# Head and Turret System

The head and turret system is responsible for the visual interaction and orientation functions of R1-C4.

During the first development year, the rotating head, facial recognition and user-tracking functions were developed and integrated into the prototype.

The mechanical design of the head and most of the initial vision and tracking implementation were mainly developed by **Vladimir Grigoriev**.

## System Principle

The objective of the system is to allow R1-C4 to detect and recognise a user, then rotate its head in order to follow the user's movement.

The system combines:

- Camera-based user detection
- Facial recognition
- Real-time target tracking
- Head rotation control

The vision processing is handled by the main computing platform, while correction commands are sent to the embedded controller responsible for actuating the turret.

## Vision and Tracking

The first version of the vision system included:

- LBPH facial recognition
- CSRT real-time tracking
- Kalman filtering for motion prediction

Once a user is detected and recognised, the tracking algorithm follows their movement and generates correction commands to orient the head.

## Head Rotation

The turret is driven by a stepper motor controlled through a TMC2209 driver.

This allows the head to rotate independently from the robot body and follow the detected user.

## First Development Phase

During the first development year, the system was successfully tested with facial recognition and head tracking.

The available demonstration video shows the robot recognising **Vladimir Grigoriev** and rotating the head in order to follow his movement.

This first implementation validated the general principle of the vision and turret-control system.

## Current Development

During the second development year, the existing head architecture is being retained while several elements are being updated.

The current work includes:

- Reorganising the electronics inside the head
- Adapting the facial-recognition data for a new user
- Improving the integration of the vision system with the rest of the robot
- Preparing the head system for future autonomous behaviours

The mechanical geometry of the head itself is not being redesigned as part of the current development work.

## Documentation

The `videos/` folder contains demonstrations of the first facial-recognition and head-tracking implementation.

Additional software and electronics documentation will be added as the head/turret system continues to evolve.