# SFML-Linux-CompileScript
  This is my first Bash-Script, so there may be a lot of unnessecary stuff in there.  
  Also I never learned Bash-Scripting, I just wanted a handy Console-Command for compiling my SFML-Code.  
## How to use
Example of a Project-Layout:  
  
  <img src="https://raw.githubusercontent.com/EineSalatgurke/SFML-Linux-CompileScript/master/projectLayout.png">
* Your \*.cpp-Files need to be located in the *SourceFiles*-Folder
* Your \*.h-Files need to be located in the *HeaderFiles*-Folder
  
__Console-Command to Complie the Example:__
```
${ProjectFolder} sfmlc main.cpp firstClass.cpp otherClass.cpp
```
This will generate an executable file called *sfml_app*.  
And your done!
</ul>
