---
title: Laguerre-Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 4

---
## [](#header-2)Laguerre-Gaussian beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Laguerre_Gaussian_box.png">
</p>
This function is responsible for the generation of the amplitude map of Laguerre-Gaussian beam. Laguerre-Gaussian beam can be defined by the equation [1,2]: 
<p align="center">
\(LG^l_{p}=\frac{1}{\sqrt{2}}\left(\frac{\rho}{w_{0}}\right)^{|m|}\exp{\left[\frac{-\rho^2}{w_{0}^2}\right]}\exp{[jm\phi]}\)
<p>
Users can specify the azimuthal and radial indexes \(l,p\) and the beam waist \(w_{0}\). An example below represents: A) Laguerre-Gaussian beam \(l = 1\), \(p = 0\) and \(w_{0} = 1\), B) Laguerre-Gaussian beam \(l = 1\), \(p = 3\) and \(w_{0} = 1\):
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Laguerre_Gaussian.png">
</p>


[1] Marek Wichtowski. Optyka liniowa. Wydawnictwo Naukowe PWN, Warszawa, 2020.

[2] Rüdiger Paschotta. Beam quality deterioration of lasers caused by intracavity beam distortions. Opt. Express, 14(13):6069–6074, Jun 2006
