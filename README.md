# UT_Mechatronics_course

## Four-Legged Walking Robot

## Overview

This project was completed as part of the **Mechatronics course final project** at the **University of Tehran**. The objective was to **design, build, and program** a four-legged walking robot. Each project group consisted of three students, with specific responsibilities assigned to each member.

Our robot utilizes **Chebyshev’s Lambda mechanism**, with the goal of achieving stable walking motion. The mechanical design was created using **SolidWorks**, and the mechanism's motion was analyzed with **SAM software** before the final assembly using wood and plexiglass. 

---

## Table of Contents

- [Project Features](#project-features)
- [System Architecture](#system-architecture)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Hardware Components](#hardware-components)
- [Software Components](#software-components)
- [Installation and Setup](#installation-and-setup)
- [Operation](#operation)
- [Simulation](#simulation)
- [Project Team](#project-team)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Project Features

- **Four-legged walking mechanism** based on Chebyshev’s Lambda mechanism.
- **Arduino-based control system** with joystick operation.
- **Obstacle detection** using an ultrasonic sensor.
- **Gyroscopic feedback** for stability enhancement.
- **Simulation validation** using SAM software and Simulink.
- **Manufacturing using wood and plexiglass materials.**

---

## System Architecture

The project consists of the following major components:

1. **Mechanical Design:**  
   - 3D modeling and motion analysis in **SolidWorks**.  
   - Laser-cut wooden and plexiglass parts for assembly.
   
2. **Electronics Design:**  
   - Integration of motors, sensors, and microcontroller (Arduino UNO).
   
3. **Programming:**  
   - Control algorithms for movement and obstacle avoidance using **Arduino IDE**.
   
4. **Simulation:**  
   - Motion analysis and validation using **SAM software** and **Simulink**.

---

## Roles and Responsibilities

- **Mechanical Design:**  
  - Designed by my groupmates using **SolidWorks**.
  - Analyzed the walking mechanism using **SAM software** to validate before building.

- **Programming (My Contribution):**  
  - Selected **Arduino UNO** as the microcontroller.  
  - Programmed the robot to move in four directions using a **joystick**, with movement control via two DC motors and an **L298 driver**.  
  - Implemented obstacle detection using an **SRF04 ultrasonic sensor**, stopping the robot when encountering a wall.

---

## Hardware Components

The following hardware components were used:

- **Microcontroller:** Arduino UNO
- **Motors:** Two DC motors (12V, 0.5A, 150 RPM)
- **Sensors:**
  - **Ultrasonic Sensor (SRF04)** for obstacle detection
  - **Gyroscope Sensor (MPU-6050 GY521)** for motion stabilization
- **Motor Driver:** L298 motor driver module
- **Frame Material:** Laser-cut wood and plexiglass
- **Joystick:** Used for manual control input

---

## Software Components

- **Arduino IDE:** For programming the microcontroller.
- **SolidWorks:** For 3D modeling and mechanical simulation.
- **Simulink (MATLAB):** For dynamic simulation and motion validation.
- **SAM Software:** Used for analyzing the walking mechanism.

---

## Installation and Setup

### Hardware Setup

1. Assemble the mechanical parts using the provided SolidWorks designs.
2. Connect electronic components following the provided wiring diagram.
3. Use a 12V power supply to power the system.

### Software Setup

1. Install the [Arduino IDE](https://www.arduino.cc/en/software).
2. Upload the provided Arduino code to the board.
3. Install MATLAB/Simulink for running simulations.

---

## Operation

1. Power on the robot.
2. Use the joystick to control movement in four directions.
3. The ultrasonic sensor continuously measures the distance to obstacles.
4. If an obstacle is detected within **5 cm**, the robot stops automatically.
5. The gyroscope sensor provides real-time feedback to maintain stability.

---

## Simulation

- **SAM Software** was used to analyze and optimize the walking trajectory of the robot.
- **Simulink** was employed to evaluate dynamic performance and validate control algorithms.

---

## Project Team

- **Amirhossein Chahe**
- **Mahdi Chalaki**
- **Amirhossein Afkhami**
