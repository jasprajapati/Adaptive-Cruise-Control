# Adaptive Cruise Control System (Arduino + MATLAB)

This project demonstrates the simulation and implementation of an **Adaptive Cruise Control (ACC)** system using **MATLAB** and **Arduino UNO**. The ACC system dynamically adjusts vehicle speed based on real-time distance measurements to enhance driving safety, reduce tailgating, and improve driver convenience.

> Developed as a final project for *GENG 8030 – Computational Methods & Modeling for Engineering Applications* at the University of Windsor.

---

## 🚗 Project Overview

The ACC system operates in two modes:  
- **Cruise Control Mode**: Maintains a constant speed as set by the user.  
- **Adaptive Mode**: Adjusts speed based on the distance to a leading vehicle, measured via an ultrasonic sensor.

Users can switch between modes using onboard pushbuttons. The speed and system status are displayed on an LCD. The controller is implemented using **Arduino UNO**, and the program logic is built in **MATLAB** using the *Ultrasonic* and *LCD Add-on* libraries.

---

## 🔧 Key Features

- Dual-mode operation: **Cruise** and **Adaptive Cruise Control**
- **Distance sensing** using ultrasonic sensor for real-time obstacle detection
- **LCD display** for speed visualization and system status
- **MATLAB integration** with Arduino for sensor control and logic simulation
- **Button-controlled input interface** for speed settings and mode selection

---

## 🛠️ Hardware Components

| Component             | Function                                        |
|----------------------|-------------------------------------------------|
| Arduino UNO           | Microcontroller for system logic                |
| Ultrasonic Sensor     | Measures distance to obstacles                  |
| 16x2 LCD Display      | Shows speed and system mode                     |
| Push Buttons (5)      | User input: Set Speed, Adaptive, Inc/Dec, Cancel|
| Potentiometer         | Adjust LCD contrast                             |
| Breadboard & Wires    | Circuit prototyping and connection              |
| Resistors             | For signal conditioning and pull-downs         |

---

## 🔁 System Workflow

1. **Start** – User powers the system and is greeted on the LCD.
2. **Set Speed** – User presses a button to engage standard cruise mode.
3. **Adaptive Mode** – Ultrasonic sensor monitors distance and adjusts speed accordingly.
4. **Cancel Mode** – Stops any mode and gradually reduces speed.
5. **Display Feedback** – LCD shows current mode and speed in real-time.

---

## 💻 Software Architecture

- **Platform**: MATLAB + Arduino Support Package
- **Libraries Used**:  
  - Ultrasonic  
  - LCD Add-on  

- **Main Functions**:
  - Sensor readouts and distance calculations
  - Button signal reading (analog pins A1–A5)
  - Speed regulation logic
  - Mode switching
  - LCD display update with delay handling

---

## 🧠 Key Skills Demonstrated

- Embedded system control using **Arduino & MATLAB**
- Distance sensing and real-time data integration
- Pushbutton-based input interface
- LCD-based user feedback system
- State machine logic implementation for adaptive systems
- Functional decomposition and flowchart-based design
- Component wiring and breadboard prototyping

---



