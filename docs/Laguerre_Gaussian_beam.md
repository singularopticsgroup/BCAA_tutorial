---
title: Laguerre-Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 4

---
## [](#header-2)Laguerre-Gaussian beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
This function is responsible for the generation of the amplitude map of Laguerre-Gaussian beam. 
Users can specify the azimuthal and radial indexes (_l,p_).



An example below represents: A) Laguerre-Gaussian beam _l_ = 1 _p_ = 0, B) Laguerre-Gaussian beam _l_ = 1 _p_ = 3
<p align="center">
\(U_{l,m}(\rho,\phi,z)=A_{l,m}\left[ \frac{W_{0}}{W(z)} \right]\left( \frac{\rho}{W(z)} \right)^l \mathbb{L}_{m}^l\left( \frac{2\rho^2}{W^2(z)} \ \right)\exp{\left( -\frac{\rho^2}{W^2(z)} \right)} \\
\times \ \exp{\left[ -jkz -jk\frac{\rho^2}{2R(z)}+jm\phi+j(l+2m+1)\varsigma(z) \right]}\)
<p>
 


