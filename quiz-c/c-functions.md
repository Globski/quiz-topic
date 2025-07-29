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

# Question: What are the functions in `<string.h>` and what do they do?

## C String Library (`<string.h>`) Functions by Category

---

### 🧠 Memory Manipulation Functions

| Function    | Description                                               |
| ----------- | --------------------------------------------------------- |
| `memchr()`  | Finds the first occurrence of a byte in a block of memory |
| `memcmp()`  | Compares two blocks of memory                             |
| `memcpy()`  | Copies data from one memory location to another           |
| `memmove()` | Like `memcpy()` but safe for overlapping memory areas     |
| `memset()`  | Fills memory with a constant byte                         |

---

### 🔤 String Copying and Concatenation

| Function    | Description                                                          |
| ----------- | -------------------------------------------------------------------- |
| `strcpy()`  | Copies one string into another                                       |
| `strncpy()` | Copies a specified number of characters from one string into another |
| `strcat()`  | Appends one string to another                                        |
| `strncat()` | Appends a specified number of characters from one string to another  |

---

### 🧪 String Comparison

| Function    | Description                                  |
| ----------- | -------------------------------------------- |
| `strcmp()`  | Compares two strings by ASCII value          |
| `strncmp()` | Compares up to `n` characters of two strings |
| `strcoll()` | Compares strings using the current locale    |

---

### 🔍 String Searching

| Function    | Description                                                      |
| ----------- | ---------------------------------------------------------------- |
| `strchr()`  | Finds the first occurrence of a character in a string            |
| `strrchr()` | Finds the last occurrence of a character in a string             |
| `strstr()`  | Finds the first occurrence of a substring                        |
| `strpbrk()` | Finds the first matching character from a set                    |
| `strcspn()` | Returns length before any character from a set is found          |
| `strspn()`  | Returns length of prefix consisting only of specified characters |

---

### 🧩 String Tokenization and Transformation

| Function    | Description                                     |
| ----------- | ----------------------------------------------- |
| `strtok()`  | Tokenizes (splits) a string using delimiters    |
| `strxfrm()` | Transforms a string for locale-based comparison |

---

### 🧮 String Length and Errors

| Function     | Description                              |
| ------------ | ---------------------------------------- |
| `strlen()`   | Returns the length of a string           |
| `strerror()` | Returns the description of an error code |

---

# `math.h` Functions in C

## 🔺 Trigonometric Functions

| Function     | Description                                              |
| ------------ | -------------------------------------------------------- |
| `sin(x)`     | Returns the sine of angle `x` (in radians)               |
| `cos(x)`     | Returns the cosine of angle `x` (in radians)             |
| `tan(x)`     | Returns the tangent of angle `x` (in radians)            |
| `asin(x)`    | Returns the arcsine of `x`, in radians                   |
| `acos(x)`    | Returns the arccosine of `x`, in radians                 |
| `atan(x)`    | Returns arctangent of `x` (range: `-π/2` to `π/2`)       |
| `atan2(y,x)` | Returns `atan(y/x)` considering quadrant (polar angle θ) |

---

## 🌐 Hyperbolic Functions

| Function   | Description                        |
| ---------- | ---------------------------------- |
| `sinh(x)`  | Returns hyperbolic sine of `x`     |
| `cosh(x)`  | Returns hyperbolic cosine of `x`   |
| `tanh(x)`  | Returns hyperbolic tangent of `x`  |
| `asinh(x)` | Returns inverse hyperbolic sine    |
| `acosh(x)` | Returns inverse hyperbolic cosine  |
| `atanh(x)` | Returns inverse hyperbolic tangent |

---

## 🧮 Exponential & Logarithmic Functions

| Function   | Description                                     |
| ---------- | ----------------------------------------------- |
| `exp(x)`   | Returns `e^x`                                   |
| `exp2(x)`  | Returns `2^x`                                   |
| `expm1(x)` | Returns `e^x - 1` (more precise for small `x`)  |
| `log(x)`   | Returns natural logarithm (base `e`) of `x`     |
| `log10(x)` | Returns base-10 logarithm of `x`                |
| `log1p(x)` | Returns `log(1+x)` (more precise for small `x`) |
| `log2(x)`  | Returns base-2 logarithm of `x`                 |
| `logb(x)`  | Returns exponent in representation of `x`       |
| `ilogb(x)` | Integer version of `logb()`                     |

---

## ✳️ Power, Roots, and Rounding

