# Question: List the common data types in C# with their size and example.

### Data Types in C#

| Type   | Size     | Example                |
| ------ | -------- | ---------------------- |
| int    | 4 bytes  | int x = 100;           |
| double | 8 bytes  | double pi = 3.14;      |
| char   | 2 bytes  | char letter = 'A';     |
| string | Varies   | string name = "C#";    |
| bool   | 1 byte   | bool isAlive = true;   |

---

# Question: List the reserved keywords and contextual keywords in C#.

### Reserved Keywords

| Keyword    | Keyword    | Keyword     | Keyword      | Keyword     | Keyword    |
| ---------- | ---------- | ----------- | ------------ | ----------- | ---------- |
| abstract   | as         | base        | bool         | break       | byte       |
| case       | catch      | char        | checked      | class       | const      |
| continue   | decimal    | default     | delegate     | do          | double     |
| else       | enum       | event       | explicit     | extern      | false      |
| finally    | fixed      | float       | for          | foreach     | goto       |
| if         | implicit   | in          | in (generic modifier) | int   | interface |
| internal   | is         | lock        | long         | namespace   | new        |
| null       | object     | operator    | out          | out (generic modifier) | override |
| params     | private    | protected   | public       | readonly    | ref        |
| return     | sbyte      | sealed      | short        | sizeof      | stackalloc |
| static     | string     | struct      | switch       | this        | throw      |
| true       | try        | typeof      | uint         | ulong       | unchecked  |
| unsafe     | ushort     | using       | virtual      | void        | volatile   |
| while      |            |             |              |             |            |

---

### Contextual Keywords

| Keyword   | Keyword    | Keyword     | Keyword       | Keyword          | Keyword              |
| --------- | ---------- | ----------- | ------------- | ---------------- | -------------------- |
| add       | alias      | ascending   | descending    | dynamic          | from                 |
| get       | global     | group       | into          | join             | let                  |
| orderby   | partial (type) | partial (method) | remove | select | set |

---

# Question: List some commonly used C# data types grouped by their category.

### Integral Data Types
| Data Type | Size    | Range                                                      |
| --------- | ------- | ---------------------------------------------------------- |
| byte      | 1 byte  | 0 to 255                                                   |
| sbyte     | 1 byte  | -128 to 127                                                |
| short     | 2 bytes | -32,768 to 32,767                                          |
| ushort    | 2 bytes | 0 to 65,535                                                |
| int       | 4 bytes | -2,147,483,648 to 2,147,483,647                            |
| uint      | 4 bytes | 0 to 4,294,967,295                                         |
| long      | 8 bytes | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807    |
| ulong     | 8 bytes | 0 to 18,446,744,073,709,551,615                            |

### Floating-Point Data Types
| Data Type | Size    | Precision              |
| --------- | ------- | ---------------------- |
| float     | 4 bytes | 6-7 decimal places     |
| double    | 8 bytes | 15-16 decimal places   |
| decimal   | 16 bytes| 28-29 decimal places   |

### Character and Boolean Data Types
| Data Type | Size    | Description            |
| --------- | ------- | ---------------------- |
| char      | 2 bytes | Stores a single character |
| bool      | 1 byte  | Stores true or false   |

---

# Question: List some commonly used C# type conversion methods.

### Type Conversion Methods
| Sr.No. | Method     | Description                                                 |
| ------ | ---------- | ----------------------------------------------------------- |
| 1      | ToBoolean  | Converts a type to a Boolean value, where possible.          |
| 2      | ToByte     | Converts a type to a byte.                                  |
| 3      | ToChar     | Converts a type to a single Unicode character, where possible. |
| 4      | ToDateTime | Converts a type (integer or string type) to date-time structures. |
| 5      | ToDecimal  | Converts a floating point or integer type to a decimal type. |
| 6      | ToDouble   | Converts a type to a double type.                           |
| 7      | ToInt16    | Converts a type to a 16-bit integer.                        |
| 8      | ToInt32    | Converts a type to a 32-bit integer.                        |
| 9      | ToInt64    | Converts a type to a 64-bit integer.                        |
| 10     | ToSByte    | Converts a type to a signed byte type.                      |
| 11     | ToSingle   | Converts a type to a small floating point number.           |
| 12     | ToString   | Converts a type to a string.                                |
| 13     | ToType     | Converts a type to a specified type.                        |
| 14     | ToUInt16   | Converts a type to an unsigned int type.                    |
| 15     | ToUInt32   | Converts a type to an unsigned long type.                   |
| 16     | ToUInt64   | Converts a type to an unsigned big integer.                 |

