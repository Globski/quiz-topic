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

**Answer:** Desktop software, web applications, mobile apps, cloud-based systems, IoT solutions, games, and AI-powered applications

---

# Question: What types of applications can be written using the .NET Framework?

**Answer:** Windows applications, Web applications, and Web services.

---

# Question: Which programming languages can access and communicate with the .NET Framework?

**Answer:** C#, C++, Visual Basic, Jscript, COBOL, and others.

---

# Question: What does the .NET Framework provide to client languages such as C#?

**Answer:** An enormous library of codes and components.

---

# Question: Name at least five components of the .NET Framework.

**Answer:** Common Language Runtime (CLR), .NET Framework Class Library, Common Language Specification, Common Type System, Metadata and Assemblies, Windows Forms, ASP.Net and ASP.Net AJAX, ADO.Net, Windows Workflow Foundation (WF), Windows Presentation Foundation, Windows Communication Foundation (WCF), LINQ.

---

# Question: What IDEs does Microsoft provide for C# programming?

**Answer:** Visual Studio 2010 (VS), Visual C# 2010 Express (VCE), and Visual Web Developer.

---

# Question: Which C# development tools are freely available from Microsoft?

**Answer:** Visual C# 2010 Express (VCE) and Visual Web Developer.

---

# Question: Can C# source code be written without Visual Studio? If yes, how?

**Answer:** Yes, using a basic text editor like Notepad and compiling the code into assemblies with the command-line compiler (part of the .NET Framework).

---

# Question: How do Visual C# Express and Visual Web Developer differ from Visual Studio?

**Answer:** They are trimmed-down versions of Visual Studio but retain most features and have the same appearance.

---

# Question: What is required to install the Express edition of C# tools?

**Answer:** An active internet connection.

---

# Question: What is Mono in the context of C# development?

**Answer:** Mono is an open-source version of the .NET Framework that includes a C# compiler and runs on multiple operating systems.

---

# Question: Which operating systems can run Mono?

**Answer:** Android, BSD, iOS, Linux, OS X, Windows, Solaris, and UNIX.

---

# Question: What is the purpose of Mono?

**Answer:** To run Microsoft .NET applications cross-platform and to provide better development tools for Linux developers.

---

# Question: What are the essential components included in the .NET SDK?

**Answer:** C# Compiler (csc.exe), .NET CLI, and .NET Runtime.

---

# Question: How do you verify .NET SDK installation on Windows, macOS, or Linux?

**Answer:** Run the command `dotnet --version` in the terminal or command prompt.

---

# Question: What is the expected output of `dotnet --version` after a successful installation (example given)?

**Answer:** 8.0.100

---

# Question: What command installs Homebrew on macOS?

**Answer:**

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

# Question: What command installs the .NET SDK via Homebrew?

**Answer:** `brew install dotnet-sdk`

---

# Question: Which command updates system packages on Ubuntu/Debian before installing the .NET SDK?

**Answer:** `sudo apt update && sudo apt upgrade`

---

# Question: What command installs the .NET SDK on Ubuntu/Debian?

**Answer:** `sudo apt install dotnet-sdk-8.0`

---

# Question: List three popular editors/IDEs for writing C# code.

**Answer:** Visual Studio, Visual Studio Code (VS Code), and JetBrains Rider.

---

# Question: Which editors are recommended for the best C# development experience?

**Answer:** Visual Studio and Visual Studio Code (VS Code).

---

# Question: How do you install the C# Dev Kit extension in VS Code?

**Answer:** Open VS Code → Extensions (Ctrl+Shift+X) → Search for "C#" → Install C# Dev Kit extension.

---

# Question: Which command creates a new C# console application?

**Answer:**

```bash
dotnet new console -o MyCSharpApp
```

---

# Question: What is the minimal "Hello, C# World!" program in C#?

