---
title: Bessel beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 6
---
## [](#header-2)Bessel beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Bessel_beam_box.png">
</p>
To generate the Bessel beam, user has to specify two parameters: refractive index and axicon angle. Moreover user can add optical vortex by controling the topological charge \(m\). Thanks to that the perfect optical vortex will be obtained. All parameters can be found in Bessel beam equation [1]:
<p align="center">
\(E(\rho,\phi)= \mathbb{J}_{1}(k_{r}r)\exp{\left(jk_{z}z\right)}\exp{(jm\phi)},\)
<p>
where \(\mathbb{J}_{1}\) is a Bessel function of first kind, \(k_{r}\) - wave vector in \(r\) direction, \(r\) - radius (distance from the beam axis), \(k_{z}\) - wave vector in \(z\) direction, \(m\) - topological charge. 
Examples of the generated amplitude maps are below. First one shows how manipulation of axicon angels affects final hologram. A) \(refractive\: index = 1.1\), \(axicon\\ angle = 0.2^{\circ}\), \(m = 0\); B) \(refractive\; index = 1.1\), \(axicon angle = 0.5^{\circ}\), \(m = 0\)
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Bessel_axicon.png">
</p>
