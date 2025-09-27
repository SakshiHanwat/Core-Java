# Introduction to Java ☕

## What is Java?
- Java is a **high-level, object-oriented, platform-independent programming language**.
- Developed by **Sun Microsystems (James Gosling, 1995)**.
- **Write Once, Run Anywhere (WORA)** – Java code runs on all platforms that support JVM.

---

## JDK, JRE, JVM

### 🔹 JVM (Java Virtual Machine)
- It is the engine that runs Java bytecode.
- Converts **bytecode (.class files)** into machine code.
- Provides platform independence.
- Part of JRE.

### 🔹 JRE (Java Runtime Environment)
- Contains JVM + Libraries.
- Provides environment to **run Java programs**.
- Does NOT contain development tools (like compiler).

### 🔹 JDK (Java Development Kit)
- Contains JRE + Development tools (compiler, debugger, etc.).
- Used by developers to **write, compile, and run Java programs**.

---

## Java Program Flow 🚦

1. **Write Code** → `.java` file (e.g., `Main.java`)
2. **Compile** → `javac Main.java` → generates `.class` file (Bytecode)
3. **Execute** → JVM loads `.class` file → converts bytecode → machine code
4. Runs on OS + Hardware via JVM.

---

## Components in Execution

- **Source Code (.java)** → written by developer.
- **Compiler (javac)** → converts `.java` → `.class` (bytecode).
- **Bytecode (.class)** → platform-independent instructions.
- **JVM** → executes bytecode on any OS.
- **OS + Hardware** → actual execution layer.

---

## Example: Hello World
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
# 📘 Variables in Java

---

## 🔹 What Happens Behind the Scenes
- As a Java developer, you **write code** with a `.java` extension.  
- The code is compiled by **`javac` (Java Compiler)** → generates **Bytecode** (`.class` file).  
- Bytecode is run inside the **JVM** (Java Virtual Machine), which is part of **JRE**.  
- **JRE** = JVM + Built-in Libraries.  
- JRE runs on top of the **Operating System (OS)**.  
- Developers install **JDK** (Java Development Kit), which provides:
  - Compiler (`javac`)
  - Updated JRE + JVM  
- Current LTS version: **JDK 17** (but concept remains the same even in future versions).  

---

## 🔹 Why Do We Build Software?
- To **solve real-world problems** with virtual solutions.  
- Examples:
  - **Amazon** → Online shopping  
  - **Uber** → Cab booking  
  - **Online Banking** → Money transfers  
- The most important thing in software is **DATA**.

---

## 🔹 Working with Data
- Applications **accept data from the user**, process it, and may store it.  
- **Storage Types**:
  - **Permanent Storage** → Database (data remains even after shutdown).  
  - **Temporary Storage** → **Variables** (data exists while program runs).  

---

## 🔹 What is a Variable?
- A **variable** is like a **box** that stores data.  
- Each variable has:
  1. **Name** → Identifier (e.g., `num`, `marks`, `user`)  
  2. **Value** → Data stored inside (e.g., `5`, `6.5`, `"Naveen"`)  
  3. **Type** → Defines what kind of data can be stored.  

---

## 🔹 Syntax of a Variable
```java
type variableName = value;
