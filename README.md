# Purpose
The project's goal is to save conventional streetlight power consumption by adapting the brightness based on motion. 

# Setup
The system uses ESP-NOW wireless communication protocol. Multiple streetlights communicate with each other to coordinate the change in brightness based on the location of the motion. The hardware is assembled
on a breadboard which consists of an LED, HC-SR04 ultrasonic sensor, and ESP32 microcontroller. Information regarding the project's design can be found in this [Design Document](./Documentation/PDFs/LightCity_DesignDocument.pdf).

# Usage
By knowing the MAC addresses of the other ESP32s, each ESP32s adjusts their brightness based on the brightness of its neighboring ESP32. Information regarding the project's purpose and usage can be found in this [Analysis Document](./Documentation/PDFs/LightCity_AnalysisDocument.pdf).