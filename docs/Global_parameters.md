---
title: Global parameters
layout: default
parent: Beam Builder
grand_parent: Graphic User Interface
nav_order: 2
---
## [](#header-2)Global parameters
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Global_parameters.png">
</p>
Useres can control the Blazed grating in x and y direction (diffraction grating). The set diffraction grating will be $w_{0}$ added to all holograms, this is necessary for proper working of DMD. Examples: A) \(x=50\), \(y=50\); B) \(x=300\), \(y=0\).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Blazed_grating_example.png">
</p>
Another two parameters which can be controled by the user are the pixel size (constant for all presented holograms, equal to 8) and rotation of the beam.  Examples: A) \(Rotate=45^{cicr}\); B) \(Rotate=68^{cicr}\).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Rotate_example.png">
</p>



<p align="center">
  <img src="/BCAA_tutorial/assets/images/Gaussian_beam.png">
</p>
This function is responsible for the Gaussian beam generation. Where the basic Gaussian beam equation, assuming that the propagation path equals 0 (z=0), is [1]:
<p align="center">
\(E(x,y,z=0) = exp\left(\frac{-\rho^2}{w_{0}^2}\right)\), where \(\rho = \sqrt{x^2+y^2}\)
<p>
The \(w_{0}\) is a beam waist, which users can control.
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Beam_waist.png">
</p>
The generated amplitude map is presented below, A) for \(w_{0}=1\) and B) \(w_{0}=2\), both with \(blazed\) \(grating\) \(x,y=300\) :
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Gauss1_2.png">
</p>
