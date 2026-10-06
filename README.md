# 🏢 Smart Building – Occupancy-Based Energy Management System

An Arduino-based Smart Building prototype designed to improve **energy efficiency, room automation, and occupant comfort**.

The system uses two IR sensors to detect the direction of movement through a doorway and maintain the number of people inside the room. Based on occupancy, it automatically controls the room light and fan/pump. A DHT11 sensor monitors temperature and humidity, while an OLED display provides real-time information.

---

## 🚀 Project Overview

The main idea of this project is to reduce unnecessary energy consumption by automatically controlling electrical appliances based on room occupancy.

Two IR sensors are placed at the entrance:

- **IR Sensor A** → Outside the room
- **IR Sensor B** → Inside the room

The system determines whether a person is **entering or leaving** by checking the order in which the sensors are triggered.

### 👤 Entry

```text
A → B

### exit
B to A
