# Read Me
Executing in Visual Studio 2019
#Step 1:
-Create new Visual C++ Empty Project lets say Project1
-Create new C++ file within your project
-Paste code in the created C++ file

#Step 2:
-Right click on Project1 > Properties > C/C++ > Additional Include Directories > Click on the dropdown box
-Click on edit > folder > Desktop > Glew and Glut > freeglut > include
 Then do the same and include Glew and Glut > glew-1.11.0 > include
 -Click OK
 
 -Linker > Input > Additional Dependancies > Click on the dropdown box
 -Click on edit then type these two filenames
  freeglut.lib
  glew32.lib
-Click OK

-Linker > General > Additional Library Dictionarries > Click on the dropdown box
-Click on edit > folder > Desktop > Glew and Glut > freeglut > lib
 Then do the same and include Glew and Glut > glew-1.11.0 > lib
 -Click OK
 
 -Apply > OK
 
 #Step 3:
 -Copy the following files Desktop > Glew and Glut > freeglut.dll glew32.dll
 -Then right click on Project1 > Open Folder inn File Explorer
 -Paste the copied files
 
 #Step 4:
 -Click on Local Windows Debugger to run the program
