# 🔥 Fire and Smoke Detection using 555 Timer IC

This project presents a cost-effective and straightforward fire and smoke detection system using the NE555 timer IC. Designed for early detection of fire hazards, the system employs basic electronic components, making it ideal for educational purposes and DIY enthusiasts.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Hardware Components](#hardware-components)
- [Circuit Description](#circuit-description)
- [Working Principle](#working-principle)
- [Applications](#applications)
- [Limitations](#limitations)
- [Getting Started](#getting-started)
- [Circuit Diagram](#circuit-diagram)
- [References](#references)

---

## 🔍 Project Overview

This project is focused on developing a simple yet effective fire and smoke detection system using the NE555 Timer IC. The setup is designed to sense temperature or smoke changes and activate an alert mechanism like a buzzer, making it ideal for homes, schools, or labs as a basic safety device.

---

## 🎯 Objectives

- Detect the presence of fire or smoke using simple sensors.
- Trigger an audible or visual alert upon detection.
- Implement the detection logic using the NE555 timer IC in monostable mode.
- Provide a low-cost and easy-to-build solution for early fire detection.

---

## 🧰 Hardware Components

| Component          | Specification / Description                             |
|--------------------|---------------------------------------------------------|
| **NE555 Timer IC** | Used for generating timing pulses (Monostable mode)     |
| **Thermistor**     | Temperature-sensitive resistor (e.g., NTC 10kΩ)          |
| **Smoke Sensor**   | MQ2/MQ3 – Detects smoke or combustible gases             |
| **Resistors**      | Various values (e.g., 1kΩ, 10kΩ – for biasing/timing)    |
| **Capacitors**     | Timing capacitors (e.g., 10µF, 100nF)                    |
| **Buzzer**         | 5V Piezo buzzer – audible alert                         |
| **LED (Optional)** | 5mm Red/Green LED – visual fire/smoke indicator         |
| **Power Supply**   | 9V Battery or DC adapter                                |
| **Breadboard/PCB** | For circuit assembly and prototyping                    |
| **Connecting Wires** | Jumper wires (male-to-male) for circuit connections   |


---

## ⚙️ Circuit Description

The NE555 timer is configured in monostable mode. When a threshold temperature or smoke level is reached, the sensor triggers the timer circuit. The timer activates the buzzer for a specific duration, indicating the presence of fire or smoke. The timing is set by the RC components connected to the timer.

---

## 🔧 Working Principle

1. The thermistor/smoke sensor changes resistance with heat/smoke.
2. This change affects the voltage at the trigger pin of the 555 timer.
3. When the threshold is crossed, the 555 timer outputs a HIGH signal.
4. This activates a buzzer or LED to alert the user.
5. The output remains high for a time determined by `T = 1.1 × R × C`.

---

## 🚀 Applications

- Fire detection in homes and small offices
- Educational electronics projects
- DIY alarm systems
- Early warning systems for kitchens or server rooms

---

## ⚠️ Limitations

- Not suitable for large-scale or industrial fire detection
- May have false positives depending on environmental conditions
- Limited detection range compared to commercial detectors

---

## 🛠️ Getting Started

1. Gather all components listed above.
2. Build the circuit on a breadboard or PCB as per the schematic.
3. Connect the sensor and buzzer appropriately.
4. Power the circuit using a 9V battery or adapter.
5. Test using a match or smoke to see the buzzer activate.

---

## 🔧 Working Model

![Working Model](images/working_model.jpg)

## 🔌 Circuit Diagram

![Circuit Diagram](images/circuit_diagram.png)


