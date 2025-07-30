# Question: What are the only two possible Boolean values in PHP?

**Answer:** true and false

---

# Question: What are the valid ways to write the Boolean value `true` in PHP?

**Answer:** true, TRUE, or True (case-insensitive)

---

# Question: What are the valid ways to write the Boolean value `false` in PHP?

**Answer:** false, FALSE, or False (case-insensitive)

---

# Question: How do you declare a Boolean variable with the value true in PHP?

**Answer:** `$var = true;`

---

# Question: What will the following code output?

```php
$gender = "Male";
var_dump($gender == "Male");
```

**Answer:** `bool(true)`

---

# Question: What is the output of the following code?

```php
$is_sunny = true;
if ($is_sunny) {
    echo "It is a sunny day!";
} else {
    echo "It is not sunny today.";
}
```

**Answer:** It is a sunny day!

---

# Question: Which PHP control structures rely on Boolean values to function?

**Answer:** if, while, for, foreach

---

# Question: What does the following code print?

```php
$mark = 60;
if ($mark > 50)
    echo "pass";
else
    echo "fail";
```

**Answer:** pass

---

# Question: How do you explicitly convert a value to a Boolean in PHP?

**Answer:** By using the `(bool)` casting operator, e.g., `(bool)$value`

---

# Question: What Boolean value does a non-zero number convert to in PHP?

**Answer:** true

---

# Question: What Boolean value does the number 0 convert to in PHP?

**Answer:** false

---

# Question: What Boolean value does a non-empty string convert to in PHP?

**Answer:** true

---

# Question: What Boolean value does an empty string (`""`) convert to in PHP?

**Answer:** false

---

# Question: What Boolean value does an empty array convert to in PHP?

**Answer:** false

---

# Question: What is the output of this code?

```php
$a = 10;
var_dump((bool)$a);
```

**Answer:** `bool(true)`

---

# Question: What is the output of this code?

```php
$a = 0;
var_dump((bool)$a);
```

**Answer:** `bool(false)`

---

# Question: What is the output of this code?

```php
$a = "Hello";
var_dump((bool)$a);
```

**Answer:** `bool(true)`

---

# Question: What is the output of this code?

```php
$a = "";
var_dump((bool)$a);
```

**Answer:** `bool(false)`

---

# Question: What is the output of this code?

```php
$a = array();
var_dump((bool)$a);
```

**Answer:** `bool(false)`

---

# Question: What are the main Boolean (logical) operators in PHP?

**Answer:** `&&` (AND), `||` (OR), `!` (NOT)

---

# Question: What is the output of the following code?

```php
$a = true;
$b = false;
var_dump($a && $b);
```

**Answer:** `bool(false)`

---

# Question: What is the output of the following code?

```php
$a = true;
$b = false;
var_dump($a || $b);
```

**Answer:** `bool(true)`

---

# Question: What is the output of this code?

```php
$a = true;
var_dump(!$a);
```

**Answer:** `bool(false)`

---

# Question: What is strict comparison in PHP, and how is it performed with Booleans?

**Answer:** It uses the `===` operator to compare both value and type, returning a Boolean result.

---

# Question: What is the output of the following code?

```php
$val1 = true;
$val2 = 1;
var_dump($val1 == $val2);
var_dump($val1 === $val2);
```

**Answer:**
`bool(true)`
`bool(false)`

---

# Question: What does the PHP function `is_bool()` do?

**Answer:** Checks if a value is of Boolean type

---

# Question: What does the PHP function `isset()` do?

**Answer:** Checks if a variable is defined and is not null

---

# Question: What is the output of this code?

```php
$is_bool = is_bool(true);
var_dump($is_bool);
```

**Answer:** `bool(true)`

---

# Question: What is the output of this code if `$name` is not defined?

```php
$isset = isset($name);
var_dump($isset);
```

**Answer:** `bool(false)`

---

# Question: How do you loop through an array of Boolean values in PHP?

