# Phase 1 requirements - Robotic Arm Project requirements 
## Project Objective
Design and build a functional robotic arm while learning CAD, mechanical design, programming, electronics, and robotics
## Primary goal
The robotic arm should be able to move objects from one location to another using controlled joints.

## Initial Design Goals

- Multiple degrees of freedom
- Controlled movement of each joint
- Stable base
- Lightweight but strong structure
- Programmable movement
- Ability to pick up and move small objects
- Modular design so components can be replaced or improved

## Skills I Want to Develop

- Onshape CAD
- Mechanical design
- Kinematics
- Python programming
- Electronics
- Motors and motor control
- Sensors
- 3D printing
- Engineering documentation
- Testing and iteration

## Constraints

Budget: TBD

Maximum size: TBD

Maximum payload: TBD

Power source: TBD

Number of joints: TBD

## Success Criteria

The project will be considered successful when the completed arm can:

1. Move each joint independently.
2. Move to programmed positions.
3. Pick up a small object.
4. Move the object to another location.
5. Repeat the movement reliably.

## Current Status

Phase 1 — Requirements

# Phase 1 — Robotic Arm Architecture

## Initial Design

The robotic arm will use 5 degrees of freedom plus a gripper.

## Degrees of Freedom

1. Base rotation — rotates the arm left and right.
2. Shoulder — raises and lowers the main arm.
3. Elbow — extends and folds the arm.
4. Wrist pitch — tilts the end effector up and down.
5. Wrist rotation — rotates the end effector.
6. Gripper — opens and closes to hold objects.

## Initial Targets

- Reach: approximately 18–24 inches
- Payload: approximately 0.5–1 pound
- Programmable movement
- 3D-printed structural components
- Modular construction
- Functional gripper

## Design Goal

The arm should be capable of picking up a small object, moving it to another location, and placing it accurately.

## Status

Initial architecture selected. Dimensions and components will be determined during the next design stage.
# Phase 1 — Initial Dimensions

## Baseline Geometry

| Component | Target Dimension |
|---|---:|
| Base diameter | 6 in |
| Base height | 4 in |
| Upper arm | 10 in |
| Forearm | 10 in |
| Wrist assembly | 3 in |
| Gripper | 3–4 in |
| Maximum reach | Approximately 23–25 in |

## Payload Target

Initial target payload: 0.5 lb

## Design Considerations

The dimensions are preliminary and may change after calculating joint torque requirements and selecting motors.

The arm will be designed around the capabilities of the selected motors rather than assuming the motors can handle the initial dimensions.

## Status

Initial dimensions established. Motor selection and torque calculations are the next major engineering step.

# Phase 1 — Initial Dimensions

## Baseline Geometry

| Component | Target Dimension |
|---|---:|
| Base diameter | 6 in |
| Base height | 4 in |
| Upper arm | 10 in |
| Forearm | 10 in |
| Wrist assembly | 3 in |
| Gripper | 3–4 in |
| Maximum reach | Approximately 23–25 in |

## Payload Target

Initial target payload: 0.5 lb

## Design Considerations

The dimensions are preliminary and may change after calculating joint torque requirements and selecting motors.

The arm will be designed around the capabilities of the selected motors rather than assuming the motors can handle the initial dimensions.

## Status

Initial dimensions established. Motor selection and torque calculations are the next major engineering step.

# Phase 1 — Preliminary Torque Requirements

## Purpose

Determine the torque requirements for the robotic arm before selecting motors.

## Current Design Parameters

- Upper arm length: 10 in
- Forearm length: 10 in
- Target payload: 0.5 lb
- Initial safety factor: 2×

## Important Variables

The final torque requirements depend on:

- Weight of the upper arm
- Weight of the forearm
- Weight of the wrist assembly
- Weight of the gripper
- Payload weight
- Distance of each mass from the joint
- Acceleration
- Friction
- Mechanical losses

## Design Approach

Motor selection will be based on calculated torque requirements rather than selecting motors first and designing around them.

The torque calculations will be updated after estimating the weight of each component.

## Status

Preliminary torque requirements established. Component mass estimates are the next step.
# Phase 1 — Construction Method

## Construction Approach

The robotic arm will use a hybrid construction method combining 3D-printed components with metal hardware and mechanical components.

## 3D-Printed Components

The following components are planned to be 3D printed:

- Upper arm structure
- Forearm structure
- Joint housings
- Motor mounts
- Wrist components
- Gripper components
- Supporting brackets

## Mechanical Hardware

The design will use:

- Screws and bolts
- Nuts
- Bearings
- Shafts or metal rods
- Washers and spacers

## Design Priorities

The structure will be designed to balance:

1. Strength
2. Weight
3. Ease of manufacturing
4. Cost
5. Ease of modification

## Manufacturing Strategy

Parts will initially be designed for 3D printing. Prototype parts will be tested before final versions are produced.

If a component proves too weak, it will be redesigned or reinforced.

## Status

Initial construction method selected. Material specifications and manufacturing requirements will be refined during CAD development.

# Phase 1 — Joint Architecture

## Overview

The robotic arm will use five primary rotational degrees of freedom plus a gripper actuator.

## Joint Layout

### J1 — Base Rotation
Rotates the entire arm around a vertical axis.

### J2 — Shoulder
Raises and lowers the upper arm.

### J3 — Elbow
Raises and lowers the forearm relative to the upper arm.

### J4 — Wrist Pitch
Tilts the end effector upward and downward.

### J5 — Wrist Rotation
Rotates the end effector around the forearm axis.

### Gripper
Opens and closes to hold objects.

## Modular Joint Design

Each powered joint will be designed as a modular assembly consisting of:

- Actuator
- Motor mount
- Joint housing
- Bearings
- Shaft or mechanical connection
- Arm link

The modular approach will allow individual components to be replaced or redesigned without requiring the entire robotic arm to be redesigned.

## Engineering Priorities

- Minimize unnecessary weight
- Provide adequate structural strength
- Reduce joint friction
- Provide adequate torque
- Make components replaceable
- Design for manufacturability
- Allow future upgrades

## Status

Joint architecture established. Ready to begin detailed mechanical CAD design.

## Status 

Created and separated base and arm link 1 components 
Added 20 mm pivot hole to arm link 1
Created ShoulderRevoluteJoint.
Joint axis: X-axis.
Base is grounded.
Arm Link 1 rotates freely around the pivot.
Verified the joint using Fusion 360’s Drive Joints tool.


