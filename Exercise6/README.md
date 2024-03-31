# AutoCAD ObjectARX Application - Listing Objects
 
## Overview
 
This ObjectARX application introduces the `listObjects` function, tailored to retrieve and exhibit the class names of all objects within the current space of an AutoCAD drawing. The acquired class names are promptly showcased within the AutoCAD Text Window.
 
## Functionality
 
The `listObjects` function executes the following operations:
 
1. Obtains access to the current AutoCAD database.
2. Retrieves the current space object, typically Model Space or Paper Space.
3. Iterates through each object within the current space.
4. For each object, retrieves the entity and displays its class name.
5. Ensures the closure of each entity post retrieval and display of its class name.
6. Concludes by closing the current space object.
7. Clears the block iterator object from memory.
8. Initiates the display of the AutoCAD Text Window.
 
## Usage
 
1. **Compilation and Loading:**
 
   - Launch the ObjectARX project in Microsoft Visual Studio.
   - Compile the project and load the resulting DLL within AutoCAD.
 
2. **Executing the Command:**
 
   - Within AutoCAD, execute the designated custom command linked to the `listObjects` function (e.g., "LISTOBJECTS").
 
3. **Reviewing Results:**
 
   - Observe the function's execution, with the class names of all objects within the current space promptly displayed within the AutoCAD Text Window.