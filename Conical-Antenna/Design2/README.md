# Asymmetric Conical Antenna

## Overview

This design presents an asymmetric conical antenna developed and analyzed using ANSYS HFSS for operation from 1 GHz to 3 GHz.

Unlike a conventional rotationally symmetric conical radiator, this antenna employs an asymmetric conical geometry. The asymmetric structure is used to shape the current distribution and radiation behavior while maintaining broadband impedance characteristics across the intended operating band.

The radiating conical elements are made of copper, while the lower metallic ground/base plate is modeled using aluminum. The antenna is excited through an RG402 semi-rigid coaxial cable.

The antenna performance was evaluated using reflection coefficient, VSWR, realized gain, azimuth and elevation radiation patterns, and three-dimensional far-field radiation patterns at multiple frequencies across the operating band.

## Key Features

- **Simulation Tool:** ANSYS HFSS
- **Antenna Type:** Conical Antenna
- **Operating Frequency Range:** 1–3 GHz
- **Structure Type:** Asymmetric Conical Radiator
- **Polarization:** Linear
- **Radiation Characteristic:** Omni-directional
- **Feed Type:** Coaxial Feed
- **Coaxial Cable:** RG402 Semi-Rigid
- **Main Performance Parameters:** S11, VSWR, realized gain and radiation patterns
- **Radiation Pattern Evaluation Frequencies:** 1 GHz, 2 GHz and 3 GHz
- **Analyzed Planes:** Azimuth and Elevation

## Materials

- **Conical Radiating Elements:** Copper
- **Ground / Base Plate:** Aluminum
- **Feed Cable:** RG402 semi-rigid coaxial cable
- **Surrounding Medium:** Air / free-space simulation region
- **Simulation Environment:** ANSYS HFSS

## 3D Model

<table>
<tr>
<td align="center">
  <img src="geometry1.png" width="100%"><br>
</td>
<td align="center">
  <img src="geometry2.png" width="100%"><br>
</td>
</tr>
</table>

## Reflection Coefficient

![S11](S11.png)

## VSWR

![VSWR](VSWR.png)

## Realized Gain

![Realized Gain](Realized%20Gain.png)

## Radiation Patterns

### 1 GHz

#### Azimuth Pattern

![1 GHz Azimuth](1GHz_Azimuth.png)

#### Elevation Pattern

![1 GHz Elevation](1GHz_Elevation.png)

#### 3D Radiation Pattern

![1 GHz 3D Radiation Pattern](1GHz_3D%20Plot.png)

### 2 GHz

#### Azimuth Pattern

![2 GHz Azimuth](2GHz_Azimuth.png)

#### Elevation Pattern

![2 GHz Elevation](2GHz_Elevation.png)

#### 3D Radiation Pattern

![2 GHz 3D Radiation Pattern](2GHz_3D%20Plot.png)

### 3 GHz

#### Azimuth Pattern

![3 GHz Azimuth](3GHz_Azimuth.png)

#### Elevation Pattern

![3 GHz Elevation](3GHz_Elevation.png)

#### 3D Radiation Pattern

![3 GHz 3D Radiation Pattern](3GHz_3D%20Plot.png)
