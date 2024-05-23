---
title: Super Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 2

---
## [](#header-2)Super Gaussian beam

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Gaussian_beam.png">
</p>
Super Gaussian beam equation, assuming that the propagation path equals 0 (z=0), is [1]:
<p align="center">
\(E(x,y,z=0) = exp\left(\frac{-\rho^2}{w_{0}^2}\right)^{Gi}\), where \(\rho = \sqrt{x^2+y^2}\)
<p>
The \(w_{0}\) is a beam waist and parameter \(Gi\) is an order of Super-Gaussian beam, both of them users can control. Where for \(Gi=1\) Super-Gaussian beam becomes regular Gaussian beam.
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Beam_waist.png">
</p>
The generated amplitude map is presented below, A) for \(w_{0}=1\) and B) \(w_{0}=2\), both with \(blazed grating x,y=300\) :
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Gauss1_2.png">
</p>


The function responsible for the Super Gaussian beam design allows the user to control the Gi parameter. 
Below, is an example of a Super Gaussian beam with Gi=0 (Gaussian beam) and Gi=2. 


 


