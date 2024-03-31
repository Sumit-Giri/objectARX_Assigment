# AutoCAD ObjectARX Application - Adding Layer Functionality
 
## Overview
 
This ObjectARX application introduces the `addLayer` function, designed to manage the presence of a layer named "OBJ" within the current AutoCAD drawing. Should the "OBJ" layer be absent, the function dynamically creates it, configuring specific properties as required.
 
## Functionality
 
The `addLayer` function executes the following operations:
 
1. **Verify Existing Layer:**
 
   - Scans the Layer Table to confirm the existence of a layer named "OBJ."
 
2. **Generate New Layer if Absent:**
 
   - In the event of non-existence, the function proceeds to:
 
     - Access the Layer Table for modification.
 
     - Generate a new AcDbLayerTableRecord to represent the "OBJ" layer.
 
     - Define the layer's name as "OBJ" and its color as cyan.
 
     - Incorporate the fresh layer into the Layer Table.
 
     - Conclude by closing both the Layer Table and the created layer record to release resources.
 
## Usage
 
1. **Compilation and Loading:**
 
   - Initiate the ObjectARX project in Microsoft Visual Studio.
 
   - Compile the project and load the ensuing DLL within AutoCAD.
 
2. **Executing the Command:**
 
   - Within AutoCAD, invoke the designated custom command tied to the `addLayer` function (e.g., "ADDLAYER").
 
3. **Observing Outcomes:**
 
   - Witness the function's execution, ensuring the presence of a "OBJ" layer within the drawing, complete with specified properties if necessary.