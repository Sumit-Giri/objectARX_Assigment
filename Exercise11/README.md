# AutoCAD ObjectARX Application
 
## Overview
 
This ObjectARX application introduces the `commandAndSystemVariable` function, designed to interact with the CIRCLERAD system variable in AutoCAD. The function facilitates various tasks as follows:
 
1. Retrieves the current value of the CIRCLERAD system variable using `acedGetVar` and displays it via `acutPrintf`.
2. Defines a center point for a circle (`pt`) and a radius (`rrad`).
3. Executes the CIRCLE command with the provided values utilizing `acedCommandS`.
4. Pauses for user input before finalizing the circle creation with the PAUSE option using another call to the CIRCLE command.
5. Resets the value of the CIRCLERAD system variable back to its original value through `acedSetVar`.
 
## Usage
 
1. **Build and Load:**
   - Open the ObjectARX project in Microsoft Visual Studio.
   - Build the project and load the resulting DLL in AutoCAD.
 
2. **Execute the Command:**
   - In AutoCAD, invoke the designated custom command linked to the `commandAndSystemVariable` function (e.g., "MYCOMMAND").
 
3. **Interact with CIRCLERAD:**
   - Upon execution, the function retrieves and displays the current value of the CIRCLERAD system variable, creates a circle based on specified values, and prompts for user interaction.