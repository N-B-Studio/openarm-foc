Planned Hardware
6 DOF robot arm
Optional 1 DOF gripper
Optional dexterous hand
ODrive Mini / custom G431 FOC driver
STM32H7 main controller
STM32G431 motor/control nodes
3D-printed links and actuator housings
Software Goals
LeRobot-compatible robot interface
Joint state streaming
Action command interface
Dataset recording
Teleoperation tools
ROS2 / URDF / MoveIt support
Python SDK
Roadmap
Phase 1: Minimal Working Arm
 6DOF mechanical design
 ODrive-based FOC joint control
 CAN joint command protocol
 Basic Python control script
Phase 2: LeRobot Compatibility
 Implement LeRobot robot interface
 Dataset recording
 Leader-follower teleoperation
 Camera + joint synchronized logging
Phase 3: Force Feedback
 Torque/current feedback
 Leader arm feedback
 Gripper force feedback
Phase 4: Dexterous Hand
 Tendon-driven hand
 G431 servo board
 LeRobot-compatible hand actions
License

Hardware: CERN-OHL-S v2 or CERN-OHL-P v2
Software: Apache-2.0
Documentation: CC-BY-4.0
