# SFML-Linux-CompileScript
  This is my first Bash-Script, so there may be a lot of unnessecary stuff in there.  
  Also I never learned Bash-Scripting, I just wanted a handy Console-Command for compiling my SFML-Code.  
## How to use
Example of a Project-Layout:  
<p align="center">
  <img src="https://raw.githubusercontent.com/EineSalatgurke/SFML-Linux-CompileScript/master/projectLayout.png">
</p>
<ul>
  <li>Your *.cpp-Files need to be located in the SourceFiles-Folder</li>
  <li>Your *.h-Files need to be located in the HeaderFiles-Folder</li>
</ul>

Console-Command to Complie the Example:
```
${ProjectFolder} sfmlc main.cpp firstClass.cpp otherClass.cpp
```
This will generate an executable file called *sfml_app*.  
And your done! ;)
