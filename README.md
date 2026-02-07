Hi, I’m Sophia (@s-0-p-h-i-a)

Mathematics & Computer Science B.Sc. student building hands-on microcontroller projects to develop a solid foundation in embedded systems, with a focus on control systems, hardware/software integration and performance firmware architecture.

### Current Tools
- C / C++
- CLI compile+upload
- Arduino, STM32
- Basic electronics and breadboarding, sensors, actuators

### Contact
www.linkedin.com/in/ana-sophia-wdp

---
## Featured Projects

### ICE Engine Mini Prototype  
https://github.com/s-0-p-h-i-a/ICE_Engine_Simulation

An ECU firmware–inspired internal combustion engine simulation prototype.

This project aims to incrementally combine small engine sub-system simulations into a single control system. The goal is not realism or performance, but learning how engine-related components interact, how data flows through a system, and how to design, test, and refactor firmware modules.

**Current capabilities**
- Live RPM calculation using a Hall sensor and servo-driven “flywheel” with magnet for edge signal generation
- LED-based cylinder state visualisation (combustion cycle)
- Joystick-based runtime control (enable/disable modules, speed selection)
- Data interface feeding live telemetry to a plotter

**Planned extensions**
- Crankshaft module
- Cylinder head simulation (DOHC, valves, injectors, ignition)
- Communication with data logger MCU
- Fault injection and diagnostics experiments

---
### I/O Control + Data Logging System (WIP)
https://github.com/s-0-p-h-i-a/Arduino_Practice/tree/main/Analog_IO%2BData_Logger

A firmware-inspired control and logging system with 2 microcontrollers connected via UART.

Project goal: build performance firmware-like control system while implementing error handling and logging, and laying foundations for future fault injection.

**I/O MCU**
- Takes user/sensor input via joystick, potentiometer and water sensor and processes input data to control the colour of an RGB LED via PWM
- Error handling system uses error codes to log sub-system states
- Produces periodic system snapshots with I/O data and error codes, and transmits them to data logger MCU via UART

**Data Logger MCU**
- Receives TX MCU system snapshots
- Processes received data and displays system reports on serial plotter and I/O data as LED matrix visualisation

**Current Status**
- High-level system design complete
- First code draft compiled
- Ongoing validation testing through progressive integration of different modules and functionalities

---
## Other Repositories

- **Engine Modules**  
  https://github.com/s-0-p-h-i-a/Engine_Modules  
  Isolated engine-related modules and experiments developed before integration into the main system.

- **Arduino Practice Projects**  
  https://github.com/s-0-p-h-i-a/Arduino_Practice  
  Small hardware and sensor projects focused on fundamentals.

- **CLI C / C++ Practice**  
  https://github.com/s-0-p-h-i-a/CLI_Apps  
  Console-based programs used to practice core language concepts and control flow.
