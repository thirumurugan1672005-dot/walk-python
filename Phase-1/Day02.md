# How Python runs Programs

## Interpetor
   Interpetor is kind of software logic between hardware and software that runs your python programs
## Programmers View How Python runs
   * You type program in source file  its extension is .py
   * Now the program execute from top to bottom
   * and output will be shown in terminal or GUI
## Pythons View of Execution
   * First convert the source code (.py) into bytecode(.pyc)
   * Bytecode is hidden from user in hidden directory __pycache__ and it contains bytecode instructions
   * Bytecode instructions is told it is faster than source files
   * Bytecode instructions is Python specific
   * If the Source file don't change or there is no alternate python version it skips the compilation(translation) process and execut
     ### Python Virtual Machine
     * It installed along with python it just a long code loop that executes bytecode instructions

# Alternate Implementations
1.CPython : Standard Implementations written using ANSI C Standard
2.Jython : For Java
3.IronPython : For .NET and C#
4.Numba : Peformance enhacement for Numpy or math related loops
5.PyPy: which makes execution still faster

# Frozen Binaries
Frozen binaries means the bundling the interpetor , PVM, standard library to give into executables so you can run without installing python