---

# Question: List some commonly used C# escape sequences and their meaning.

### Escape Sequences
| Escape Sequence | Meaning                |
| --------------- | ---------------------- |
| \\              | \ character            |
| \'              | ' character            |
| \"              | " character            |
| \?              | ? character            |
| \a              | Alert or bell          |
| \b              | Backspace              |
| \f              | Form feed              |
| \n              | Newline                |
| \r              | Carriage return        |
| \t              | Horizontal tab         |
| \v              | Vertical tab           |
| \xhh...         | Hexadecimal number of one or more digits |

---

# Question: List some commonly used C# operators grouped by their category.

### Arithmetic Operators
| Operator | Description                                      | Example         |
| -------- | ------------------------------------------------ | --------------- |
| +        | Adds two operands                                | A + B = 30      |
| -        | Subtracts second operand from the first          | A - B = -10     |
| *        | Multiplies both operands                         | A * B = 200     |
| /        | Divides numerator by denominator                 | B / A = 2       |
| %        | Modulus Operator, remainder after division       | B % A = 0       |
| ++       | Increment operator, increases value by one       | A++ = 11        |
| --       | Decrement operator, decreases value by one       | A-- = 9         |

### Relational Operators
| Operator | Description                                                                 | Example              |
| -------- | --------------------------------------------------------------------------- | -------------------- |
| ==       | Checks if two operands are equal                                            | (A == B) is not true |
| !=       | Checks if two operands are not equal                                        | (A != B) is true     |
| >        | Checks if left operand is greater than right                                | (A > B) is not true  |
| <        | Checks if left operand is less than right                                   | (A < B) is true      |
| >=       | Checks if left operand is greater than or equal to right                    | (A >= B) is not true |
| <=       | Checks if left operand is less than or equal to right                       | (A <= B) is true     |

### Logical Operators
| Operator | Description                                                                 | Example              |
| -------- | --------------------------------------------------------------------------- | -------------------- |
| &&       | Logical AND, true if both operands are true                                 | (A && B) is false    |
| \|\|     | Logical OR, true if at least one operand is true                            | (A \|\| B) is true   |
| !        | Logical NOT, reverses the logical state of operand                          | !(A && B) is true    |

### Bitwise Operators
**Bitwise operator works on bits and performs bit by bit operation.**  

Truth Table:  

| p | q | p & q | p \| q | p ^ q |
|---|---|-------|-------|-------|
| 0 | 0 | 0     | 0     | 0     |
| 0 | 1 | 0     | 1     | 1     |
| 1 | 1 | 1     | 1     | 0     |
| 1 | 0 | 0     | 1     | 1     |

