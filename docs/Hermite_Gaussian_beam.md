---
title: Hermite-Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 3

---
## [](#header-2)Hermite-Gaussian beam

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<p align="center">
  <img src="/BCAA_tutorial/assets/images/Hermite_Gaussian_box.png">
</p>

To generate an Hermite-Gaussian beam, the user has to specify two parameters: the vertical mode index _m_ and the horizontal mode index _n_. Both parameters are crucial in Hermite-Gaussian equetion [1]: 
<p align="center">
\(HG_{n,m} = \frac{1}{w_{0}}\mathbb{G}_{n}\left[\frac{\sqrt{2}\cdot x}{w_{0}}\right]\mathbb{G}_{m}\left[\frac{\sqrt{2}\cdot y}{w_{0}}\right]exp\left(\frac{-\rho^2}{w_{0}^2}\right)\),
<p>
where 
<p align="center">
  \(\mathbb{G}_{n}(u)=\mathbb{H}_{n}exp\left( \frac{-u^2}{2} \right) \), \(n=0,1,2,...\)
<p>
<p align="center">
  \(\mathbb{G}_{m}(u)=\mathbb{H}_{m}exp\left( \frac{-u^2}{2} \right) \), \(m=0,1,2,...\).
<p> 
The \(\mathbb{H}_{n}\) and \(\mathbb{H}_{m}\) are known as Hermite polynomial of order \(n,m\).
An example below presents the amplitude map of Hermite-Gaussian beam: A) for the horizontal mode \(n=3\) and the vertical mode \(m=3\), B) \(n=5\) and \(m=2\).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Hermite_Gaussian.png">
</p>
 
[1] B.E.A. Saleh and M.C. Teich. Fundamentals of Photonics. Wiley Series in Pure and Applied Optics. Wiley, 2019.

