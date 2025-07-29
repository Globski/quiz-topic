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

