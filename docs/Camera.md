---
title: Camera
layout: default
parent: Device communication
nav_order: 2
---
## [](#header-2)Camera

This component is responsible for the app-camera connection. This is initiated by the user. The _Camera menu_ and then _Connect with camera_ button has to be pushed. Then the component starts working (A) and as the next step determines if the Image Acquisition Toolbox is present in the used version of the MATLAB software (B). Together with that, the app runs through each of the available add-on camera adapter, that enables connection with the camera. Such an add-on has to be installed separately according to the camera manufacturer's documentation, regarding camera operation through MATLAB (C). After the initiation, the user will be able to select one of the active camera adapters (D).

![](/assets/images/Connect_with_camera_whole_process.png)


Which successfully opens the app preview. In the last process, the user has to select the proper camera resolution in the camera selection toolbar:


This opens the new window with the live camera preview.

User can easily modify camera parameters, such as brightness, contrast, expsoure or gain. To do so, once the preview is open, user has to click the _Options_ push botton, which will open a new pop-up window, where these parameters can be modified: 



Once these parameters are set, the _Ok_ push button updates their values. User can modify each parameter either through the edit field or using the slider just next to it.

----
