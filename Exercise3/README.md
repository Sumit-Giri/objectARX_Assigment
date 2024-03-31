# AutoCAD ObjectARX Application - Hello World
## Overview
This ObjectARX application defines a custom command, "AddCommand," that displays the message "HElLO OM" when the user enters the command in the AutoCAD command line.
## Initialization
1. **Unlock and Register as MDI Aware:**
   - Unlock and register the application as MDI (Multiple Document Interface) aware.
2. **Print Initialization Message:**
   - Outputs a message to the AutoCAD command line, indicating successful loading of the application.
3. **Register New Modal Command:**
   - Registers a new modal command named "AddCommand" within the "MyGroup" group.
   - Associates the command with the `AddCommand` function in the `CExerciset3App` class.
## Custom Command - Display
The `addCommand` function defines the behavior of the custom command "AddCommand." When invoked, it prints the message "Welcome to the World of AutoCAD!!!" to the AutoCAD command line.
## Unload
1. **Print Unload Message:**
   - Outputs a message to the AutoCAD command line, indicating that the application is being unloaded.
## Usage
1. **Build and Load:**
   - Open the ObjectARX project in Microsoft Visual Studio.
   - Build the project and load the resulting DLL in AutoCAD.
2. **Run the Command:**
   - In AutoCAD, enter the custom command "AddCommand" in the command line.
3. **View Results:**
   - The command will display the message "Welcome in the World of AutoCAD" in the AutoCAD command line.
 