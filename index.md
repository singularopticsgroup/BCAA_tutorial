---
title: Introduction
layout: home
nav_order: 1
---
This tutorial was created to ensure support for the Binary Complex Amplitude App (BCAA), which was created in MATLAB software. Created to control over beam shaping processes. BCAA allows user to control both the Digital Micromirror Device (DMD) and an external camera.

To operate, it requires a MATLAB R2023b or newer with an active Image Acquisition Toolbox and optional Add-ons that enable MATLAB – camera communication.

The application is divided into two sections. The left section stands as an **control** one, allowing the user to see what kind of hologram is currently displayed at the DMD Screen, to load external data or control the external camera. The right section is responsible for **beam shaping** - the modification of hologram parameters as well as for operating the beam correction algorithms.

![](./assets/images/BCAA_v2.png)


fsdgdgfsdg

1. **Rayleigh Range**:

   $$ z_R = \frac{\pi w_0^2}{\lambda} $$

2. **Beam Radius**:

   $$ w(z) = w_0 \sqrt{1 + \left(\frac{z}{z_R}\right)^2} $$

3. **Electric Field Distribution**:

   $$ E(x,y,z) = E_0 \frac{w_0}{w(z)} \exp\left(-\frac{x^2 + y^2}{w(z)^2}\right) $$
