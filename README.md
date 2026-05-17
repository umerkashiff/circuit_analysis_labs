# Circuit Analysis and Design: Laboratory Practicum

[![Simulation Environment](https://img.shields.io/badge/Environment-Proteus_8_Professional-2C2C2C?style=for-the-badge)](https://www.labcenter.com/)
[![Institution](https://img.shields.io/badge/Institution-Engineering_Department-2C2C2C?style=for-the-badge)]()
[![Course](https://img.shields.io/badge/Course-Electrical_Networks-2C2C2C?style=for-the-badge)]()

<div align="center">
  <img src="[https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/Op-Amp_Inverting_Amplifier.svg/500px-Op-Amp_Inverting_Amplifier.svg.png](https://miro.medium.com/0*v9HoBe1g2EZ8jOPp.png)" alt="p=Proteus Logo" width="400">
  <br>
  <em>System-level and component-level circuit simulation topologies.</em>
</div>

## Abstract

This repository contains the definitive documentation and simulation files for the electrical network analysis laboratory practicum. The curriculum bridges theoretical circuit principles with applied simulation modeling. All schematic captures, transient analyses, and component validations are engineered exclusively within the Proteus Design Suite. 

## Architectural Standard

The repository enforces a strict, modular hierarchy to separate procedural guidelines, experimental data, and simulation source files. Every experiment adheres to the following tripartite structure:

```text
├── Experiment_XX_Name/
│   ├── lab-manual/            # Official procedural documentation and pre-lab requirements
│   ├── lab-report/            # Formal documentation including calculated vs. simulated telemetry
│   └── proteus-files/         # .pdsprj workspace files and associated simulation dependencies
````
## Laboratory Index

The coursework is divided into logical phases, progressing from passive linear circuits to active signal processing.

### Phase I: Fundamentals and Instrumentation

| Lab ID | Objective | Core Components / Concepts |
| :--- | :--- | :--- |
| **01** | **Instrumentation Calibration** | Oscilloscopes, Signal Generators, Multimeters |
| **02** | **Ohm's Law & Power Dissipation** | Linear resistive networks, Ohmmeter design logic |
| **03** | **Kirchhoff's Laws (KVL & KCL)** | Mesh and Nodal analysis validation via simulation |

### Phase II: Advanced Network Theorems

| Lab ID | Objective | Core Components / Concepts |
| :--- | :--- | :--- |
| **04** | **Superposition Theorem** | Multi-source linear networks, independent source isolation |
| **05** | **Thevenin's Theorem** | Equivalent voltage sources, series impedance calculation |
| **06** | **Norton's Theorem** | Equivalent current sources, parallel admittance models |
| **07** | **Maximum Power Transfer** | Load matching, theoretical vs. simulated power curves |

### Phase III: Active Components and Amplification

| Lab ID | Objective | Core Components / Concepts |
| :--- | :--- | :--- |
| **08** | **Op-Amp Fundamentals** | Inverting & non-inverting topologies, LM741 characteristics |
| **09** | **Signal Operations** | Op-Amp based integrators, differentiators, and summing amplifiers |

## Simulation Methodology

All computational models are built utilizing **Proteus VSM (Virtual System Modelling)**. This allows for real-time co-simulation of schematic parameters alongside virtual instrumentation.

### Execution Guidelines:

1. Navigate to the desired experiment's `proteus-files/` directory.
2. Initialize the `.pdsprj` file.
3. Ensure the active simulation profile matches the frequency and transient settings defined in the corresponding `lab-manual/`.
4. Execute the simulation to observe virtual instrument outputs (e.g., simulated oscilloscope probes, logic analyzers).

---
*Document formulated for academic repository indexing.*
