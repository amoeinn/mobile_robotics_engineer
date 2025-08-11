# ROS 2 URDF Assignment – Mobile Robotics Engineer

## Task Overview
This project includes:
- A 3-DOF robotic arm with correct transform trees
- Visual and joint enhancements
- A mobile manipulator robot
- Ackerman drive model
- Debugging a wheeled robot with a lifting mechanism

## How to View
1. Source your ROS 2 workspace:
   ```bash
   source install/setup.bash
   ```

2. Launch with:
   ```bash
   ros2 launch module_1_assignment view_robot_launch.py
   ```

3. Update `view_robot_launch.py` with the correct URDF file to test different robots.

## Notes
- Joints include revolute, prismatic, and continuous types
- Visuals are minimal and use simple link structure
- Wheels are round and suitable for simulation
