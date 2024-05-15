---
title: DMD
layout: default
parent: Device communication
nav_order: 1
---
## [](#header-2)DMD
If the DMD is properly connected and BCAA has detected it, the black diode will turn green. Moreover, the DMD resolution will be automatically detected and displayed under the mentioned diode. If DMD is not connected the default value of the resolution is 1920x1080.
<p align="center">
  <img src="/./assets/images/DMD_Resolution.png">
</p>

Central push buttons (`Start`, `Save`, `Stop`, and `Free`) are responsible for communication with external hardware. In particular, `start` forces the recalculation of the currently displayed hologram, in case any parameter has been modified. `Save` allows the user to export the currently displayed hologram as an external image file. When external data is loaded and displayed with a fixed time on the DMD screen, the `Stop` button can be used to stop displaying new holograms. Then the `Free` button can be used to free device memory. Thanks to that the whole process can be repeated.  

SLM Screen provides insights into the structure of the hologram currently displayed on the SLM. This will also remain active, even if the SLM is not connected, allowing to use the LBSA independently, as a hologram designing software. To do so, the user can modify the SLM resolution to control the resolution of the hologram that will be created. 
   

----
