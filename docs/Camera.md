---
title: Camera
layout: default
parent: Device communication
nav_order: 2
---
## [](#header-2)Camera

This component is responsible for the app-camera connection. This is initiated simultaneously with the start of an app. The component first determines if the Image Acquisition Toolbox is present in the used version of the MATLAB software.
Together with that, the app runs through each of the available add-on camera adapter, that enables connection with the camera. Such an add-on has to be installed separately according to the camera manufacturer's documentation, regarding camera operation through MATLAB.
<p align="center">
  <img src="./assets/images/Connect_with_camera_whole_process.png">
</p>
![](/./assets/images/Connect_with_camera_whole_process.png)
The step-by-step notifications of this process are displayed in the command line:



After the initiation, the user will be able to select one of the active camera adapters:



Which successfully opens the app preview. In the last process, the user has to select the proper camera resolution in the camera selection toolbar:


This opens the new window with the live camera preview.

User can easily modify camera parameters, such as brightness, contrast, expsoure or gain. To do so, once the preview is open, user has to click the _Options_ push botton, which will open a new pop-up window, where these parameters can be modified: 



Once these parameters are set, the _Ok_ push button updates their values. User can modify each parameter either through the edit field or using the slider just next to it.

----
