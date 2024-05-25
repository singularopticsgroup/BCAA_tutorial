---
title: Airy beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 7
---
## [](#header-2)Airy beam
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Airy_beam_box.png">
</p>
This function is responsible for the Airy beam hologram generation. Airy beam can be defined as:
<p align="center">
\(E(x,y)= Ai\left(\frac{Xk_{r}}{s}\right)Ai\left(\frac{Yk_{r}}{s}\right)exp\left(bk_{r}\left(\frac{X+Y}{s}\right)\right),\)
<p>
where \(Ai\) is Airy function, \(X,Y\) - x,y coordinate defined as the resolution of DMD, \(s\) - scale, \(b\) - phase factor. Below is an example of Airy beam hologram with various parameters: A) \(b=0\), \(s=1\); B) 
\(b=0\), \(s=3\); C) \(b=0.15\), \(s=1\); D) \(b=0.15\), \(s=3\).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Airy_beam.png">
</p>
