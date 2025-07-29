# Question: What are the keywords in C and what do they do?

## C Keywords by Category

---

### 🔁 Control Flow

| Keyword    | Description                                               |
| ---------- | --------------------------------------------------------- |
| `if`       | Makes a conditional statement                             |
| `else`     | Used with `if` for alternative execution                  |
| `switch`   | Selects one of many code blocks to be executed            |
| `case`     | Marks a block of code in switch statements                |
| `default`  | Specifies the default block of code in a switch statement |
| `for`      | Creates a `for` loop                                      |
| `while`    | Creates a `while` loop                                    |
| `do`       | Used together with `while` to create a `do-while` loop    |
| `break`    | Breaks out of a loop or a switch block                    |
| `continue` | Skips to the next iteration of a loop                     |
| `goto`     | Jumps to a line of code marked by a label                 |
| `return`   | Exits from a function and optionally returns a value      |

---

### 🧮 Data Types

| Keyword    | Description                                                    |
| ---------- | -------------------------------------------------------------- |
| `int`      | Integer type (usually 32-bit)                                  |
| `char`     | Character type (typically 1 byte)                              |
| `float`    | Floating point type (typically 32-bit)                         |
| `double`   | Double precision float (typically 64-bit)                      |
| `short`    | Short integer (usually 16-bit)                                 |
| `long`     | Long integer (usually at least 32-bit; `long long` for 64-bit) |
| `unsigned` | Integer or char with only positive values                      |
| `signed`   | Integer or char with both positive and negative values         |
| `void`     | No value / no return type / unspecified pointer type           |

---

### 🏗️ Type Modifiers & Utilities

| Keyword   | Description                                             |
| --------- | ------------------------------------------------------- |
| `const`   | Declares a constant (read-only) value                   |
| `sizeof`  | Returns memory size of a variable or type (in bytes)    |
| `typedef` | Defines a custom type alias                             |
| `enum`    | Declares an enumerated set of named constants           |
| `struct`  | Declares a structure                                    |
| `static`  | Maintains local variable’s value between function calls |

---

### 📦 Storage Class Specifiers

| Keyword      | Description                                                      |
| ------------ | ---------------------------------------------------------------- |
| `static`     | Variable retains value between function calls (internal linkage) |
| `extern`\*   | Declares a variable defined elsewhere (not shown above)          |
| `register`\* | Suggests storing variable in CPU register (optional hint)        |
| `auto`\*     | Default storage class for local variables (rarely used today)    |

> \*Not always included in beginner lists, but are official C keywords.

---

### ✅ Miscellaneous

| Keyword | Description                                                  |
| ------- | ------------------------------------------------------------ |
| `void`  | Used for functions that return no value, or generic pointers |

---

# Question: What are the functions in `<stdio.h>` and what do they do?

## C Standard I/O Library (`<stdio.h>`) Functions by Category

---

### 📥 Standard Input Functions

| Function    | Description                              |
| ----------- | ---------------------------------------- |
| `getchar()` | Reads a single character from user input |
| `scanf()`   | Reads formatted input from the console   |
| `fscanf()`  | Reads formatted input from a file        |
| `sscanf()`  | Reads formatted input from a string      |

---

### 📤 Standard Output Functions

| Function     | Description                                                      |
| ------------ | ---------------------------------------------------------------- |
| `putchar()`  | Writes a single character to the console                         |
| `puts()`     | Writes a string followed by newline to the console               |
| `printf()`   | Writes formatted output to the console                           |
| `fprintf()`  | Writes formatted output to a file                                |
| `sprintf()`  | Writes formatted output to a string                              |
| `snprintf()` | Same as `sprintf()` but with buffer size limit for memory safety |

---

### 📂 File Handling Functions

| Function   | Description                             |
| ---------- | --------------------------------------- |
| `fopen()`  | Opens a file and returns a file pointer |
| `fclose()` | Closes a file                           |
| `remove()` | Deletes a file                          |
| `rename()` | Renames a file                          |

---

### 📄 File Reading Functions

| Function  | Description                          |
| --------- | ------------------------------------ |
| `fgetc()` | Reads a single character from a file |
| `fgets()` | Reads a line (string) from a file    |
| `fread()` | Reads a block of memory from a file  |
| `getc()`  | Equivalent to `fgetc()`              |

---

### 📝 File Writing Functions

| Function   | Description                         |
| ---------- | ----------------------------------- |
| `fputc()`  | Writes a single character to a file |
| `fputs()`  | Writes a string to a file           |
| `fwrite()` | Writes a block of memory to a file  |
| `putc()`   | Equivalent to `fputc()`             |

---

### 📍 File Positioning and Info

| Function   | Description                                          |
| ---------- | ---------------------------------------------------- |
| `fseek()`  | Moves the file pointer to a specified location       |
| `ftell()`  | Returns the current location of the file pointer     |
| `rewind()` | Resets the file pointer to the beginning of the file |

---

### ⚠️ File Error and Status

| Function   | Description                                                |
| ---------- | ---------------------------------------------------------- |
| `feof()`   | Checks if the file pointer has reached the end of the file |
| `ferror()` | Checks if an error occurred in a file operation            |

---

# Question: What are the functions in `<stdlib.h>` and what do they do?

## C Standard Library (`<stdlib.h>`) Functions by Category

---

### 🔢 Number Conversion Functions

| Function  | Description                                         |
| --------- | --------------------------------------------------- |
| `atof()`  | Converts a string to a `double`                     |
| `atoi()`  | Converts a string to an `int`                       |
| `atol()`  | Converts a string to a `long int`                   |
| `atoll()` | Converts a string to a `long long int`              |
| `abs()`   | Returns the absolute (positive) value of an integer |

---

### 🧠 Dynamic Memory Management

| Function    | Description                                        |
| ----------- | -------------------------------------------------- |
| `malloc()`  | Allocates memory without initializing it           |
| `calloc()`  | Allocates memory and initializes all bytes to zero |
| `realloc()` | Resizes previously allocated memory                |
| `free()`    | Frees previously allocated memory                  |

---

### 🎲 Random Number Generation

| Function  | Description                       |
| --------- | --------------------------------- |
| `rand()`  | Generates a pseudo-random integer |
| `srand()` | Seeds the random number generator |

---

### 📊 Sorting and Division

| Function  | Description                                                       |
| --------- | ----------------------------------------------------------------- |
| `qsort()` | Sorts an array using the quicksort algorithm                      |
| `div()`   | Performs integer division and returns both quotient and remainder |

---

### ❌ Program Control

| Function | Description                                         |
| -------- | --------------------------------------------------- |
| `exit()` | Terminates the program with a specified exit status |

---
