# Pre-Requisites
<ul>
    <li>JDK - any version, latest if possible</li>
    <li>JVM</li>
    <li>JRE</li>
    <li>and IDE/text editor</li>
</ul>


# Introduction

To execute a java program we need a Java Virtual Machine(JVM) to execute our java file. We start our with a java file that we write, and when we run it it turns into a javac file which get compiled using Java Development Kit (JDK). Once compiled that javac turns into a class file which is compiled by the Java Runtime Environment (JRE). Every java program is a class. By convention, classnames should be the same name as the file name. 

## Scanner
We may be interested in learning how to read data from out keyboard. We can ``` import java.util.Scanner; ``` to have this functionality. We'll need to create an object to use this library : ``` Scanner s = new Scanner(System.in); ```. Theres many methods to read in data types to our scanner.
<details>
    <summary>Theres many methods to read in data types to our scanner</summary>
    <ul>
        <li>nextInt()</li>
        <li>nextFloat()</li>
        <li>nextDouble()</li>
        <li>next()</li>
        <li>nextLine()</li>
        <li>nextByte()</li>
        <li>nextShort()</li>
        <li>nextLong()</li>
        <li>nextBoolean()</li>
        <li>hasNextInt()</li>
        <li>hasNextFloat()</li>
</ul>
</details>

