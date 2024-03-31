# AutoCAD ObjectARX Application - Load and Unload in AutoCAD
## Overview
This AutoCAD ObjectARX application is for loading and unloading of a ObjectARX dll file in AutoCAD.
 
## Integration Steps
### 1. Building the Debug Version:
 
   - Launch the ObjectARX project in Microsoft Visual Studio.
   - Compile the debug version of the project.
 
### 2. Loading the ObjectARX File:
 
   - In AutoCAD, utilize the "APPLOAD" command accessible via the AutoCAD command line.
   - Navigate to and load the compiled ObjectARX DLL (debug version) into AutoCAD.
 
### 3. Unloading Feature:
 
   - Upon completion of using the custom command, unload the feature by executing the following steps:
     - Click on the "Unload" command within the Appload window.
     - Alternatively, use the "NETUNLOAD" command via the AutoCAD command line.
 
## Usage
 
1. **Building the Debug Version:**
   - Open the ObjectARX project in Microsoft Visual Studio.
   - Compile the debug version of the project.
 
2. **Loading the ObjectARX File:**
   - Within AutoCAD, input the "APPLOAD" command in the AutoCAD command line.
   - Navigate to and load the compiled ObjectARX DLL (debug version) into AutoCAD.
 
3. **Executing the Custom Command:**
   - In AutoCAD, input the custom command "AddCommand" via the AutoCAD command line.
   - Upon execution, the command will display the message "Welcome in the World of AutoCAD."
 
4. **Unloading the Feature:**
   - After utilizing the custom command, unload the feature by using either the "Unload" command in the Appload window or the "NETUNLOAD" command in the AutoCAD command line.