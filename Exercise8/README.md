# AutoCAD ObjectARX Application - Color Modification
 
## Overview
 
This ObjectARX application introduces the `changeColor` function, facilitating the interactive alteration of selected object colors within AutoCAD. Users are prompted to select objects, input color specifications, and subsequently witness the color transformation of the chosen objects based on their input.
 
## Functionality
 
The `changeColor` function executes the following steps:
 
1. **Object Selection Prompt:**
   - Prompts the user to select objects within AutoCAD.
 
2. **Color Selection Prompt:**
   - If objects are selected, the function prompts the user to input a color keyword or numeric value, defaulting to "Red" if no input is provided.
 
3. **Color Modification of Selected Objects:**
   - Iterates through the selected objects, adjusting their colors as per the user's input.
   - Users can specify colors using keywords ("Red," "Yellow," "Green") or numeric values (1, 2, 3).
   - If the user selects "Bylayer," the object's color defaults to the layer color.
 
4. **Closure of Selected Objects:**
   - Concludes by closing the selected objects post-color modification.
 
## Usage
 
1. **Compilation and Loading:**
   - Launch the ObjectARX project in Microsoft Visual Studio.
   - Compile the project and load the resulting DLL within AutoCAD.
 
2. **Executing the Command:**
   - Within AutoCAD, execute the designated custom command linked to the `changeColor` function (e.g., "CHANGECOLOR").
 
3. **Object Selection:**
   - Utilize AutoCAD's selection tools to choose objects within the drawing.
 
4. **Color Specification:**
   - Provide a color keyword or numeric value when prompted.
 
5. **Observing the Outcome:**
   - Witness the color modification of the selected objects based on the user's input.