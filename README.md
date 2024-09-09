# WeatherNode

<img src="https://github.com/phiflip/WeatherNode/blob/main/illustrations/logo_icon.png" width="150" alt="WeatherNode main logo type">

**WeatherNode** is a versatile and educational meteorological station project that uses the power of CubeCell microcontrollers, a range of environmental sensors, and Node-RED for real-time data processing and visualization. This project is designed to provide hands-on experience with IoT (Internet of Things) technologies, data acquisition, cloud integration, and real-time analytics.

<img src="https://github.com/phiflip/WeatherNode/blob/main/illustrations/NodeRed_Dashboard.PNG" alt="WeatherNode Node-RED Dashboard">

## Project Overview

The WeatherNode project allows you to build a fully functional weather station capable of measuring various environmental parameters such as temperature, humidity, air pressure, and more. Data collected by the sensors is transmitted via LoRaWAN to a central server where it is processed and visualized using Node-RED.

### Key Features

- **CubeCell Integration:** Uses CubeCell microcontrollers which are optimized for low-power IoT applications and provide seamless integration with LoRaWAN networks.
- **Multi-Sensor Setup:** Supports a variety of sensors to monitor environmental conditions such as temperature, humidity, air quality, and more.
- **Node-RED Interface:** Data is processed and visualized in real-time using a customizable Node-RED dashboard, providing intuitive insights into environmental conditions.
- **Cloud Connectivity:** The project demonstrates how to integrate IoT devices with cloud services like Google Spreadsheets, Oracle Cloud, and AWS for data storage and further processing.
- **Educational Focus:** Ideal for students and educators, the WeatherNode project is structured to guide users through the process of setting up IoT systems, from hardware assembly to software integration and cloud deployment.

## Getting Started

### Prerequisites

Before starting, ensure you have the following:

- **Hardware:**
  - CubeCell microcontroller
  - Environmental sensors (e.g., temperature, humidity, pressure sensors)
  - LoRaWAN gateway (optional but recommended)
  - Breadboard, jumper wires, and other basic electronics components

- **Software:**
  - Arduino IDE (for programming the CubeCell)
  - Node-RED (installed locally or on a cloud platform like Oracle or AWS)
  - Google account (for spreadsheet integration)
  - Git (for cloning the repository and version control)

### Setup Instructions

1. **Hardware Assembly:**
   - Connect the sensors to the CubeCell microcontroller following the wiring diagrams provided in the `/documentation` folder.

2. **CubeCell Programming:**
   - Program the CubeCell with the provided `.ino` files using the Arduino IDE. Instructions on how to install necessary libraries and upload the code can be found in the `setup_guide.md` file.

3. **Node-RED Configuration:**
   - Set up Node-RED on your preferred platform (local or cloud). Detailed instructions for Node-RED setup, including flows for data processing and dashboard customization, are available in the `/node_red` folder.

4. **Cloud Integration:**
   - Integrate with Google Spreadsheets or other cloud services to store and analyze the data. The detailed steps are provided in the `/cloud_integration` folder.

5. **Testing and Troubleshooting:**
   - Test the full setup by collecting data and visualizing it in the Node-RED dashboard. Refer to the `troubleshooting.md` for common issues and solutions.

## Documentation

- **[Troubleshooting](./troubleshoot/README.md):** Solutions for common issues encountered during the setup and operation of the WeatherNode.



