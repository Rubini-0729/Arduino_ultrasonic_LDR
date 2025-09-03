# Arduino_ultrasonic_LDR
📌 Overview

This project demonstrates an energy-efficient smart street light system using Arduino, an Ultrasonic Sensor, and an LDR (Light Dependent Resistor).
The LDR detects day/night.
The Ultrasonic sensor detects the presence of vehicles or people.
The LED (street light) turns ON automatically only at night when an obstacle is detected.
This reduces power wastage and enhances smart city infrastructure.


⚡ Working Principle

1. Daytime (LDR High Value) → LED always OFF.


2. Nighttime (LDR Low Value) →

If an object is within 50 cm, the LED (street light) turns ON.

If no object is detected, the LED remains OFF.
