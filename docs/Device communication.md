---
title: Device communication
layout: default
has_children: true
nav_order: 2
---
## [](#header-2)Device communication

![](/lbsa/assets/images/Control_full.png)

The main part of this section of BCAA is the communication with external devices. The BCAA requires MATLAB 2023b or newer, with the Image Acqusition Toolbox. Additionally, user is responsible to install adaptors enabling software - camera communication, through add-ons available within MATLAB. At the initation phase, the BCAA will check available components and display their status in the commend line.

In the brought example, three such adaptors were installed: winvideo, gentl, gige. Two among them detected cameras connected to the computer, therefore they were mentioned as a Detected cameras. Additionally, BCAA detected one DMD having the 1920 x 1080 resolution.
<p align="center">
  <img width="599" height="740" src="/BCAA_tutorial/assets/images/control_all.png">
</p>
To sum up the BCAA Device communication section can be divided into three parts. First of them is responsible for the connection with DMD modulator, camera and local hard drive. What’s more user can choose the camera preview and see if the DMD is properly connected. Second part contains the preview of created holograms and in case the DMD is connected, this serves also as a preview of what is currently being displayed on the DMD. The last part enables to load and send external data to DMD screen and control display time of them.






----
