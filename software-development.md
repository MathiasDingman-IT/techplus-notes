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

---

# Data Types

Data types define the kind of information a variable can store within a program.

---

## Character (Char)

A **character** or **char** stores a single letter, number, or symbol.

### Examples

```text
7
X
#
```

---

## Strings

A **string** stores a sequence of characters, words, or sentences.

### Example

```text
"Hello World"
```

---

## Numbers

### 1. Integers

Integers are **whole numbers** without decimal points.

### Examples

```text
23
-7
243
```

---

### 2. Floats

Floats are numbers that contain **decimal points** or fractional values.

### Examples

```text
4.01
-98.432
1.2
```

---

## Boolean

A **Boolean** data type stores one of two logical values.

### Examples

```text
True
False
```

---

# Programming Concepts

## Identifiers

### Variables

Variables act like containers that store data such as:
- Numbers
- Words
- Sentences
- Other values

The value stored in a variable can change while the program is running.

### Constants

Constants are values that do not change during program execution.

---

# Arrays

Arrays are variables that store multiple values in a single structure.

Arrays can be:
- One-dimensional
- Two-dimensional
- Three-dimensional

## Vectors

Vectors are a type of array that store groups of the same data type.

### Example

```text
[23, 7, 355, 821]
```

> Note: Each value in an array has an index position. The first value is stored at index `0`, the second at index `1`, and so on.

---

# Functions

Functions are reusable blocks of code designed to perform a specific task.

A function:
1. Receives data (input)
2. Processes the data
3. Returns a result (output)

### Example

```text
Function add(num1, num2)
Return num1 + num2
```

---

# Objects

## Object-Oriented Programming (OOP)

Object-Oriented Programming (OOP) is a programming technique that organises code into **objects** and **classes**.

### Objects can contain:
- Attributes
- Methods
- Properties

A **class** acts as a blueprint for creating objects.

### Example

A cup can be considered an object.

#### Attributes
- Glass
- Paper
- Ceramic

#### Methods
- Holding hot drinks
- Holding cold drinks

---

# Programming Organisational Techniques and Logic Concepts

## Organisational Techniques

### 1. Pseudocode

Pseudocode is the process of planning a program using structured plain language instead of a specific programming language syntax.

---

### 2. Object-Oriented Programming (OOP)

See the section above.

---

### 3. Comments

Comments are notes added to code to explain what the program is doing.

### Example in Python

```python
# This is a comment
```

---

### 4. Flowchart Concepts

Flowcharts are diagrams used to represent the logic and structure of a program.

#### Common Flowchart Symbols

| Symbol | Meaning |
|---|---|
| Oval | Start or End |
| Parallelogram | Input or Output |
| Diamond | Decision (Yes/No or True/False) |
| Rectangle | Process |
| Arrow | Direction of Program Flow |

---

# Logic Concepts

## 1. Branching

Branching uses control statements to decide which section of code runs next.

### Common Examples

- `IF`
- `ELSE`
- `ELSE IF`

Branching allows programs to make decisions.

---

## 2. Looping

Looping repeats code based on a condition.

### Common Examples

- `FOR` loops
- `WHILE` loops

Loops help automate repetitive tasks within programs.
