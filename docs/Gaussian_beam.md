---
title: Gaussian beam
layout: default
parent: Light Structuring
grand_parent: Graphic User Interface
nav_order: 1

---
## [](#header-2)Gaussian beam

![](/lbsa/assets/images/Airy.png)


This function is responsible for the Gaussian beam generation. Where the basic Gaussian beam equation, assuming that the propagation path equals 0 (z=0), is [1]:
\begin{align}
E(x,y) = exp(\frac{-\rho^2}{w_{0}^2}), where \rho = \sqrt{x^2+y^2}
\end{align}


 
The  w_{0} is a beam waist, which users can control.

The generated amplitude map is presented below:

<p align="center">
$(x,y) = exp(\frac{-\rho^2}{w_{0}^2})$, where $\rho = \sqrt{x^2+y^2}$
<p>


When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are:
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

_Square root of 9_
$$\sqrt{9}$$

![](/lbsa/assets/images/Airy.bmp)

[1] B.E.A. Saleh and M.C. Teich. Fundamentals of Photonics. Wiley Series in Pure and Applied Optics. Wiley, 2019.
 


