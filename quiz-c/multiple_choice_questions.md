# Question: What are the different versions of the C language along with their standard publication dates?

**Answer:**
The versions of the C language and their publication dates are:

* K\&R: February 22, 1978
* C89 (ANSI X3.159-1989): December 14, 1989
* C90 (ISO/IEC 9899:1990): December 20, 1990
* C95 (ISO/IEC 9899/AMD1:1995): March 30, 1995
* C99 (ISO/IEC 9899:1999): December 16, 1999
* C11 (ISO/IEC 9899:2011): December 15, 2011

---

# Question: How do you write a simple C program that prints "Hello, World"?

**Answer:**
Create a file with the `.c` extension (e.g., `hello.c`) and add the following code:

```c
#include <stdio.h>
int main(void)
{
    puts("Hello, World");
    return 0;
}
```

---

# Question: What is the purpose of the line `#include <stdio.h>` in a C program?

**Answer:**
The line `#include <stdio.h>` tells the compiler to include the contents of the standard library header file `stdio.h`, which contains declarations for functions like `puts()`. Including this header is necessary before using such functions.

---

# Question: What does the function signature `int main(void)` signify in a C program?

**Answer:**
The signature `int main(void)` defines a function named `main` that takes no arguments (`void`) and returns an integer (`int`). Program execution starts from the `main()` function.

---

# Question: What is the purpose of curly braces `{ ... }` in a C function?

**Answer:**
Curly braces are used in pairs to indicate the beginning and end of a block of code. In this case, they mark where the `main()` function begins and ends.

---

# Question: What does the line `puts("Hello, World");` do in a C program?

**Answer:**
The line calls the `puts()` function to output the text `"Hello, World"` to standard output (usually the screen), followed by a newline.

---

# Question: Where must a string literal be placed in a C program?

**Answer:**
In C, every string literal must be placed inside double quotes `"…"`. For example, `"Hello, World"` is a string literal that will be written to the screen.

---

# Question: Why is a semicolon `;` necessary at the end of each statement in C?

**Answer:**
In C programs, every statement must be terminated with a semicolon (`;`). This tells the compiler where one statement ends and another begins.

---

# Question: What does `return 0;` indicate in the `main()` function of a C program?

**Answer:**
The `return 0;` statement indicates that the program has exited successfully. Since `main()` is declared to return an integer (`int`), returning 0 fulfills that requirement and signals successful execution.

---

# Question: What happens after the `return 0;` statement is executed in a C program?

**Answer:**
After the `return 0;` statement is executed, the execution of the program terminates.

---

# Question: What types of text editors can be used to write a C program?

**Answer:**
Simple text editors like `vim` or `gedit` on Linux, and `Notepad` on Windows can be used. Cross-platform editors like Visual Studio Code or Sublime Text are also suitable, as long as they save files in plain text format.

---

# Question: Why must C source files be saved in plain text format?

**Answer:**
C source files must be saved in plain text format because compilers cannot read rich text or other formatted files like RTF. They only work with plain text source code.

---

# Question: What must be done before running a C program?

**Answer:**
Before running a C program, the source file (e.g., `hello.c`) must be compiled into an executable file (e.g., `hello` on Unix/Linux or `hello.exe` on Windows) using a C compiler.

---

# Question: How do you compile a C program using the GCC compiler?

**Answer:**
To compile a C program using GCC, open a terminal, navigate to the source file’s location, and run:

```bash
gcc hello.c -o hello
```

This creates an executable named `hello` if there are no errors in the source code.

---

# Question: What does the `-o` option do in the `gcc` command?

**Answer:**
The `-o` option in the `gcc` command specifies the name of the output executable file. For example, `-o hello` creates an executable named `hello`.

---

# Question: What is the purpose of `-Wall -Wextra -Werror` in the GCC command?

**Answer:**
These are warning options:

* `-Wall`: enables common warning messages
* `-Wextra`: enables additional warnings
* `-Werror`: treats warnings as errors
  They help identify problems that could cause failures or unexpected results.

---

# Question: What is the full GCC command including warning options for compiling `hello.c`?

**Answer:**
The full command is:

```bash
gcc -Wall -Wextra -Werror -o hello hello.c
```

---

# Question: How do you compile a C program using the `clang` compiler?

**Answer:**
Use the command:

```bash
clang -Wall -Wextra -Werror -o hello hello.c
```

Clang’s command-line options are designed to be similar to GCC’s.

---

# Question: How do you compile a C program using the Microsoft `cl.exe` compiler?

**Answer:**
On a Windows system with Visual Studio and proper environment setup, run:

```cmd
cl hello.c
```

This compiles the program and creates an executable file `hello.exe` in the current directory.

---

# Question: What are some warning options for `cl.exe` similar to GCC's `-Wall`?

**Answer:**
One example is `/W3`, which enables a set of warnings similar to what `-Wall` does in GCC.

---
