# RHCP Quad Antenna

## Overview

This design presents a quad antenna developed and analyzed using ANSYS HFSS for right-hand circular polarization (RHCP) operation.

Circular polarization is achieved through two intentional cuts introduced into the radiating structure. These perturbations modify the current distribution on the antenna and excite two orthogonal field components with the required phase relationship for RHCP operation.

The antenna performance was evaluated using VSWR, principal-plane radiation patterns and three-dimensional realized gain results.

## Key Features

- **Simulation Tool:** ANSYS HFSS
- **Antenna Type:** Quad Antenna
- **Polarization:** Right-Hand Circular Polarization (RHCP)
- **Target Frequency:** 2.6 GHz
- **Main Performance Parameters:** VSWR, E-plane pattern, H-plane pattern and RHCP realized gain
- **Radiation Pattern Evaluation Frequency:** 2.6 GHz

## Design Description

The antenna consists of a conductive quad-shaped radiating element placed above an aluminum ground structure.

Two localized cuts are introduced into the radiating element in order to perturb the surface-current distribution. These cuts create two orthogonal resonant field components with an appropriate phase difference, enabling right-hand circular polarization.

The radiating element is modeled using copper, while the ground structure is modeled using aluminum.

The antenna is excited through an RG402 semi-rigid coaxial feed. The coaxial feeding structure provides a practical transition between the RF source and the radiating element while maintaining a compact mechanical configuration.

The electromagnetic model was developed in ANSYS HFSS and evaluated around 2.6 GHz. Radiation characteristics were examined in both the E-plane and H-plane, while the three-dimensional RHCP realized gain pattern was used to visualize the circularly polarized radiation behavior of the antenna.

## Materials and Feeding

- **Radiating Element:** Copper
- **Ground Plane:** Aluminum
- **Feed Cable:** RG402 semi-rigid coaxial cable
- **Surrounding Medium:** Air / free-space simulation region

## Circular Polarization Mechanism

The two cuts introduced into the antenna geometry act as perturbations on the radiating structure.

These perturbations modify the effective current path and produce two orthogonal electromagnetic field components. When the amplitudes of these components are sufficiently similar and their phase difference approaches 90°, circular polarization is obtained.

The orientation and placement of the cuts are selected to generate right-hand circular polarization (RHCP).

## 3D Model

![Geometry](geometry.png)

## VSWR

![VSWR](VSWR.png)

## Radiation Patterns at 2.6 GHz

<p align="center">
  <img src="2,6GHz_E%20-%20Plane.png" width="48%">
  <img src="2,6GHz_H%20-%20Plane.png" width="48%">
</p>

<p align="center">
  <b>E-Plane</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>H-Plane</b>
</p>

## RHCP Realized Gain

![RHCP Realized Gain](Realized%20Gain%20RHCP%203D%20Plot.png)
