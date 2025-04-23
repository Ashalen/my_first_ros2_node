# My First ROS 2 Node

This repository contains my first ROS 2 node, implemented in Python. The node logs a message to the console every second.

## Features
- A simple ROS 2 node that publishes a log message every second.
- Demonstrates the use of timers in ROS 2.

## Requirements
- ROS 2 Humble (or compatible version)
- Python 3.10 or later

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/username/my_first_ros2_node.git

2. Build the package:
   ```bash
   cd ~/ros2_ws
   colcon build --packages-select my_robot_controller

3.Source the workspace:
   ```bash
      source ~/ros2_ws/install/setup.bash
