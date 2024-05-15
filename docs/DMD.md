---
title: DMD
layout: default
parent: Device communication
nav_order: 1
---
## [](#header-2)DMD
If the DMD is properly connected and BCAA has detected it, the black diode will turn green. Moreover, the DMD resolution will be automatically detected and displayed under the mentioned diode. If DMD is not connected the default value of the resolution is 1920x1080.
<p align="center">
  <img src="/./assets/images/DMD Resolution.png">
</p>
Additionally, the list box provides an option to select the available camera.

Central push buttons (`start`, `save`, and `snapshot`) are responsible for communication with external hardware. In particular, `start` forces the recalculation of the currently displayed hologram, in case any parameter has been modified. `Save` allows the user to export the currently displayed hologram as an external image file and finally `snapshot` initiates the screenshot of the image currently captured by the camera, which can be saved on the computer hard drive. 

The toggle button `Auto update` switches between auto/manual mode. By default, the app operates in manual mode, which requires updating the hologram manually, through the `Start` button. The auto-update performs the update automatically. 

SLM Screen provides insights into the structure of the hologram currently displayed on the SLM. This will also remain active, even if the SLM is not connected, allowing to use the LBSA independently, as a hologram designing software. To do so, the user can modify the SLM resolution to control the resolution of the hologram that will be created. 
   
![](/lbsa/assets/images/Control.png)
----
