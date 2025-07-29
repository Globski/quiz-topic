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

