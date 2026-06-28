# OpenArm-FOC

OpenArm-FOC is an open-source, 3D-printable, torque-controlled robotic arm platform designed for VLA, imitation learning, teleoperation, and dexterous manipulation research.

The goal is to bring low-cost FOC/CAN servo robotics into the Hugging Face LeRobot ecosystem.

## Key Features

- 3D-printable robot arm
- FOC / torque-control capable actuators
- CAN / CAN-FD distributed control
- Leader-follower teleoperation
- Compatible with LeRobot-style datasets and APIs
- Designed for VLA, ACT, Diffusion Policy, and imitation learning
- Modular gripper / dexterous hand interface
- Target BOM: under USD $500 depending on component choice

## Why

SO-101 is a great low-cost entry platform for LeRobot.  
OpenArm-FOC aims to provide a higher-performance alternative with better actuator feedback, torque control, smoother motion, and future force-feedback support.

## System Architecture

```text
Camera
  |
LeRobot / VLA Policy
  |
PC / ROS2 / Python API
  |
H7 Robot Brain
  |
CAN / CAN-FD
  |
FOC Servo Nodes
  |
6DOF Arm + Gripper / Dexterous Hand
```

## License

Hardware: CERN-OHL-S v2 or CERN-OHL-P v2
Software: Apache-2.0
Documentation: CC-BY-4.0
