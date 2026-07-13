# Bio-Inspired Robotic Fish

## Overview

![Robotic Fish Final Design](Media/FullASM_v2.png)

The Bio-Inspired Robotic Fish is an ongoing robotics project investigating undulatory propulsion as an alternative to conventional propeller-based underwater locomotion. The objective is to develop a modular robotic platform capable of generating fish-like swimming motion through a mechanically actuated flexible body.

The project combines mechanism design, computational fluid dynamics (CFD), rapid prototyping, and soft robotics to explore how rotary motion can be transformed into efficient traveling wave motion suitable for underwater propulsion.

---

## Project Objectives

The primary objectives of the project are to:

- Develop a mechanical system capable of converting a single rotary input into a traveling wave along a flexible body.
- Design a hydrodynamically efficient external body inspired by biological swimmers.
- Create a modular internal architecture that supports rapid iteration of actuators and transmission mechanisms.
- Investigate manufacturing techniques combining rigid and compliant materials.
- Evaluate propulsion concepts through simulation and physical prototyping.

---

## Problem Description

Conventional underwater vehicles primarily rely on propellers for propulsion. While effective, propellers generate noise, expose moving components, and are not optimized for maneuverability in confined or environmentally sensitive environments.

Many aquatic organisms instead produce propulsion by generating traveling waves along their bodies and fins. This method provides efficient thrust generation while enabling precise maneuvering and reduced acoustic signature.

This project explores the engineering challenges associated with reproducing this biological locomotion using practical mechanical systems and accessible manufacturing techniques. The long-term objective is to develop a modular research platform capable of evaluating different propulsion mechanisms, body geometries, and manufacturing methods.

---

## Exterior Design

The external body is designed to balance hydrodynamic performance, manufacturability, and accessibility to internal components. Multiple design iterations are evaluated using CAD modeling and Computational Fluid Dynamics (CFD) to investigate body shape, drag characteristics, and flow behavior before fabrication.

Design considerations include:

- Streamlined body geometry
- Hydrodynamic efficiency
- Internal packaging volume
- Modular outer shell construction
- Ease of assembly and maintenance

CFD analysis is used throughout the design process to compare body geometries, visualize flow behavior, and identify opportunities for improving overall performance.

<!-- Insert exterior CAD render here -->
![Robotic Fish Final Design](Media/FullASM.png)

Detailed CFD setup, mesh generation, and results are available in the analysis report:

[CFD Analysis Report](Analysis/CFD_report.pdf)

---

## Interior Design

The internal mechanical architecture focuses on generating undulatory motion using a compact rotary actuator and transmission mechanism. The design investigates methods of converting continuous rotary motion into a controlled traveling wave capable of propagating through a compliant tail section.

Current design investigations include:

- Actuator selection
- Motion transmission mechanisms
- Linkage geometry optimization
- Flexible body integration
- Waterproof packaging strategy
- Electronics packaging and cable routing

The modular architecture allows alternative mechanisms and actuation strategies to be evaluated without redesigning the complete platform.

<!-- Insert exploded CAD view here -->
![Internal Mechanism](Media/FullASM_expl.png)
![Internal Mechanism](Media/GearBox.png)
![Internal Mechanism](Media/GearBox_expl.png)
![Internal Mechanism](Media/TailModule_v2.png)

---

## Manufacturing

The robotic fish is designed around rapid prototyping techniques that enable fast design iteration while minimizing manufacturing cost and complexity.

Planned manufacturing processes include:

- **3D Printing** for structural components and enclosure features.
- **Laser Cutting** for precision linkage components and internal mechanisms.
- **Silicone Molding** for compliant fins and flexible body sections.
- **Commercial Hardware** for shafts, bearings, fasteners, and drive components.

Combining rigid and compliant manufacturing methods allows the system to better replicate biological motion while maintaining a modular mechanical architecture.

<!-- Insert manufacturing images here -->
![Internal Mechanism](Media/TailMoldASM.png)
![Internal Mechanism](Media/ShadedSectionView.png)
---

## Prototype Demonstration

Prototype testing will evaluate the effectiveness of the propulsion mechanism and validate the relationship between the generated mechanical waveform and resulting swimming motion.

Planned demonstrations include:

- Dry mechanism testing
- Undulatory motion characterization
- Controlled swimming demonstrations
- Performance comparisons between design iterations

Prototype videos and experimental results will be added as development progresses.

<!-- Insert demonstration video here -->
<video src="Media/Prototype_Demo.mp4" width="100%" controls></video>
---

## Skills Demonstrated

### Mechanical Design

- Mechanism design
- CAD modeling and assembly design
- Design iteration
- Mechanical packaging
- Biomimetic engineering

### Engineering Analysis

- Computational Fluid Dynamics (ANSYS Fluent)
- Mechanism analysis
- Design trade studies

### Manufacturing

- Design for additive manufacturing
- Laser-cut component design
- Silicone molding
- Rapid prototyping

### Robotics

- Biomimetic system design
- Motion generation
- Actuator integration
- Mechanical system architecture

### Engineering Tools

- SolidWorks
- ANSYS Fluent
- MATLAB
- 3D Printing
- Laser Cutting
- Git/GitHub

---

## Acknowledgments

This project was completed as part of a robotics design course at Purdue University under the guidance of **Prof. Rob Scharff**.

Special thanks to the project team for their contributions:

- **Prof. Rob Scharff** – Project advisor and course instructor.
- **Artur Zhang** – Electrical Systems Lead, responsible for the electrical architecture and hardware integration.
- **Jonathan Wu** – Actuation Systems Lead, responsible for the development of the actuation subsystem and motion generation concepts.

Unless otherwise noted, the mechanical system design, CAD development, manufacturing strategy, engineering analysis, and project documentation presented in this repository represent my individual contributions. Team members are credited within specific files and documentation where they made direct contributions.
