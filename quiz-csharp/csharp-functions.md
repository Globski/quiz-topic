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
