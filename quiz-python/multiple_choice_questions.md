# Question: What is Python and what are some of its common uses?

**Answer:**
Python is a popular programming language that can be used on a server to create web applications. It is widely used for various programming tasks due to its simplicity and versatility.

---

# Question: Who created Python and when was it released?

**Answer:**
Python was created by Guido van Rossum and released in 1991.

---

# Question: What are some common uses of Python?

**Answer:**
Python is used for web development (server-side), software development, mathematics, system scripting, connecting to database systems, handling big data, performing complex mathematics, rapid prototyping, and production-ready software development.

---

# Question: Why is Python considered easy to learn and use?

**Answer:**
Python has a simple syntax similar to English, allows developers to write fewer lines of code compared to some other languages, runs on an interpreter system for quick prototyping, and uses indentation (whitespace) to define code blocks instead of curly braces or semicolons.

---

# Question: What platforms can Python run on?

**Answer:**
Python works on multiple platforms including Windows, Mac, Linux, and Raspberry Pi.

---

# Question: What major version of Python is recommended to use?

**Answer:**
Python 3 is the most recent major version, although Python 2 is still somewhat popular but only receives security updates.

---

# Question: How can you check if Python is installed on a Windows PC?

**Answer:**
You can check by searching for Python in the Start menu or by opening Command Prompt (cmd.exe) and typing:
`python --version`

---

# Question: Where can you download Python if it is not already installed?

