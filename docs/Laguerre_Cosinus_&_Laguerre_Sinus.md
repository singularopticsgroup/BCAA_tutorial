---
title: Laguerre-Cosinus & Laguerre-Sinus
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 5

---
## [](#header-2)Laguerre-Cosinus & Laguerre-Sinus

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<p align="center">
  <img src="/BCAA_tutorial/assets/images/Laguerre_SinCos_box.png">
</p>
This functions are responsible for creating amplitude maps of Laguerre-Cosinus and Laguerre-Sinus beams [1]. 
<p align="center">
\(LC^l_{p}=\frac{1}{\sqrt{2}}\left(\frac{\rho}{w_{0}}\right)^{|m|}\exp{\left[\frac{-\rho^2}{w_{0}^2}\right]}\mathbb{L}_{p}^l\exp{[jm\phi]}cos(l\phi),\)
<p>
<p align="center">
\(LS^l_{p}=\frac{1}{\sqrt{2}}\left(\frac{\rho}{w_{0}}\right)^{|m|}\exp{\left[\frac{-\rho^2}{w_{0}^2}\right]}\mathbb{L}_{p}^l\exp{[jm\phi]}sin(l\phi),\)
<p>
where \(m\) is a topological charge, \(\mathbb{L}_{p}^l\) is Laguerre polynomial. The superposition of these two beams creates a Laguerre-Gaussian beam. Users can specify the azimuthal and radial indexes \(l,p\) in both cases. The presented examples shows the Laguerre-Cosinus (A) and Laguerre-Sinus (B) amplitude maps, both for the azimuthal index \(l = 1\) and radial index \(p = 5\).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Laguerre_SinCos.png">
</p>
 
[1] Liu, Kui & Cai, Chunxiao & Li, Juan & Ma, Long & Sun, Hengxin & Gao, J.R., Squeezing-enhanced rotating-angle measurement beyond the quantum limit. Applied Physics Letters (2018). 113. 261103. 10.1063/1.5066028. 