**Answer:**

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, C# World!");
    }
}
```

---

# Question: How do you run a C# program created with .NET CLI?

**Answer:** Use the command `dotnet run`.

---

# Question: How can you run C# programs without installing the .NET SDK?

**Answer:** Use an online C# compiler that allows writing, saving, executing, and sharing C# code.

---

# Question: What is NuGet in the context of C# development?

**Answer:** A package manager for .NET that allows adding libraries and dependencies to C# projects.

---

# Question: What command installs the Newtonsoft.Json NuGet package?

**Answer:**

```bash
dotnet add package Newtonsoft.Json
```

---

# Question: What is Newtonsoft.Json commonly used for?

**Answer:** JSON serialization and deserialization.

---

# Question: Which shortcut starts debugging in Visual Studio?

**Answer:** F5.

---

# Question: What do you need to install in VS Code to debug C# applications?

**Answer:** The C# Debugger extension.

---

# Question: What are the essential components of a C# program?

**Answer:** Using statements, a namespace declaration, a class, and the Main() method containing sequential statements.

---

# Question: In C#, where does program execution begin?

**Answer:** In the `Main()` method.

---

# Question: What does the following line do?

```csharp
using System;
```

**Answer:** It imports the `System` namespace, enabling access to classes like `Console`.

---

# Question: What is the purpose of `Console.ReadKey();` in the Hello World program?

**Answer:** It makes the program wait for a key press so the output window doesn’t close immediately when launched from Visual Studio .NET.

---

# Question: What does the `namespace` keyword do in C#?

**Answer:** It groups related classes together to organize code.

---

# Question: What is a class in C#?

**Answer:** A blueprint that contains data and method definitions; classes generally contain multiple methods defining behavior.

---

# Question: What is the role of the `Main` method in C#?

**Answer:** It is the entry point of the program that specifies what the class does when executed.

---

# Question: What type of code is ignored by the compiler in C#?

**Answer:** Comments, e.g., code enclosed in `/* ... */`.

---

# Question: Which method is used to display output text to the screen?

**Answer:** `Console.WriteLine()`.

---

# Question: What is the output of this code?

```csharp
namespace MyApplication
{
    class Program
    {
        static void Main()
        {
            Console.WriteLine("Hello from MyApplication!");
        }
    }
}
```

**Answer:** `Hello from MyApplication!`

---

# Question: What is the output of this code?

```csharp
using System;

class Example
{
    static void Main()
    {
        Console.WriteLine("Using directive example.");
    }
}
```

**Answer:** `Using directive example.`

---

# Question: Why must every C# program have at least one class?

**Answer:** Because C# is an object-oriented language and classes are the foundation for program logic.

---

# Question: What is the output of this code?

```csharp
class Car
{
    string model = "Tesla";

    static void Main()
    {
        Car myCar = new Car();
        Console.WriteLine("Car Model: " + myCar.model);
    }
}
```

**Answer:** `Car Model: Tesla`

---

# Question: Which method always serves as the entry point for C# programs?

**Answer:** The `Main()` method.

---

# Question: What is the output of this code?

```csharp
class Start
{
    static void Main()
    {
        Console.WriteLine("This is the main entry point of the program.");
    }
}
```

**Answer:** `This is the main entry point of the program.`

---

# Question: What is a statement in C#?

**Answer:** An instruction inside the `Main()` method, such as variable assignments or method calls.

---

# Question: What is the output of this code?

```csharp
class StatementsExample
{
    static void Main()
    {
        int a = 5, b = 10;
        int sum = a + b;
        Console.WriteLine("Sum: " + sum);
    }
}
```

**Answer:** `Sum: 15`

---

# Question: What do access modifiers in C# define?

**Answer:** The visibility and accessibility of classes, fields, and methods.

---

# Question: What is the output of this code?

```csharp
class Example
{
    private int secretNumber = 42;

    public void Display()
    {
        Console.WriteLine("Access Modifier Example: " + secretNumber);
    }
}

class Program
{
    static void Main()
    {
        Example obj = new Example();
        obj.Display();
    }
}
```

**Answer:** `Access Modifier Example: 42`

---

# Question: Give four best practices for organizing a C# program.

**Answer:** Use proper indentation, give meaningful names to identifiers, keep methods short and focused, and store related classes in separate files.

---

# Question: What naming rules are recommended in C#?

**Answer:** PascalCase for classes and camelCase for variables.

---

# Question: Is C# case-sensitive?

**Answer:** Yes, C# is case-sensitive.

---

# Question: What symbol must end all C# statements and expressions?

**Answer:** A semicolon (`;`).

---

# Question: Does the file name in C# need to match the class name (like in Java)?

**Answer:** No, the file name can be different from the class name.

---

# Question: What are the steps to create and run a C# console app in Visual Studio?

**Answer:** Start Visual Studio → File → New → Project → Choose Visual C# → Console Application → Name project → Write code in editor → Press Run button or F5 to execute.

---

# Question: What command compiles a C# file named `helloworld.cs` using the command-line compiler?

**Answer:** `csc helloworld.cs`

---

# Question: What file is generated after successful compilation of `helloworld.cs`?

**Answer:** `helloworld.exe`

---

# Question: What command executes the compiled Hello World program from the command line?

**Answer:** `helloworld`

---

# Question: What is the expected output when running the command-line compiled Hello World program?

**Answer:** `Hello World`

---

