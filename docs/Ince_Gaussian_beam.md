---
title: Ince-Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 8
---
## [](#header-2)Ince-Gaussian beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Ince_Gaussian_beam_box.png">
</p>
The Ince-Gaussian beam is a more complex solution of the wave equation that can be expressed using the Ince function. These beams are defined in elliptic coordinates and are a generalization of the Hermite-Gaussian and Laguerre-Gaussian beams. The Ince-Gaussian beam equation is presented below [1]:
<p align="center">
\(E^{Parity}_{p,m}(\theta,\xi,z=0)=\frac{C_{p,m}}{w0}C^{m}_{p}(ec,\theta)C^{m}_{p}(ec,j\xi)exp\left(-\left(\frac{X^2+Y^2}{w0}\right)^2\right),\)
<p>
where \(C_{p,m}\) - normalization constant, \(C^{m}_{p}\) - even or odd Ince functions of order \(p\) and degree \(m\), \(m\) and \(p\) are the radial and angular elliptic mode numbers, \(ec\) - ellipticity parameter, (\(\xi, \theta\)) - elliptic coordinates, (\(X, Y\)) - Cartesian coordinates.
  
Users can modify 
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Ince_Gaussian_even.png">
</p>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Ince_Gaussian_odd.png">
</p>



[1] Zhou, G., Zhu, K., & Liu, F. (2007). Vectorial structure of Ince–Gaussian beam in the far field. Journal of Modern Optics, 54(18), 2807–2817. https://doi.org/10.1080/09500340701243616
