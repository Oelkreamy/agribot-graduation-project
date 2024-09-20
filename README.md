# Seed Sowing Mobile Robot

## Project Overview

The **Seed Sowing Robot** automates the process of seed sowing, providing a more efficient alternative to manual agricultural methods. This robot, developed using ROS (Robot Operating System) and embedded systems, is designed to autonomously plant seeds while integrating soil preparation and irrigation systems.

## Features

- **Autonomous Seed Sowing**: Implements efficient path planning, localization, and navigation algorithms.
- **Mechanical Design**: Custom chassis, auger, and drill system designed for precise and efficient seed placement.
- **Electrical System**: Uses Arduino, Raspberry Pi, and ESP32 for controlling motors and sensors.
- **Simulation**: Tested and validated in Gazebo using ROS for navigation and seed sowing operations.
- **ROS Integration**: Utilizes ROS for mapping, navigation, and sensor data processing.

## Key Components

### Mechanical Components
- **Chassis**: Holds the robot's frame, supporting motors and sensors.
- **Auger**: A drill for precise seed planting.
- **Wheels and Motors**: 4 DC motors for driving and 3 servo motors for seed planting and soil covering.

### Electrical Components
- **Raspberry Pi 4 Model B**
- **Arduino Mega**
- **ESP32 Microcontroller**
- **LiDAR Sensor** for environment mapping and obstacle detection.
- **12V DC Motors** with gearboxes for navigation.
- **Sensors** for moisture, level, and environmental monitoring.

### Software Components
- **ROS Nodes** for controlling robot navigation, seed planting, and sensor data processing.
- **SLAM (Simultaneous Localization and Mapping)** for real-time mapping and navigation.
- **Gazebo Simulation** for testing robot performance in a simulated environment.
- **Sensor Fusion** to integrate data from various sensors for accurate navigation and planting.

## Project Objectives

- Automate seed sowing to reduce manual labor and increase agricultural efficiency.
- Design and implement a robot capable of autonomous navigation, seed sowing, and soil management.
- Use ROS for software control and Gazebo for simulation and testing.

## Hardware Setup

1. **Assemble the Chassis**: Install the motors, auger, and other mechanical components.
2. **Electrical Wiring**: Connect Raspberry Pi, Arduino, ESP32, and other electronic components.
3. **Install Sensors**: Attach LiDAR, moisture, and level sensors.
4. **Motor Setup**: Configure the motors for driving and drilling.

## Software Setup

1. Install **Ubuntu 20.04** and **ROS Noetic** on the Raspberry Pi.
2. Set up the ROS workspace with required packages for navigation, mapping, and control.
3. Use **Gazebo** for simulation, testing robot performance in virtual environments.
4. Implement **sensor fusion** to integrate data from LiDAR, IMU, and other sensors.

### Prerequisites

- **Ubuntu 20.04**
- **ROS Noetic**
- **Gazebo**
- **Arduino IDE**

### Contributors

- **Omar Ashraf Abdelmawgoud**
- **Khaled Abdelnasser Elshamndy**
- **Assem Yasser Mohamed Elsharbeiny**
- **Mohamed Ahmed Mohamed Khater**
- **Mohamed Kamal Ali Ahmedr**
