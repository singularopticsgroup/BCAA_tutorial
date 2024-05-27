---
title: Zernike polynomials
layout: default
parent: Graphic User Interface
nav_order: 3
---
## [](#header-2)Zernike polynomials

In order to manually introduce or subtract aberration, the Zernike polynomial component has been added as a separate function. 
It allows the user to introduce Zernike polynomials, by specifying the value of polynomials having an azimuthal and radial index, 
according to:
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Zernike_definition.png">
</p>

Which is mirrored in the BCAA:
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Zernike_BCAA.png">
</p>

Each polynomial is calculated on the unitary disk, where the shorter side of the set resolution is taken as the disk diameter. 
By default, the function is restricted to 3rd-order Zernike polynomials, however,
 more complex holograms can be easily achieved by the combination of those available.
As the result, the set of polynomials will be combined into the final hologram and superposed with other BCAA functions, in the control panel.  

The examples of using Zernike polynomial are presented below: A) Laguerre-Gaussian beam _p=0_, _l=1_, _beam waist=2_; B) Laguerre-Gaussian beam _p=0_, _l=1_, _beam waist=2_ with Vertical astigmatism _Value=100_; C) Laguerre-Gaussian beam _p=0_, _l=1_, _beam waist=2_ with Vertical coma _Value=100_; D) Laguerre-Gaussian beam _p=0_, _l=1_, _beam waist=2_ with Defocuse _Value=100_. There is no necessary to use such a huge value, in real experimental setup affects of Zernike polynomials on real beam are noticeable for significantly smaller values (e.g. 1-10). But changes in amplitude hologramsthere are bearly seen, that's why here values equal to 100 are implemented.
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Zernike_example.png">
</p>
