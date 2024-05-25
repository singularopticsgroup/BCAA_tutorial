---
title: Camera
layout: default
parent: Device communication
nav_order: 2
---
## [](#header-2)Camera

This component is responsible for the app-camera connection. This is initiated by the user. The _Camera menu_ and then _Connect with camera_ button has to be pushed. 
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Connect_with_camera.png">
</p>
Then the component starts working (A) and as the next step determines if the Image Acquisition Toolbox is present in the used version of the MATLAB software (B). Together with that, the app runs through each of the available add-on camera adapter, that enables connection with the camera. Such an add-on has to be installed separately according to the camera manufacturer's documentation, regarding camera operation through MATLAB (C). After the initiation, the user will be able to select one of the active camera adapters (D).
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Connect_with_camera_whole_process.png">
</p>
Which successfully opens the app preview. In the last process, the user has to select the proper camera resolution in the camera selection toolbar:
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Select_camera.png">
</p>
This opens the new window with the live camera preview.
<p align="center">
  <img src="/BCAA_tutorial/assets/images/Camera_preview.png">
</p>

----
