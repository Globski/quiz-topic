# Question: What is C# and who developed it?

**Answer:** C# (pronounced “C-Sharp”) is a simple, modern, general-purpose, object-oriented programming language developed by Microsoft within its .NET initiative led by Anders Hejlsberg.

---

# Question: List four common applications of C#.

**Answer:**

1. Web Development (ASP.NET)
2. Desktop Applications (Windows Forms, WPF)
3. Game Development (Unity)
4. Cloud & AI Applications

---

# Question: What is the entry point of a C# program?

**Answer:** The `static void Main(string[] args)` method serves as the entry point of a C# program.

---

# Question: Which method is used to print output to the console in C#?

**Answer:** `Console.WriteLine()`

---

# Question: What tools are typically required to run C# programs?

**Answer:**

* .NET SDK (downloadable from dotnet.microsoft.com)
* A code editor such as VS Code, Visual Studio, or an online compiler

---

# Question: Write the minimal code needed for a C# program that prints `Hello, World!`.

**Answer:**

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Hello, World!");
    }
}
```

---

# Question: Explain what `class Program` represents in C#.

**Answer:** It defines a class named `Program` which contains the code logic, including the `Main` method that acts as the program’s entry point.

---

# Question: Give an example of declaring and using variables in C#.

**Answer:**

```csharp
int age = 25;
string name = "Alice";
Console.WriteLine("Name: " + name);
Console.WriteLine("Age: " + age);
```

---

# Question: Match the following data types with their sizes: `int`, `double`, `char`, `string`, `bool`.

**Answer:**

* `int`: 4 bytes
* `double`: 8 bytes
* `char`: 2 bytes
* `string`: variable size
* `bool`: 1 byte

---

# Question: What will the following code output?

```csharp
double price = 99.99;
bool isAvailable = true;
Console.WriteLine("Price: $" + price);
Console.WriteLine("In Stock: " + isAvailable);
```

**Answer:**

```
Price: $99.99
In Stock: True
```

---

# Question: Write an `if-else` example in C# that checks if someone is eligible to vote (age ≥ 18).

**Answer:**

```csharp
int age = Convert.ToInt32(Console.ReadLine());
if (age >= 18)
    Console.WriteLine("You are eligible to vote!");
else
    Console.WriteLine("Sorry, you must be 18+ to vote.");
```

---

# Question: What are the three main types of loops in C# and their uses?

**Answer:**

* `for loop`: when the number of iterations is known
* `while loop`: repeats while a condition is true
* `do-while loop`: executes at least once before checking the condition

---

# Question: What will the following code output?

```csharp
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine("Iteration: " + i);
}
```

**Answer:**

```
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4
Iteration: 5
```

---

# Question: How are functions defined in C#? Provide an example.

**Answer:** Functions are defined using the `static` keyword inside a class.
Example:

```csharp
static void Greet(string name)
{
    Console.WriteLine("Hello, " + name + "!");
}
```

---

# Question: How do you create and use objects in C#?

**Answer:**

```csharp
Car myCar = new Car();
myCar.Brand = "Tesla";
myCar.ShowBrand();
```

---

# Question: What is the output of the following OOP example?

```csharp
Car myCar = new Car();
myCar.Brand = "Tesla";
myCar.ShowBrand();
```

**Answer:**

```
Car Brand: Tesla
```

---

# Question: How do you write and read a text file in C#?

**Answer:**

```csharp
File.WriteAllText("test.txt", "Hello, C#!");
string content = File.ReadAllText("test.txt");
Console.WriteLine("File Content: " + content);
```

---

# Question: What will be created by the above file handling code, and what will its contents be?

**Answer:** A file named `test.txt` will be created in the local directory containing the text:

```
Hello, C#!
```

---

# Question: List three reasons why C# is recommended for beginners.

**Answer:**

1. Easy-to-learn syntax
2. Strong object-oriented foundation
3. Managed and secure under the .NET runtime

---

# Question: Who developed C#, and which organizations approved it?

**Answer:** C# was developed by Anders Hejlsberg and his team at Microsoft. It is approved by ECMA (European Computer Manufacturers Association) and ISO (International Standards Organization).

---

# Question: What is C# designed for, and what does CLI stand for?

**Answer:** C# is designed for the Common Language Infrastructure (CLI), which consists of executable code and a runtime environment that allows multiple high-level languages to run on different platforms and architectures.

---

# Question: List at least five reasons why C# is a widely used professional language.

**Answer:**

1. It is modern and general-purpose
2. It is object-oriented
3. It is component-oriented
4. It is structured and easy to learn
5. It produces efficient programs
6. It can be compiled on multiple platforms
7. It is part of the .NET Framework

---

# Question: What are the key characteristics of C#?

**Answer:**

* Object-Oriented (supports OOP principles)
* Type-Safe (prevents unsafe memory operations)
* Cross-Platform (runs on Windows, Linux, macOS with .NET Core)
* Scalable & Maintainable
* Rich Library Support (UI, database, networking)
* High Performance (compiles to IL and runs on CLR)

---

# Question: List five strong programming features of C#.

**Answer:**

* Boolean Conditions
* Automatic Garbage Collection
* Delegates and Events Management
* Easy-to-use Generics
* LINQ and Lambda Expressions
  (others include Standard Library, Assembly Versioning, Properties & Events, Indexers, Conditional Compilation, Multithreading, Windows Integration)

---

# Question: Why is C# considered easy to learn for beginners?

**Answer:** Because its syntax is similar to C, C++, and Java, making it beginner-friendly and familiar to those with prior programming knowledge.

---

# Question: What advantages does C# offer in terms of error prevention?

**Answer:** C# is strongly typed, which enforces strict type safety and reduces programming errors.

---

# Question: Name at least three frameworks or platforms that C# integrates seamlessly with.

**Answer:** ASP.NET, Blazor, Xamarin, and Unity.

---

# Question: Compare C#, Java, Python, and C++ in terms of memory management.

**Answer:**

* C#: Automatic (Garbage Collection)
* Java: Automatic (Garbage Collection)
* Python: Automatic (Garbage Collection)
* C++: Manual

---

# Question: Which two programming languages are best suited for game development?

**Answer:** C# (Unity) and C++

---

# Question: Describe the three main steps of how C# works.

**Answer:**

1. Writing Code (in Visual Studio, VS Code, or any editor)
2. Compilation (code is compiled into Intermediate Language, IL)
3. Execution (IL code runs on the Common Language Runtime, CLR)

---

# Question: Write the code for a basic C# program that prints `Hello, World!`.

**Answer:**

```csharp
using System;

