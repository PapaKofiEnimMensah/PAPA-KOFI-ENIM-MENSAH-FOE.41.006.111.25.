# Smart Device Management System

This mini project is part of **EL 162/234 Object-Oriented Programming** taught by Dr. Matthew Cobbinah.  
It shows how inheritance, encapsulation, and object-oriented design can be applied in Python.

## Project Overview
The program models a **Smart Home System** with different devices:
- **SmartDevice (Parent Class)** → common attributes like name, device ID, and power status.
- **TemperatureSensor** → reads temperature values.
- **SmartLight** → controls brightness (0–100).
- **SecurityCamera** → starts and stops recording.

Each child class inherits from `SmartDevice` and uses `super()` to initialize shared attributes.

##  Key Features
- Encapsulation of sensitive attributes (`device_id`, `power_status`).
- Getter and setter methods with validation (e.g., brightness range).
- Demonstrates inheritance and method overriding.
- Simple **menu-driven interface** for user interaction.

