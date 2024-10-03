---
id: 9lka1j2q3fz258xp8pvs8jw
title: C#
desc: ''
updated: 1722329213456
created: 1722271651894
---

### What is NET Framework?
- A software framework developed by Microsoft that provides a controlled environment for the development and execution of applications.  
- It includes a large class library known as the Framework Class Library (FCL) and provides language interoperability across several programming languages.
  - C#.NET
  - VB.NET
  - C++.NET
  - J#.NET
  - F#.NET
  - JSCRIPT.NET
  - WINDOWS POWERSHELL
  - IRON RUBY
  - IRON PYTHON
  - C OMEGA
  - ASML(Abstract State Machine Language)

### What is C#?

- It is a modern, object-oriented programming language developed by Microsoft.
- It is part of the .NET framework and is designed for building a variety of applications that run on the .NET runtime, including web, desktop, and mobile applications.  
        

#### Basic Syntax

- **Structure of a C# Program:**
  ```csharp
  using System;

  namespace HelloWorld
  {
      class Program
      {
          static void Main(string[] args)
          {
              Console.WriteLine("Hello, World!");
          }
      }
  }
  ```

  - **using System;**: This statement includes the System namespace, which contains fundamental classes and base classes that define commonly-used value and reference data types, events and event handlers, interfaces, attributes, and processing exceptions.
  - **namespace HelloWorld**: Namespaces are used to organize code. They provide a way to keep one set of names separate from another.
  - **class Program**: A class is a blueprint for creating objects. It contains fields, properties, methods, and events.
  - **static void Main(string[] args)**: The `Main` method is the entry point of a C# program. It is where the program starts execution.

#### Data Types and Variables

- **Primitive Data Types:**
  - `int`: Represents an integer.
  - `float`: Represents a single-precision floating-point number.
  - `double`: Represents a double-precision floating-point number.
  - `char`: Represents a single character.
  - `string`: Represents a sequence of characters.
  - `bool`: Represents a boolean value (true or false).

- **Declaring and Initializing Variables:**
  ```csharp
  int age = 25;
  double height = 5.9;
  char grade = 'A';
  string name = "John Doe";
  bool isStudent = true;
  ```

- **Type Casting and Type Conversion:**
  - Implicit conversion: Automatic conversion by the compiler.
    ```csharp
    int num = 123;
    double dnum = num; // Implicit conversion from int to double
    ```
  - Explicit conversion: Requires a cast.
    ```csharp
    double dnum = 123.45;
    int num = (int)dnum; // Explicit conversion from double to int
    ```

#### Operators

- **Arithmetic Operators:**
  - `+`: Addition
  - `-`: Subtraction
  - `*`: Multiplication
  - `/`: Division
  - `%`: Modulus (remainder)

- **Relational Operators:**
  - `==`: Equal to
  - `!=`: Not equal to
  - `>`: Greater than
  - `<`: Less than
  - `>=`: Greater than or equal to
  - `<=`: Less than or equal to

- **Logical Operators:**
  - `&&`: Logical AND
  - `||`: Logical OR
  - `!`: Logical NOT

- **Assignment Operators:**
  - `=`: Assignment
  - `+=`: Addition assignment
  - `-=`: Subtraction assignment
  - `*=`: Multiplication assignment
  - `/=`: Division assignment
  - `%=`: Modulus assignment

### Practical Exercises

1. **Hello World Program:**

```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
```

- **Explanation:**
  - The `Main` method is the entry point of the program.
  - `Console.WriteLine("Hello, World!");` prints "Hello, World!" to the console.

2. **Variables and Data Types:**

```csharp
using System;

namespace VariablesAndDataTypes
{
    class Program
    {
        static void Main(string[] args)
        {
            int age = 25;
            double height = 5.9;
            char grade = 'A';
            string name = "John Doe";
            bool isStudent = true;

            Console.WriteLine($"Name: {name}, Age: {age}, Height: {height}, Grade: {grade}, Is Student: {isStudent}");
        }
    }
}
```

- **Explanation:**
  - Declares and initializes variables of different data types.
  - Uses `Console.WriteLine` to print the values of the variables.

3. **Basic Arithmetic Operations:**

```csharp
using System;

namespace BasicArithmetic
{
    class Program
    {
        static void Main(string[] args)
        {
            int num1 = 10;
            int num2 = 5;

            Console.WriteLine($"Addition: {num1 + num2}");
            Console.WriteLine($"Subtraction: {num1 - num2}");
            Console.WriteLine($"Multiplication: {num1 * num2}");
            Console.WriteLine($"Division: {num1 / num2}");
        }
    }
}
```

- **Explanation:**
  - Demonstrates the use of basic arithmetic operators.
  - Uses `Console.WriteLine` to display the results of the operations.

### Summary

- **C#** is a powerful, object-oriented programming language used for a variety of applications.
- **Visual Studio** is the primary IDE used for C# development.
- Understanding the **basic syntax**, **data types**, and **operators** is crucial for writing simple C# programs.
- Practical exercises help reinforce the concepts and provide hands-on experience.

### Next Steps

In the next session, we will cover control structures such as conditional statements and loops, which are essential for making decisions and repeating tasks in your programs.