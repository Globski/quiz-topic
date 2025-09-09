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