**Answer:**
Python can be downloaded for free from [https://www.python.org/](https://www.python.org/).

---

# Question: How do you run a Python script named `hello.py` from the command line?

**Answer:**
Navigate to the directory containing `hello.py` and run:
`python hello.py`

---

# Question: What is the output of the following Python code?

```python
print("Hello, World!")
```

**Answer:**
The output will be:
`Hello, World!`

---

# Question: How can you check the version of Python running in the editor using code?

**Answer:**
By importing the sys module and printing the version:

```python
import sys
print(sys.version)
```

---

# Question: What command can you type in the terminal to enter the Python interactive command line?

**Answer:**
Type either `python` or `py` and press Enter.

---

# Question: How does Python indicate a block of code?

**Answer:**
Python uses indentation (spaces at the beginning of a line) to indicate a block of code.

---

# Question: Why is indentation important in Python?

**Answer:**
Unlike many other languages where indentation is just for readability, in Python, incorrect indentation causes syntax errors because it defines the structure of the code.

---

# Question: What will happen if you write this code?

```python
if 5 > 2:
print("Five is greater than two!")
```

**Answer:**
Python will give a syntax error because the print statement is not indented under the if statement.

---

# Question: Is there a fixed number of spaces required for indentation in Python?

**Answer:**
No, the number of spaces is flexible, but it must be consistent within the same block. Typically, 4 spaces are used.

---

# Question: How do you create variables in Python?

**Answer:**
Variables are created by assigning a value to a name, for example:

```python
x = 5
y = "Hello, World!"
```

No explicit declaration command is needed.

---

# Question: How do you write a comment in Python?

**Answer:**
By starting the line with a `#`, e.g.:

```python
# This is a comment.
print("Hello, World!")
```

---

# Question: What are some common uses of comments in Python?

**Answer:**
Comments can be used to explain code, make it more readable, and prevent execution of code when testing.

---

# Question: How do you write a single-line comment in Python?

**Answer:**
By starting the line with a `#`. Everything after the `#` on that line is ignored by Python.

---

# Question: Can comments be placed at the end of a line of code? If yes, how?

**Answer:**
Yes, by adding `#` after the code on the same line. Python will ignore everything after the `#`.

---

# Question: How can comments be used to prevent code from running?

**Answer:**
By adding a `#` before the code line, making it a comment so Python skips executing it.

---

# Question: Does Python have a specific syntax for multiline comments?

**Answer:**
No, Python does not have a dedicated multiline comment syntax. You can use multiple single-line comments (`#` on each line) or use a multiline string (triple quotes) that is not assigned to a variable as a workaround.

---

# Question: How does using triple quotes (`""" ... """`) create a multiline comment?

**Answer:**
Triple-quoted strings that are not assigned to any variable are ignored by Python at runtime, effectively acting as multiline comments.

---

# Question: How are variables created in Python?

**Answer:**
Variables are created when you assign a value to a name. Python does not require declaring the variable type beforehand.

---

# Question: Can variables change their data type after being created? Provide an example.

**Answer:**
Yes, variables can change type. For example:

```python
x = 4       # x is an int  
x = "Sally" # x is now a str
```

---

# Question: How can you specify the data type of a variable explicitly in Python?

**Answer:**
By using casting functions such as `str()`, `int()`, and `float()`. For example:

```python
x = str(3)    # x will be '3'  
y = int(3)    # y will be 3  
z = float(3)  # z will be 3.0
```

---

# Question: How can you check the data type of a variable?

**Answer:**
Using the `type()` function. For example:

```python
print(type(x))
```

---

# Question: Are single quotes and double quotes interchangeable for string variables in Python?

**Answer:**
Yes, strings can be declared with either single or double quotes:

```python
x = "John"  
x = 'John'
```

---

# Question: Are variable names case-sensitive in Python? Explain with an example.

**Answer:**
Yes, variable names are case-sensitive. For example:

```python
a = 4  
A = "Sally"
```

Here, `a` and `A` are two different variables.

---

# Question: What are the basic rules for naming variables in Python?

**Answer:**

* A variable name must start with a letter or an underscore (\_).
* It cannot start with a number.
* It can only contain letters, numbers, and underscores (A-Z, a-z, 0-9, \_).
* Variable names are case-sensitive.
* Variable names cannot be Python keywords.

---

# Question: Which of the following are legal variable names in Python?

`myvar`, `my_var`, `_my_var`, `myVar`, `MYVAR`, `myvar2`, `2myvar`, `my-var`, `my var`

**Answer:**
Legal variable names are:
`myvar`, `my_var`, `_my_var`, `myVar`, `MYVAR`, `myvar2`
Illegal variable names are:
`2myvar` (starts with number), `my-var` (contains hyphen), `my var` (contains space)

---

# Question: Are Python variable names case-sensitive? Give an example.

**Answer:**
Yes, they are case-sensitive. For example:

```python
age = 25  
Age = 30  
AGE = 35
```

These are three different variables.

---

# Question: What are three common naming conventions for multi-word variable names in Python?

**Answer:**

* Camel Case: `myVariableName` (first word lowercase, subsequent words capitalized)
* Pascal Case: `MyVariableName` (each word capitalized)
* Snake Case: `my_variable_name` (words separated by underscores)

---

# Question: How do you assign multiple values to multiple variables in one line in Python?

**Answer:**
You can assign values like this:

```python
x, y, z = "Orange", "Banana", "Cherry"
```

---

# Question: What must you ensure when assigning multiple values to multiple variables?

**Answer:**
The number of variables must match the number of values; otherwise, Python will raise an error.

---

# Question: How can you assign the same value to multiple variables in one line?

**Answer:**
By chaining the assignment:

```python
x = y = z = "Orange"
```

---

# Question: What is unpacking in Python and how does it work with collections?

**Answer:**
Unpacking is extracting values from a collection (like a list or tuple) into variables. For example:

```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
```

---

# Question: How do you print the value of a variable in Python?

**Answer:**
By passing the variable to the `print()` function. Example:

```python
x = "Python is awesome"
print(x)
```

---

# Question: How can you print multiple variables separated by spaces?

**Answer:**
By passing multiple variables separated by commas inside `print()`. Example:

```python
print(x, y, z)
```

---

# Question: How can you concatenate multiple string variables in a print statement?

**Answer:**
Using the `+` operator to join strings. Example:

```python
print(x + y + z)
```

Make sure to include spaces inside the strings if you want spaces in the output.

---

# Question: What happens when you try to add a string and a number using the `+` operator in `print()`?

**Answer:**
Python raises a TypeError because you cannot directly add (concatenate) a string and an integer.

---

# Question: What is the preferred way to print variables of different data types together?

**Answer:**
Separate them with commas in the `print()` function, which supports different data types. Example:

```python
print(x, y)
```

---

# Question: What is a global variable in Python?

**Answer:**
A global variable is a variable created outside of any function, accessible both inside and outside of functions.

---

# Question: What happens if you create a variable with the same name inside a function?

**Answer:**
The variable inside the function is local to that function and does not affect the global variable with the same name.

---

# Question: How can you create or modify a global variable inside a function?

**Answer:**
By using the `global` keyword before the variable name inside the function.

---

# Question: Provide an example of using the `global` keyword to create a global variable inside a function.

**Answer:**

```python
def myfunc():
  global x
  x = "fantastic"

myfunc()
print("Python is " + x)  # Output: Python is fantastic
```

---

# Question: How do you change the value of an existing global variable inside a function?

**Answer:**
Use the `global` keyword inside the function to refer to the global variable, then assign a new value to it.

---

# Question: What is a data type in programming?

**Answer:**
A data type specifies the kind of data a variable can hold and determines what operations can be performed on that data.

---

# Question: Name some built-in data types in Python.

**Answer:**
Python built-in data types include:

* Text Type: `str`
* Numeric Types: `int`, `float`, `complex`
* Sequence Types: `list`, `tuple`, `range`
* Mapping Type: `dict`
* Set Types: `set`, `frozenset`
* Boolean Type: `bool`
* Binary Types: `bytes`, `bytearray`, `memoryview`
* None Type: `NoneType`

---

# Question: How can you find out the data type of a variable in Python?

**Answer:**
Use the `type()` function, e.g., `type(x)`

---

# Question: How is the data type of a variable determined in Python?

**Answer:**
It is set automatically when you assign a value to the variable.

---

# Question: How can you explicitly specify the data type of a variable in Python?

**Answer:**
By using constructor functions like `str()`, `int()`, `float()`, `list()`, `tuple()`, `dict()`, etc.

---

# Question: What are some key features of Python that make it powerful and easy to use?

**Answer:**
Python has efficient high-level data structures, simple but effective object-oriented programming, elegant syntax, dynamic typing, and is an interpreted language.

---

# Question: Where can you find the official Python interpreter and standard library?

**Answer:**
From the official Python website: [https://www.python.org/](https://www.python.org/)

---

# Question: How can Python be extended beyond its standard features?

**Answer:**
Python can be extended with new functions and data types implemented in C, C++, or other languages callable from C.

---

# Question: How can you start the Python interpreter on a Unix machine if it is installed at `/usr/local/bin/python3.13`?

**Answer:**
By typing the command `python3.13` in the shell, assuming `/usr/local/bin` is in your search path.

---

# Question: How do you exit the Python interpreter from the command line?

**Answer:**
Type the end-of-file character (Control-D on Unix, Control-Z on Windows), or type the command `quit()`.

---

# Question: What command can you use to execute Python code directly from the command line without entering interactive mode?

**Answer:**
Use `python -c "command"`, where `"command"` is the Python code to execute.

---

# Question: How can you run a Python module as a script from the command line?

**Answer:**
By using `python -m module [arg] ...`, which executes the source file for the specified module.

---

# Question: What is the difference between the primary prompt and the secondary prompt in interactive mode?

**Answer:**
The primary prompt (`>>>`) appears when waiting for a new command, while the secondary prompt (`...`) appears when entering continuation lines of multi-line constructs.

---

# Question: What variable contains the list of command-line arguments passed to a Python script, and how do you access it?

**Answer:**
The list is stored in `sys.argv`, which you can access by importing the `sys` module with `import sys`.

---

# Question: How does Python treat source code files by default in terms of encoding?

**Answer:**
Python treats source code files as UTF-8 encoded by default.

---

# Question: How do you specify a different encoding (e.g., Windows-1252) for a Python source file?

**Answer:**
Add a special comment as the first line: `# -*- coding: cp1252 -*-`

If there is a shebang line, the encoding declaration should be the second line.

---

# Question: What is the purpose of the `-i` option when running a Python script?

**Answer:**
It runs the script and then enters interactive mode afterwards.

---

# Question:

Why might a professional developer prefer Python over C/C++ or Java for writing test suites or quick scripts?

**Answer:**
Because Python is simpler to use and has a faster write/test cycle since it is interpreted and doesn’t require compiling and linking, which saves development time.

---

# Question:

List three types of tasks mentioned that Python can help automate.

**Answer:**

* Search-and-replace over many text files
* Renaming and rearranging photo files
* Writing a small custom database or a specialized GUI application or a simple game

---

# Question:

What are some limitations of shell scripts or batch files compared to Python?

**Answer:**
Shell scripts are best at moving files and changing text data but are not well-suited for GUI applications or games.

---

# Question:

What advantages does Python offer over languages like Awk or Perl?

**Answer:**
Python has more general and flexible data types, supports a larger problem domain, and many tasks are at least as easy to perform as in Awk or Perl.

---

# Question:

How does Python help in writing reusable code?

**Answer:**
Python allows you to split your program into modules that can be reused in other Python programs.

---

# Question:

Name two examples of functionality provided by Python’s standard modules.

**Answer:**

* File I/O (input/output)
* Interfaces to graphical user interface toolkits like Tk

---

### Question:

Why is Python considered a “high-level” language, and what is one consequence of this?

**Answer:**
Because it provides built-in flexible data types (like arrays and dictionaries) and abstracts away low-level details; as a consequence, Python programs tend to be shorter and more readable than equivalent programs in lower-level languages.

---

# Question:

What unique feature of Python’s syntax helps make programs more readable compared to languages like C or Java?

**Answer:**
Statement grouping by indentation instead of using beginning and ending brackets.

---

# Question:

What is the origin of the name “Python” for the programming language?

**Answer:**
It is named after the BBC comedy show “Monty Python’s Flying Circus,” not the reptile.

---

# Question:

How can Python be extended for performance or integration with other languages?

**Answer:**
By adding new built-in functions or modules written in C, or by embedding the Python interpreter into C applications to serve as an extension or command language.

---

# Question:. Why might someone want to use Python instead of Unix shell scripts or Windows batch files for automation tasks?

**Answer:** Because shell scripts and batch files are good for simple file moving or text processing, but are not well-suited for GUI applications or games, where Python offers more versatility.

---


# Question: What are some examples of tasks Python can help automate?

**Answer:** Search-and-replace in many files, renaming and rearranging photos, writing custom databases, creating specialized GUI applications, or simple games.

---

# Question: How does Python help speed up the development cycle compared to compiled languages like C++ or Java?

**Answer:** Python is interpreted, so no compilation and linking are needed, which saves time during development.

---

# Question: What are two high-level data types built into Python that help express complex operations simply?

**Answer:** Flexible arrays (lists) and dictionaries.

---

# Question: Why do Python programs tend to be shorter than equivalent programs in C, C++, or Java?

**Answer:** Because Python uses high-level data types, indentation for statement grouping, and doesn’t require variable declarations.

---

# Question: How can Python be used in conjunction with C programming?

**Answer:** Python can be extended with C functions for speed or integrated as an extension language within C applications.

---

# Question: What is a unique cultural aspect of Python’s name and documentation style?

**Answer:** It is named after the BBC show “Monty Python’s Flying Circus,” and Monty Python references are encouraged in documentation.

---

# Question: What are the benefits of Python’s interactive interpreter?

**Answer:** It allows experimenting with code, writing throw-away programs, and testing functions quickly without compiling.

---

# Question: How does Python support modular programming?

**Answer:** By allowing programs to be split into reusable modules.

---

# Question: How can you distinguish between input and output in Python interactive examples?

**Answer:**
Input lines begin with prompts `>>>` or `...`, while lines without prompts represent output from the interpreter.

---

# Question: What symbol starts a comment in Python, and where can it appear?

**Answer:**
Comments start with the hash character `#` and extend to the end of the line. They can appear at the start of a line or after code/whitespace but not inside string literals.

---

# Question: What arithmetic operators are available in Python for basic calculations?

**Answer:**
`+` (addition), `-` (subtraction), `*` (multiplication), `/` (division), `//` (floor division), `%` (modulus), and `**` (exponentiation).

---

# Question: What is the difference between `/` and `//` operators in Python?

**Answer:**
`/` performs classic division and returns a floating-point number; `//` performs floor division and returns an integer result by discarding the fractional part.

---

# Question: What happens if you try to use a variable before assigning a value in Python?

**Answer:**
Python raises a `NameError` indicating the variable is not defined.

---

# Question: How does Python handle operations involving integers and floating-point numbers?

**Answer:**
If operands have mixed types (int and float), Python converts the integer to float before the operation.

---

# Question: How does Python represent text data and what are the ways to define strings?

**Answer:**
Text data is represented by the `str` type (strings). Strings can be enclosed in single quotes `'...'` or double quotes `"..."` with the same effect.

---

# Question: How do you include a quote character inside a string?

**Answer:**
Either escape the quote using a backslash `\'` or use the other type of quote to enclose the string.

---

# Question: What does the print() function do differently compared to just typing a string in the Python shell?

**Answer:**
`print()` outputs the string without quotes and interprets special characters like `\n` as newlines, providing more readable output.

---

# Question: How do you create a raw string, and what is its purpose?

**Answer:**
By prefixing the string literal with `r` (e.g., `r'C:\path'`). Raw strings prevent backslash escapes from being processed.

---

# Question: What are string slicing and indexing? How are negative indices used?

**Answer:**
Indexing accesses a single character by position (starting at 0). Negative indices count from the end (-1 is last character). Slicing extracts substrings by specifying start and end indices.

---

# Question: Are Python strings mutable? What happens if you try to assign to an indexed position?

**Answer:**
Strings are immutable; attempting to assign to an indexed position results in a `TypeError`.

---

# Question: How can you concatenate and repeat strings in Python?

**Answer:**
Use the `+` operator to concatenate and the `*` operator to repeat strings.

---

# Question: What is a list in Python, and how is it different from a string?

**Answer:**
A list is a mutable sequence of items (possibly of different types) enclosed in square brackets `[ ]`. Unlike strings, lists can be modified after creation.

---

# Question: How do you add new elements to a list?

**Answer:**
Using the `append()` method, e.g., `list.append(element)` adds an item at the end.

---

# Question: What happens when you assign one list variable to another?

**Answer:**
Both variables refer to the same list object; changes via one variable affect the other.

---

# Question: How do you create a shallow copy of a list?

**Answer:**
By slicing the entire list: `copy = original[:]`.

---

# Question: How does Python treat slices that are out of the valid index range?

**Answer:**
Out-of-range slice indices are handled gracefully and do not raise errors; the slice simply includes all valid elements within the range.

---

# Question: What is the syntax for a while loop in Python, and what must follow a compound statement entered interactively?

**Answer:**
A while loop starts with `while <condition>:` followed by an indented block. When entered interactively, a blank line must follow the block to indicate its end.

---

# Question: What does the statement `a, b = b, a + b` do in Python?

**Answer:**
It simultaneously assigns `a` to `b`’s value and `b` to `a + b` — multiple assignment with right-hand side expressions evaluated before assignment.

---

# Question: How does Python treat non-zero and zero values in conditions?

**Answer:**
Non-zero values are treated as `True`, zero as `False`. Similarly, non-empty sequences are `True` and empty sequences are `False`.

---

# Question: What is the use of the keyword argument `end` in the print() function?

**Answer:**
It specifies what to print after the output; for example, `end=','` prevents a newline and appends a comma instead.

---

