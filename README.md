
# Smart Home Automation System

This repository contains the code and design for a **Smart Home Automation System** that automates the control of various household appliances. The system allows users to manage **lights**, **heating and cooling systems**, and a **serial tank** through an integrated interface, enhancing convenience and energy efficiency.

## Features

- **Automated Lights**: Control the lighting system of the house, turning lights on or off based on conditions or manual input.
- **Heater and Cooler Switches**: Manage heating and cooling devices to maintain desired temperature levels in your home.
- **Serial Tank Control**: Automatically manage the water level in a serial tank, ensuring efficient water usage.

## Technologies Used

- **C** and **C++**: For embedded systems programming and controlling hardware components.
- **Arduino**: Used to interface with sensors and control the various devices.
- **PICSimLab**: To simulate circuits and ensure smooth integration of hardware components.
- **IoT**: For enabling remote control and automation of appliances.

## How It Works

The system uses an **Arduino** microcontroller to interface with the hardware components, such as sensors, relays, and switches. The automation process is handled through embedded code written in **C/C++**, which monitors inputs (like temperature and water level) and triggers actions accordingly.

- **Lights**: The lights can be controlled manually or set to turn on/off based on certain triggers (e.g., time or occupancy sensors).
- **Heater and Cooler**: The temperature is monitored, and based on predefined thresholds, the heater or cooler is turned on/off automatically.
- **Serial Tank**: A sensor monitors the water level in the tank, and the system controls the water pump to fill or stop filling as needed.
