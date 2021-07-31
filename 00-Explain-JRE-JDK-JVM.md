# What are JDK, JRE, and JVM?

## JDK 

JDK is the development kit we need to create a **java** program.
It stands for **Java Development Kit**. It is a tool that is responsible for **compiling** and **packaging** Java programs.
It contains standard libraries and programs that are responsible for executing the java programs.
The JDK includes a private **JVM** and other resources to finish the development of the Java application.
JDK is a tool that takes the source code we write and **translate it** into a format that the **JRE** and the **JVM** can execute. 
JDK includes features like **debuggers** which help us test and find errors in our code. Also, the **Java Compiler** to compile that code.

## JRE 

JRE stands for **Java Runtime Environment**. It refers to a runtime environment where **Java bytecode** can be executed.
The **JRE** includes **JVM** which is the **Java Virtual Machine**.
JRE is used to **run** our Java Programs. It includes a set of different libraries that come with Java.
**JRE** does not include any development tools. JRE is used to run the program we've created using **Java Development Kit**.

## JVM
**JVM** stands for **Java virtual machine**. It is part of the **Java Runtime Environment**. We can imagine that as an abstract machine that works with
**compiled Java code**. When a program is executed from the **Java Runtime Environment** it runs this virtual machine and that's how our code is executed.
The **JDK** takes the java code that we've typed into our **IDE**, **creates** a **.class** file, and that file is executed via the **JRE** in the **Java Virtual Machine**.


