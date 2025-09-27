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
