---
title: Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 1
---
## [](#header-2)Gaussian beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
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
The generated amplitude map is presented below, A) for \(w_{0}=1\) and B) \(w_{0}=2\), both with _blazed grating_ \(x,y=300\) :
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Gauss1_2.png">
</p>

[1] B.E.A. Saleh and M.C. Teich. Fundamentals of Photonics. Wiley Series in Pure and Applied Optics. Wiley, 2019.
 


