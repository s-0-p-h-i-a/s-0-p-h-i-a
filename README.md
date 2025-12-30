Hi, I’m Sophia (@s-0-p-h-i-a)

Mathematics & Computer Science B.Sc. student building hands-on projects to develop a solid foundation in embedded systems, with a focus on automotive applications and ECU-style firmware architecture.

Learning Goals:
- Clear system decomposition and module boundaries
- Incremental complexity and validation
- Understanding fundamentals before abstraction
- Documentation of design decisions and debugging process

### Current Focus
- C / C++ for embedded-style programming
- Arduino-based prototyping
- Basic electronics, sensors, and actuators
- Engine-related systems as a learning domain

---
## Featured Project

### ICE Engine Mini Prototype  
🔗 https://github.com/s-0-p-h-i-a/ICE_Engine_Simulation

An ECU firmware–inspired internal combustion engine simulation prototype.

This project incrementally combines small engine sub-systems into a single, structured embedded-style application. The goal is not realism or performance, but learning how engine-related components interact, how data flows through a system, and how to design, test, and refactor firmware modules.

**Current capabilities**
- Live RPM calculation using a servo-driven “flywheel” and Hall sensor
- LED-based cylinder state visualisation (combustion cycle)
- Joystick-based runtime control (enable/disable modules, speed selection)
- Data interface feeding live telemetry to a plotter

**Planned extensions**
- Crankshaft module
- Cylinder head simulation (DOHC, valves, injectors, ignition)
- Fault injection and diagnostics experiments

The project includes progressive refactors, validation notes, and build/test plans to document learning and engineering trade-offs.

Note: This project intentionally simplifies or abstracts several real-world engine and ECU aspects (e.g. servo-based flywheel for RPM edge generation) to focus on system structure, signal handling, and incremental validation.

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
