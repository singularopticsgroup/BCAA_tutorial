---
title: Technical Panel
layout: default
nav_order: 4
has_children: false
---
## [](#header-2)Technical Panel
**DMD Base Control Constructor**


The first critical operation involves a decision diamond titled "Does input exist?" This checks for the necessary input parameters such as _libName_, _hFileName_, and _deviceNum_, which are essential for configuring the system.
 
If the inputs are absent, the path from the decision diamond indicates that the system will automatically fill the input fields with default values or placeholders, such as empty brackets. This step prepares the system for initialization even without specific user inputs.
 
Moving on to the _Initiate DLL_ phase, this function begins by assessing if the inputs are still empty after the attempt to populate them with default values. If they are, it fills them with defaults and proceeds to load the DLL library corresponding to the _libName_ and _hFileName_. This step is crucial as it establishes the linkages required for subsequent device interactions.
 
The next segment, _Initiate Device_, deals with direct hardware interactions. It involves connecting to the device using the DLL, retrieving device properties such as Device ID and DMD size, and assigning these properties to ensure the device is configured correctly and ready for operation.y configurations and dependencies are correctly handled before any device operations begin.
 
**callDLLFun**


The function within the DLL is called using the syntax _calllib(obj.libName, funName, varargin{:})_, with the funName (the name of the function) and varargin (a list of variable arguments) as inputs.
 
Next, the _returnValue Decision_ block evaluates the returnValue from the DLL function call. If returnValue is empty, the process identifies pointers within varargin and moves to extract and retrieve values from these pointers. If returnValue is not empty, the flow proceeds to the _checkReturnFlag_ decision block.
 
The _checkReturnFlag_ decision block assesses whether a flag within the returnValue, which typically indicates success or an error, is correct. If the flag indicates an error, a warning is displayed that includes the function name and the flag, alerting the user to the issue.
 
In the _Pointers Handling_ step, if the returnValue was empty, the system extracts pointers from varargin and retrieves values from these pointers. The extracted values are then either outputted or processed further as required.
