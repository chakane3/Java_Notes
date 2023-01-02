# Features And Architecture

## Compilier vs Architecture
A compiler will take your human readable code and translate it down to other languages where its machine readable. An interpreter will only give you the "result" of your program. Meaning it directly translates your code. Languages like c/c++ are compiler languages whereas Javascript is an interpreted language. Java is a mix between these two. <br>

Heres how java works in short: 

We have a ```file.java```  we wrote and then will later compile. When we run our program we turn our java file into byte code: ```file.class```; note this when we use ```javac file``` as a command to build our class file.
<br>
However, if we use ```java file```, it then gets interpreted in the Java Virtual Machine(JVM) which is an interpreter of the Java language. This is how Java is a mic of both interpreter and compiler language

## Platform Independency
When we run java code, we should know the JVM only "talks" to your operating system. Which mean you can use different OS systems and still use the same bytecode to run programs. "Write Once, Run Anywhere"

# Architecture of JVM
When we execute our java program, the class file will have to come from main memory in your hardware. Your memory has 3 parts: (1) Heap, (2) Stack, (3) Code section.

# Features of Java
<ul>
    <li>JVM has a security manager to check is theres anything malicious going on.</li>
    <li>Java code can be ran across any operating system all thanks to of JVM</li>
    <li>Can handle multithreading</li>

</ul>

