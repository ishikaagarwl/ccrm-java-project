# ccrm-java-project
A Java application to manage students, courses, and grades. It features a menu-driven console and demonstrates key Java concepts like OOP, exception handling, and design patterns.

Project Overview & How to Run
This project is a console-based Campus Course & Records Manager (CCRM). It's a Java SE application designed to manage students, courses, enrollments, and grades for an educational institute . The program allows users to perform CRUD (Create, Read, Update, Deactivate) operations on students and courses, handle enrollments, record grades, and perform file operations like importing/exporting data and creating backups.

How to Run
JDK Version: JDK 11 or higher is recommended.
Compile from src directory:
javac edu/ccrm/cli/Main.java -d ../bin

Evolution of Java 
1995: Java 1.0 is released by Sun Microsystems with the motto "Write once, run anywhere."
1998: J2SE 1.2 introduces the Collections Framework, Swing for GUIs, and JIT (Just-In-Time) compilation.
2004: J2SE 5.0 (Tiger) brings major language enhancements like Generics, Enums, Autoboxing, and Annotations.
2014: Java SE 8 marks a revolutionary change with the introduction of Lambda Expressions, the Stream API, and a new Date/Time API.
2018: Java SE 11 becomes the next Long-Term Support (LTS) version, adding new features like the var keyword for local variables.
2021: Java SE 17 is the latest LTS version, introducing Sealed Classes and Pattern Matching for instanceof.

Java ME vs. SE vs. EE Comparison
Java ME (Micro Edition)
Target: Designed for resource-constrained devices like sensors, early mobile phones, and embedded systems.
Core API: Includes a limited subset of the Java SE API, supplemented with libraries specific to mobile and embedded devices.
Typical Use: Commonly used for IoT devices and embedded systems.

Java SE (Standard Edition)
Target: The core platform for general-purpose development on desktops, servers, and for console applications.
Core API: Contains the complete standard Java API, including the Collections Framework, I/O libraries, and core language features.
Typical Use: Building desktop applications, command-line tools, and serves as the foundation for all other Java editions.

Java EE (Enterprise Edition)
Target: Built for developing large-scale, distributed, and web-based enterprise applications.
Core API: Extends Java SE by adding a rich set of APIs for web services, persistence (JPA), servlets, and more.
Typical Use: Deployed on web and application servers to power complex business software and services.

JDK vs. JRE vs. JVM Explained
JVM (Java Virtual Machine): The JVM is an abstract machine that executes Java bytecode. It's the component that makes Java platform-independent. When you run a Java program, the JVM interprets the compiled .class files for the underlying operating system.
JRE (Java Runtime Environment): The JRE is the software package required to run a Java application. It contains the JVM, core class libraries, and supporting files. You would distribute your application with the JRE so users can run it without needing development tools.
JDK (Java Development Kit): The JDK is a full-featured software development kit for creating Java applications. It is a superset of the JRE, meaning it includes everything the JRE has, plus development tools like the compiler (javac), the archiver (jar), and a debugger.

Windows & Eclipse Setup Steps
Windows JDK Installation 
Download: Go to the official Oracle Java or OpenJDK website and download the JDK installer for Windows.
Run Installer: Execute the downloaded .msi or .exe file and follow the setup wizard's instructions.
Set Environment Variables:
Find the JDK installation path 
Add the JDK's bin folder to your system's Path variable (e.g., %JAVA_HOME%\bin).
Verify Installation: Open Command Prompt and run java -version. You should see the installed Java version.



Eclipse Project Setup 
New Project: Go to File > New > Java Project.
Project Name: Enter a name for your project,  CCRM-Project.
JRE: Ensure the correct JRE is selected (it should default to your installed JDK).
Create Packages: Right-click the src folder in the Package Explorer and select New > Package. Create all the required packages.
Create Classes: Right-click a package and select New > Class to create your Java files.

