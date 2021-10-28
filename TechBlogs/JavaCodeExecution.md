# JavaCode Execution Process
- when we start learning java programming language we often hear about JDK, JRE and JVM huh! Everytime i tried to learn about them i will end up being confused now let me clearly explain the concept which i understand.
- quick sneek peek JDK contains JRE, JRE contains JVM.


```JDK -> JRE -> JVM```

### JDK
  1) when we want to run the java code in our local system we first download JDK and then the reqired code editor which uses the JDK to write the code. so what is JDK?
  2) well, the JDK stands for java development kit and it is a kit(package) which is used to develop the java applications and it contains so many tools which are required for us to develop the java programs(but all of them are abstracted for us that is the jdk itself uses them when we write the code without our intervention so we dont get to know about these tools) but the most well known components in JDK are javac(java compiler), JRE and JVM.
  3) now we write our code in the code editor and clicks on run button now the actual picture starts.
  4) first the JDK invokes compiler to compile the rawcode(HelloWorld.java) which we wrote just now, into the bytecode(HelloWorld.class). Next JDK invokes the JRE for furhter process.
### JRE
  1) JRE stands for java run time environment. This combine our bytecode produced by the compiler to the essential libraries which we used in our code,  this process is also called as class loading.
  2) After that bytecode is sent into bytecode verifier to check the accuracy of our code. Then JRE creates an instance of JVM for further process.
  3) JRE is platform independetnt.
### JVM
  1) JVM stands for java virtual machine. JVM(contains interpretor and JIT )allocates memory for our code in the ram and uses interpretor and sometimes JIT to convert the bytecode to machine code then our computer runs the code and produces the output .
  2) JVM is platform dependent.
  3) JIT(just in time compiler) it is introduced to improve the efiiceincy of converting byte code to machine code.(By directing the process of repeated steps/functions in our code)
  
