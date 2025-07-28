# Question: Why is C considered an important programming language to learn?

**Answer:** Because it is one of the oldest programming languages and many modern languages are based on it, including C++.

---

# Question: What are the two main things needed to start programming in C?

**Answer:** A text editor (or IDE) and a C compiler.

---

# Question: What is a text editor used for in C programming?

**Answer:** To write and save the source code of C programs.

---

# Question: What is an IDE, and why is it useful for C programming?

**Answer:** An IDE (Integrated Development Environment) is a specialized text editor that simplifies writing, managing, and debugging C programs.

---

# Question: What does IDE stand for?

**Answer:** Integrated Development Environment.

---

# Question: What is the role of the C compiler in the programming process?

**Answer:** To compile, or translate, C source code into a language that the computer can understand and execute.

---

# Question: Why can't the computer execute C source code directly?

**Answer:** Because the source code must first be compiled into machine code, which is the only language the computer can understand.

---

# Question: What command can macOS users run in Terminal to check if a C compiler is already installed?

**Answer:** `cc -v`

---

# Question: What is the purpose of the `cc -v` command on macOS?

**Answer:** It checks whether a C compiler is already installed by printing the compiler version and details if available.

---

# Question: What command should macOS users run if the C compiler is not installed?

**Answer:** `xcode-select --install`

---

# Question: What does the `xcode-select --install` command do?

**Answer:** It installs Xcode command-line tools, which include the C compiler.

---

# Question: What is the purpose of the `#include` lines at the top of a C file?

**Answer:** They include necessary libraries for the program to function. (Detailed explanation comes later in the course.)

---

# Question: What is the significance of the `main` function in a C program?

**Answer:** It is the entry point where execution begins when the program runs.

---

# Question: What is a method (function) in C?

**Answer:** A container where instructions (code) can be written and executed by the computer.

---

# Question: What is the role of the `printf` function in `main.c` code?

**Answer:** It prints text (e.g., "Hello, World") to the screen.

---

# Question: What are the two steps required to execute a C program?

**Answer:** First, **build (compile)** the program; then **run** the built executable.

---

# Question: What does compiling a C program do?

**Answer:** It translates human-readable C code into machine-readable code the computer can execute.

---

# Question: What will happen if a C program has no output instruction like `printf`?

**Answer:** The console window may not appear because there's nothing to display.

---

# Question: What is a C program essentially composed of?

**Answer:** A set of instructions that, when executed correctly, perform tasks for the computer.

---

# Question: How is writing a C program similar to writing a recipe?

**Answer:** Both are sets of instructions that, when followed in order, produce a desired result.

---

# Question: What does the `printf` function do in C?

**Answer:** It prints text output to the screen.

---

# Question: Why is a semicolon important in a C instruction?

**Answer:** It tells the compiler that the instruction is complete and allows the next instruction to be interpreted.

---

# Question: What happens if you copy and paste a `printf` instruction multiple times?

**Answer:** The instruction will be executed multiple times, printing its output repeatedly.

---

# Question: What is the purpose of `\n` in a C string?

**Answer:** It is a newline character that moves the output cursor to a new line.

---

# Question: In what order are instructions in the `main` function executed?

**Answer:** From top to bottom, in the order they appear.

---

# Question: What happens when the order of instructions in a C program is changed?

**Answer:** The output changes accordingly because the computer executes them in the new order.

---

# Question: What kind of shape can be drawn using `printf` and characters like `/`, `|`, and `_`?

**Answer:** A triangle shape can be drawn using slashes, vertical bars, and underscores printed on new lines.

---

# Question: What effect does reordering drawing instructions have on the output shape?

**Answer:** It changes the appearance of the shape, potentially creating incorrect or distorted figures.

---

# Question: What is the fundamental principle behind how a C program works?

**Answer:** A C program specifies a list of instructions to be executed in sequence by the computer.

---

# Question: What are variables used for in C programming?

**Answer:** To store and manage data values like numbers, text, or characters in a program.

---

# Question: Why is using variables better than hardcoding values multiple times?

**Answer:** Variables make it easier to manage and update data by changing the value in one place rather than everywhere it appears.

---

# Question: What type of data is typically used to store a name in C?

**Answer:** A string of characters stored using the `char` type and square brackets to indicate multiple characters.

---

# Question: What is the syntax to declare a character variable that stores a name?

**Answer:** `char variable_name[] = "value";`

---

# Question: Why do we use square brackets `[]` when declaring `char characterName[]`?

**Answer:** To indicate that the variable will store multiple characters, forming a string.

---

# Question: What is the keyword used in C to declare a variable that stores characters?

**Answer:** `char`

---

# Question: Why is it helpful to use descriptive variable names?

**Answer:** Descriptive names help indicate the purpose or content of the variable, making the code more readable and maintainable.

---

# Question: What would happen in a large program if you didn’t use variables for repeated data like names or ages?

**Answer:** You would have to manually search and replace every occurrence, which is time-consuming and error-prone.

---

# Question: What does assigning a value to a variable look like in C?

**Answer:** `type variable_name[] = "value";` (e.g., `char characterName[] = "John";`)

---

# Question: What must always be placed at the end of a variable declaration in C?

**Answer:** A semicolon (`;`)

---

