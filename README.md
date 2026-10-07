# 2-DoF Humanoid Robot Ankle

A 2-DoF humanoid robot ankle designed using a parallel differential mechanism, with two motor inputs providing independent pitch and roll motion.

The project focuses on mechanical design, CAD modelling, and mathematical analysis of the ankle mechanism, including the derivation of its inverse kinematics.

## Project Overview

The ankle mechanism was designed as a compact robotic joint capable of producing two rotational degrees of freedom:

* **Pitch** – rotation about the Y-axis
* **Roll** – rotation about the X-axis

The mechanism uses two motor-driven inputs and a differential/parallel mechanical arrangement to generate the desired ankle orientation.

### Coordinate System

The coordinate system used for the kinematic analysis is:

* **X** – Forward
* **Y** – Left
* **Z** – Up

The ankle orientation is represented using the rotation formulation:

```text
R = Rx(φ) · Ry(θ)
```

where:

* `θ` represents the ankle pitch angle
* `φ` represents the ankle roll angle

## Key Features

* 2-DoF humanoid robotic ankle
* Parallel/differential mechanical mechanism
* Two-motor actuation
* Detailed CAD design and assembly
* Forward and inverse kinematic analysis
* Analytical inverse kinematics derived manually
* Designed for humanoid robotic applications

## Repository Contents

```text
CAD/
├── Assembly/       # Complete CAD assembly
├── Parts/          # Individual components
└── STEP/           # STEP models

Kinematics/
└── Inverse_Kinematics_Derivation.pdf

Images/
└── Assembly images from different views
```

## CAD Design

The complete ankle mechanism was designed and assembled in CAD, including the individual mechanical components and their final assembly.

### Final Assembly

<p align="center">
  <img src="Images/Screenshot 2026-09-21 201430.png" width="700">
</p>

### Additional Views

<p align="center">
  <img src="Images/Screenshot 2026-09-21 201109.png" width="400">
</p>

<p align="center">
  <img src="Images/Screenshot 2026-09-21 205614.png" width="400">
</p>

<p align="center">
  <img src="Images/Screenshot 2026-09-22 085105.png" width="400">
</p>

## Kinematic Analysis

The inverse kinematics of the ankle mechanism was derived analytically from the mechanism geometry.

The derivation relates the desired ankle orientation `(θ, φ)` to the corresponding actuator positions required to achieve that orientation.

The complete hand-derived mathematical analysis is provided in:

**[Inverse Kinematics Derivation](Kinematics/Inverse_Kinematics_Derivation.pdf)**

## Engineering Concepts

This project involved:

* Robotic joint design
* Mechanical mechanism design
* CAD modelling
* Parallel mechanisms
* Differential mechanisms
* Coordinate transformations
* Rotation matrices
* Forward kinematics
* Inverse kinematics
* Geometric modelling

## Tools

* SolidWorks
* Mathematical modelling
* Analytical kinematics

## Project Status

**Completed**

The mechanical design and analytical inverse kinematic derivation have been completed.

## Author

**Chaniru Ranawaka**

BSc (Hons) Electronic & Telecommunication Engineering
University of Moratuwa

---

## License

This project is provided for educational and portfolio purposes.
