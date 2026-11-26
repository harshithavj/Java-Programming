# Day 01 – Introduction to Java

## 1. Overview

Java is a high-level, object-oriented, class-based programming language developed by James Gosling and his team at Sun Microsystems. It was officially released in 1995.

Java is widely used for developing desktop applications, web applications, enterprise software, backend systems, and Android applications.


## 2. Key Features of Java

- **Simple:** Java has a clear syntax and removes complex features.
- **Object-Oriented:** Java organizes programs using classes and objects.
- **Platform Independent:** Java bytecode can run on any system with a compatible Java Virtual Machine (JVM).
- **Secure:** Java provides features such as bytecode verification and controlled memory access.
- **Multithreaded:** Java supports executing multiple threads concurrently.
- **Portable:** Java programs can be transferred across compatible platforms.
- **High Performance:** The Just-In-Time (JIT) compiler improves execution performance.

## 3. How Java Works

Java follows the principle:

**Write Once, Run Anywhere (WORA).**

Java source code is not directly converted into machine code by the Java compiler. Instead, it is compiled into bytecode, which is executed by the JVM.

### Execution Process

1. Write the Java source code in a `.java` file.
2. The Java compiler (`javac`) compiles the source code.
3. A `.class` file containing bytecode is generated.
4. The JVM loads and executes the bytecode.

### Java Execution Flow

```text
Java Source Code (.java file)
      |
      v
   Compiler
   (javac)
      |
      v
   Bytecode (Intermediate Language - Non Human Understandable)
   (.class file)
      |
      v
     JVM(JVM is platfrom dependent)
      |
      v
  Machine Code
      |
      v
    Output
```
Java is platform independent/portable/Architectural Neutral

## 4. JDK, JRE and JVM

**JDK (Java Development Kit):**
Provides the tools required to develop, compile, and run Java applications. It includes the compiler and runtime components.

**JRE (Java Runtime Environment):**
Provides the runtime environment and libraries required to execute Java applications.

**JVM (Java Virtual Machine):**
Executes Java bytecode and enables platform-independent execution.

## 5. First Java Program

```java
public class HelloWorld {

    public static void main(String[] args) {

        System.out.println("Hello World");

    }
}
```

### Code Explanation

- `public`: Access modifier.
- `class`: Keyword used to define a class.
- `HelloWorld`: Name of the class.
- `main()`: Execution point of a standard Java application.
- `String[] args`: Accepts command-line arguments.
- `System.out.println()`: Prints the specified message and moves to the next line.

### Output

```text
Hello World
```

## 6. Applications of Java

- Web application development
- Android application development
- Enterprise software development
- Banking and financial applications
- Cloud-based applications
- Desktop application development
- Backend development

## 7. Key Takeaways

- Java is a high-level, object-oriented programming language.
- Java supports platform independence through bytecode and JVM.
- The JDK provides tools to develop Java applications.
- The JVM executes Java bytecode.
- Java is widely used in modern software development.

**Day 01 Status: Introduction to Java – Completed**