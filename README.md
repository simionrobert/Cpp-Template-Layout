cpp-template-layout
===

`cpp-template-layout` is a template for a simple Visual Studio based C++ solution: it can be used as the basis for new projects.

It is designed for Visual Studio Community 2019 for single or multiple projects inside one solution.

Install
------

To install this project, please ensure that you have installed the following (install guides are provided on the respective websites):

  - [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/)


Project structure
-------------

This project has been set up with a specific file/folder structure in mind. The following describes some important features of this setup:

  - `bin` : Contains the final executabiles (generated)
  - `build`: Contains intermediate files generated during build time (generated)
  - `include`: Public projects header files that need to be exposed (generated)
  - `lib`: External libraries used in the projects
  - `src`: Solution source files (*.cpp), organised in separate folders for multiple .vxcproj projects or only a `main.cpp` for single projects

Options
-------------

You can generate the `.gitignore` file using [gitignore.io](https://www.gitignore.io/)

Build output and intermediate directories for each project can be changed in: 
 - RightClick on project in the solution view /General/OutputDirectory 
 - RightClick on project in the solution view /General/IntermediateDirectory
