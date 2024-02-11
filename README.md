# Transformer Drone Project

## Overview
This project aims to develop a transformer drone, characterized by its innovative design that includes 8 servos (2 on each arm), Electronic Speed Controllers (ESCs), Electric Ducted Fans (EDFs), Printed Circuit Board (PCB), and a Pixhawk flight controller. The ultimate goal is to achieve autonomous flight capabilities, enabling the drone to perform complex maneuvers, transformations, and tasks without human intervention.

## Features
- **Transformer Design**: Utilizes 8 servos for transformation mechanisms, enhancing mobility and versatility.
- **Flight Components**: Incorporates ESCs and EDFs for precise control and powerful thrust.
- **Control System**: Employs a Pixhawk flight controller for advanced flight modes and stability.
- **Prototype Board**: Integrates custom circuits and components, facilitating unique functionalities and experimentation.

## Hardware Requirements
- 8x Servo Motors
- ESCs compatible with EDFs
- Electric Ducted Fans (EDFs)
- Printed Circuit Board (PCB)
- Pixhawk Flight Controller
- Power Supply/Battery Pack
- LiDar Camera
- Jetson Nano
- Arduino Nano Sense
- Bunch of Sensors
- Miscellaneous: wires, connectors, mounting brackets, etc.

## Software Requirements
- PX4 or ArduPilot firmware for the Pixhawk
- Custom software for control algorithms 
- Ground Control Software (e.g., QGroundControl) or Mission Planner

## Setup Instructions
1. **Assembly**: Start by mounting the servos onto each arm of the drone. Follow this by installing the ESCs and connecting them to the EDFs. Ensure all mechanical connections are secure.
2. **Wiring**: Connect the ESCs to the Pixhawk according to the flight controller's documentation. Ensure power distribution is correctly set up from the battery to the ESCs and Pixhawk (Using a Power Distribution Board).
3. **Flight Controller Setup**: Install the PX4 or ArduPilot firmware on the Pixhawk. Configure the basic settings using a ground control software like QGroundControl.
4. **Testing**: Perform initial tests to ensure all components are functioning correctly. This includes servo movement tests, EDF thrust tests, and basic flight tests.

## Usage
- **Manual Control**: Initially, the drone will be operated manually to test flight characteristics and system integrity.
- **Autonomous Development**: Begin programming autonomous flight capabilities by implementing and testing algorithms for tasks such as takeoff, landing, and waypoint navigation.

## Future Development
The project aims to expand the drone's autonomous capabilities, including but not limited to:
- Autonomous obstacle avoidance
- GPS-based navigation
- Real-time data processing for environmental awareness
- Integration with AI for dynamic decision-making
- In-flight transformation into different pre-defined drone configurations

## Contributing
- We only welcome contributions from members of our team. If you are a team member and would like to contribute in the form of code, bug reports, feature requests, or documentation improvements, please feel free to make your changes and submit a pull request.

This README provides a basic overview of the Transformer Drone Project. As the project evolves, so will this document, to reflect the latest changes and advancements.