**Answer:** Using a `foreach` loop, e.g.:

```php
foreach ($boolArray as $value) {
   var_dump($value);
}
```

---

# Question: What is the output of this code?

```php
$boolArray = [true, false, true];
foreach ($boolArray as $value) {
   var_dump($value);
}
```

**Answer:**
`bool(true)`
`bool(false)`
`bool(true)`

---

# Question: What are the Boolean constants in PHP?

**Answer:** `true` and `false`

---

# Question: What is the output of this code?

```php
const STATUS = true;
if (STATUS) {
   echo "Status is active!";
}
```

**Answer:** Status is active!

---

# Question: Name three practical applications of Booleans in PHP.

**Answer:** User authentication, form validation, feature toggles

---

# Question: What is the output of this code?

```php
$user_logged_in = true;
if ($user_logged_in) {
   echo "Welcome, User!";
}
```

**Answer:** Welcome, User!

---

# Question: What scalar type in PHP represents whole numbers without decimal points?

**Answer:** `int` (integer)

---

# Question: How is a decimal integer represented in PHP?

**Answer:** As a regular whole number without any prefix, e.g., `1234`

---

# Question: What prefix is used for hexadecimal integers in PHP?

**Answer:** `0x`

---

# Question: How do you write a binary integer in PHP?

**Answer:** With the prefix `0b`, e.g., `0b1111`

---

# Question: Before PHP 8.1.0, how was octal notation specified?

**Answer:** Using the prefix `0o` or `0O`

---

# Question: Starting from PHP 8.1.0, how is octal notation interpreted?

**Answer:** Any number prefixed with `0` and without a decimal point is interpreted as octal

---

# Question: Write the correct syntax to declare a positive, negative, and zero integer in PHP.

**Answer:**

```php
$num1 = 10;     // positive
$num2 = -5;     // negative
$num3 = 0;      // zero
```

---

# Question: List the rules that apply to PHP integers.

**Answer:**

* Must have at least one digit
* Cannot contain a decimal point
* Can be positive or negative
* Can be in decimal, hexadecimal, octal, or binary formats

---

# Question: What is the integer range for 32-bit systems in PHP?

**Answer:** -2,147,483,648 to 2,147,483,647

---

# Question: What constants are used to check the integer limits in PHP?

**Answer:** `PHP_INT_MAX`, `PHP_INT_MIN`, and `PHP_INT_SIZE`

---

# Question: What is the output of the following code?

```php
echo PHP_INT_MAX . "\n";
echo PHP_INT_MIN;
```

**Answer:**

```
9223372036854775807
-9223372036854775808
```

(Note: Actual output may vary depending on system architecture)

---

# Question: What output does the following code produce?

```php
$a = 1234;
echo "1234 is an Integer in decimal notation: $a\n";
```

**Answer:** `1234 is an Integer in decimal notation: 1234`

---

# Question: What is the decimal value of the following octal integer?

```php
$b = 0123;
```

**Answer:** `83` (Octal 123 = Decimal 83)

---

# Question: What is the decimal value of the following hexadecimal integer?

```php
$c = 0x1A;
```

**Answer:** `26`

---

# Question: What is the decimal value of this binary integer?

```php
$d = 0b1111;
```

**Answer:** `15`

---

# Question: From which PHP version can integer literals include underscores for readability?

**Answer:** PHP 7.4.0

---

# Question: What is the output of this code?

```php
$a = 1_234_567;
echo "1_234_567 is an Integer with _ as separator: $a";
```

**Answer:** `1_234_567 is an Integer with _ as separator: 1234567`

---

# Question: Does PHP support unsigned integers?

**Answer:** No, PHP does not support unsigned ints.

---

# Question: What happens when an integer exceeds the int type boundary?

**Answer:** It is automatically interpreted as a float.

---

# Question: What is the result of the following operation?

