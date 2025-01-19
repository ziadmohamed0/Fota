Here's a README file for your repository in English:

---

# Embedded IoT Projects

This repository contains a collection of projects related to embedded systems and the Internet of Things (IoT), developed during training courses and personal projects.

## Projects

### 1. Firmware Over-the-Air (FOTA) Update

This project involves developing a system for over-the-air (FOTA) firmware updates using the STM32F103C8T6 microcontroller. A custom bootloader is developed to enable firmware updates, and drivers are created to support the FOTA functionality.

**Features:**
- Development of a custom bootloader for the STM32F103C8T6 microcontroller.
- Creation of drivers to support the FOTA functionality.
- Use of the MQTT protocol to manage updates.
- Testing of the MQTT protocol and flow automation using Node-RED.

**Tools and Technologies:**
- Programming Language: C
- Development Environment: STM32CubeIDE
- Protocol: MQTT
- Flow Automation: Node-RED

### 2. MQTT Protocol with ESP8266

This project demonstrates how to use the MQTT protocol with the ESP8266 module to communicate with an MQTT server. Node-RED is used to test the connection and manage the messages.

**Features:**
- Configuring the ESP8266 module to connect to a Wi-Fi network.
- Connecting to an MQTT server and sending/receiving messages.
- Using Node-RED to test and manage MQTT flows.

**Tools and Technologies:**
- Programming Language: C
- Development Environment: Arduino IDE
- Protocol: MQTT
- Flow Automation: Node-RED

## Getting Started

### Prerequisites

- STM32F103C8T6 development board for the first project.
- ESP8266 module for the second project.
- Node-RED installed on your system.
- MQTT server (e.g., Mosquitto).

### Running the Projects

1. Clone the repository:
   ```bash
   git clone https://github.com/ziadmohamed0/Embedded_IOT.git
   ```

2. Follow the instructions in each project folder for setup and execution.

## Contributing

Contributions to this repository are welcome. Please open an "Issue" to discuss any proposed changes or submit a "Pull Request" directly.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Let me know if you'd like any changes!
