PX4 Autopilot Module: Agricultural Mission System & Emergency Handling

This project documents the development and integration of a custom PX4 flight control module tailored for agricultural UAV missions. The module introduces spraying functionalities, dynamic mission management, and robust emergency handling procedures such as GPS failure recovery and payload monitoring.

Although the work was conducted as part of a corporate internship and the source code cannot be publicly released, this repository serves as a technical overview of my contributions to PX4, illustrating my engagement with open-source systems at the kernel level.

### Project Highlights
- Developed a new agricultural mission module from scratch for PX4.
- Created custom MAVLink messages and integrated them via uORB to support:

**Features**
* Start/stop spraying triggers
* Tank volume estimation
* Dynamic mission rescheduling
* Integrated with QGroundControl for real-time telemetry and mission feedback.
* Verified functionality in Gazebo simulation and on STM32-based hardware targets.


**Designed and tested emergency handling logic for:**
* GPS jamming and fallback scenarios
* Sprayer malfunction detection
* Battery-payload correlation checks

```
Component	        |  Description
-------------------------------------------------------
PX4 Autopilot	        |  Open-source flight stack
uORB	                |  PX4’s internal publish/subscribe middleware
MAVLink	                |  Lightweight message protocol
STM32                   |  FMU	Target platform
QGroundControl	        |  Mission planner and telemetry tool
Gazebo	                |  Simulation environment
```

**Documentation**
All core contributions and module designs have been documented in two comprehensive technical reports:
- PX4 Module Creation and MAVLink Integration (PDF)
- PX4 Emergency Procedures Design Document (PDF)

**These documents provide:**
* Architecture diagrams
* Interface definitions
* Simulation test results
* Design decisions and engineering trade-offs
* These documents were submitted and evaluated during my internship and reflect my experience integrating new features into large-scale open-source systems like PX4.

**This project represents:**
* My ability to work within large open-source ecosystems (PX4, MAVLink, QGC).
* Proficiency with embedded systems (STM32, C++) and communication protocols.
* Engineering maturity to implement real-world, safety-critical logic with rigorous documentation.
* A mindset for modular, testable, and scalable flight control logic.

**Disclaimer**
Due to corporate confidentiality, the source code cannot be published. This repository only includes design-level documentation and implementation summaries.

**Author**

Can Ömer
Embedded Systems & Security Enthusiast
LinkedIn · https://www.linkedin.com/in/omer-can-vural/
Email · can.omer.5306@outlook.com

