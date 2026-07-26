# ABTRACTION-Automation-System
# ABSTRACTION-Automation-System

## Project Overview
This repository contains a Python implementation of an automated control system designed for the new **UMaT Auditorium**. The system leverages Object-Oriented Programming (OOP) principles—specifically **Abstraction**, **Inheritance**, and **Polymorphism**—to manage diverse building operations under a unified interface.

## Key Features & OOP Concepts

1. **Abstraction (`BuildingSystem`)**:
   - An abstract base class defining mandatory operational methods: `start()`, `stop()`, and `status()`.

2. **Concrete Subclasses**:
   - `AirConditioningSystem`: Manages climate control.
   - `LightingSystem`: Controls auditorium illumination.
   - `SecuritySystem`: Manages perimeter arming/disarming.

3. **Polymorphism**:
   - Systems are grouped inside a standard Python list and processed uniformly via a single loop without needing to know specific class implementations.

4. **Extensibility (Open/Closed Principle)**:
   - Added `FireAlarmSystem` seamlessly into the control loop without altering existing base or child classes.