```php
$x = 1000000;
$y =  50000000000000 * $x;
var_dump($y);
```

**Answer:** `float(5.0E+19)`

---

# Question: Does PHP have an operator for integer division?

**Answer:** No, PHP does not have a dedicated operator for integer division.

---

# Question: Which PHP function should be used to perform integer division?

**Answer:** `intdiv()`

---

# Question: What is the output of the following code?

```php
$x = 10;
$y = 3.5;
$z = $x / $y;
var_dump($z);
$z = intdiv($x, $y);
var_dump($z);
```

**Answer:**

```
float(2.857142857142857)
int(3)
```

---

# Question: What are the four arithmetic operations supported for integers in PHP?

**Answer:** Addition, subtraction, multiplication, and division

---

# Question: Identify the error in the following PHP arithmetic code:

```php
$a = 10;
$b = 5;
echo "Addition = ".$a + $b;
```

**Answer:** String concatenation `.` has lower precedence than `+`, so it results in unexpected behavior. Parentheses should be used or the operation restructured.

---

# Question: What is the correct output of this fixed arithmetic block?

```php
$a = 10;
$b = 5;
echo "Addition = " . ($a + $b);
```

**Answer:** `Addition = 15`

---

# Question: Which PHP function checks if a variable is an integer?

**Answer:** `is_int()`

---

# Question: What are the aliases of `is_int()`?

**Answer:** `is_integer()` and `is_long()`

---

# Question: What is the purpose of the constant `PHP_INT_SIZE`?

**Answer:** It returns the size of an integer in bytes on the current platform.

---

# Question: What is the default result type of division between an int and a float in PHP?

**Answer:** `float`

---

# Question: What is the purpose of PHP Files and I/O functions?

**Answer:** They are used for reading, writing, creating, and deleting files to enable data storage and management in web applications.

---

# Question: What is the function used to open a file in PHP?

**Answer:** `fopen()`

---

# Question: What are the required arguments for `fopen()`?

**Answer:** The file name and the mode in which to operate.

---

# Question: What does the `r` mode do in `fopen()`?

**Answer:** Opens the file for reading only and places the file pointer at the beginning of the file.

---

# Question: What does the `r+` mode do in `fopen()`?

**Answer:** Opens the file for reading and writing, with the pointer at the beginning.

---

# Question: What happens when you open a file in `w` mode?

**Answer:** It opens the file for writing, places the pointer at the beginning, and truncates the file to zero length. If the file doesn't exist, it attempts to create it.

---

# Question: How is `w+` mode different from `w`?

**Answer:** `w+` opens the file for both reading and writing, while also truncating it and creating it if it does not exist.

---

# Question: What does `a` mode do in `fopen()`?

**Answer:** Opens the file for writing only, placing the pointer at the end of the file and creating it if it doesn’t exist.

---

# Question: How does `a+` differ from `a`?

**Answer:** `a+` allows both reading and writing, with the pointer at the end, and creates the file if it does not exist.

---

# Question: What is returned by `fopen()` if the file cannot be opened?

**Answer:** `false`

---

# Question: What does `fopen()` return if the file is successfully opened?

**Answer:** A file pointer resource.

---

# Question: What function is used to close an open file in PHP?

**Answer:** `fclose()`

---

# Question: What argument is required by `fclose()`?

**Answer:** A file pointer.

---

# Question: What does `fclose()` return on success or failure?

**Answer:** Returns `true` on success, and `false` on failure.

---

# Question: Which function is used to read content from a file?

**Answer:** `fread()`

---

# Question: What arguments does `fread()` require?

**Answer:** A file pointer and the length in bytes to read.

---

# Question: How do you get the size of a file in bytes in PHP?

**Answer:** Using `filesize()` function with the file name as the argument.

---

# Question: List the steps to read a file in PHP.

**Answer:**

1. Open the file with `fopen()`.
2. Get the size using `filesize()`.
3. Read contents with `fread()`.
4. Close the file with `fclose()`.

