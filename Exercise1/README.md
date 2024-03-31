## Project Overview
This project serves as a template for developing ObjectARX applications in the AutoCAD environment. It is set up as an MFC (Microsoft Foundation Classes) Dynamic Link-Library (DLL) with a DLL extension.
## Setup Instructions
1. **Initiate a New ObjectARX Project:**
   - Open Microsoft Visual Studio.
   - Create a new project as an MFC Dynamic Link-Library (DLL) with a DLL extension.
2. **Configure Project for ObjectARX:**
   - Customize C++ and Linker properties to prepare the project for ObjectARX development.
3. **Incorporate Necessary Libraries:**
   - Within the project's properties, establish links with ObjectARX libraries and any other prerequisites essential for AutoCAD applications.
4. **Define acrxEntryPoint Function:**
   - Set up the `acrxEntryPoint` function as the starting point for the ObjectARX application.
   - Handle initialization and unloading messages like `AcRx::kInitAppMsg` and `AcRx::kUnloadAppMsg`.
5. **Execute Command for Message Display:**
   - Implement code to display the message "Hello in the world of AutoCAD" when the command "AddCommand" is entered in AutoCAD.
   - Define a personalized command function (e.g., `addCommand`) and register it using `acedRegCmds->addCommand`.
## Usage
1. Build the project in Microsoft Visual Studio.
2. Load the resulting DLL in AutoCAD.
3. Enter the command "AddCommand" to see the message in the AutoCAD environment.