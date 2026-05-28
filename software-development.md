# Software and Development Concepts

## Programming Languages

### Interpreted Languages

An **interpreted language** runs code through an interpreter, which reads and executes the program one instruction at a time during runtime.

Interpreted languages are generally:
- Platform independent
- Easier to debug and test
- Faster to develop with

However, they often:
- Have slower performance than compiled languages
- Have more limited direct access to system resources

### Common Examples

- Python
- JavaScript
- Ruby
- Perl

---

## Scripting Languages

In addition to interpreted languages, many operating systems include their own scripting languages for automation and system management.

### Examples

- **Windows** uses **PowerShell**
- **Linux** uses **Bash**

Scripting languages are commonly used to:
- Automate tasks
- Manage files and systems
- Run administrative commands

---

## Markup Languages

> Note: **Markup languages** are not considered programming languages.

Markup languages use tags to organise and display information. They do not make decisions or perform logical operations like programming languages.

Web browsers read these tags to determine how content should appear on a webpage.

### Common Examples

- HTML
- XML

---

## Compiled Programming Languages

Compiled languages use a **compiler** to translate source code into machine language before the program runs.

The compiled output is usually converted into a binary executable file, such as:
- `.exe` on Windows

Because the code is already in machine language, it can communicate directly with the processor and hardware devices, including:
- Cameras
- Sensors
- USB devices
- GPS hardware

Compiled languages generally offer:
- Faster performance
- Greater hardware access
- Better efficiency for demanding applications

### Common Examples

- C
- C++
- Java

Many high-performance applications and video games are written using compiled languages.

### Platform Dependency

Compiled programs are often **platform dependent**, meaning software compiled for one operating system may not work on another without modification.

Rewriting or adapting software for another platform is known as **porting**.

---

# Runtime Code

Runtime code combines features of both **compiled** and **interpreted** languages.

It uses a two-step process:

1. A compiler converts the source code into low-level intermediate code called **bytecode**
2. A runtime engine or interpreter translates the bytecode into machine language specific to the computer running the program

This approach allows the same bytecode to run on multiple platforms without rewriting the original program.

### Advantages of Runtime Code

- Platform portability
- Easier software distribution
- Flexibility across operating systems

### Common Examples

- C#
- Java

---
## Assembly Languages

Assembly languages are **low-level programming languages** that communicate directly with computer hardware.

They are closely related to **binary machine code** and use short mnemonic instructions that represent processor commands.

Assembly language provides:
- Very high performance
- Direct hardware control
- Efficient memory usage

However, it is:
- Difficult to learn
- Time-consuming to write
- Platform specific

Assembly language is commonly used in:
- Embedded systems
- Device drivers
- Operating systems
- Hardware programming

---

## Query Languages

Query languages are specialised programming languages used to retrieve, manage, and manipulate data stored in databases.

They allow users to:
- Search for information
- Update records
- Organise data
- Generate reports

### Common Example

- **Structured Query Language (SQL)**

SQL is widely used in:
- Websites
- Business systems
- Banking systems
- Data analysis applications
