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