class HelloWorld
{
    static void Main()
    {
        Console.WriteLine("Hello, World!");
    }
}
```

---

# Question: What will be the output of the above `HelloWorld` program?

**Answer:**

```
Hello, World!
```

---

# Question: Which C# framework is commonly used for desktop applications?

**Answer:** WPF (Windows Presentation Foundation) and WinForms.

---

# Question: Write an example of a simple Windows Forms application in C#.

**Answer:**

```csharp
using System;
using System.Windows.Forms;

class Program
{
    static void Main()
    {
        MessageBox.Show("Hello, Windows Forms!");
    }
}
```

---

# Question: Which framework does C# use for high-performance web applications?

**Answer:** ASP.NET Core.

---

# Question: Write an example of a simple ASP.NET Core API in C#.

**Answer:**

```csharp
using Microsoft.AspNetCore.Mvc;

[ApiController]
[Route("[controller]")]
public class HelloController : ControllerBase
{
    [HttpGet]
    public string Get()
    {
        return "Hello from ASP.NET Core API!";
    }
}
```

---

# Question: Which game engine primarily uses C# as its scripting language?

**Answer:** Unity.

---

# Question: Write a basic Unity script in C# that prints a message to the debug log.

**Answer:**

```csharp
using UnityEngine;

public class HelloUnity : MonoBehaviour
{
    void Start()
    {
        Debug.Log("Hello from Unity Game!");
    }
}
```

---

# Question: Which framework allows C# to be used for cross-platform mobile app development?

**Answer:** Xamarin.

---

# Question: Provide a simple Xamarin C# code snippet that displays “Hello Xamarin!”.

**Answer:**

```csharp
using Xamarin.Forms;

public class App : Application
{
    public App()
    {
        MainPage = new ContentPage
        {
            Content = new Label { Text = "Hello Xamarin!" }
        };
    }
}
```

---

# Question: How is C# used in cloud and IoT development?

**Answer:** It is widely used in Microsoft Azure for building cloud applications and IoT solutions.

---

# Question: Write a sample C# program that connects to Azure Storage.

**Answer:**

```csharp
using Azure.Storage.Blobs;

class Program
{
    static void Main()
    {
        BlobServiceClient client = new BlobServiceClient("your-connection-string");
        Console.WriteLine("Connected to Azure Storage!");
    }
}
```

---

# Question: Is C# free and open-source?

**Answer:** Yes, C# is completely free and open-source, along with the .NET framework.

---

# Question: How does C# compare to Python?

**Answer:** C# is faster and more structured, making it better for large applications, while Python is simpler, more flexible, but slower.

---

# Question: Can you build mobile apps using C#? If yes, how?

**Answer:** Yes, using Xamarin, C# can build cross-platform mobile apps for both Android and iOS with a single codebase.

---

# Question: What kinds of applications can be built with C#?

**Answer:** Desktop software, web applications, mobile apps, cloud-based systems, IoT solutions, games, and AI-powered applications.

---