| Function       | Description                                       |
| -------------- | ------------------------------------------------- |
| `pow(x, y)`    | Returns `x` raised to the power `y`               |
| `sqrt(x)`      | Returns square root of `x`                        |
| `cbrt(x)`      | Returns cube root of `x`                          |
| `ceil(x)`      | Rounds `x` up to nearest integer                  |
| `floor(x)`     | Rounds `x` down to nearest integer                |
| `trunc(x)`     | Truncates decimal, keeps integer part             |
| `round(x)`     | Rounds to nearest integer                         |
| `rint(x)`      | Rounds `x` to integer using current rounding mode |
| `nearbyint(x)` | Same as `rint()` but no exceptions raised         |
| `lrint(x)`     | Rounds to nearest integer, returns `long`         |
| `llrint(x)`    | Rounds to nearest integer, returns `long long`    |
| `lround(x)`    | Rounds away from zero, returns `long`             |
| `llround(x)`   | Rounds away from zero, returns `long long`        |

---

## 🧮 Arithmetic Helpers & Comparisons

| Function         | Description                                   |
| ---------------- | --------------------------------------------- |
| `fabs(x)`        | Returns absolute value of `x`                 |
| `fdim(x, y)`     | Positive difference `x - y` or `0` if `x < y` |
| `fmax(x, y)`     | Returns greater of `x` or `y`                 |
| `fmin(x, y)`     | Returns lesser of `x` or `y`                  |
| `fma(x, y, z)`   | Returns `(x * y) + z` with single rounding    |
| `copysign(x, y)` | Returns `x` with sign of `y`                  |

---

## 🔧 Remainders & Modulus

| Function          | Description                                               |
| ----------------- | --------------------------------------------------------- |
| `fmod(x, y)`      | Floating-point remainder of `x / y`                       |
| `remainder(x, y)` | Remainder, rounded to nearest integer multiple            |
| `remquo(x, y, z)` | Returns remainder of `x/y`, stores quotient at `*z`       |
| `modf(x, y)`      | Splits `x` into integer part (stored at `*y`) and decimal |

---

## 🧠 Bitwise/Precision Scaling & Decomposition

| Function           | Description                                                    |
| ------------------ | -------------------------------------------------------------- |
| `frexp(x, y)`      | Decomposes `x` into `m * 2^n`; returns `m`, stores `n` in `*y` |
| `ldexp(x, y)`      | Computes `x * 2^y`                                             |
| `scalbn(x, y)`     | Efficient version of `x * 2^y`                                 |
| `scalbln(x, y)`    | Like `scalbn()` but `y` is `long int`                          |
| `nextafter(x, y)`  | Smallest number > `x` in direction of `y`                      |
| `nexttoward(x, y)` | Same as above but `y` is `long double`                         |

---

## 🧩 Special Values & Error Functions

| Function    | Description                                          |
| ----------- | ---------------------------------------------------- |
| `nan(s)`    | Returns a NaN (Not a Number)                         |
| `erf(x)`    | Error function at `x`                                |
| `erfc(x)`   | Complementary error function at `x`                  |
| `tgamma(x)` | Gamma function of `x`                                |
| `lgamma(x)` | Logarithm of absolute value of gamma function at `x` |

---

# Question: List the functions provided by the C `ctype.h` library and their descriptions.

## C `ctype.h` Functions

The `<ctype.h>` header provides functions for character classification and transformation.

| Function     | Description                                               |
| ------------ | --------------------------------------------------------- |
| `isalnum()`  | Checks whether a character is alphanumeric                |
| `isalpha()`  | Checks whether a character is a letter                    |
| `isblank()`  | Checks whether a character is a space or tab              |
| `iscntrl()`  | Checks whether a character is a control character         |
| `isdigit()`  | Checks whether a character is a decimal digit             |
| `isgraph()`  | Checks whether a character has a graphical representation |
| `islower()`  | Checks whether a character is a lowercase letter          |
| `isprint()`  | Checks whether a character is a printable character       |
| `ispunct()`  | Checks whether a character is a punctuation character     |
| `isspace()`  | Checks whether a character is a whitespace character      |
| `isupper()`  | Checks whether a character is an uppercase letter         |
| `isxdigit()` | Checks whether a character is a hexadecimal digit         |
| `tolower()`  | Returns a lowercase version of a character                |
| `toupper()`  | Returns an uppercase version of a character               |

---
