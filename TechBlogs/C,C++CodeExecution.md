# C and C++ Code Execution
- Did u ever wondered how our c or c++ code executes under the hood? now let me explain it which i understand.
- Quick sneek peek into execution steps.


``` Preprocessing -> Compiler -> Linker -> Loader```
1) When we write our code in c or c++ language(HelloWorld.c or HelloWorld.cpp) and runs it the first step involved is preprocessing the raw code this includes the execution of prepocessors in our code such as Macros, Fileinclusions and etc.. which are declared by "#" and also removes the comments in our code.
2) This preprocessed code is sent to compiler which compiles our code into object code(lowlevelcode or byte code) such as HelloWorld.obj .
3) This object code is linked  with the code that is preprocessed in the first step to form the complete machine code or executable code such as Helloworld.exe(in windows).
4) Then this machine code is loaded in the memory in our OperatingSystem and thus the computer runs it and produces the output.
