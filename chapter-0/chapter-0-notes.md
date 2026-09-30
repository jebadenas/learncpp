High-level language source code -> compiled by compiler -> produces executable
The resulting executable is ran on hardware that produces the desired outcome
of the source code.

Interpreters are programs that directly executre the instructions in source code.
- Does not required them to be compiled first
- Needs to be done everytime the program is run
- Intepreter must be installed on every machine

How C++ programs get developed:
1) Define the proplem to solve
2) Design a solution
3) Write a program that implements the solution
4) Compile the program
5) Link object files
6) Test program 
7) Debug (Loop back to Step 4)

Compiler:
- Checks source code if it follows C++ language
- Translates C++ into machine language instructions which are stored in an 
intermediate file called an object file

Linker:
- Combines all of the object files and produce the wanted output file (e.g., 
executable file that can be run)
- Linker reads the obejct files and makes sure they are valid
- Linker ensures all cross-file dependencies. (e.g., if something is defined in
one cpp file and used in another cpp file then linker connects them together)
- Links library files (collection of precompiled code that have been "packaged
up" for reuse in other programs.)


