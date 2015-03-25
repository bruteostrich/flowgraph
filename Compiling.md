## Compiling Plugins ##
Just run compiler and it will compile all the plugins.
When you get an error the line numbers are based off of the Source.vb file.

**Command line**
  * ExitNoError - If there are no errors/warnings after compiling it will exit.


## Compiling fgs files ##
**This is still early in development.**

Drag and drop fgs file on to the compiler. (while not running)
Will then find all needed plugins then compile them.
Puts compiled files and fgsSource.vb are in "\Compiled"

**Command line**
  * ExitNoError  - If there are no errors/warnings after compiling it will exit.
  * ClassLibrary - Compiles as .dll
  * NoDraw       - Removes all the GUI.


## Compiling Flowgraph ##
Needed to compile [VisualStudio 2010 Express](http://www.microsoft.com/express/Downloads/#2010-Visual-Basic) and [SlimDX March 2011 SDK](http://slimdx.org/download.php)