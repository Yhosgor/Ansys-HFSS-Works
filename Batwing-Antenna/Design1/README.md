# Batwing Antenna - Design 1

## Overview

This design presents a broadband batwing antenna developed and analyzed using ANSYS HFSS.  
The antenna geometry is based on a flared dipole-like structure intended to provide wideband impedance behavior and relatively stable radiation characteristics over the operating frequency range.

The design was evaluated in terms of input matching, VSWR, realized gain, two-dimensional radiation patterns and three-dimensional far-field radiation characteristics.

## Key Features

- **Simulation Tool:** ANSYS HFSS
- **Antenna Type:** Batwing Antenna
- **Operating Band:** L-S Band
- **Polarization:** Linear
- **Radiation Characteristic:** Uni-Directional
- **Main Performance Parameters:** S11, VSWR, realized gain and radiation patterns
- **Radiation Pattern Evaluation Frequencies:** 1.8 GHz, 2.4 GHz and 3.2 GHz
- **3D Radiation Pattern:** Evaluated at 2.4 GHz

## Design Description

The antenna consists of a symmetric flared conductive structure forming the radiating element.It contributes to broadband impedance behavior compared with a conventional narrow dipole structure.

The electromagnetic model was created in ANSYS HFSS and optimized by evaluating the antenna reflection coefficient, voltage standing wave ratio, realized gain and far-field radiation characteristics.

The radiation performance was examined at several frequencies across the operating band in order to observe the variation of the E-plane and H-plane patterns with frequency.

## Materials

- **Radiating Element:** Conductive metallic structure
- **Surrounding Medium:** Air / free-space simulation region
- **Ground / Supporting Structure:** Included according to the simulated antenna configuration

> Note: Exact material properties and mechanical dimensions are intentionally omitted from the public portfolio.

## 3D Model

![Geometry](geometry.png)

## Reflection Coefficient

![S11](S11.png)

## VSWR

![VSWR](VSWR.png)

## Realized Gain

![Realized Gain](Realized%20Gain.png)

## Radiation Patterns

### 1.8 GHz

<p align="center">
  <img src="E-Plane_1,8GHz.png" width="48%">
  <img src="H-Plane_1,8GHz.png" width="48%">
</p>

### 2.4 GHz

<p align="center">
  <img src="E-Plane_2,4GHz.png" width="48%">
  <img src="H-Plane_2,4GHz.png" width="48%">
</p>

### 3.2 GHz

<p align="center">
  <img src="E-Plane_3,2GHz.png" width="48%">
  <img src="H-Plane_3,2GHz.png" width="48%">
</p>

## 3D Radiation Pattern

![3D Radiation Pattern](2,4GHz_3D%20Plot.png)