---

# Question: What happens if `fopen()` fails to open a file?

**Answer:** It returns `false`, and appropriate error handling like displaying a message and exiting should be used.

---

# Question: In the reading example, what is stored in `$filetext`?

**Answer:** The contents of the file read using `fread()`.

---

# Question: What is the output of the reading file example?

**Answer:** File size in bytes and the file contents wrapped in `<pre>` tags.

---

# Question: Which function is used to write content to a file?

**Answer:** `fwrite()`

---

# Question: What are the required arguments of `fwrite()`?

**Answer:** A file pointer and the string of data to write.

---

# Question: What is the optional third argument in `fwrite()` and what does it do?

**Answer:** An integer specifying the length of data to write; it limits how much of the string is written.

---

# Question: What does the writing file example do?

**Answer:** Creates a new file, writes a heading into it, closes it, and then reopens and reads its contents for display.

---

# Question: How is the existence of the newly created file confirmed in the example?

**Answer:** By using `file_exists()` with the file name as an argument.

---

# Question: What is the role of `file_exists()` in PHP?

**Answer:** It checks whether a file exists, returning `true` if it does and `false` if it doesn't.

---

# Question: Where is the new file created in the example?

**Answer:** At `/home/user/guest/newfile.txt`

---

# Question: What output is expected from the writing example?

**Answer:** The file size, contents (`"This is  a simple test"`), and the file name.

---

# Question: What tag is used in the example to preserve the format of the file content?

**Answer:** `<pre>`

---

# Question: What happens if you try to open a file that does not exist in `r` mode?

**Answer:** `fopen()` will fail and return `false`.

---

# Question: What is the significance of using `"r"` mode when reading files in the examples?

**Answer:** It ensures the file is opened in read-only mode with the pointer at the beginning.

---

# Question: Can `fwrite()` be used to append text to a file?

**Answer:** Yes, by opening the file in `a` or `a+` mode.

---

# Question: What must always be done after file operations are complete?

**Answer:** The file must be closed using `fclose()`.

---

# Question: What does the PHP `abs()` function do?

**Answer:** It returns the absolute (positive) value of a number, disregarding its sign.

---

# Question: What is the return type of `abs()` when a float is passed?

**Answer:** Float.

---

# Question: What is the return type of `abs()` when an integer is passed?

**Answer:** Integer.

---

# Question: What does the PHP `ceil()` function do?

**Answer:** It rounds a float number up to the next highest integer and returns it as a float.

---

# Question: What is the output of `ceil(-3.95)`?

**Answer:** -3.

---

# Question: What data type does `ceil()` always return?

**Answer:** Float.

---

# Question: What does `exp($x)` return in PHP?

**Answer:** Euler’s number (e) raised to the power of `$x`.

---

# Question: What is the output of `exp(M_LN2)`?

**Answer:** 2.

---

# Question: What is the value of Euler's number `M_E`?

**Answer:** 2.7182818284590452354.

---

# Question: What is the relationship between `exp()` and natural logarithm?

**Answer:** `exp()` is the inverse of the natural logarithm.

---

# Question: What does the `floor()` function do in PHP?

**Answer:** Rounds a float number down to the next lowest integer and returns it as a float.

---

# Question: What is the result of `floor(-3.95)`?

**Answer:** -4.

---

# Question: What is returned by `floor(15.05)`?

**Answer:** 15.

---

# Question: What does `intdiv(x, y)` do in PHP?

**Answer:** It returns the integer quotient of the division `x/y`, ignoring the remainder.

---

# Question: What is the result of `intdiv(3, 10)`?

**Answer:** 0.

---

# Question: What happens if `intdiv()` is called with 0 as the denominator?

**Answer:** A `DivisionByZeroError` exception is thrown.

---

# Question: What does `intdiv(2.90, 1.90)` return?

**Answer:** 2 (fractional parts are ignored).

---

