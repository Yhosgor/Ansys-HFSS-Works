# RHCP Bi-Quad Antenna

## Overview

This design presents a quad antenna developed and analyzed using ANSYS HFSS for right-hand circular polarization (RHCP) operation.

Circular polarization is achieved through two intentional cuts introduced into the radiating structure. These perturbations modify the current distribution on the antenna and excite two orthogonal field components with the required phase relationship for RHCP operation.

The antenna performance was evaluated using VSWR, principal-plane radiation patterns and three-dimensional realized gain results.

## Key Features

- **Simulation Tool:** ANSYS HFSS
- **Antenna Type:** Quad Antenna
- **Polarization:** Right-Hand Circular Polarization (RHCP)
- **Target Frequency:** 2.6 GHz
- **Main Performance Parameters:** S11, VSWR, E-plane pattern, H-plane pattern and RHCP realized gain
- **Radiation Pattern Evaluation Frequency:** 2.6 GHz

## Materials and Feeding

- **Radiating Element:** Copper
- **Ground Plane:** Aluminum
- **Feed Cable:** RG402 semi-rigid coaxial cable
- **Surrounding Medium:** Air / free-space simulation region

## 3D Model

![Geometry](geometry.png)

## Reflection Coefficient

![S11](S11.png)

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
