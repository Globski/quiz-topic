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

