# 0.8–6 GHz Cavity-Backed Spiral Antenna

## Overview

This design presents a wideband cavity-backed spiral antenna developed and analyzed using ANSYS HFSS for operation from 0.8 GHz to 6 GHz.

The antenna employs an exponentially tapered balun to support broadband impedance transformation and feeding. The spiral antenna and balun are implemented on an FR-4 substrate with a different thickness.

A conventional spiral antenna generally exhibits bi-directional radiation characteristics. In this design, a cavity-backed configuration is used in order to obtain a unidirectional radiation pattern. Eccosorb AN77 absorber material is placed inside the cavity to reduce unwanted internal reflections.

The antenna performance was evaluated using reflection coefficient, VSWR, realized gain, axial ratio versus frequency and cross-polar discrimination (XPD). In addition, E-plane, H-plane, axial-ratio radiation patterns and 3D realized gain patterns were examined at multiple frequencies across the operating band.

## Key Features

- **Simulation Tool:** ANSYS HFSS
- **Antenna Type:** Cavity-Backed Spiral Antenna
- **Operating Frequency Range:** 0.8–6 GHz
- **Polarization:** Circular Polarization
- **Radiation Characteristic:** Uni-directional
- **Feeding Structure:** Exponentially Tapered Balun
- **Main Performance Parameters:** S11, VSWR, realized gain, axial ratio and XPD
- **Radiation Pattern Evaluation Frequencies:** 1, 2, 3, 4, 5 and 6 GHz
- **Analyzed Planes:** E-Plane and H-Plane

## Materials

- **Spiral Antenna Substrate:** FR-4
- **Balun Substrate:** FR-4
- **Absorber Material:** Eccosorb AN77
- **Surrounding Medium:** Air / free-space simulation region
- **Simulation Environment:** ANSYS HFSS

## Exponentially Tapered Balun Geometry

<table>
<tr>
<td align="center">
  <img src="Exponentialy Tapered Balun geometry1.png" width="100%">
</td>
<td align="center">
  <img src="Exponentialy Tapered Balun geometry2.png" width="100%">
</td>
</tr>
</table>

## Spiral Antenna Geometry

<table>
<tr>
<td align="center">
  <img src="Spiral%20geometry.png" width="100%">
</td>
<td align="center">
  <img src="Cavity%20backed%20spiral%20geometry.png" width="100%">
</td>
</tr>
</table>

## Reflection Coefficient

![S11](S11.png)

## VSWR

![VSWR](VSWR.png)

## Realized Gain

![Realized Gain](Realized%20Gain.png)

## Axial Ratio vs Frequency

![Axial Ratio vs Frequency](Axial%20Ratio_v_Frequency.png)

## Cross Polar Discrimination (XPD)

![Cross Polar Discrimination](Cross%20Polar%20Discrimination.png)

## Radiation Patterns

### 1 GHz

<table>
<tr>
<td align="center">
  <img src="1GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="1GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="1GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="1GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>

### 2 GHz

<table>
<tr>
<td align="center">
  <img src="2GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="2GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="2GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="2GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>

### 3 GHz

<table>
<tr>
<td align="center">
  <img src="3GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="3GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="3GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="3GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>

### 4 GHz

<table>
<tr>
<td align="center">
  <img src="4GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="4GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="4GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="4GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>

### 5 GHz

<table>
<tr>
<td align="center">
  <img src="5GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="5GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="5GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="5GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>

### 6 GHz

<table>
<tr>
<td align="center">
  <img src="6GHz_E-Plane.png" width="100%">
</td>
<td align="center">
  <img src="6GHz_H-Plane.png" width="100%">
</td>
</tr>
<tr>
<td align="center">
  <img src="6GHz_Axial%20Ratio%20Radiation%20Pattern.png" width="100%">
</td>
<td align="center">
  <img src="6GHz_Realized%20Gain%20Plot%203D.png" width="100%">
</td>
</tr>
</table>
