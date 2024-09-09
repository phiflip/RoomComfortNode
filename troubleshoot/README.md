# Troubleshooting Guide for WeatherNode

Welcome to the Troubleshooting section of the WeatherNode repository. This guide is intended to help you diagnose and resolve common issues that may arise when working with the WeatherNode project. Below you will find descriptions of known issues, their causes, and recommended solutions. For each issue, there may also be example scripts provided to assist with troubleshooting.

## Table of Contents

1. [Issue: Sensor Disconnects After Prolonged Operation](#Issue: CubeCell Not Recognized or No Port Assigned in Arduino IDE)
2. [Issue: Inconsistent Data Readings](#issue-inconsistent-data-readings)


---

## Issue: CubeCell Not Recognized or No Port Assigned in Arduino IDE

**Description:**  
In some cases, especially during the initial setup (e.g., Week 1), the CubeCell board may not be recognized by the Arduino IDE, or no port is assigned.

**Cause:**  
This issue is typically caused by a missing or incorrect driver for the CP2102 USB-to-UART bridge used by the CubeCell.

**Solution:**  
Windows users need to install the CP2102 driver. Follow these steps:
1. Download and install the CP2102 driver from the official source: [CP2102 Driver](https://www.pololu.com/docs/0J7/all#2).
2. After installation, restart your computer.
3. Reconnect the CubeCell board and open the Arduino IDE.
4. Check if the port is now correctly assigned under `Tools > Port`.

**Additional Tips:**
- If the port still doesn't appear, try using a different USB cable or USB port on your computer.
- Ensure that the CubeCell board is properly powered and connected.


---





**Note:** This guide is a living document and will be updated as new issues and solutions are identified. Always check for the latest version in the repository.

