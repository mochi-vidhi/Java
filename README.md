# Welcome to java Tutorial ☕

```java
class Hello{
public static void main(){
  System.out.println("Welcome to java Tutorial!!");
}
}
```
### What is java ?? 🤔☕
- Developed by Sun Microsystems in 1995, Java is a highly popular, object-oriented programming language. It is intended to let application developers write once, and run anywhere (WORA), 
  meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.
- Java applications are compiled to byte code that can run on any Java Virtual Machine. The syntax of Java is similar to c/c++.
### Why java is so famous??? 😎☕
- If you see the programming index the top five programming language you will always find java there may be at the first position or 4th position.
- [Top programming Languages](https://www.statista.com/chart/16567/popular-programming-languages/).
- java has multiple features which helps it to be used in the Enterprise market.
### Uses of java  😊☕
```java
- Desktop Applications such as acrobat reader, media player, antivirus, etc.🖥️
- Web Applications such as irctc.co.in, javatpoint.com, etc.🌐
- Enterprise Applications such as banking applications. 🏦
- Mobile 📱
- Embedded System
- Smart Card 🏧
- Robotics 🤖
- Games, etc. 🎮
```
###  NEXT ⏩ Features of Java 🚀☕
```java
- Simple
- Object-Oriented
- Portable
- Platform independent
- Secured
- Robust
- Architecture neutral
- Interpreted
- High Performance
- Multithreaded
- Distributed
- Dynamic   
```
### c++ 🆚 java
| Topic                | C++                                        | Java                                       |
|----------------------|--------------------------------------------|--------------------------------------------|
| Memory Management    | Use of pointers, structures, union         | No use of pointers. Supports references, thread and interfaces. |
| Libraries            | Comparatively available with low-level functionalities | Wide range of classes for various high-level services |
| Multiple Inheritance | Provide both single and multiple inheritance. | Multiple inheritances is partially done through interfaces |
| Operator Overloading | Supports operator overloading              | It doesn’t support this feature            |
| Program Handling     | Functions and variables can reside outside classes. | Functions and variables reside only in classes, packages are used. |
| Portability          | Platform dependent, must be recompiled for different platform | Platform independent, byte code generated works on every OS. |
| Thread Support       | No built-in support for threads, depends on libraries. | It has built-in thread support.            |
### java ⚔️ Python
| Topic                | Java                                        | Python                                      |
|----------------------|---------------------------------------------|---------------------------------------------|
| Compilation process | Both compiled and interpreted. Compiled into bytecode, then interpreted. | Interpreted language, code is executed directly. |
| Code Length          | Longer lines of code compared to Python.    | 3-5 times shorter than equivalent Java programs. |
| Syntax Complexity    | Block defined by curly braces, end statements by semicolons. | No need for semicolons or curly braces, uses indentation. |
| Ease of Typing       | Strongly typed, requires defining exact datatypes. | Dynamically typed, no need to define exact datatypes. |
| Speed of Execution   | Faster execution speed compared to Python.  | Expected to run slower than Java programs.   |
| Multiple Inheritance | Partially done through interfaces.           | Limited support, single inheritance preferred. |
## Integrated development environment Software / java
### what is IDE??📝
- An integrated development environment (IDE) is a software application that helps programmers develop software code efficiently. It increases developer productivity
  by combining capabilities such as software editing, building, testing, and packaging in an easy-to-use application. Just as writers use text editors
  and accountants use spreadsheets, software developers use IDEs to make their job easier.
### Getting Started  🛠️ ☕
- TO write java code you need place basicaly to write code you need editor like notepad we have but multiple software which we can write java code.
-  we can write java on notepad plus plus,wordpad but to make real life projects,to debug the code,to run the code we need IDE.
```java
- 1 Eclipse       2 IntelliJ IDEA   3 NetBeans
- 4 V.S.Code      5 BlueJ           4 DrJava
- 5 JDeveloper    6 JCreator        7 MyEclipse
- 8 jGRASP        9 Greenfoot      10 Android Studio
```
### 🔧 [JDK (Java Development Kit)](https://www.oracle.com/in/java/technologies/downloads/)
- [All about JDK😄](https://www.geeksforgeeks.org/jdk-in-java/?ref=lbp)
- [How to Install JDK🚀](https://youtu.be/WRISYpKhIrc?si=EAWKn38Fz8X8r8Sy)
- [How JVM Works – JVM Architecture? 🤔🚀](https://www.geeksforgeeks.org/jvm-works-jvm-architecture/?ref=lbp)
### Differences between JDK🛠️, JRE🏃‍♂️ and JVM 💻
| Aspect          | JDK (Java Development Kit)                                          | JRE (Java Runtime Environment)                                          | JVM (Java Virtual Machine)                                             |
|-----------------|------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|
| Full Form       | Java Development Kit                                                 | Java Runtime Environment                                                 | Java Virtual Machine                                                    |
| Description     | Software development kit used for developing Java applications      | Environment used for executing Java applications                        | Virtual machine that runs Java bytecode                                 |
| Components      | Compiler, libraries, tools, and documentation                      | Libraries and environment necessary for executing Java applications     | Virtual machine implementation that executes Java bytecode             |
| Usage           | Needed for developing Java applications                             | Needed for running Java applications                                    | Responsible for executing Java bytecode                                 |
| Example Use     | Case Developing Java applications, building and packaging applications | Running Java applications, executing Java applets                       | Executing compiled Java bytecode, providing platform independence for Java code |
| Installation    | Requires downloading and installing the JDK package from the Oracle website | Comes bundled with the JDK installation, or can be downloaded separately | Part of the JDK installation, no separate installation needed            |
### between Byte Code 🏁 Machine Code
+------------------+------------------+------------------+------------------+------------------+
| Java Program     | Java Compiler    | Java Byte Code   | Java Interpreter | Machine Code     |          
| (Source Code)    |                  |                  |                  |                  |             
+------------------+------------------+------------------+------------------+------------------+

| S.NO. | Byte Code                                               | Machine Code                                             |
|-------|---------------------------------------------------------|----------------------------------------------------------|
| 01.   | Byte Code consisting of binary, hexadecimal, macro instructions like (new, add, swap, etc) and it is not directly understandable by the CPU. It is designed for efficient execution by software such as a virtual machine. | Machine Code consisting of binary instructions that are directly understandable by the CPU. |
| 02.   | Byte code is considered as the intermediate-level code. | Machine Code is considered as the low-level code.      |
| 03.   | Byte code is a non-runnable code generated after compilation of source code and it relies on an interpreter to get executed. | Machine code is a set of instructions in machine language or in binary format and it is directly executed by CPU. |
| 04.   | Byte code is executed by the virtual machine then the Central Processing Unit. | Machine code is not executed by a virtual machine it is directly executed by CPU. |
| 05.   | Byte code is less specific towards machine than the machine code. | Machine code is more specific towards machine than the byte code. |
| 06.   | It is platform-independent as it is dependent on the virtual machine and the system having a virtual machine can be executed irrespective of the platform. | It is not platform independent because the object code of one platform can not be run on the different Operating System. Object varies depending upon system architecture and native instructions associated with the machine. |
| 07.   | All the source code need not be converted into byte code for execution by CPU. Some source code written by any specific high-level language is converted into byte code then byte code to object code for execution by CPU. | All the source code must be converted into machine code before it is executed by the CPU. |





