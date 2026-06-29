# Autonomous Rover

## Overview

Autonomous Rover is a ROS2-based mobile robot developed for autonomous navigation and obstacle detection in indoor environments. The system integrates LiDAR sensing, custom ROS2 interfaces, navigation modules, and microcontroller-based motor control to enable autonomous movement on a physical rover platform.

The project was deployed on real hardware and tested using LiDAR-based environment perception and autonomous navigation capabilities.

---

## Features

* ROS2-based modular architecture
* LiDAR integration for environment sensing
* Autonomous navigation
* Obstacle detection and avoidance
* Custom ROS2 message interfaces
* Physical rover deployment
* RViz visualization and debugging
* micro-ROS communication with onboard microcontroller

---

## System Architecture

LiDAR Sensor
↓
ROS2 Driver Node
↓
Navigation Stack
↓
Navigation Controller
↓
micro-ROS Agent
↓
ESP32 Microcontroller
↓
Motor Driver
↓
DC Motors

---

## Hardware Components

* ESP32 Microcontroller
* LiDAR Sensor
* Motor Driver Module
* DC Gear Motors
* Battery Pack
* Rover Chassis

---

## Software Stack

* ROS2
* Ubuntu Linux
* RViz
* micro-ROS
* Custom ROS2 Packages

---

## Repository Structure

```text
warehouse_navigation/       Navigation and control modules
warehouse_scanning/         Sensor and scanning functionalities
warehouse_robot_bringup/    Launch and system startup configurations
warehouse_msgs/             Custom ROS2 message definitions
sllidar_ros2/              LiDAR driver package
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Asparsix/Autonomous-Rover.git
cd Autonomous-Rover
```

Build the workspace:

```bash
colcon build
source install/setup.bash
```

---


## Demonstration

The rover was tested on physical hardware with LiDAR-based sensing and autonomous navigation.

### Capabilities Demonstrated

* Autonomous movement
* Obstacle detection
* Real-time sensor visualization
* ROS2 communication across multiple nodes
* Physical deployment and testing

---

## Challenges Faced

* LiDAR integration and calibration
* ROS2 node communication
* Real-time motor control
* Navigation parameter tuning
* Hardware-software integration
* Physical robot testing and debugging

---

## Future Improvements

* Sensor fusion using IMU and wheel odometry
* Enhanced localization
* Advanced path planning
---


