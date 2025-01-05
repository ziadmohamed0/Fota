# FOTA (Firmware Over-The-Air) Project

This repository contains the implementation of a FOTA system developed during a course on Firmware Over-The-Air (FOTA) updates. The project involves creating a bootloader and drivers for FOTA functionality on the STM32F103C8T6 microcontroller. Additionally, MQTT protocol integration was explored using Node-RED.

## Features
- **Bootloader Development**: A custom bootloader was designed to enable firmware updates for the STM32F103C8T6 microcontroller.
- **Driver Development**: Drivers were implemented to support FOTA functionality.
- **MQTT Integration**: Utilized MQTT protocol for communication and update management.
- **Node-RED**: Leveraged Node-RED for MQTT testing and workflow automation.

## Hardware
- **Microcontroller**: STM32F103C8T6
- **Microcontroller**: ESP8266
  
## Tools and Technologies
- **IDE**: STM32CubeIDE
- **Programming Language**: C
- **Protocol**: MQTT
- **Workflow Automation**: Node-RED

## Getting Started

### Prerequisites
- STM32F103C8T6 development board
- Node-RED installed on your system
- MQTT broker (e.g., Mosquitto)

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ziadmohamed0/Fota.git
   ```
2. Open the project in STM32CubeIDE.
3. Compile and flash the bootloader onto the STM32F103C8T6 microcontroller.
4. Set up an MQTT broker and configure Node-RED for communication.
5. Test the FOTA system by publishing firmware updates via MQTT.

## Lessons Learned
- Bootloader design and implementation for STM32 microcontrollers.
- Integration of MQTT protocol for IoT applications.
- Workflow automation using Node-RED.

## Repository Structure
- **/Bootloader**: Contains the bootloader implementation.
- **/Drivers**: Includes the drivers required for FOTA functionality.
- **/MQTT**: Scripts and configurations for MQTT communication.

## Author
[Ziad Mohamed](https://github.com/ziadmohamed0)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
Feel free to explore the repository and use the provided resources to understand the implementation of FOTA systems for embedded applications!