| Operator | Description                                                                 | Example                                     |
| -------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| &        | Binary AND, copies bit if it exists in both operands                        | (A & B) = 12 → 0000 1100                    |
| \|       | Binary OR, copies bit if it exists in either operand                        | (A \| B) = 61 → 0011 1101                   |
| ^        | Binary XOR, copies bit if it exists in one operand but not both             | (A ^ B) = 49 → 0011 0001                    |
| ~        | Binary Ones Complement, flips bits                                          | (~A) = -61 → 1100 0011 (2's complement)     |
| <<       | Binary Left Shift, moves bits left                                          | A << 2 = 240 → 1111 0000                    |
| >>       | Binary Right Shift, moves bits right                                        | A >> 2 = 15 → 0000 1111                     |

### Assignment Operators
| Operator | Description                                                                 | Example                   |
| -------- | --------------------------------------------------------------------------- | ------------------------- |
| =        | Simple assignment                                                           | C = A + B                 |
| +=       | Add AND assignment                                                          | C += A → C = C + A        |
| -=       | Subtract AND assignment                                                     | C -= A → C = C - A        |
| *=       | Multiply AND assignment                                                     | C *= A → C = C * A        |
| /=       | Divide AND assignment                                                       | C /= A → C = C / A        |
| %=       | Modulus AND assignment                                                      | C %= A → C = C % A        |
| <<=      | Left shift AND assignment                                                   | C <<= 2 → C = C << 2      |
| >>=      | Right shift AND assignment                                                  | C >>= 2 → C = C >> 2      |
| &=       | Bitwise AND assignment                                                      | C &= 2 → C = C & 2        |
| ^=       | Bitwise XOR assignment                                                      | C ^= 2 → C = C ^ 2        |
| \|=      | Bitwise OR assignment                                                       | C \|= 2 → C = C \| 2      |

### Miscellaneous Operators
| Operator | Description                                                                 | Example                               |
| -------- | --------------------------------------------------------------------------- | ------------------------------------- |
| sizeof() | Returns the size of a data type                                             | sizeof(int) → 4                       |
| typeof() | Returns the type of a class                                                 | typeof(StreamReader)                   |
| &        | Returns the address of a variable                                           | &a (address of variable a)            |
| *        | Pointer to a variable                                                       | *a (pointer named 'a')                |
| ?:       | Conditional Expression (ternary operator)                                   | condition ? value1 : value2           |
| is       | Checks if an object is of a certain type                                    | if(Ford is Car)                        |
| as       | Safe cast, returns null if cast fails                                       | StringReader r = obj as StringReader  |

### Operator Precedence and Associativity
| Category        | Operators                       | Associativity  |
| --------------- | ------------------------------- | -------------- |
| Postfix         | () [] -> . ++ --                | Left to right  |
| Unary           | + - ! ~ ++ -- (type)* & sizeof  | Right to left  |
| Multiplicative  | * / %                           | Left to right  |
| Additive        | + -                             | Left to right  |
| Shift           | << >>                           | Left to right  |
| Relational      | < <= > >=                       | Left to right  |
| Equality        | == !=                           | Left to right  |
| Bitwise AND     | &                               | Left to right  |
| Bitwise XOR     | ^                               | Left to right  |
| Bitwise OR      | \|                              | Left to right  |
| Logical AND     | &&                              | Left to right  |
| Logical OR      | \|\|                            | Left to right  |
| Conditional     | ?:                              | Right to left  |
| Assignment      | = += -= *= /= %= >>= <<= &= ^= \|= | Right to left |
| Comma           | ,                               | Left to right  |

Perfect 🎯 — that’s the **Operator Precedence & Associativity** section. I’ll add it to our structured markdown reference at the end so the file is now 100% complete.

`csharp-operators-by-category.md`

```markdown
# Question: List some commonly used C# operators grouped by their category.

---

### Arithmetic Operators

Assume variable **A = 10** and **B = 20**

| Operator             | Symbol | Description                                           | Example        |
| -------------------- | ------ | ----------------------------------------------------- | -------------- |
| Addition             | +      | Adds two operands                                     | A + B = 30     |
| Subtraction          | -      | Subtracts second operand from the first               | A - B = -10    |
| Multiplication       | *      | Multiplies both operands                              | A * B = 200    |
| Division             | /      | Divides numerator by denominator                      | B / A = 2      |
| Modulus              | %      | Modulus operator and remainder after integer division | B % A = 0      |
| Increment Operator   | ++     | Increases integer value by one                        | A++ = 11       |
| Decrement Operator   | --     | Decreases integer value by one                        | A-- = 9        |

---

### Assignment Operators

| Operator                | Symbol | Description                                                                 | Example                              |
| ----------------------- | ------ | --------------------------------------------------------------------------- | ------------------------------------ |
| Simple Assignment       | =      | Assigns values from right side operands to left side operand                 | C = A + B → assigns value of A + B   |
| Add and Assign          | +=     | Adds right operand to the left operand and assigns the result                | C += A → equivalent to C = C + A     |
| Subtract and Assign     | -=     | Subtracts right operand from the left operand and assigns the result         | C -= A → equivalent to C = C - A     |
| Multiply and Assign     | *=     | Multiplies right operand with the left operand and assigns the result        | C *= A → equivalent to C = C * A     |
| Divide and Assign       | /=     | Divides left operand by the right operand and assigns the result             | C /= A → equivalent to C = C / A     |
| Modulus and Assign      | %=     | Takes modulus using two operands and assigns the result                      | C %= A → equivalent to C = C % A     |
| Left Shift and Assign   | <<=    | Left shift AND assignment operator                                           | C <<= 2 → same as C = C << 2         |
| Right Shift and Assign  | >>=    | Right shift AND assignment operator                                          | C >>= 2 → same as C = C >> 2         |
| Bitwise AND and Assign  | &=     | Bitwise AND assignment operator                                              | C &= 2 → same as C = C & 2           |
| Bitwise XOR and Assign  | ^=     | Bitwise exclusive OR assignment operator                                     | C ^= 2 → same as C = C ^ 2           |
| Bitwise OR and Assign   | \|=    | Bitwise inclusive OR assignment operator                                     | C \|= 2 → same as C = C \| 2         |

---

### Relational Operators

Assume variable **A = 10** and **B = 20**

| Operator                  | Symbol | Description                                                                                           | Example                  |
| ------------------------- | ------ | ----------------------------------------------------------------------------------------------------- | ------------------------ |
| Equal to                  | ==     | Checks if values of two operands are equal. If yes, condition becomes true.                           | (A == B) → false         |
| Not equal to              | !=     | Checks if values of two operands are not equal. If yes, condition becomes true.                       | (A != B) → true          |
| Greater than              | >      | Checks if left operand is greater than right operand. If yes, condition becomes true.                  | (A > B) → false          |
| Less than                 | <      | Checks if left operand is less than right operand. If yes, condition becomes true.                     | (A < B) → true           |
| Greater than or equal to  | >=     | Checks if left operand is greater than or equal to right operand. If yes, condition becomes true.      | (A >= B) → false         |
| Less than or equal to     | <=     | Checks if left operand is less than or equal to right operand. If yes, condition becomes true.         | (A <= B) → true          |

---

### Logical Operators

Assume variable **A = true** and **B = false**

| Operator     | Symbol | Description                                                                                     | Example            |
| ------------ | ------ | ----------------------------------------------------------------------------------------------- | ------------------ |
| Logical AND  | &&     | Returns true if both operands are true                                                          | (A && B) → false   |
| Logical OR   | \|\|   | Returns true if at least one of the operands is true                                            | (A \|\| B) → true  |
| Logical NOT  | !      | Reverses the logical state of its operand. If condition is true, it becomes false, and vice-versa | !(A && B) → true   |

---

### Bitwise Operators

Assume variable **A = 60** (0011 1100 in binary) and **B = 13** (0000 1101 in binary)

| Operator         | Symbol | Description                                                                                           | Example                                             |
| ---------------- | ------ | ----------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Binary AND       | &      | Copies a bit to the result if it exists in both operands                                              | (A & B) = 12 → 0000 1100                            |
| Binary OR        | \|     | Copies a bit if it exists in either operand                                                           | (A \| B) = 61 → 0011 1101                           |
| Binary XOR       | ^      | Copies the bit if it is set in one operand but not both                                               | (A ^ B) = 49 → 0011 0001                            |
| Ones Complement  | ~      | Unary operator that flips bits                                                                        | (~A) = -61 → 1100 0011 (2’s complement form)        |
| Left Shift       | <<     | Moves bits of left operand left by the number of positions specified by right operand                 | A << 2 = 240 → 1111 0000                            |
| Right Shift      | >>     | Moves bits of left operand right by the number of positions specified by right operand                | A >> 2 = 15 → 0000 1111                             |

---

### Miscellaneous and Conditional Operators

| Operator      | Symbol / Syntax | Description                                                                                   | Example                                                                 |
| ------------- | --------------- | --------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| sizeof        | sizeof()        | Returns the size of a data type                                                               | sizeof(int) → 4                                                         |
| typeof        | typeof()        | Returns the type of a class                                                                   | typeof(StreamReader)                                                     |
| Address-of    | &               | Returns the address of a variable                                                             | &a → actual memory address of variable a                                |
| Pointer       | *               | Pointer to a variable                                                                         | *a → creates pointer named 'a' to a variable                            |
| Conditional   | ? :             | Conditional expression operator (ternary). If condition is true, returns X; otherwise, Y       | condition ? valueX : valueY                                              |
| is            | is              | Determines whether an object is of a certain type                                             | if (Ford is Car) → checks if Ford is an object of class Car              |
| as            | as              | Safe type casting. Returns null instead of raising exception if cast fails                    | `object obj = new StringReader("Hello"); StringReader r = obj as StringReader;` |

---

### Operator Precedence and Associativity

#### By Category

| Category        | Operators                                  | Associativity   |
| --------------- | ------------------------------------------ | --------------- |
| Postfix         | () [] -> . ++ --                           | Left to Right   |
| Unary           | + - ! ~ ++ -- (type)* & sizeof             | Right to Left   |
| Multiplicative  | * / %                                      | Left to Right   |
| Additive        | + -                                        | Left to Right   |
| Shift           | << >>                                      | Left to Right   |
| Relational      | < <= > >=                                  | Left to Right   |
| Equality        | == !=                                      | Left to Right   |
| Bitwise AND     | &                                          | Left to Right   |
| Bitwise XOR     | ^                                          | Left to Right   |
| Bitwise OR      | \|                                         | Left to Right   |
| Logical AND     | &&                                         | Left to Right   |
| Logical OR      | \|\|                                       | Left to Right   |
| Conditional     | ?:                                         | Right to Left   |
| Assignment      | = += -= *= /= %= >>= <<= &= ^= \|=          | Right to Left   |
| Comma           | ,                                          | Left to Right   |

#### By Precedence Level

| Precedence Level | Operators             | Associativity   |
| ---------------- | --------------------- | --------------- |
| Highest (1)      | () [] .               | Left to Right   |
| 2                | ++ -- (postfix)       | Left to Right   |
| 3                | ++ -- + - (prefix) ! ~ | Right to Left  |
| 4                | * / %                 | Left to Right   |
| 5                | + -                   | Left to Right   |
| 6                | << >>                 | Left to Right   |
| 7                | < <= > >=             | Left to Right   |
| 8                | == !=                 | Left to Right   |
| 9                | &                     | Left to Right   |
| 10               | ^                     | Left to Right   |
| 11               | \|                    | Left to Right   |
| 12               | &&                    | Left to Right   |
| 13               | \|\|                  | Left to Right   |
| 14               | ?: (ternary)          | Right to Left   |
| 15               | = += -= *= /= %= &= ^= <<= >>= | Right to Left |
| Lowest (16)      | , (comma)             | Left to Right   |


---

# Question: List the types of decision-making statements in C#.

### Decision-making Statements

| Sr.No. | Statement              | Description                                                                 |
| ------ | ---------------------- | --------------------------------------------------------------------------- |
| 1      | if statement           | An if statement consists of a boolean expression followed by one or more statements. |
| 2      | if...else statement    | An if statement can be followed by an optional else statement, which executes when the boolean expression is false. |
| 3      | nested if statements   | You can use one if or else if statement inside another if or else if statement(s). |
| 4      | switch statement       | A switch statement allows a variable to be tested for equality against a list of values. |
| 5      | nested switch statements | You can use one switch statement inside another switch statement(s). |

---

Here’s the next one formatted properly into **`csharp-loops.md`**:

```markdown
# Question: List the types of loops in C#.

### Loop Statements

| Sr.No. | Loop Type        | Description                                                                 |
| ------ | ---------------- | --------------------------------------------------------------------------- |
| 1      | while loop       | It repeats a statement or a group of statements while a given condition is true. It tests the condition before executing the loop body. |
| 2      | for loop         | It executes a sequence of statements multiple times and abbreviates the code that manages the loop variable. |
| 3      | do...while loop  | It is similar to a while statement, except that it tests the condition at the end of the loop body. |
| 4      | nested loops     | You can use one or more loops inside any other while, for, or do...while loop. |
