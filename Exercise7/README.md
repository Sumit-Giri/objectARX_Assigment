# AutoCAD ObjectARX Application - Drawing Lines
 
## Overview
 
This ObjectARX application introduces the `inputLine` function, facilitating the drawing of lines in AutoCAD through interactive input of two points by the user. Subsequently, the line is incorporated into the current space block of the drawing.
 
## Functionality
 
The `inputLine` function carries out the following operations:
 
1. Accesses the current AutoCAD database.
2. Retrieves the current space block, commonly Model Space or Paper Space.
3. Initiates user prompts to input the first point using `acedGetPoint`.
4. Upon successful acquisition of the first point, proceeds to prompt the user for the second point.
5. Upon obtaining both points successfully, generates a new AcDbLine object utilizing the specified points.
6. Incorporates the new Line object into the current space block.
7. Concludes by closing both the current space block and the Line object.
 
## Usage
 
1. **Compilation and Loading:**
 
   - Launch the ObjectARX project in Microsoft Visual Studio.
   - Compile the project and load the resulting DLL within AutoCAD.
 
2. **Executing the Command:**
 
   - Within AutoCAD, execute the designated custom command linked to the `inputLine` function (e.g., "DRAWLINE").
 
3. **Following Prompts:**
 
   - Respond to the prompts to interactively input the first and second points.
 
4. **Observing Result:**
 
   - Observe the creation of a line based on the input points, subsequently added to the current space block.