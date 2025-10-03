# EME5903 — Electromechanical Systems (AASTMT)

This repository contains Simulink labs, MATLAB scripts, and documentation for the **Electromechanical Systems** course (EME5903) in the Mechatronics Department at the Arab Academy for Science, Technology & Maritime Transport (AASTMT).  

The goal is to teach students how to **model**, **analyze**, and **design** electromechanical systems, and to integrate computer control for synergistic system behavior.

---

## Table of Contents

- [Course Description](#course-description)  
- [Course Topics & Labs](#course-topics--labs)  
- [Repository Structure](#repository-structure)  
- [Requirements](#requirements)  
- [Getting Started](#getting-started)  
- [How to Use the Labs](#how-to-use-the-labs)  
- [Learning Outcomes](#learning-outcomes)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Course Description

This course emphasizes:

- Modeling mechanical, electrical, and electromechanical systems  
- Formulating state-space representations  
- Sizing motors  
- Designing controllers (e.g. PID)  
- Applying all of the above in simulation using MATLAB & Simulink  

---

## Course Topics & Labs

- **Lab 1 – Translational Mechanical System**  
  Modeling mass-spring-damper and analyzing response (in Simulink).  

- **Lab 2 – Rotational Mechanical System**  
  Rotational inertia, torque, and angular dynamics modeling.  

- (Future labs / topics include)  
  - Electromechanical coupling (motors)  
  - State-space modeling  
  - Controller design (PID, perhaps more advanced controllers)  
  - Motor sizing and performance analysis  

---

## Repository Structure

```

AASTMT-EME5903-Electromechanical-Systems/
├── LICENSE
├── Lab1 – Translational Mechanical System/
│   ├── translational_model.slx
│   ├── translational_scripts.m
│   └── README.md
├── Lab2 – Rotational Mechanical System/
│   ├── rotational_model.slx
│   ├── rotational_scripts.m
│   └── README.md
├── (Future labs)/
├── README.md              ← This file
└── (supporting scripts, documentation, etc.)

````

> *Note: Replace placeholder names with the actual file/folder names you use in your repo.*

---

## Requirements

- MATLAB (recommended version: R2020a or later)  
- Simulink  
- (Optional but useful) Control System Toolbox, Simscape / Simscape Electrical  

---

## Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/Nathan85001/AASTMT-EME5903---Electromechanical-Systems.git
   cd AASTMT-EME5903---Electromechanical-Systems
````

2. Launch MATLAB and set the working folder to the repository root.

3. Browse into any Lab folder (e.g. `Lab1 – Translational Mechanical System`) and open the `.slx` file in Simulink or run the `.m` script.

---

## How to Use the Labs

* Each lab folder contains:

  * A Simulink model (`.slx`) ready for simulation
  * MATLAB script(s) for parameter setup, result plotting, or derivation steps
  * A README or documentation file explaining the lab’s objective, instructions, and how to run it

* Start with **Lab1**, run the simulation, examine results (plots, scopes), then modify parameters (mass, damping, stiffness) to see effects.

* Move to **Lab2**, study rotational analogs, compare with translational results.

* Future labs can build upon these foundations: adding coupling, control, and performance analysis.

---

## Learning Outcomes

After completing the labs and exercises, students will be able to:

* Derive dynamic equations for mechanical (translational & rotational) systems
* Build equivalent models (mass-spring-damper, rigid body systems)
* Formulate state-space representations
* Understand electrical models (in future labs) and couple them to mechanical systems
* Design and simulate controllers (e.g. PID)
* Perform basic motor sizing and system-level performance analysis

---

## Contributing

Contributions, enhancements, and additional lab modules are welcome. Suggested process:

1. Fork the repository
2. Create a topic branch (e.g. `lab3-electromechanical`, `pid-controller`)
3. Add models, scripts, and documentation
4. Submit a Pull Request with a clear explanation of new features or changes

When adding new labs or modules, include a short README in each folder to explain objectives, usage, and any parameters.

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for more details.