# Question: What is the result of `intdiv(-10, 3)`?

**Answer:** -3.

---

# Question: What does `log10()` return in PHP?

**Answer:** The base-10 logarithm of a number.

---

# Question: What is `log10(100)` equal to?

**Answer:** 2.

---

# Question: What constant equals `log10(M_E)`?

**Answer:** `M_LOG10E`.

---

# Question: What is the result of `log10(0)`?

**Answer:** -INF.

---

# Question: What is the result of `log10(sqrt(-1))`?

**Answer:** NAN.

---

# Question: What does the `max()` function return?

**Answer:** The highest value from an array or a list of values.

---

# Question: What is the result of `max(array("Java", "Angular", "PHP", "C", "Kotlin"))`?

**Answer:** PHP.

---

# Question: If comparable values evaluate as equal in `max()`, which one is returned?

**Answer:** The first parameter.

---

# Question: What happens when `max()` is called with a mixed-type array?

**Answer:** Standard comparison rules apply; the highest value is returned accordingly.

---

# Question: What does `max(23, "Java", 142, 1e2, 99)` return?

**Answer:** 142.

---

# Question: What does the `min()` function return?

**Answer:** The lowest value from an array or a list of values.

---

# Question: What is the result of `min(array("Java", "Angular", "PHP", "C", "Kotlin"))`?

**Answer:** Angular.

---

# Question: What happens when `min()` is called with a mixed-type array?

**Answer:** Standard comparison rules apply; the lowest value is returned accordingly.

---

# Question: What does `min(array(23, 5.55, 142, 56, 99))` return?

**Answer:** 5.55.

---

# Question: If multiple values evaluate equally in `min()`, which one is returned?

**Answer:** The first parameter.

---

# Question: What does `pow(x, y)` compute in PHP?

**Answer:** It computes `x` raised to the power of `y`.

---

# Question: What is another way to calculate powers in PHP besides `pow()`?

**Answer:** Using the exponentiation operator `**`.

---

# Question: What does `pow(10, 0)` return?

**Answer:** 1.

---

# Question: What is the result of `pow(100, 0.5)`?

**Answer:** 10.

---

# Question: How can the area of a circle be calculated using `pow()`?

**Answer:** `M_PI * pow(radius, 2)`.

---

# Question: What does the `round()` function do?

**Answer:** It rounds a float to a specified number of decimal digits.

---

# Question: What is the default precision of `round()` if not specified?

**Answer:** 0.

---

# Question: What does `round(1234.567, -2)` return?

**Answer:** 1200.

---

# Question: What does the `PHP_ROUND_HALF_UP` mode do?

**Answer:** Rounds number away from 0 when it is halfway (e.g., 1.5 → 2, -1.5 → -2).

---

# Question: What is the behavior of `PHP_ROUND_HALF_DOWN`?

**Answer:** Rounds number toward 0 when halfway (e.g., 1.5 → 1, -1.5 → -1).

---

# Question: What does the `PHP_ROUND_HALF_EVEN` mode do?

**Answer:** Rounds to the nearest even number.

---

# Question: What does `PHP_ROUND_HALF_ODD` do?

**Answer:** Rounds to the nearest odd number.

---

# Question: What does `sqrt($num)` return?

**Answer:** The square root of `$num`.

---

# Question: What is the return value of `sqrt(-1)`?

**Answer:** NAN.

---

# Question: What is the value of the predefined constant `M_SQRT2`?

**Answer:** 1.4142135623731.

---

# Question: What does `M_2_SQRTPI` represent?

**Answer:** The value of `2/sqrt(pi)`.

---

# Question: What constant represents the square root of 1/2?

**Answer:** `M_SQRT1_2`.

---


# Question: What is the value of `M_PI` in PHP?

**Answer:** 3.14159265358979323846.

---

# Question: What constant represents log base 2 of Euler’s number?

**Answer:** `M_LOG2E`.

---

