# Make C++ Project in VS Code

+ Plain raw version
+ With tools (e.g. "CodeRunner)


## Raw Version
(Example how to use Cpp ind VS Code (Linux))

Sources: 
- https://code.visualstudio.com/docs/cpp/config-linux 
- https://code.visualstudio.com/docs/editor/variables-reference


1. create json build file for compiling
- Terminal > Configure Default Build Task
- choose C/C++: g++ build active file

2. Open file
- new bash terminal ("+")
- cd /folder/path
- ./filenamewithoutextension

3. create json debug file (launch.json)
- Run > Add Configuration... 
- choose C++ (GDB/LLDB)
- choose g++ build and debug active fil^

## Use Tools / PlugIn

https://www.youtube.com/playlist?list=PLKMOdY6Bhga7BUgPca5EX1J-JYQIbX5fn

### Section 1 - Beginning
https://www.youtube.com/watch?v=pu1XNDwQPl0&list=PLKMOdY6Bhga7BUgPca5EX1J-JYQIbX5fn&index=1

- main.cpp ... because cp compiler looks for main.cpp first

### Section 2 - Make-Files
https://www.youtube.com/watch?v=whQQF4kVjPY&list=PLKMOdY6Bhga7BUgPca5EX1J-JYQIbX5fn&index=2

- allow to compile multiple source files together 
- Make File Plugins: CMake ???