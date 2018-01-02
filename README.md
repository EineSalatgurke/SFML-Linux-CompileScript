# SFML-Linux-CompileScript
  This is my first Bash-Script, so there may be a lot of unnessecary stuff in there.  
  Also I never learned Bash-Scripting, I just wanted a handy Console-Command for compiling my SFML-Code.  
  
## Requirements
You need the default SFML-Installation for Linux.  
__Installation:__
```
$ sudo apt-get install libsfml-dev
```
The script needs the *-lsfml-system*, *-lsfml-window*, ... options.
You can get further information [here](https://www.sfml-dev.org/tutorials/2.0/start-linux.php).
  
## How to use
  Example for a Project-Layout:  

  ![ProjectLayout](https://raw.githubusercontent.com/EineSalatgurke/SFML-Linux-CompileScript/master/projectLayout.png)
  * Your \*.cpp-Files need to be located in the *SourceFiles*-Folder
  * Your \*.h-Files need to be located in the *HeaderFiles*-Folder

  __Console-Command to Complie the Example:__
  ```
  ${ProjectFolder} sfmlc main.cpp firstClass.cpp otherClass.cpp
  ```
  This will generate an executable file called *sfml_app*.  
  And your done!