# Question: What does `INF` represent in PHP?

**Answer:** Infinity.

---

# Question: What does `NAN` stand for in PHP?

**Answer:** Not A Number.

---

# Question: What is the value of `M_EULER`?

**Answer:** 0.57721566490153286061.

---

# Question: What are Heredoc and Nowdoc used for in PHP?

**Answer:** They are used to write long multi-line strings without needing excessive quotes or escape characters, allowing for clean and readable syntax.

---

# Question: What is the main difference between Heredoc and Nowdoc in PHP?

**Answer:** Heredoc expands variables and interprets escape sequences like double-quoted strings, whereas Nowdoc treats the content as raw text and does not expand variables or interpret escape sequences, like single-quoted strings.

---

# Question: Which PHP string type does **not** interpret escape characters or expand variables?

**Answer:** Single-quoted strings and Nowdoc strings.

---

# Question: Why is Heredoc useful when working with strings that contain quotes?

**Answer:** Because it eliminates the need to escape quotes and still expands variables, making it similar to double-quoted strings.

---

# Question: What is the syntax for beginning a Heredoc string in PHP?

**Answer:** Use `<<<IDENTIFIER` followed by a newline, then the multi-line string content, and finally the same `IDENTIFIER` on its own line to close the string.

---

# Question: Can a Heredoc string span multiple lines?

**Answer:** Yes, Heredoc strings can span multiple lines.

---

# Question: What types of characters can be used in a Heredoc or Nowdoc identifier?

**Answer:** Identifiers must be alphanumeric or underscores, starting with a non-digit or an underscore.

---

# Question: What characters must appear before and after the closing identifier in Heredoc/Nowdoc?

**Answer:** Only newline characters are allowed before and after the closing identifier.

---

# Question: What happens if the closing identifier in a Heredoc is indented further than any line in the body?

**Answer:** A `ParseError` will be raised due to invalid body indentation.

---

# Question: What happens to indentation when using Heredoc?

**Answer:** Any indentation before the closing identifier is stripped from all lines in the Heredoc string, provided it's consistent and not deeper than the body lines.

---

# Question: In Heredoc syntax, do you need to escape single or double quotes within the string?

**Answer:** No, quotes do not need to be escaped in Heredoc strings.

---

# Question: Does Heredoc expand variables?

**Answer:** Yes, it expands variables like double-quoted strings.

---

# Question: What will the following PHP code output?

```php
$lang="PHP";
echo <<<EOS
Heredoc strings in $lang expand vriables.
The escape sequences are also interpreted.
Here, the hexdecimal ASCII characters produce \x50\x48\x50
EOS;
```

**Answer:**

```
Heredoc strings in PHP expand vriables.
The escape sequences are also interpreted.
Here, the hexdecimal ASCII characters produce PHP
```

---

# Question: What does the following code demonstrate?

```php
<?php
$str = <<<'ID'
This is a nowdoc string with $var and \n newlines.
ID;
?>
```

**Answer:** It demonstrates that Nowdoc strings do not expand variables (`$var` remains literal) and do not interpret escape sequences (`\n` remains literal).

---

# Question: How does Nowdoc syntax differ from Heredoc syntax?

**Answer:** Nowdoc requires the identifier after `<<<` to be enclosed in single quotes, whereas Heredoc does not.

---

# Question: Which string type behaves like a double-quoted string without escaping?

**Answer:** Heredoc.

---

# Question: Which string type behaves like a single-quoted string without escaping?

**Answer:** Nowdoc.

---

# Question: In Nowdoc, are escape sequences like `\n` or `\t` interpreted?

**Answer:** No, they are treated as literal text.

---

# Question: What must follow the `<<<` operator in Nowdoc syntax?

**Answer:** A single-quoted identifier.

---

# Question: What error is shown if the indentation level of the Heredoc body is inconsistent or incorrect?

**Answer:** `PHP Parse error: Invalid body indentation level`.

---


