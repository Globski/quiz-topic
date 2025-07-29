# Question: List all PHP keywords.

### PHP Keywords

| Keyword        | Description                                                |
| -------------- | ---------------------------------------------------------- |
| `abstract`     | Declare a class as abstract                                |
| `and`          | A logical operator                                         |
| `as`           | Used in the `foreach` loop                                 |
| `break`        | Break out of loops and `switch` statements                 |
| `callable`     | A data type which can be executed as a function            |
| `case`         | Used in the `switch` conditional                           |
| `catch`        | Used in the `try...catch` statement                        |
| `class`        | Declare a class                                            |
| `clone`        | Create a copy of an object                                 |
| `const`        | Define a class constant                                    |
| `continue`     | Jump to the next iteration of a loop                       |
| `declare`      | Set directives for a block of code                         |
| `default`      | Used in the `switch` statement                             |
| `do`           | Create a `do...while` loop                                 |
| `echo`         | Output text                                                |
| `else`         | Used in conditional statements                             |
| `elseif`       | Used in conditional statements                             |
| `empty`        | Check if an expression is empty                            |
| `enddeclare`   | End a `declare` block                                      |
| `endfor`       | End a `for` block                                          |
| `endforeach`   | End a `foreach` block                                      |
| `endif`        | End an `if` or `elseif` block                              |
| `endswitch`    | End a `switch` block                                       |
| `endwhile`     | End a `while` block                                        |
| `extends`      | Extends a class or interface                               |
| `final`        | Declare a class, property, or method as final              |
| `finally`      | Used in the `try...catch` statement                        |
| `fn`           | Declare an arrow function                                  |
| `for`          | Create a `for` loop                                        |
| `foreach`      | Create a `foreach` loop                                    |
| `function`     | Create a function                                          |
| `global`       | Import variables from the global scope                     |
| `goto`         | Jump to a line of code                                     |
| `if`           | Create a conditional statement                             |
| `implements`   | Implement an interface                                     |
| `include`      | Embed code from another file                               |
| `include_once` | Embed code from another file, only once                    |
| `instanceof`   | Test an object's class                                     |
| `insteadof`    | Resolve conflicts with traits                              |
| `interface`    | Declare an interface                                       |
| `isset`        | Check if a variable exists and is not `null`               |
| `list`         | Assign array elements into variables                       |
| `namespace`    | Declare a namespace                                        |
| `new`          | Create an object                                           |
| `or`           | A logical operator                                         |
| `print`        | Output text                                                |
| `private`      | Declare a property, method, or constant as private         |
| `protected`    | Declare a property, method, or constant as protected       |
| `public`       | Declare a property, method, or constant as public          |
| `require`      | Embed code from another file                               |
| `require_once` | Embed code from another file, only once                    |
| `return`       | Exit a function and return a value                         |
| `static`       | Declare a property or method as static                     |
| `switch`       | Create a `switch` block                                    |
| `throw`        | Throw an exception                                         |
| `trait`        | Declare a trait                                            |
| `try`          | Create a `try...catch` structure                           |
| `unset`        | Delete a variable or array element                         |
| `use`          | Use a namespace or trait                                   |
| `var`          | Declare a variable (obsolete, use `public`/`private` etc.) |
| `while`        | Create a `while` loop or end a `do...while` loop           |
| `xor`          | A logical operator                                         |
| `yield`        | Used in generator functions                                |
| `yield from`   | Delegate generator operations                              |

---

# Question: List all PHP array functions and their descriptions.

### PHP Array Functions

| Function                    | Description                                                                                       |
| --------------------------- | ------------------------------------------------------------------------------------------------- |
| `array()`                   | Creates an array                                                                                  |
| `array_change_key_case()`   | Changes all keys in an array to lowercase or uppercase                                            |
| `array_chunk()`             | Splits an array into chunks of arrays                                                             |
| `array_column()`            | Returns the values from a single column in the input array                                        |
| `array_combine()`           | Creates an array by using one array for keys and another for values                               |
| `array_count_values()`      | Counts all the values of an array                                                                 |
| `array_diff()`              | Compares arrays and returns the differences (compare values only)                                 |
| `array_diff_assoc()`        | Compares arrays and returns the differences (compare keys and values)                             |
| `array_diff_key()`          | Compares arrays and returns the differences (compare keys only)                                   |
| `array_diff_uassoc()`       | Compares arrays (keys and values) using a user-defined function for key comparison                |
| `array_diff_ukey()`         | Compares arrays (keys only) using a user-defined function for key comparison                      |
| `array_fill()`              | Fills an array with values                                                                        |
| `array_fill_keys()`         | Fills an array with values, specifying keys                                                       |
| `array_filter()`            | Filters the values of an array using a callback function                                          |
| `array_flip()`              | Exchanges all keys with their associated values                                                   |
| `array_intersect()`         | Compares arrays and returns the matches (compare values only)                                     |
| `array_intersect_assoc()`   | Compares arrays and returns the matches (compare keys and values)                                 |
| `array_intersect_key()`     | Compares arrays and returns the matches (compare keys only)                                       |
| `array_intersect_uassoc()`  | Compares arrays (keys and values) using a user-defined key comparison function                    |
| `array_intersect_ukey()`    | Compares arrays (keys only) using a user-defined key comparison function                          |
| `array_key_exists()`        | Checks if the specified key exists in the array                                                   |
| `array_keys()`              | Returns all the keys of an array                                                                  |
| `array_map()`               | Sends each value of an array to a user-defined function and returns the new array                 |
| `array_merge()`             | Merges one or more arrays                                                                         |
| `array_merge_recursive()`   | Recursively merges one or more arrays                                                             |
| `array_multisort()`         | Sorts multiple or multi-dimensional arrays                                                        |
| `array_pad()`               | Inserts a specified number of items into an array, with a specified value                         |
| `array_pop()`               | Deletes the last element of an array                                                              |
| `array_product()`           | Calculates the product of the values in an array                                                  |
| `array_push()`              | Inserts one or more elements to the end of an array                                               |
| `array_rand()`              | Returns one or more random keys from an array                                                     |
| `array_reduce()`            | Iteratively reduces the array to a single value using a callback function                         |
| `array_replace()`           | Replaces values in the first array with values from following arrays                              |
| `array_replace_recursive()` | Recursively replaces values in the first array with values from following arrays                  |
| `array_reverse()`           | Returns an array in reverse order                                                                 |
| `array_search()`            | Searches an array for a given value and returns the key                                           |
| `array_shift()`             | Removes the first element from an array and returns it                                            |
| `array_slice()`             | Returns selected parts of an array                                                                |
| `array_splice()`            | Removes and replaces specified elements of an array                                               |
| `array_sum()`               | Returns the sum of values in an array                                                             |
| `array_udiff()`             | Compares arrays (values only) using a user-defined function                                       |
| `array_udiff_assoc()`       | Compares arrays (keys and values) with built-in key comparison and user-defined value comparison  |
| `array_udiff_uassoc()`      | Compares arrays (keys and values) using two user-defined functions                                |
| `array_uintersect()`        | Compares arrays (values only) using a user-defined function                                       |
| `array_uintersect_assoc()`  | Compares arrays (keys and values) using built-in key comparison and user-defined value comparison |
| `array_uintersect_uassoc()` | Compares arrays (keys and values) using two user-defined functions                                |
| `array_unique()`            | Removes duplicate values from an array                                                            |
| `array_unshift()`           | Adds one or more elements to the beginning of an array                                            |
| `array_values()`            | Returns all values from an array                                                                  |
| `array_walk()`              | Applies a user-defined function to every element in an array                                      |
| `array_walk_recursive()`    | Applies a user-defined function recursively to each element in an array                           |
| `arsort()`                  | Sorts an associative array in descending order according to value                                 |
| `asort()`                   | Sorts an associative array in ascending order according to value                                  |
| `compact()`                 | Creates an array from variables and their values                                                  |
| `count()`                   | Returns the number of elements in an array                                                        |
| `current()`                 | Returns the current element in an array                                                           |
| `each()`                    | **Deprecated** — Returns the current key/value pair from an array                                 |
| `end()`                     | Moves the internal pointer to the last element                                                    |
| `extract()`                 | Imports variables from an array into the current symbol table                                     |
| `in_array()`                | Checks if a value exists in an array                                                              |
| `key()`                     | Fetches a key from the current element                                                            |
| `krsort()`                  | Sorts an associative array in descending order according to key                                   |
| `ksort()`                   | Sorts an associative array in ascending order according to key                                    |
| `list()`                    | Assigns variables as if they were an array                                                        |
| `natcasesort()`             | Case-insensitive natural order sorting                                                            |
| `natsort()`                 | Natural order sorting                                                                             |
| `next()`                    | Moves the internal array pointer to the next element                                              |
| `pos()`                     | Alias of `current()`                                                                              |
| `prev()`                    | Moves the internal array pointer to the previous element                                          |
| `range()`                   | Creates an array containing a range of elements                                                   |
| `reset()`                   | Moves the internal pointer to the first element                                                   |
| `rsort()`                   | Sorts an indexed array in descending order                                                        |
| `shuffle()`                 | Shuffles an array                                                                                 |
| `sizeof()`                  | Alias of `count()`                                                                                |
| `sort()`                    | Sorts an indexed array in ascending order                                                         |
| `uasort()`                  | Sorts values using a user-defined function while maintaining index association                    |
| `uksort()`                  | Sorts keys using a user-defined comparison function                                               |
| `usort()`                   | Sorts values using a user-defined comparison function                                             |

---

# Question: What are PHP String Functions and how are they used?

---

## 📖 PHP String Functions Overview

PHP provides a rich set of **string manipulation functions** that allow you to:

* Create and format strings
* Search and replace substrings
* Parse strings and convert between formats
* Handle character encoding
* Calculate similarity and hash values

---

## ⚙️ Installation

PHP string functions are **part of the PHP core**.
**No installation is required** to use them.

---

## 🔤 PHP String Functions

| Function                       | Description                                                       |
| ------------------------------ | ----------------------------------------------------------------- |
| `addcslashes()`                | Adds backslashes in front of specified characters                 |
| `addslashes()`                 | Adds backslashes before predefined characters                     |
| `bin2hex()`                    | Converts ASCII to hexadecimal                                     |
| `chop()`                       | Removes whitespace (or other characters) from the end of a string |
| `chr()`                        | Returns a character from a given ASCII value                      |
| `chunk_split()`                | Splits a string into smaller parts                                |
| `convert_cyr_string()`         | Converts a string between Cyrillic encodings                      |
| `convert_uudecode()`           | Decodes a uuencoded string                                        |
| `convert_uuencode()`           | Encodes a string using uuencode                                   |
| `count_chars()`                | Returns info about characters used in a string                    |
| `crc32()`                      | Calculates CRC32 polynomial hash                                  |
| `crypt()`                      | Performs one-way string hashing                                   |
| `echo()`                       | Outputs one or more strings                                       |
| `explode()`                    | Splits a string into an array using a delimiter                   |
| `fprintf()`                    | Writes a formatted string to an output stream                     |
| `get_html_translation_table()` | Gets the table used by `htmlentities()` / `htmlspecialchars()`    |
| `hebrev()`                     | Converts Hebrew text to visual text                               |
| `hebrevc()`                    | Converts Hebrew text and newlines to `<br>`                       |
| `hex2bin()`                    | Converts hex to ASCII                                             |
| `html_entity_decode()`         | Converts HTML entities to characters                              |
| `htmlentities()`               | Converts characters to HTML entities                              |
| `htmlspecialchars_decode()`    | Converts special HTML entities to characters                      |
| `htmlspecialchars()`           | Converts special characters to HTML entities                      |
| `implode()` / `join()`         | Joins array elements into a string                                |
| `lcfirst()`                    | Converts first character to lowercase                             |
| `levenshtein()`                | Calculates Levenshtein distance (edit distance)                   |
| `localeconv()`                 | Gets locale formatting info                                       |
| `ltrim()`                      | Trims whitespace from the beginning of a string                   |
| `md5()`                        | Returns MD5 hash of a string                                      |
| `md5_file()`                   | Returns MD5 hash of a file                                        |
| `metaphone()`                  | Calculates the metaphone key of a string                          |
| `money_format()`               | Formats a string as currency (deprecated)                         |
| `nl_langinfo()`                | Gets language and locale info                                     |
| `nl2br()`                      | Converts newlines to `<br>`                                       |
| `number_format()`              | Formats a number with grouped thousands                           |
| `ord()`                        | Gets ASCII value of the first character                           |
| `parse_str()`                  | Parses query strings into variables                               |
| `print()`                      | Outputs strings                                                   |
| `printf()`                     | Outputs a formatted string                                        |
| `quoted_printable_decode()`    | Decodes a quoted-printable string                                 |
| `quoted_printable_encode()`    | Encodes an 8-bit string to quoted-printable                       |
| `quotemeta()`                  | Escapes meta characters                                           |
| `rtrim()`                      | Trims whitespace from the end of a string                         |
| `setlocale()`                  | Sets locale info                                                  |
| `sha1()`                       | Returns SHA-1 hash of a string                                    |
| `sha1_file()`                  | Returns SHA-1 hash of a file                                      |
| `similar_text()`               | Calculates similarity percentage                                  |
| `soundex()`                    | Returns the soundex key of a string                               |
| `sprintf()`                    | Returns a formatted string                                        |
| `sscanf()`                     | Parses a string according to a format                             |
| `str_getcsv()`                 | Parses CSV string into array                                      |
| `str_ireplace()`               | Case-insensitive string replacement                               |
| `str_pad()`                    | Pads a string to a certain length                                 |
| `str_repeat()`                 | Repeats a string multiple times                                   |
| `str_replace()`                | Replaces part of a string (case-sensitive)                        |
| `str_rot13()`                  | Applies ROT13 transformation                                      |
| `str_shuffle()`                | Randomly shuffles characters in a string                          |
| `str_split()`                  | Splits a string into an array of characters                       |
| `str_word_count()`             | Counts words in a string                                          |
| `strcasecmp()`                 | Binary-safe, case-insensitive string comparison                   |
| `strchr()` / `strstr()`        | Finds first occurrence of a substring (case-sensitive)            |
| `strcmp()`                     | Binary-safe, case-sensitive string comparison                     |
| `strcoll()`                    | Locale-based string comparison                                    |
| `strcspn()`                    | Returns length of segment not containing any given characters     |
| `strip_tags()`                 | Strips HTML and PHP tags                                          |
| `stripcslashes()`              | Unquotes a string quoted with `addcslashes()`                     |
| `stripslashes()`               | Unquotes a string quoted with `addslashes()`                      |
| `stripos()`                    | Finds position of substring (case-insensitive)                    |
| `stristr()`                    | Finds first occurrence (case-insensitive)                         |
| `strlen()`                     | Gets length of a string                                           |
| `strnatcasecmp()`              | Natural order comparison (case-insensitive)                       |
| `strnatcmp()`                  | Natural order comparison (case-sensitive)                         |
| `strncasecmp()`                | Compares first n chars (case-insensitive)                         |
| `strncmp()`                    | Compares first n chars (case-sensitive)                           |
| `strpbrk()`                    | Searches string for any of a set of characters                    |
| `strpos()`                     | Finds position of first occurrence (case-sensitive)               |
| `strrchr()`                    | Finds last occurrence of a character in a string                  |
| `strrev()`                     | Reverses a string                                                 |
| `strripos()`                   | Finds last occurrence (case-insensitive)                          |
| `strrpos()`                    | Finds last occurrence (case-sensitive)                            |
| `strspn()`                     | Returns span of chars from allowed list                           |
| `strtok()`                     | Tokenizes a string                                                |
| `strtolower()`                 | Converts string to lowercase                                      |
| `strtoupper()`                 | Converts string to uppercase                                      |
| `strtr()`                      | Translates characters in a string                                 |
| `substr()`                     | Returns substring                                                 |
| `substr_compare()`             | Compares two strings from specific start                          |
| `substr_count()`               | Counts number of times a substring occurs                         |
| `substr_replace()`             | Replaces part of a string                                         |
| `trim()`                       | Trims whitespace from both ends of a string                       |
| `ucfirst()`                    | Uppercases first character of a string                            |
| `ucwords()`                    | Uppercases first letter of each word                              |
| `vfprintf()`                   | Writes formatted string to a stream                               |
| `vprintf()`                    | Outputs formatted string                                          |
| `vsprintf()`                   | Returns formatted string                                          |
| `wordwrap()`                   | Wraps a string to a specified number of characters                |

---

# What are PHP Variable Handling Functions and how are they used?

---

## 📖 PHP Variable Handling Functions Overview

PHP provides built-in functions to **check, convert, manipulate, or retrieve information about variables**. These are essential for validating types, debugging, and handling dynamic data in your applications.

---

## ⚙️ Installation

These functions are **built into PHP core**, so **no installation is required**.

---

## 🧠 PHP Variable Handling Functions

| Function              | Description                                                             |
| --------------------- | ----------------------------------------------------------------------- |
| `boolval()`           | Returns the boolean value of a variable                                 |
| `debug_zval_dump()`   | Dumps internal Zend value representation of a variable                  |
| `doubleval()`         | Alias of `floatval()`                                                   |
| `empty()`             | Checks whether a variable is empty                                      |
| `floatval()`          | Returns the float value of a variable                                   |
| `get_defined_vars()`  | Returns all currently defined variables as an array                     |
| `get_resource_type()` | Returns the type of a resource                                          |
| `gettype()`           | Returns the type of a variable (e.g., string, integer, array, etc.)     |
| `intval()`            | Returns the integer value of a variable                                 |
| `is_array()`          | Checks whether a variable is an array                                   |
| `is_bool()`           | Checks whether a variable is a boolean                                  |
| `is_callable()`       | Checks whether a variable is callable (e.g., a function)                |
| `is_countable()`      | Checks whether a variable is countable (e.g., arrays, objects)          |
| `is_double()`         | Alias of `is_float()`                                                   |
| `is_float()`          | Checks whether a variable is a float                                    |
| `is_int()`            | Checks whether a variable is an integer                                 |
| `is_integer()`        | Alias of `is_int()`                                                     |
| `is_iterable()`       | Checks whether a variable is iterable (array or implements Traversable) |
| `is_long()`           | Alias of `is_int()`                                                     |
| `is_null()`           | Checks whether a variable is `NULL`                                     |
| `is_numeric()`        | Checks whether a variable is a number or numeric string                 |
| `is_object()`         | Checks whether a variable is an object                                  |
| `is_real()`           | Alias of `is_float()`                                                   |
| `is_resource()`       | Checks whether a variable is a resource                                 |
| `is_scalar()`         | Checks whether a variable is scalar (int, float, string, or bool)       |
| `is_string()`         | Checks whether a variable is a string                                   |
| `isset()`             | Checks whether a variable is set and is not `NULL`                      |
| `print_r()`           | Prints human-readable information about a variable                      |
| `serialize()`         | Converts a variable into a storable string representation               |
| `settype()`           | Sets the type of a variable                                             |
| `strval()`            | Returns the string value of a variable                                  |
| `unserialize()`       | Converts serialized data back into PHP values                           |
| `unset()`             | Destroys a specified variable                                           |
| `var_dump()`          | Dumps information (type and value) about a variable                     |
| `var_export()`        | Outputs structured information (as valid PHP code) about a variable     |

---


# Question: List all PHP calendar functions and their descriptions.

### PHP Calendar Functions

| Function              | Description                                                                 |
| --------------------- | --------------------------------------------------------------------------- |
| `cal_days_in_month()` | Returns the number of days in a month for a specified year and calendar     |
| `cal_from_jd()`       | Converts a Julian Day Count into a date of a specified calendar             |
| `cal_info()`          | Returns information about a specified calendar                              |
| `cal_to_jd()`         | Converts a date in a specified calendar to Julian Day Count                 |
| `easter_date()`       | Returns the Unix timestamp for midnight on Easter of a specified year       |
| `easter_days()`       | Returns the number of days after March 21 that Easter falls in a given year |
| `frenchtojd()`        | Converts a French Republican date to a Julian Day Count                     |
| `gregoriantojd()`     | Converts a Gregorian date to a Julian Day Count                             |
| `jddayofweek()`       | Returns the day of the week                                                 |
| `jdmonthname()`       | Returns a month name                                                        |
| `jdtofrench()`        | Converts a Julian Day Count to a French Republican date                     |
| `jdtogregorian()`     | Converts a Julian Day Count to a Gregorian date                             |
| `jdtojewish()`        | Converts a Julian Day Count to a Jewish date                                |
| `jdtojulian()`        | Converts a Julian Day Count to a Julian date                                |
| `jdtounix()`          | Converts a Julian Day Count to a Unix timestamp                             |
| `jewishtojd()`        | Converts a Jewish date to a Julian Day Count                                |
| `juliantojd()`        | Converts a Julian date to a Julian Day Count                                |
| `unixtojd()`          | Converts a Unix timestamp to a Julian Day Count                             |

---

# Question: List all predefined PHP calendar constants, their types, and the PHP version they were introduced in.

### PHP Predefined Calendar Constants

| Constant                       | Type    | PHP Version |
| ------------------------------ | ------- | ----------- |
| `CAL_GREGORIAN`                | Integer | PHP 4       |
| `CAL_JULIAN`                   | Integer | PHP 4       |
| `CAL_JEWISH`                   | Integer | PHP 4       |
| `CAL_FRENCH`                   | Integer | PHP 4       |
| `CAL_NUM_CALS`                 | Integer | PHP 4       |
| `CAL_DOW_DAYNO`                | Integer | PHP 4       |
| `CAL_DOW_SHORT`                | Integer | PHP 4       |
| `CAL_DOW_LONG`                 | Integer | PHP 4       |
| `CAL_MONTH_GREGORIAN_SHORT`    | Integer | PHP 4       |
| `CAL_MONTH_GREGORIAN_LONG`     | Integer | PHP 4       |
| `CAL_MONTH_JULIAN_SHORT`       | Integer | PHP 4       |
| `CAL_MONTH_JULIAN_LONG`        | Integer | PHP 4       |
| `CAL_MONTH_JEWISH`             | Integer | PHP 4       |
| `CAL_MONTH_FRENCH`             | Integer | PHP 4       |
| `CAL_EASTER_DEFAULT`           | Integer | PHP 4.3     |
| `CAL_EASTER_ROMAN`             | Integer | PHP 4.3     |
| `CAL_EASTER_ALWAYS_GREGORIAN`  | Integer | PHP 4.3     |
| `CAL_EASTER_ALWAYS_JULIAN`     | Integer | PHP 4.3     |
| `CAL_JEWISH_ADD_ALAFIM_GERESH` | Integer | PHP 5.0     |
| `CAL_JEWISH_ADD_ALAFIM`        | Integer | PHP 5.0     |
| `CAL_JEWISH_ADD_GERESHAYIM`    | Integer | PHP 5.0     |


---

# Question: What are the runtime configuration settings that affect PHP date/time functions?

### PHP Date/Time Configuration Directives

| Name                     | Description                                                    | Default     | PHP Version |
| ------------------------ | -------------------------------------------------------------- | ----------- | ----------- |
| `date.timezone`          | The default timezone used by all date/time functions           | `""`        | PHP 5.1     |
| `date.default_latitude`  | The default latitude for `date_sunrise()` and `date_sunset()`  | `"31.7667"` | PHP 5.0     |
| `date.default_longitude` | The default longitude for `date_sunrise()` and `date_sunset()` | `"35.2333"` | PHP 5.0     |
| `date.sunrise_zenith`    | The default zenith angle for sunrise, used by `date_sunrise()` | `"90.83"`   | PHP 5.0     |
| `date.sunset_zenith`     | The default zenith angle for sunset, used by `date_sunset()`   | `"90.83"`   | PHP 5.0     |

---

# Question: What are the available PHP date/time functions and what do they do?

### PHP Date/Time Functions

| Function                                  | Description                                                                       |
| ----------------------------------------- | --------------------------------------------------------------------------------- |
| `checkdate()`                             | Validates a Gregorian date                                                        |
| `date_add()`                              | Adds days, months, years, hours, minutes, and seconds to a date                   |
| `date_create_from_format()`               | Returns a new `DateTime` object formatted according to a specified format         |
| `date_create()`                           | Returns a new `DateTime` object                                                   |
| `date_date_set()`                         | Sets a new date                                                                   |
| `date_default_timezone_get()`             | Returns the default timezone used by all date/time functions                      |
| `date_default_timezone_set()`             | Sets the default timezone used by all date/time functions                         |
| `date_diff()`                             | Returns the difference between two dates                                          |
| `date_format()`                           | Returns a date formatted according to a specified format                          |
| `date_get_last_errors()`                  | Returns warnings/errors found in a date string                                    |
| `date_interval_create_from_date_string()` | Sets up a `DateInterval` from the relative parts of the string                    |
| `date_interval_format()`                  | Formats a time interval                                                           |
| `date_isodate_set()`                      | Sets the ISO date                                                                 |
| `date_modify()`                           | Modifies the timestamp                                                            |
| `date_offset_get()`                       | Returns the timezone offset                                                       |
| `date_parse_from_format()`                | Returns detailed info about a specified date from a specified format              |
| `date_parse()`                            | Returns an associative array with detailed info about a specified date            |
| `date_sub()`                              | Subtracts days, months, years, hours, minutes, and seconds from a date            |
| `date_sun_info()`                         | Returns info about sunrise/sunset and twilight times for a given day and location |
| `date_sunrise()`                          | Returns the sunrise time for a specified day and location                         |
| `date_sunset()`                           | Returns the sunset time for a specified day and location                          |
| `date_time_set()`                         | Sets the time                                                                     |
| `date_timestamp_get()`                    | Returns the Unix timestamp of a `DateTime` object                                 |
| `date_timestamp_set()`                    | Sets the date and time based on a Unix timestamp                                  |
| `date_timezone_get()`                     | Returns the timezone of a `DateTime` object                                       |
| `date_timezone_set()`                     | Sets the timezone for a `DateTime` object                                         |
| `date()`                                  | Formats a local date and time                                                     |
| `getdate()`                               | Returns date/time information of a timestamp or the current local date/time       |
| `gettimeofday()`                          | Returns the current time with microseconds                                        |
| `gmdate()`                                | Formats a GMT/UTC date and time                                                   |
| `gmmktime()`                              | Returns the Unix timestamp for a GMT date                                         |
| `gmstrftime()`                            | Formats a GMT/UTC date and time according to locale settings                      |
| `idate()`                                 | Formats a local time/date as integer                                              |
| `localtime()`                             | Returns the local time                                                            |
| `microtime()`                             | Returns the current Unix timestamp with microseconds                              |
| `mktime()`                                | Returns the Unix timestamp for a date                                             |
| `strftime()`                              | Formats a local time/date according to locale settings                            |
| `strptime()`                              | Parses a time/date generated with `strftime()`                                    |
| `strtotime()`                             | Parses an English textual datetime into a Unix timestamp                          |
| `time()`                                  | Returns the current time as a Unix timestamp                                      |
| `timezone_abbreviations_list()`           | Returns an associative array containing DST, offset, and timezone names           |
| `timezone_identifiers_list()`             | Returns an indexed array with all timezone identifiers                            |
| `timezone_location_get()`                 | Returns location information for a specified timezone                             |
| `timezone_name_from_abbr()`               | Returns the timezone name from an abbreviation                                    |
| `timezone_name_get()`                     | Returns the name of the timezone                                                  |
| `timezone_offset_get()`                   | Returns the timezone offset from GMT                                              |
| `timezone_open()`                         | Creates a new `DateTimeZone` object                                               |
| `timezone_transitions_get()`              | Returns all transitions for the timezone                                          |
| `timezone_version_get()`                  | Returns the version of the timezone database                                      |

---

## PHP Predefined Date/Time Constants

| **Constant**             | **Description**                                               | **Example Output**                 |
| ------------------------ | ------------------------------------------------------------- | ---------------------------------- |
| `DATE_ATOM`              | Atom standard date format                                     | `2019-01-18T14:13:03+00:00`        |
| `DATE_COOKIE`            | HTTP Cookies format                                           | `Fri, 18 Jan 2019 14:13:03 UTC`    |
| `DATE_ISO8601`           | ISO-8601 format                                               | `2019-01-18T14:13:03+0000`         |
| `DATE_RFC822`            | RFC 822 standard format                                       | `Fri, 18 Jan 2019 14:13:03 +0000`  |
| `DATE_RFC850`            | RFC 850 format                                                | `Friday, 18-Jan-19 14:13:03 UTC`   |
| `DATE_RFC1036`           | RFC 1036 format                                               | `Friday, 18-Jan-19 14:13:03 +0000` |
| `DATE_RFC1123`           | RFC 1123 format                                               | `Fri, 18 Jan 2019 14:13:03 +0000`  |
| `DATE_RFC2822`           | RFC 2822 format                                               | `Fri, 18 Jan 2019 14:13:03 +0000`  |
| `DATE_RFC3339`           | Same as `DATE_ATOM` (added in PHP 5.1.3)                      | `2019-01-18T14:13:03+00:00`        |
| `DATE_RFC3339_EXTENDED`  | Extended RFC 3339 format (added in PHP 7.0.0)                 | `2019-01-18T16:34:01.000+00:00`    |
| `DATE_RSS`               | RSS format                                                    | `Fri, 18 Jan 2019 14:13:03 +0000`  |
| `DATE_W3C`               | World Wide Web Consortium (W3C) format                        | `2019-01-18T14:13:03+00:00`        |
| `SUNFUNCS_RET_TIMESTAMP` | Returns a timestamp (added in PHP 5.1.2)                      | *(e.g. `1579355583`)*              |
| `SUNFUNCS_RET_STRING`    | Returns sunrise/sunset as hours\:minutes (added in PHP 5.1.2) | `09:41`                            |
| `SUNFUNCS_RET_DOUBLE`    | Returns sunrise/sunset as a float number (added in PHP 5.1.2) | `9.75`                             |


---

# PHP Directory Functions

| **Function**  | **Description**                                                    |
| ------------- | ------------------------------------------------------------------ |
| `chdir()`     | Changes the current working directory                              |
| `chroot()`    | Changes the root directory (must be run as root)                   |
| `closedir()`  | Closes a directory handle                                          |
| `dir()`       | Returns an instance of the `Directory` class                       |
| `getcwd()`    | Returns the current working directory                              |
| `opendir()`   | Opens a directory handle for use with `readdir()` and `closedir()` |
| `readdir()`   | Reads and returns an entry from an open directory handle           |
| `rewinddir()` | Resets the directory handle to the beginning of the directory      |
| `scandir()`   | Returns an array of files and directories inside the given path    

---

# PHP Error Handling & Logging Configuration

| **Directive**            | **Default** | **Description**                                                                                                       | **Changeable**   |
| ------------------------ | ----------- | --------------------------------------------------------------------------------------------------------------------- | ---------------- |
| `error_reporting`        | `NULL`      | Sets which PHP errors are reported (integer value or named constants like `E_ALL`)                                    | `PHP_INI_ALL`    |
| `display_errors`         | `"1"`       | Shows errors on screen. ❗ Should be `Off` on production systems.                                                      | `PHP_INI_ALL`    |
| `display_startup_errors` | `"0"`       | Shows errors that occur during PHP's startup. Useful for debugging only.                                              | `PHP_INI_ALL`    |
| `log_errors`             | `"0"`       | Logs errors to server's error log or file specified in `error_log`. 🔒 Use in production instead of `display_errors`  | `PHP_INI_ALL`    |
| `log_errors_max_len`     | `"1024"`    | Max length (in bytes) for each logged error. Use `0` for unlimited. Affects logs, screen output, and `$php_errormsg`. | `PHP_INI_ALL`    |
| `ignore_repeated_errors` | `"0"`       | Avoid logging the same error from the same file/line repeatedly.                                                      | `PHP_INI_ALL`    |
| `ignore_repeated_source` | `"0"`       | Avoid logging repeated errors from different files or lines.                                                          | `PHP_INI_ALL`    |
| `report_memleaks`        | `"1"`       | Displays memory leak reports from Zend Memory Manager.                                                                | `PHP_INI_ALL`    |
| `track_errors`           | `"0"`       | Enables `$php_errormsg` variable to hold the last error message.                                                      | `PHP_INI_ALL`    |
| `html_errors`            | `"1"`       | Wraps error messages in HTML. Set to `"0"` if sending plain text or JSON output.                                      | `PHP_INI_ALL`    |
| `xmlrpc_errors`          | `"0"`       | Converts errors to XML-RPC fault responses (used in XML-RPC servers).                                                 | `PHP_INI_SYSTEM` |
| `xmlrpc_error_number`    | `"0"`       | Value used for XML-RPC faultCode.                                                                                     | `PHP_INI_ALL`    |
| `docref_root`            | `""`        | Base URL for PHP manual references in error messages. (e.g. `/phpmanual/`)                                            | `PHP_INI_ALL`    |
| `docref_ext`             | `""`        | File extension for manual links (e.g. `.html`, `.php`).                                                               | `PHP_INI_ALL`    |
| `error_prepend_string`   | `NULL`      | String to prepend to every error message.                                                                             | `PHP_INI_ALL`    |
| `error_append_string`    | `NULL`      | String to append to every error message.                                                                              | `PHP_INI_ALL`    |
| `error_log`              | `NULL`      | Path to the log file or set to `"syslog"` to use the system logger. Must be writable by the server.                   | `PHP_INI_ALL`    |

---

### 🔧 Changeable Modes Explained:

* `PHP_INI_ALL`: Can be set in `php.ini`, `.htaccess`, or at runtime with `ini_set()`.
* `PHP_INI_SYSTEM`: Can only be set in `php.ini` or web server config.

---

## PHP Error and Logging Functions

| **Function**                  | **Description**                                                                 |
| ----------------------------- | ------------------------------------------------------------------------------- |
| `debug_backtrace()`           | Generates a backtrace (useful for debugging call stacks)                        |
| `debug_print_backtrace()`     | Prints a backtrace directly (usually for debugging output)                      |
| `error_clear_last()`          | Clears the last error recorded by PHP                                           |
| `error_get_last()`            | Returns an associative array of the last error (or `NULL` if no error exists)   |
| `error_log()`                 | Sends an error message to a log file, email, or system log                      |
| `error_reporting()`           | Gets or sets which PHP errors are reported (e.g., `E_ALL`, `E_NOTICE`, etc.)    |
| `restore_error_handler()`     | Restores the previously defined error handler                                   |
| `restore_exception_handler()` | Restores the previously defined exception handler                               |
| `set_error_handler()`         | Defines a custom function for handling errors                                   |
| `set_exception_handler()`     | Defines a custom function for handling uncaught exceptions                      |
| `trigger_error()`             | Triggers a user-level error (`E_USER_NOTICE`, `E_USER_WARNING`, `E_USER_ERROR`) |
| `user_error()`                | Alias of `trigger_error()` — creates a user-defined error                       |

---

## PHP Predefined Error & Logging Constants

| **Value** | **Constant**          | **Type**            | **Description**                                                                                            |
| --------- | --------------------- | ------------------- | ---------------------------------------------------------------------------------------------------------- |
| `1`       | `E_ERROR`             | Fatal Error         | Fatal run-time errors. Script execution is **halted**.                                                     |
| `2`       | `E_WARNING`           | Warning             | Run-time warnings. Script continues.                                                                       |
| `4`       | `E_PARSE`             | Parse Error         | Compile-time parse errors from the **parser** only.                                                        |
| `8`       | `E_NOTICE`            | Notice              | Run-time notices. Could indicate possible bugs.                                                            |
| `16`      | `E_CORE_ERROR`        | Core Fatal Error    | Fatal errors during **PHP startup**. Script halts.                                                         |
| `32`      | `E_CORE_WARNING`      | Core Warning        | Non-fatal warnings during **PHP startup**. Script continues.                                               |
| `64`      | `E_COMPILE_ERROR`     | Compile Fatal Error | Fatal compile-time errors from the **Zend Engine**.                                                        |
| `128`     | `E_COMPILE_WARNING`   | Compile Warning     | Non-fatal compile-time warnings from the **Zend Engine**.                                                  |
| `256`     | `E_USER_ERROR`        | User Fatal Error    | User-generated fatal errors (via `trigger_error()`). Script halts.                                         |
| `512`     | `E_USER_WARNING`      | User Warning        | User-generated non-fatal warnings (via `trigger_error()`). Script continues.                               |
| `1024`    | `E_USER_NOTICE`       | User Notice         | User-generated notices (via `trigger_error()`).                                                            |
| `2048`    | `E_STRICT`            | Code Suggestions    | Suggests best practices and forward compatibility improvements. *(Not included in `E_ALL` before PHP 5.4)* |
| `4096`    | `E_RECOVERABLE_ERROR` | Catchable Error     | Fatal error that can be caught. If uncaught, script aborts. *(Since PHP 5.2)*                              |
| `8192`    | `E_DEPRECATED`        | Deprecation Warning | Warns about code that won't work in future PHP versions. *(Since PHP 5.3)*                                 |
| `16384`   | `E_USER_DEPRECATED`   | User Deprecation    | User-generated deprecation warning via `trigger_error()`. *(Since PHP 5.3)*                                |
| `32767`   | `E_ALL`               | All Errors          | Reports **all errors and warnings**, except `E_STRICT` prior to PHP 5.4.                                   |

---

### Tips:

* Use `error_reporting(E_ALL)` in development to catch everything.
* Avoid `display_errors = On` in production; use `log_errors` instead.
* Combine constants using bitwise OR:

  ```php
  error_reporting(E_ERROR | E_WARNING | E_PARSE);
  ```

---

# PHP Exception Object

Exceptions are objects used to represent **errors or unexpected behavior** in your code. They are thrown with the `throw` statement and caught using `try...catch`.

The `Exception` class provides several **methods** to access detailed error information:

| **Method**           | **Description**                                                                |
| -------------------- | ------------------------------------------------------------------------------ |
| `__construct()`      | The constructor for the Exception object. Accepts message, code, and previous. |
| `getMessage()`       | Returns the exception **message** — a string describing the error.             |
| `getCode()`          | Returns the **user-defined exception code** (if provided).                     |
| `getFile()`          | Returns the **filename** where the exception was thrown.                       |
| `getLine()`          | Returns the **line number** where the exception occurred.                      |
| `getPrevious()`      | Returns the **previous exception**, if the current one was chained.            |
| `getTrace()`         | Returns an **array** of the stack trace when the exception was thrown.         |
| `getTraceAsString()` | Returns the **stack trace** as a **string** (human-readable).                  |

---

# PHP Runtime Configuration (Filesystem Functions)

These settings control how file handling and stream wrappers behave in PHP.

| **Name**                   | **Default** | **Description**                                                                                        | **Changeable Level** |
| -------------------------- | ----------- | ------------------------------------------------------------------------------------------------------ | -------------------- |
| `allow_url_fopen`          | `"1"`       | Enables URL-aware fopen wrappers (e.g., `http://`, `ftp://`) for file functions like `fopen()`.        | `PHP_INI_SYSTEM`     |
| `allow_url_include`        | `"0"`       | Allows `include/require` to access remote files via URL. ⚠️ Risky – should remain off in production.   | `PHP_INI_SYSTEM`     |
| `user_agent`               | `NULL`      | Sets the **user agent** string used in HTTP requests (e.g., `fopen("http://...")`).                    | `PHP_INI_ALL`        |
| `default_socket_timeout`   | `"60"`      | Sets the **default timeout (in seconds)** for socket-based streams like `fsockopen()`.                 | `PHP_INI_ALL`        |
| `from`                     | `""`        | Sets the **email address** used in `From:` header for HTTP/FTP requests.                               | `PHP_INI_ALL`        |
| `auto_detect_line_endings` | `"0"`       | When `"1"`, PHP **auto-detects line endings** (Unix `\n`, Mac `\r`, Windows `\r\n`) in file functions. | `PHP_INI_ALL`        |
| `sys_temp_dir`             | `""`        | Path to directory where **temporary files** are stored (`tempnam()`, `tmpfile()` etc.).                | `PHP_INI_SYSTEM`     |

---

### Changeable Levels Explained

| **Directive**    | **Where It Can Be Set**                           |
| ---------------- | ------------------------------------------------- |
| `PHP_INI_SYSTEM` | Only in `php.ini`, `.htaccess`, or server config. |
| `PHP_INI_ALL`    | Anywhere – including `ini_set()` at runtime.      |


---

## PHP Filesystem Runtime Configuration

These settings control how PHP interacts with files, streams, and remote resources via functions like `fopen()`, `file()`, `fgets()`, etc.

| **Directive**              | **Default** | **Description**                                                                                                                                  | **Changeable**   |
| -------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| `allow_url_fopen`          | `"1"`       | Allows `fopen()` and similar functions to access **URLs** (e.g., `http://`, `ftp://`). Disabling improves security.                              | `PHP_INI_SYSTEM` |
| `allow_url_include`        | `"0"`       | Allows `include` and `require` to load files via URLs. ⚠️ **High security risk**, should generally remain disabled.                              | `PHP_INI_SYSTEM` |
| `user_agent`               | `NULL`      | Sets the **User-Agent** string for HTTP requests made by `fopen()` or `file_get_contents()` when using URLs.                                     | `PHP_INI_ALL`    |
| `default_socket_timeout`   | `"60"`      | Sets the default **timeout in seconds** for socket-based streams (e.g., network connections).                                                    | `PHP_INI_ALL`    |
| `from`                     | `""`        | Sets the **email address** used in FTP "anonymous login" or `From:` header in HTTP requests via `ftp://` or `http://` wrappers.                  | `PHP_INI_ALL`    |
| `auto_detect_line_endings` | `"0"`       | When enabled (`"1"`), PHP automatically detects line endings (Unix, Windows, Mac) when reading text files using `fgets()` or `file()`.           | `PHP_INI_ALL`    |
| `sys_temp_dir`             | `""`        | Directory path used for **temporary files** (`tmpfile()`, `tempnam()`, etc.). Useful for redirecting temp storage to secure or large partitions. | `PHP_INI_SYSTEM` |

---

### Configuration Levels

* **PHP\_INI\_SYSTEM**: Must be set in `php.ini`, `.htaccess`, or server configuration.
* **PHP\_INI\_ALL**: Can be set in scripts using `ini_set()` at runtime.

---

#  PHP Filesystem Functions Cheat Sheet

---

### **File Path & Metadata**

| Function                | Description                      |
| ----------------------- | -------------------------------- |
| `basename()`            | Returns filename from path       |
| `dirname()`             | Returns directory part of path   |
| `pathinfo()`            | Returns info about file path     |
| `realpath()`            | Returns absolute pathname        |
| `realpath_cache_get()`  | Gets realpath cache entries      |
| `realpath_cache_size()` | Gets realpath cache size         |
| `fnmatch()`             | Matches filename to pattern      |
| `glob()`                | Returns files matching a pattern |

---

###  **File Read/Write Operations**

| Function               | Description                       |
| ---------------------- | --------------------------------- |
| `fopen()`              | Opens a file or URL               |
| `fclose()`             | Closes an open file               |
| `fread()`              | Reads from file (binary-safe)     |
| `fwrite()` / `fputs()` | Writes to file (binary-safe)      |
| `file_get_contents()`  | Reads file into a string          |
| `file_put_contents()`  | Writes string to a file           |
| `file()`               | Reads file into array             |
| `readfile()`           | Outputs file contents             |
| `fgetc()`              | Gets a character from file        |
| `fgets()`              | Gets a line from file             |
| `fgetcsv()`            | Parses a CSV line                 |
| `fputcsv()`            | Writes a CSV line                 |
| `fscanf()`             | Parses formatted input            |
| `fpassthru()`          | Writes remaining buffer to output |
| `fseek()`              | Sets file pointer position        |
| `ftell()`              | Gets file pointer position        |
| `rewind()`             | Resets file pointer to start      |
| `ftruncate()`          | Truncates file to length          |
| `fflush()`             | Flushes buffered output           |

---

###  **File Information**

| Function        | Description                    |
| --------------- | ------------------------------ |
| `file_exists()` | Checks if file or dir exists   |
| `filesize()`    | Returns file size              |
| `filetype()`    | Returns type (file, dir, link) |
| `fileatime()`   | Last access time               |
| `filectime()`   | Last change time               |
| `filemtime()`   | Last modification time         |
| `fileowner()`   | User ID of file owner          |
| `filegroup()`   | Group ID of file owner         |
| `fileinode()`   | Inode number                   |
| `fileperms()`   | File permissions               |
| `stat()`        | File status info               |
| `lstat()`       | Like stat(), but for symlinks  |
| `fstat()`       | Status of open file            |
| `linkinfo()`    | Info about hard link           |

---

###  **File Type Checks**

| Function                           | Description                      |
| ---------------------------------- | -------------------------------- |
| `is_dir()`                         | Is it a directory?               |
| `is_file()`                        | Is it a regular file?            |
| `is_link()`                        | Is it a symbolic link?           |
| `is_executable()`                  | Is file executable?              |
| `is_readable()`                    | Is file readable?                |
| `is_writable()` / `is_writeable()` | Is file writable?                |
| `is_uploaded_file()`               | Was file uploaded via HTTP POST? |

---

### **Create/Modify Files**

| Function                | Description                        |
| ----------------------- | ---------------------------------- |
| `copy()`                | Copies file                        |
| `rename()`              | Renames file or directory          |
| `unlink()` / `delete()` | Deletes file                       |
| `touch()`               | Sets access/mod time               |
| `umask()`               | Sets default file permission mask  |
| `tempnam()`             | Creates unique temp file           |
| `tmpfile()`             | Creates temp file & returns handle |
| `mkdir()`               | Creates directory                  |
| `rmdir()`               | Removes directory                  |
| `move_uploaded_file()`  | Moves uploaded file                |

---

### **File Ownership & Permissions**

| Function           | Description              |
| ------------------ | ------------------------ |
| `chmod()`          | Changes permissions      |
| `chown()`          | Changes owner            |
| `chgrp()`          | Changes group            |
| `lchown()`         | Changes symlink owner    |
| `lchgrp()`         | Changes symlink group    |
| `flock()`          | File locking             |
| `clearstatcache()` | Clears file status cache |

---

### **Links and Symlinks**

| Function     | Description            |
| ------------ | ---------------------- |
| `link()`     | Creates hard link      |
| `symlink()`  | Creates symbolic link  |
| `readlink()` | Gets target of symlink |

---

### **Pipes & Streams**

| Function            | Description                          |
| ------------------- | ------------------------------------ |
| `popen()`           | Opens pipe process                   |
| `pclose()`          | Closes pipe                          |
| `set_file_buffer()` | Alias of `stream_set_write_buffer()` |

---

### **INI Parsing**

| Function             | Description                     |
| -------------------- | ------------------------------- |
| `parse_ini_file()`   | Parses `.ini` file into array   |
| `parse_ini_string()` | Parses `.ini` string into array |

---

## Notes:

* Functions like `delete()` are just aliases or old references for `unlink()`.
* `fgetss()` was deprecated in PHP 7.3 and removed in PHP 8. Use `strip_tags()` separately if needed.
* Some functions behave differently across platforms (e.g., symlink support on Windows).


---

# PHP Filter Runtime Configuration (`php.ini`)

These settings influence how PHP filters input data from **`$_GET`, `$_POST`, `$_COOKIE`, `$_REQUEST`,** and **`$_SERVER`** superglobals.

| **Directive**          | **Default Value** | **Description**                                                                                                            | **Changeable**   |
| ---------------------- | ----------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| `filter.default`       | `"unsafe_raw"`    | Sets a **default filter** for superglobal input (`$_GET`, `$_POST`, etc.).<br>Use filter name like `string`, `email`, etc. | `PHP_INI_PERDIR` |
| `filter.default_flags` | `NULL`            | Applies **flags** to the default filter.<br>For example: `FILTER_FLAG_NO_ENCODE_QUOTES`                                    | `PHP_INI_PERDIR` |

---

### Details

#### `filter.default`

* Filters **all input data** automatically.
* The default `unsafe_raw` means: **no filtering is applied**.
* Example values:

  * `string`
  * `email`
  * `int`
  * `unsafe_raw`
* Example `php.ini` usage:

  ```ini
  filter.default = string
  ```

#### `filter.default_flags`

* Works **only** when `filter.default` is set.
* Common flags:

  * `FILTER_FLAG_STRIP_LOW`
  * `FILTER_FLAG_STRIP_HIGH`
  * `FILTER_FLAG_NO_ENCODE_QUOTES`
* Example:

  ```ini
  filter.default_flags = FILTER_FLAG_STRIP_LOW | FILTER_FLAG_STRIP_HIGH
  ```

---

### Configuration Level

| Level            | Description                                                                                     |
| ---------------- | ----------------------------------------------------------------------------------------------- |
| `PHP_INI_PERDIR` | Can be set in `php.ini`, `.htaccess`, or `httpd.conf`, but **not** at runtime using `ini_set()` |

---

### Security Tip

Unless you **know exactly what you're doing**, it's better to:

* **Manually filter input** using `filter_input()`, `filter_var()`, or proper validation libraries.
* Avoid setting `filter.default` globally, as it can lead to **confusing bugs** or **over-filtered input**.

---

## PHP Filter Functions Cheat Sheet

| **Function**           | **Description**                                                                        |
| ---------------------- | -------------------------------------------------------------------------------------- |
| `filter_has_var()`     | Checks whether a variable of a specified **input type** (e.g. `INPUT_GET`) exists      |
| `filter_id()`          | Returns the **filter ID** of a given **filter name** (used internally by PHP)          |
| `filter_input()`       | Fetches a single external variable and **filters** it (e.g. from `$_GET`, `$_POST`)    |
| `filter_input_array()` | Fetches **multiple external variables** and filters them using an **array of filters** |
| `filter_list()`        | Returns an **array of all supported filter names**                                     |
| `filter_var()`         | Filters a **single variable** (not necessarily from user input)                        |
| `filter_var_array()`   | Filters **multiple variables** in an **associative array**                             |

---

# PHP Predefined Filter Constants

### Input Types (Superglobals)

| Constant       | Description                     |
| -------------- | ------------------------------- |
| `INPUT_POST`   | POST variables (`$_POST`)       |
| `INPUT_GET`    | GET variables (`$_GET`)         |
| `INPUT_COOKIE` | COOKIE variables (`$_COOKIE`)   |
| `INPUT_ENV`    | Environment variables (`$_ENV`) |
| `INPUT_SERVER` | Server variables (`$_SERVER`)   |

---

### Validation Filters

| Constant                  | Description                       |
| ------------------------- | --------------------------------- |
| `FILTER_VALIDATE_BOOLEAN` | Validates a boolean               |
| `FILTER_VALIDATE_EMAIL`   | Validates an email address        |
| `FILTER_VALIDATE_FLOAT`   | Validates a float                 |
| `FILTER_VALIDATE_INT`     | Validates an integer              |
| `FILTER_VALIDATE_IP`      | Validates an IP address           |
| `FILTER_VALIDATE_MAC`     | Validates a MAC address           |
| `FILTER_VALIDATE_REGEXP`  | Validates against a regex pattern |
| `FILTER_VALIDATE_URL`     | Validates a URL                   |

---

### Sanitizing Filters

| Constant                        | Description                                      |
| ------------------------------- | ------------------------------------------------ |
| `FILTER_SANITIZE_EMAIL`         | Removes illegal characters from email            |
| `FILTER_SANITIZE_ENCODED`       | Encodes special characters                       |
| `FILTER_SANITIZE_NUMBER_FLOAT`  | Removes all but digits, `+`, `-`, `.`, `e`, `E`  |
| `FILTER_SANITIZE_NUMBER_INT`    | Removes all but digits, `+`, `-`                 |
| `FILTER_SANITIZE_SPECIAL_CHARS` | Removes special HTML characters                  |
| `FILTER_SANITIZE_STRING`        | Removes tags and special characters (Deprecated) |
| `FILTER_SANITIZE_URL`           | Removes illegal characters from a URL            |
| `FILTER_SANITIZE_ADD_SLASHES`   | Adds slashes to escape characters                |
| `FILTER_SANITIZE_MAGIC_QUOTES`  | Applies `addslashes()` (Deprecated/Removed)      |
| `FILTER_SANITIZE_STRIPPED`      | Alias of `FILTER_SANITIZE_STRING` (Deprecated)   |
| `FILTER_UNSAFE_RAW`             | Does nothing unless flags are used               |
| `FILTER_CALLBACK`               | Call a user-defined function                     |

---

### Flags for Filters

| Constant                        | Description                                   |
| ------------------------------- | --------------------------------------------- |
| `FILTER_FLAG_NONE`              | No special flags                              |
| `FILTER_FLAG_ALLOW_OCTAL`       | Accept octal format                           |
| `FILTER_FLAG_ALLOW_HEX`         | Accept hex format (e.g., `0x1A`)              |
| `FILTER_FLAG_STRIP_LOW`         | Strip ASCII < 32                              |
| `FILTER_FLAG_STRIP_HIGH`        | Strip ASCII > 127                             |
| `FILTER_FLAG_ENCODE_LOW`        | Encode ASCII < 32                             |
| `FILTER_FLAG_ENCODE_HIGH`       | Encode ASCII > 127                            |
| `FILTER_FLAG_ENCODE_AMP`        | Encode `&` as `&amp;`                         |
| `FILTER_FLAG_NO_ENCODE_QUOTES`  | Don't encode `'` and `"`                      |
| `FILTER_FLAG_EMPTY_STRING_NULL` | Convert empty strings to `NULL` (rarely used) |
| `FILTER_FLAG_ALLOW_FRACTION`    | Allow `.` in floats                           |
| `FILTER_FLAG_ALLOW_THOUSAND`    | Allow `,` in numbers                          |
| `FILTER_FLAG_ALLOW_SCIENTIFIC`  | Allow scientific notation (`1e10`)            |
| `FILTER_FLAG_PATH_REQUIRED`     | Require path in URL                           |
| `FILTER_FLAG_QUERY_REQUIRED`    | Require query string in URL                   |
| `FILTER_FLAG_IPV4`              | Only allow IPv4 addresses                     |
| `FILTER_FLAG_IPV6`              | Only allow IPv6 addresses                     |
| `FILTER_FLAG_NO_RES_RANGE`      | Disallow reserved IP ranges                   |
| `FILTER_FLAG_NO_PRIV_RANGE`     | Disallow private IP ranges                    |
| `FILTER_FLAG_EMAIL_UNICODE`     | Allow Unicode in email local part             |

---

### Filter Behavior Modifiers

| Constant                 | Description                                   |
| ------------------------ | --------------------------------------------- |
| `FILTER_REQUIRE_SCALAR`  | Input must be scalar (not an array or object) |
| `FILTER_REQUIRE_ARRAY`   | Input must be an array                        |
| `FILTER_FORCE_ARRAY`     | Force input into an array                     |
| `FILTER_NULL_ON_FAILURE` | Return `NULL` on failure (instead of `false`) |

---

### PHP Runtime Configuration

#### **Date/Time (php.ini settings)**

| Name                     | Description                                  | Default     | Version  |
| ------------------------ | -------------------------------------------- | ----------- | -------- |
| `date.timezone`          | Default timezone for all date/time functions | `""`        | PHP 5.1+ |
| `date.default_latitude`  | Used by `date_sunrise()` & `date_sunset()`   | `"31.7667"` | PHP 5.0+ |
| `date.default_longitude` | Same as above                                | `"35.2333"` | PHP 5.0+ |
| `date.sunrise_zenith`    | Zenith angle for sunrise                     | `"90.83"`   | PHP 5.0+ |
| `date.sunset_zenith`     | Zenith angle for sunset                      | `"90.83"`   | PHP 5.0+ |

---

#### **Filesystem (php.ini settings)**

| Name                       | Default | Description                         | Changeable       |
| -------------------------- | ------- | ----------------------------------- | ---------------- |
| `allow_url_fopen`          | `"1"`   | Allows URL-based file access        | `PHP_INI_SYSTEM` |
| `allow_url_include`        | `"0"`   | Include files via URL               | `PHP_INI_SYSTEM` |
| `user_agent`               | `NULL`  | User agent string for HTTP/FTP      | `PHP_INI_ALL`    |
| `default_socket_timeout`   | `"60"`  | Timeout for socket streams          | `PHP_INI_ALL`    |
| `from`                     | `""`    | Email for anonymous FTP/HTTP        | `PHP_INI_ALL`    |
| `auto_detect_line_endings` | `"0"`   | Detects line endings (Unix/DOS/Mac) | `PHP_INI_ALL`    |
| `sys_temp_dir`             | `""`    | Temporary directory path            | `PHP_INI_SYSTEM` |

---

#### **Filter Extension (php.ini settings)**

| Name                   | Description                    | Default        | Changeable       |
| ---------------------- | ------------------------------ | -------------- | ---------------- |
| `filter.default`       | Default filter for input types | `"unsafe_raw"` | `PHP_INI_PERDIR` |
| `filter.default_flags` | Flags for the default filter   | `NULL`         | `PHP_INI_PERDIR` |

---

### PHP Filter Functions

| Function               | Description                            |
| ---------------------- | -------------------------------------- |
| `filter_has_var()`     | Checks if input type/variable exists   |
| `filter_id()`          | Returns filter ID by name              |
| `filter_input()`       | Gets external input & filters it       |
| `filter_input_array()` | Same as above, but for multiple inputs |
| `filter_list()`        | Lists all available filters            |
| `filter_var()`         | Filters a single variable              |
| `filter_var_array()`   | Filters multiple variables             |

---

### 📌 Predefined Filter Constants

#### 🔹 **Input Types**

* `INPUT_GET`, `INPUT_POST`, `INPUT_COOKIE`, `INPUT_ENV`, `INPUT_SERVER`

#### 🔹 **Validation Filters**

* `FILTER_VALIDATE_BOOLEAN`, `FILTER_VALIDATE_EMAIL`, `FILTER_VALIDATE_FLOAT`, `FILTER_VALIDATE_INT`, `FILTER_VALIDATE_IP`, `FILTER_VALIDATE_MAC`, `FILTER_VALIDATE_REGEXP`, `FILTER_VALIDATE_URL`

#### 🔹 **Sanitizing Filters**

* `FILTER_SANITIZE_EMAIL`, `FILTER_SANITIZE_ENCODED`, `FILTER_SANITIZE_NUMBER_FLOAT`, `FILTER_SANITIZE_NUMBER_INT`, `FILTER_SANITIZE_SPECIAL_CHARS`, `FILTER_SANITIZE_URL`, `FILTER_UNSAFE_RAW`

#### 🔹 **Flags**

* `FILTER_FLAG_STRIP_LOW`, `FILTER_FLAG_STRIP_HIGH`, `FILTER_FLAG_ENCODE_LOW`, `FILTER_FLAG_ENCODE_HIGH`, `FILTER_FLAG_ALLOW_FRACTION`, `FILTER_FLAG_PATH_REQUIRED`, `FILTER_NULL_ON_FAILURE`, etc.

---

# PHP FTP Functions

| Function                        | Description                        |
| ------------------------------- | ---------------------------------- |
| `ftp_connect()`                 | Open an FTP connection             |
| `ftp_ssl_connect()`             | Open a secure FTP connection       |
| `ftp_login()`                   | Log into FTP server                |
| `ftp_put()` / `ftp_get()`       | Upload / Download file             |
| `ftp_close()` / `ftp_quit()`    | Close connection                   |
| `ftp_chdir()` / `ftp_cdup()`    | Change directory / move to parent  |
| `ftp_pwd()`                     | Get current directory              |
| `ftp_mkdir()` / `ftp_rmdir()`   | Create / remove directory          |
| `ftp_delete()` / `ftp_rename()` | Delete / rename file               |
| `ftp_rawlist()` / `ftp_nlist()` | List files with/without details    |
| `ftp_pasv()`                    | Toggle passive mode                |
| `ftp_exec()` / `ftp_raw()`      | Execute raw FTP command            |
| `ftp_size()` / `ftp_mdtm()`     | Get file size / last modified time |
| `ftp_alloc()`                   | Reserve space for upload           |

---

### **PHP Predefined FTP Constants**

| Constant     | Type  | Description                                                   |
| ------------ | ----- | ------------------------------------------------------------- |
| `FTP_ASCII`  | `int` | Use ASCII mode for file transfer (text files)                 |
| `FTP_BINARY` | `int` | Use Binary mode for file transfer (images, executables, etc.) |
| `FTP_IMAGE`  | `int` | Alias of `FTP_BINARY`                                         |
| `FTP_TEXT`   | `int` | Alias of `FTP_ASCII`                                          |

---

#### Transfer Control

| Constant         | Type  | Description                                         |
| ---------------- | ----- | --------------------------------------------------- |
| `FTP_AUTORESUME` | `int` | Automatically resume interrupted uploads/downloads  |
| `FTP_AUTOSEEK`   | `int` | Automatically seek to resume position in local file |

---

#### Asynchronous Transfer States

| Constant       | Type  | Description                           |
| -------------- | ----- | ------------------------------------- |
| `FTP_FAILED`   | `int` | Async transfer failed                 |
| `FTP_MOREDATA` | `int` | Async transfer is still in progress   |
| `FTP_FINISHED` | `int` | Async transfer completed successfully |

> These are especially used with the **non-blocking FTP functions** like:
>
> * `ftp_nb_get()`
> * `ftp_nb_put()`
> * `ftp_nb_continue()`

---

#### Other Configuration Constants

| Constant             | Type   | Description                                                                     |
| -------------------- | ------ | ------------------------------------------------------------------------------- |
| `FTP_TIMEOUT_SEC`    | `int`  | Used with `ftp_set_option()` to set timeout duration (in seconds)               |
| `FTP_USEPASVADDRESS` | `bool` | Set with `ftp_set_option()` to control if the IP from the PASV response is used |

---

# PHP JSON Extension

JSON (JavaScript Object Notation) is a lightweight data-interchange format. PHP offers native support through its **JSON extension** (enabled by default since PHP 5.2.0).

---

## PHP JSON Functions

| Function                | Description                                                                                                     |
| ----------------------- | --------------------------------------------------------------------------------------------------------------- |
| `json_encode()`         | Converts PHP data (arrays, objects, etc.) to a JSON string                                                      |
| `json_decode()`         | Converts a JSON string into a PHP variable                                                                      |
| `json_last_error()`     | Returns an integer representing the last error that occurred (if any) during `json_encode()` or `json_decode()` |
| `json_last_error_msg()` | Returns a human-readable string describing the last error                                                       |

---

## Error Constants (used with `json_last_error()`)

| Constant                           | Meaning                                      |
| ---------------------------------- | -------------------------------------------- |
| `JSON_ERROR_NONE`                  | No error has occurred                        |
| `JSON_ERROR_DEPTH`                 | Maximum stack depth exceeded                 |
| `JSON_ERROR_STATE_MISMATCH`        | Invalid/malformed JSON                       |
| `JSON_ERROR_CTRL_CHAR`             | Unexpected control character                 |
| `JSON_ERROR_SYNTAX`                | Syntax error                                 |
| `JSON_ERROR_UTF8`                  | Malformed UTF-8 characters (PHP 5.3+)        |
| `JSON_ERROR_RECURSION`             | Recursive references in value (PHP 5.5+)     |
| `JSON_ERROR_INF_OR_NAN`            | NAN or INF values (PHP 5.5+)                 |
| `JSON_ERROR_UNSUPPORTED_TYPE`      | Unsupported type (e.g., resource) (PHP 5.5+) |
| `JSON_ERROR_INVALID_PROPERTY_NAME` | Invalid property name (PHP 7.0+)             |
| `JSON_ERROR_UTF16`                 | Malformed UTF-16 characters (PHP 7.0+)       |

---

## Encoding Options (used with `json_encode()`)

| Constant                          | Description                                          |
| --------------------------------- | ---------------------------------------------------- |
| `JSON_HEX_TAG`                    | Convert `<` and `>` to `\u003C` and `\u003E`         |
| `JSON_HEX_AMP`                    | Convert `&` to `\u0026`                              |
| `JSON_HEX_APOS`                   | Convert `'` to `\u0027`                              |
| `JSON_HEX_QUOT`                   | Convert `"` to `\u0022`                              |
| `JSON_FORCE_OBJECT`               | Output objects instead of arrays                     |
| `JSON_NUMERIC_CHECK`              | Encode numeric strings as numbers                    |
| `JSON_PRETTY_PRINT`               | Format output with whitespace for readability        |
| `JSON_UNESCAPED_SLASHES`          | Don’t escape `/` characters                          |
| `JSON_PARTIAL_OUTPUT_ON_ERROR`    | Output partial data on encoding errors               |
| `JSON_PRESERVE_ZERO_FRACTION`     | Preserve `0.0` instead of converting to `0`          |
| `JSON_UNESCAPED_LINE_TERMINATORS` | Don't escape new lines (`\u2028`, `\u2029`)          |
| `JSON_INVALID_UTF8_IGNORE`        | Ignore invalid UTF-8 characters                      |
| `JSON_INVALID_UTF8_SUBSTITUTE`    | Replace invalid UTF-8 with replacement character (�) |
| `JSON_THROW_ON_ERROR`             | Throw `JsonException` on error (PHP 7.3+)            |

---

# Question: What are the PHP `libxml` functions and predefined constants, and what do they do?

---

### **PHP libxml Functions**

| Function                              | Description                                                         |
| ------------------------------------- | ------------------------------------------------------------------- |
| `libxml_clear_errors()`               | Clears the libxml error buffer                                      |
| `libxml_disable_entity_loader()`      | Enables the ability to load external entities                       |
| `libxml_get_errors()`                 | Gets all the errors from the libxml error buffer                    |
| `libxml_get_last_error()`             | Gets the last error from the libxml error buffer                    |
| `libxml_set_external_entity_loader()` | Changes the default external entity loader                          |
| `libxml_set_streams_context()`        | Sets the streams context for the next libxml document load or write |
| `libxml_use_internal_errors()`        | Disables standard libxml errors and enables user error handling     |

---

### **PHP Predefined libxml Constants**

#### **General Configuration and Optimization**

| Constant          | Description                                                        |
| ----------------- | ------------------------------------------------------------------ |
| `LIBXML_BIGLINES` | Allows line numbers > 65535 to be reported correctly               |
| `LIBXML_COMPACT`  | Enables small nodes allocation optimization for better performance |

---

#### **DTD Handling**

| Constant          | Description                |
| ----------------- | -------------------------- |
| `LIBXML_DTDATTR`  | Set default DTD attributes |
| `LIBXML_DTDLOAD`  | Load external DTD subset   |
| `LIBXML_DTDVALID` | Validate document with DTD |

---

#### **HTML Specific Parsing**

| Constant                | Description                                               |
| ----------------------- | --------------------------------------------------------- |
| `LIBXML_HTML_NOIMPLIED` | Disable automatic insertion of `<html>` and `<body>` tags |
| `LIBXML_HTML_NODEFDTD`  | Prevent automatic insertion of a default DOCTYPE          |

---

#### **Content Formatting & Tag Control**

| Constant            | Description                                                             |
| ------------------- | ----------------------------------------------------------------------- |
| `LIBXML_NOBLANKS`   | Remove blank nodes                                                      |
| `LIBXML_NOCDATA`    | Convert CDATA nodes to text nodes                                       |
| `LIBXML_NOEMPTYTAG` | Convert empty tags (e.g., `<br/>`) to explicit opening and closing tags |
| `LIBXML_NOXMLDECL`  | Omit the XML declaration when saving documents                          |

---

#### **Security & Networking**

| Constant           | Description                                    |
| ------------------ | ---------------------------------------------- |
| `LIBXML_NOENT`     | Substitute entities                            |
| `LIBXML_NOERROR`   | Suppress error messages                        |
| `LIBXML_NONET`     | Prevent network access while loading documents |
| `LIBXML_NOWARNING` | Suppress warning messages                      |

---

#### **Namespace and Parsing Behavior**

| Constant           | Description                                                         |
| ------------------ | ------------------------------------------------------------------- |
| `LIBXML_NSCLEAN`   | Remove redundant namespace declarations                             |
| `LIBXML_PARSEHUGE` | Allow parsing of large files and nodes by relaxing hardcoded limits |
| `LIBXML_PEDANTIC`  | Enable strict (pedantic) error reporting                            |
| `LIBXML_XINCLUDE`  | Enable XInclude substitution                                        |

---

#### **Error Handling Constants**

| Constant             | Description                  |
| -------------------- | ---------------------------- |
| `LIBXML_ERR_ERROR`   | Indicates recoverable errors |
| `LIBXML_ERR_FATAL`   | Indicates fatal errors       |
| `LIBXML_ERR_NONE`    | Indicates no errors          |
| `LIBXML_ERR_WARNING` | Indicates simple warnings    |

---

#### **Version Constants**

| Constant                | Description                                                      |
| ----------------------- | ---------------------------------------------------------------- |
| `LIBXML_VERSION`        | Returns libxml version number as an integer (e.g., `20617`)      |
| `LIBXML_DOTTED_VERSION` | Returns libxml version as a string (e.g., `2.6.17`)              |
| `LIBXML_SCHEMA_CREATE`  | Create default or fixed value nodes during XSD schema validation |

---

# Question: What are the PHP mail functions, runtime configuration options, and how do they work?

---

### 📧 **PHP Mail Functions**

| Function       | Description                                                     |
| -------------- | --------------------------------------------------------------- |
| `mail()`       | Sends an email directly from a script                           |
| `ezmlm_hash()` | Calculates the hash value needed by EZMLM (mailing list system) |

---

### ⚙️ **Installation & Requirements**

* **Included in Core:** No installation is required. The mail functions are part of the PHP core.
* **Requirement:** A working mail transfer agent (MTA) such as Sendmail or Postfix must be installed and configured.
* **Windows:** Uses SMTP settings from `php.ini`.

---

### 🛠️ **Runtime Configuration Options (php.ini)**

| Name                | Default Value                | Description                                                                                | Changeable       |
| ------------------- | ---------------------------- | ------------------------------------------------------------------------------------------ | ---------------- |
| `mail.add_x_header` | `"0"`                        | Adds `X-PHP-Originating-Script` with the UID and filename of the script (PHP ≥ 5.3.0)      | `PHP_INI_PERDIR` |
| `mail.log`          | `NULL`                       | Logs all `mail()` calls, including script path, line, recipient, and headers (PHP ≥ 5.3.0) | `PHP_INI_PERDIR` |
| `SMTP`              | `"localhost"`                | **Windows only:** DNS name or IP address of the SMTP server                                | `PHP_INI_ALL`    |
| `smtp_port`         | `"25"`                       | **Windows only:** SMTP server port (PHP ≥ 4.3.0)                                           | `PHP_INI_ALL`    |
| `sendmail_from`     | `NULL`                       | **Windows only:** "From" address used when sending mail with `mail()`                      | `PHP_INI_ALL`    |
| `sendmail_path`     | `"/usr/sbin/sendmail -t -i"` | Path to the sendmail program. Overrides `SMTP`, `smtp_port`, and `sendmail_from` if set    | `PHP_INI_SYSTEM` |

---

# Question: What are the PHP math functions and predefined constants?

---

### 🧮 **PHP Math Functions**

| Function          | Description                                        |
| ----------------- | -------------------------------------------------- |
| `abs()`           | Returns the absolute (positive) value of a number  |
| `acos()`          | Returns the arc cosine of a number                 |
| `acosh()`         | Returns the inverse hyperbolic cosine              |
| `asin()`          | Returns the arc sine of a number                   |
| `asinh()`         | Returns the inverse hyperbolic sine                |
| `atan()`          | Returns the arc tangent of a number (in radians)   |
| `atan2()`         | Returns the arc tangent of two variables x and y   |
| `atanh()`         | Returns the inverse hyperbolic tangent             |
| `base_convert()`  | Converts a number between arbitrary bases          |
| `bindec()`        | Converts binary to decimal                         |
| `ceil()`          | Rounds a number **up** to the nearest integer      |
| `cos()`           | Returns the cosine of a number                     |
| `cosh()`          | Returns the hyperbolic cosine                      |
| `decbin()`        | Converts decimal to binary                         |
| `dechex()`        | Converts decimal to hexadecimal                    |
| `decoct()`        | Converts decimal to octal                          |
| `deg2rad()`       | Converts degrees to radians                        |
| `exp()`           | Calculates e raised to the power of a number       |
| `expm1()`         | Returns `exp(x) - 1`                               |
| `floor()`         | Rounds a number **down** to the nearest integer    |
| `fmod()`          | Returns the remainder of x divided by y            |
| `getrandmax()`    | Returns the largest value `rand()` can return      |
| `hexdec()`        | Converts hexadecimal to decimal                    |
| `hypot()`         | Calculates the hypotenuse of a right triangle      |
| `intdiv()`        | Performs integer division                          |
| `is_finite()`     | Checks if a number is finite                       |
| `is_infinite()`   | Checks if a number is infinite                     |
| `is_nan()`        | Checks if a value is 'Not-a-Number'                |
| `lcg_value()`     | Generates a pseudo-random float between 0 and 1    |
| `log()`           | Returns the natural logarithm (base e) of a number |
| `log10()`         | Returns the base-10 logarithm                      |
| `log1p()`         | Returns `log(1 + number)`                          |
| `max()`           | Returns the highest value from an array or list    |
| `min()`           | Returns the lowest value from an array or list     |
| `mt_getrandmax()` | Returns the largest value `mt_rand()` can return   |
| `mt_rand()`       | Generates a better-quality pseudo-random number    |
| `mt_srand()`      | Seeds the Mersenne Twister random number generator |
| `octdec()`        | Converts octal to decimal                          |
| `pi()`            | Returns the value of Pi                            |
| `pow()`           | Raises a number to the power of another            |
| `rad2deg()`       | Converts radians to degrees                        |
| `rand()`          | Generates a random integer                         |
| `round()`         | Rounds a floating-point number                     |
| `sin()`           | Returns the sine of a number                       |
| `sinh()`          | Returns the hyperbolic sine                        |
| `sqrt()`          | Returns the square root                            |
| `srand()`         | Seeds the `rand()` generator                       |
| `tan()`           | Returns the tangent                                |
| `tanh()`          | Returns the hyperbolic tangent                     |

---

### 🔢 **PHP Predefined Math Constants**

#### General Constants

| Constant | Value | Description  |
| -------- | ----- | ------------ |
| `INF`    | `INF` | Infinity     |
| `NAN`    | `NAN` | Not a number |

---

#### Euler, Logarithms, and Exponentials

| Constant   | Value                    | Description                        |
| ---------- | ------------------------ | ---------------------------------- |
| `M_E`      | `2.7182818284590452354`  | The base of natural logarithms (e) |
| `M_EULER`  | `0.57721566490153286061` | Euler–Mascheroni constant          |
| `M_LNPI`   | `1.14472988584940017414` | `ln(π)`                            |
| `M_LN2`    | `0.69314718055994530942` | `ln(2)`                            |
| `M_LN10`   | `2.30258509299404568402` | `ln(10)`                           |
| `M_LOG2E`  | `1.4426950408889634074`  | `log₂(e)`                          |
| `M_LOG10E` | `0.43429448190325182765` | `log₁₀(e)`                         |

---

#### Pi and Related Constants

| Constant | Value                    | Description |
| -------- | ------------------------ | ----------- |
| `M_PI`   | `3.14159265358979323846` | Pi          |
| `M_PI_2` | `1.57079632679489661923` | Pi / 2      |
| `M_PI_4` | `0.78539816339744830962` | Pi / 4      |
| `M_1_PI` | `0.31830988618379067154` | 1 / Pi      |
| `M_2_PI` | `0.63661977236758134308` | 2 / Pi      |

---

#### Square Roots

| Constant     | Value                    | Description    |
| ------------ | ------------------------ | -------------- |
| `M_SQRTPI`   | `1.77245385090551602729` | √π             |
| `M_2_SQRTPI` | `1.12837916709551257390` | 2 / √π         |
| `M_SQRT1_2`  | `0.70710678118654752440` | √(1/2) or 1/√2 |
| `M_SQRT2`    | `1.41421356237309504880` | √2             |
| `M_SQRT3`    | `1.73205080756887729352` | √3             |

---

#### Rounding Modes

| Constant              | Value | Description                      |
| --------------------- | ----- | -------------------------------- |
| `PHP_ROUND_HALF_UP`   | `1`   | Round halves up (away from zero) |
| `PHP_ROUND_HALF_DOWN` | `2`   | Round halves down (toward zero)  |
| `PHP_ROUND_HALF_EVEN` | `3`   | Round halves toward even number  |
| `PHP_ROUND_HALF_ODD`  | `4`   | Round halves toward odd number   |

---

# Question: What are the commonly used PHP miscellaneous functions, configuration options, and constants?

## 🔧 PHP Miscellaneous Introduction

The **miscellaneous functions** in PHP are functions that don’t belong to other specific categories. They are available in the PHP core — no installation is required.

---

## ⚙️ Runtime Configuration

These `php.ini` settings affect the behavior of miscellaneous functions.

### Miscellaneous `php.ini` Configuration Options

| Name                | Description                                                         | Default     | Changeable       |
| ------------------- | ------------------------------------------------------------------- | ----------- | ---------------- |
| `ignore_user_abort` | `FALSE` means script terminates if the client connection is aborted | `"0"`       | `PHP_INI_ALL`    |
| `highlight.string`  | Color used to highlight PHP strings                                 | `"#DD0000"` | `PHP_INI_ALL`    |
| `highlight.comment` | Color used to highlight PHP comments                                | `"#FF8000"` | `PHP_INI_ALL`    |
| `highlight.keyword` | Color for highlighting PHP keywords (e.g., parentheses, semicolon)  | `"#007700"` | `PHP_INI_ALL`    |
| `highlight.default` | Default syntax color                                                | `"#0000BB"` | `PHP_INI_ALL`    |
| `highlight.html`    | Color for highlighting HTML code                                    | `"#000000"` | `PHP_INI_ALL`    |
| `browscap`          | Path to the browser capabilities file (e.g., `browscap.ini`)        | `NULL`      | `PHP_INI_SYSTEM` |

---

## 🛠️ PHP Miscellaneous Functions

| Function                 | Description                                               |
| ------------------------ | --------------------------------------------------------- |
| `connection_aborted()`   | Checks if the client has disconnected                     |
| `connection_status()`    | Returns the current connection status                     |
| `connection_timeout()`   | **Deprecated**. Checks if the script has timed out        |
| `constant()`             | Returns the value of a constant                           |
| `define()`               | Defines a constant                                        |
| `defined()`              | Checks if a constant is defined                           |
| `die()`                  | Alias of `exit()`                                         |
| `eval()`                 | Evaluates a string as PHP code                            |
| `exit()`                 | Exits the script and optionally prints a message          |
| `get_browser()`          | Returns user browser capabilities based on `browscap.ini` |
| `__halt_compiler()`      | Halts compiler execution                                  |
| `highlight_file()`       | Outputs a file with PHP syntax highlighting               |
| `highlight_string()`     | Outputs a string with PHP syntax highlighting             |
| `hrtime()`               | Returns high-resolution system time                       |
| `ignore_user_abort()`    | Allows script to continue if user aborts connection       |
| `pack()`                 | Packs data into a binary string                           |
| `php_strip_whitespace()` | Returns PHP source with comments and whitespace removed   |
| `show_source()`          | Alias of `highlight_file()`                               |
| `sleep()`                | Delays execution for specified seconds                    |
| `sys_getloadavg()`       | Gets system load average                                  |
| `time_nanosleep()`       | Delays execution for seconds and nanoseconds              |
| `time_sleep_until()`     | Pauses execution until the specified timestamp            |
| `uniqid()`               | Generates a unique identifier                             |
| `unpack()`               | Unpacks data from a binary string                         |
| `usleep()`               | Delays execution for specified microseconds               |

---

## 📌 PHP Predefined Miscellaneous Constants

| Constant                   | Description                                  |
| -------------------------- | -------------------------------------------- |
| `CONNECTION_ABORTED`       | Indicates the connection was aborted         |
| `CONNECTION_NORMAL`        | Indicates a normal connection                |
| `CONNECTION_TIMEOUT`       | Indicates a connection timeout               |
| `__COMPILER_HALT_OFFSET__` | Used with `__halt_compiler()` to mark offset |

---

# Question: What are the commonly used PHP MySQLi functions?

## 📘 PHP MySQLi Introduction

The **MySQLi (MySQL Improved)** extension allows access to MySQL database servers using an object-oriented or procedural interface.

* Designed for **MySQL version 4.1.13+**
* Introduced in **PHP 5.0.0**
* MySQL Native Driver (mysqlnd) added in **PHP 5.3.0**

🔗 For installation: [MySQLi Installation](http://php.net/manual/en/mysqli.installation.php)
🔧 For configuration: [MySQLi Configuration](http://php.net/manual/en/mysqli.configuration.php)

---

## 🛠️ PHP MySQLi Functions

### 🧾 Connection and Initialization

| Function                 | Description                                  |
| ------------------------ | -------------------------------------------- |
| `connect()`              | Opens a new connection to the MySQL server   |
| `real_connect()`         | Opens a new connection with enhanced options |
| `init()`                 | Initializes MySQLi and returns a resource    |
| `options()`              | Sets extra connect options                   |
| `ssl_set()`              | Sets SSL parameters                          |
| `ping()`                 | Pings a server connection                    |
| `select_db()`            | Selects a default database                   |
| `change_user()`          | Changes the user of the connection           |
| `close()`                | Closes the connection                        |
| `kill()`                 | Kills a MySQL thread                         |
| `thread_id()`            | Returns the thread ID                        |
| `thread_safe()`          | Checks if the client is thread-safe          |
| `get_client_info()`      | Returns MySQL client version                 |
| `get_client_version()`   | Version as integer                           |
| `get_client_stats()`     | Returns stats per client process             |
| `get_connection_stats()` | Returns client connection stats              |
| `get_host_info()`        | Returns host info                            |
| `get_proto_info()`       | Returns MySQL protocol version               |
| `get_server_info()`      | Returns MySQL server version                 |
| `get_server_version()`   | Server version as integer                    |

---

### 📊 Querying and Execution

| Function             | Description                                       |
| -------------------- | ------------------------------------------------- |
| `query()`            | Performs a SQL query                              |
| `multi_query()`      | Performs multiple queries                         |
| `next_result()`      | Prepares the next result-set from multi-query     |
| `store_result()`     | Transfers a result-set from last query            |
| `use_result()`       | Retrieves result-set from the last query executed |
| `real_query()`       | Executes a single query                           |
| `reap_async_query()` | Retrieves async query results                     |

---

### 📥 Data Fetching

| Function               | Description                                   |
| ---------------------- | --------------------------------------------- |
| `fetch_assoc()`        | Fetches row as associative array              |
| `fetch_array()`        | Fetches row as associative/numeric/both array |
| `fetch_row()`          | Fetches row as numeric array                  |
| `fetch_all()`          | Fetches all rows                              |
| `fetch_object()`       | Fetches row as an object                      |
| `data_seek()`          | Moves result pointer to a specific row        |
| `fetch_field()`        | Gets next field in result-set                 |
| `fetch_field_direct()` | Metadata for a single field                   |
| `fetch_fields()`       | Array of objects for all fields               |
| `fetch_lengths()`      | Column lengths of current row                 |

---

### 🔐 Transactions and Autocommit

| Function              | Description                      |
| --------------------- | -------------------------------- |
| `autocommit()`        | Enables/disables autocommit mode |
| `begin_transaction()` | Starts a transaction             |
| `commit()`            | Commits current transaction      |
| `rollback()`          | Rolls back current transaction   |

---

### 📌 Miscellaneous Operations

| Function          | Description                         |
| ----------------- | ----------------------------------- |
| `affected_rows()` | Affected rows in previous operation |
| `insert_id()`     | Last inserted ID                    |
| `errno()`         | Last error code                     |
| `error()`         | Last error description              |
| `error_list()`    | List of recent errors               |
| `info()`          | Info about last executed query      |
| `sqlstate()`      | Returns SQLSTATE error code         |
| `warning_count()` | Number of warnings from last query  |

---

### 🧪 Statements and Preparation

| Function      | Description                                |
| ------------- | ------------------------------------------ |
| `prepare()`   | Prepares SQL statement                     |
| `stmt_init()` | Initializes and returns a statement object |

---

### 🧰 Character Sets and Encoding

| Function               | Description                    |
| ---------------------- | ------------------------------ |
| `character_set_name()` | Returns default charset        |
| `get_charset()`        | Returns a character set object |
| `set_charset()`        | Sets the character set         |

---

### 🧩 Debugging and Meta

| Function            | Description                  |
| ------------------- | ---------------------------- |
| `debug()`           | Performs debugging functions |
| `dump_debug_info()` | Dumps debugging information  |
| `stat()`            | Returns system status        |

---

### 📁 Local Infile Handlers

| Function                     | Description                                  |
| ---------------------------- | -------------------------------------------- |
| `set_local_infile_handler()` | Sets a callback for `LOAD DATA LOCAL INFILE` |
| `set_local_infile_default()` | Unsets the user-defined handler              |

---

### 🧾 Polling and Results Handling

| Function         | Description                                  |
| ---------------- | -------------------------------------------- |
| `more_results()` | Checks for more results from `multi_query()` |
| `poll()`         | Polls for activity on MySQL connections      |
| `field_count()`  | Number of columns for last query             |
| `field_seek()`   | Moves cursor to specific field offset        |

---

# Question: What are the commonly used PHP network functions?

## 🌐 PHP Network Introduction

The **PHP Network functions** provide tools for:

* Working with sockets and DNS
* Sending and controlling HTTP headers
* System logging
* Retrieving host and protocol information

✅ **Installation**:
These functions are part of the PHP core — no installation required.

---

## 🛠️ PHP Network Functions

| Function                     | Description                                                |
| ---------------------------- | ---------------------------------------------------------- |
| `checkdnsrr()`               | Checks DNS records for a given host and record type        |
| `closelog()`                 | Closes the connection to the system logger                 |
| `define_syslog_variables()`  | **Deprecated** since PHP 5.3, **removed** in PHP 5.4       |
| `dns_check_record()`         | Alias of `checkdnsrr()`                                    |
| `dns_get_mx()`               | Alias of `getmxrr()`                                       |
| `dns_get_record()`           | Gets DNS resource records for a hostname                   |
| `fsockopen()`                | Opens an Internet or Unix domain socket connection         |
| `gethostbyaddr()`            | Gets domain name for a given IP address                    |
| `gethostbyname()`            | Gets IPv4 address for a given domain name                  |
| `gethostbynamel()`           | Returns list of IPv4 addresses for a domain                |
| `gethostname()`              | Gets the host name of the local machine                    |
| `getmxrr()`                  | Gets MX records for a specified internet host name         |
| `getprotobyname()`           | Returns protocol number for given protocol name            |
| `getprotobynumber()`         | Returns protocol name for a given number                   |
| `getservbyname()`            | Gets port number for a given Internet service and protocol |
| `getservbyport()`            | Gets service name for a given port and protocol            |
| `header()`                   | Sends a raw HTTP header                                    |
| `header_register_callback()` | Registers a callback to run when headers are sent          |
| `header_remove()`            | Removes an HTTP header that was previously set             |
| `headers_list()`             | Lists headers to be sent to the browser                    |
| `headers_sent()`             | Checks whether headers have already been sent and where    |
| `http_response_code()`       | Gets or sets the HTTP response status code                 |
| `inet_ntop()`                | Converts binary IP address to human-readable format        |
| `inet_pton()`                | Converts human-readable IP to binary format                |
| `ip2long()`                  | Converts IPv4 address to a long integer                    |
| `long2ip()`                  | Converts a long integer to an IPv4 address string          |
| `openlog()`                  | Opens a connection to the system logger                    |
| `pfsockopen()`               | Opens a **persistent** socket connection                   |
| `setcookie()`                | Sends a cookie to the client                               |
| `setrawcookie()`             | Sends a cookie without URL encoding                        |
| `socket_get_status()`        | Alias of `stream_get_meta_data()`                          |
| `socket_set_blocking()`      | Alias of `stream_set_blocking()`                           |
| `socket_set_timeout()`       | Alias of `stream_set_timeout()`                            |
| `syslog()`                   | Generates a system log message                             |

---

# Question: What are the commonly used PHP output control functions?

## 🖥️ PHP Output Control Introduction

**Output control** in PHP allows developers to manage **what content is sent to the browser** and **when**. Output can originate from:

* Statements like `echo`, `print`, `print_r`, `printf`
* PHP notices, warnings, or errors
* Any plain text outside PHP `<?php ?>` tags

💡 PHP uses **output buffers** — stacks of memory where output is stored temporarily. You can control this output before it is sent to the browser.

---

## ⚙️ Runtime Configuration (php.ini)

| Name                 | Default                                         | Description                                                                            | Version |
| -------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------- | ------- |
| `output_buffering`   | `"0"`                                           | Enables output buffering by default                                                    | 4       |
| `output_handler`     | `NULL`                                          | Sets the default handler for output buffers                                            | 4       |
| `implicit_flush`     | `"0"`                                           | Sends output to the browser immediately after every output statement                   | 4       |
| `url_rewriter.tags`  | `"a=href,area=href, frame=src,form=,fieldset="` | Defines which HTML tags get rewritten for query strings via `output_add_rewrite_var()` | 4.3     |
| `url_rewriter.hosts` | `$_SERVER['HTTP_HOST']` (current host only)     | Allows URL rewriting only for the current host unless other hosts specified            | 7.1     |

---

## 🧰 PHP Output Control Functions

| Function                      | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ |
| `flush()`                     | Sends any buffered output to the browser                     |
| `ob_clean()`                  | Clears the current topmost output buffer without sending it  |
| `ob_end_clean()`              | Clears and ends the current output buffer                    |
| `ob_end_flush()`              | Sends and then ends the current output buffer                |
| `ob_flush()`                  | Sends the contents of the output buffer and leaves it active |
| `ob_get_clean()`              | Returns and clears the output buffer                         |
| `ob_get_contents()`           | Returns contents of the current output buffer                |
| `ob_get_flush()`              | Returns and sends the output buffer, then clears it          |
| `ob_get_length()`             | Returns the length (in bytes) of the output buffer           |
| `ob_get_level()`              | Returns the number of active output buffers                  |
| `ob_get_status()`             | Returns an array with buffer status details                  |
| `ob_gzhandler()`              | Used to gzip compress output buffer (used with `ob_start()`) |
| `ob_implicit_flush()`         | Enables or disables implicit flushing                        |
| `ob_list_handlers()`          | Lists all registered output handler callbacks                |
| `ob_start()`                  | Starts a new output buffer                                   |
| `output_add_rewrite_var()`    | Adds query string parameters to URLs in output               |
| `output_reset_rewrite_vars()` | Removes variables added by `output_add_rewrite_var()`        |

---

# Question: What are PHP Regular Expressions and how are they used?

---

## 🔍 PHP Regular Expression Introduction

Regular expressions allow you to **search**, **match**, and **replace** patterns in strings.

---

## ⚙️ Installation

The PHP regular expression functions are part of the **PHP core**.
**No additional installation is required**.

---

## 🧪 Runtime Configuration (`php.ini` Settings)

These `php.ini` directives can limit the time or memory used when evaluating regex patterns:

| Name                   | Default     | Description                                             | Changeable    |
| ---------------------- | ----------- | ------------------------------------------------------- | ------------- |
| `pcre.backtrack_limit` | `"1000000"` | Max number of backtracks allowed (since PHP 5.2)        | `PHP_INI_ALL` |
| `pcre.recursion_limit` | `"100000"`  | Max recursion depth allowed (since PHP 5.2)             | `PHP_INI_ALL` |
| `pcre.jit`             | `"1"`       | Enables PCRE's just-in-time compilation (since PHP 7.0) | `PHP_INI_ALL` |

---

## 🧩 PHP Regular Expression Functions

| Function                        | Description                                                  |
| ------------------------------- | ------------------------------------------------------------ |
| `preg_filter()`                 | Replace matches **only if found**, returns string or array   |
| `preg_grep()`                   | Returns array of elements that match pattern                 |
| `preg_last_error()`             | Returns last error code from regex evaluation                |
| `preg_match()`                  | Finds **first match** of a pattern in a string               |
| `preg_match_all()`              | Finds **all matches** of a pattern                           |
| `preg_replace()`                | Replaces matches of pattern(s) with replacement(s)           |
| `preg_replace_callback()`       | Replaces matches using a **callback function**               |
| `preg_replace_callback_array()` | Uses an **array of callbacks**, one per pattern              |
| `preg_split()`                  | Splits string into array using pattern matches as delimiters |
| `preg_quote()`                  | Escapes regex metacharacters with backslashes                |

---

## ✏️ Regular Expression Modifiers

Modifiers alter how the regex engine interprets the pattern:

| Modifier | Description                                                                   |
| -------- | ----------------------------------------------------------------------------- |
| `i`      | Case-insensitive search                                                       |
| `m`      | Multiline mode: `^` and `$` match start/end of each line, not just the string |
| `u`      | Enables UTF-8 pattern matching                                                |

---

## 🔣 Regular Expression Patterns

### Bracket Expressions

| Expression | Description                                   |
| ---------- | --------------------------------------------- |
| `[abc]`    | Matches any **one character** inside brackets |
| `[^abc]`   | Matches any character **not** inside brackets |
| `[0-9]`    | Matches any **digit from 0 to 9**             |

---

## ⚡ Metacharacters

These characters have special meanings in patterns:

| Metacharacter | Description                                                       |                                                         |     |         |
| ------------- | ----------------------------------------------------------------- | ------------------------------------------------------- | --- | ------- |
| \`            | \`                                                                | Alternation: matches **any one** of the patterns (\`cat | dog | fish\`) |
| `.`           | Matches **any one character**                                     |                                                         |     |         |
| `^`           | Matches **start of string** (`^Hello`)                            |                                                         |     |         |
| `$`           | Matches **end of string** (`World$`)                              |                                                         |     |         |
| `\d`          | Matches any **digit**                                             |                                                         |     |         |
| `\s`          | Matches any **whitespace**                                        |                                                         |     |         |
| `\b`          | Matches **word boundary** (`\bword\b`)                            |                                                         |     |         |
| `\uxxxx`      | Matches **Unicode character** specified by 4-digit hex (`\u00E9`) |                                                         |     |         |

---

## 🔁 Quantifiers

Quantifiers define **how many** times a pattern can match:

| Quantifier | Description                            |
| ---------- | -------------------------------------- |
| `n+`       | One or more `n`                        |
| `n*`       | Zero or more `n`                       |
| `n?`       | Zero or one `n`                        |
| `n{x}`     | Exactly `x` occurrences of `n`         |
| `n{x,y}`   | Between `x` and `y` occurrences of `n` |
| `n{x,}`    | At least `x` occurrences of `n`        |

> 💡 Use a **backslash (\\)** to escape special characters.
> Example: to match `?` one or more times, use `'/\?+/'`.

---

# Question: What are PHP SimpleXML functions and how are they used?

---

## 📖 PHP SimpleXML Introduction

**SimpleXML** is an extension that allows PHP developers to **easily read, parse, and manipulate XML data**.

* It converts XML documents into **PHP objects** that can be iterated like arrays.
* It is most effective when the structure of the XML document is already known.

---

## ⚙️ Installation

Since **PHP 5**, the SimpleXML extension is built into PHP core.
**No additional installation is required.**

---

## 🔧 PHP SimpleXML Functions

| Function                   | Description                                                       |
| -------------------------- | ----------------------------------------------------------------- |
| `__construct()`            | Creates a new `SimpleXMLElement` object                           |
| `__toString()`             | Returns the string content of an element                          |
| `addAttribute()`           | Appends an attribute to the SimpleXML element                     |
| `addChild()`               | Appends a child element to the SimpleXML element                  |
| `asXML()`                  | Returns a well-formed XML string from a `SimpleXMLElement` object |
| `attributes()`             | Returns the attributes/values of an element                       |
| `children()`               | Returns the children of a specified node                          |
| `count()`                  | Counts the number of children of a specified node                 |
| `getDocNamespaces()`       | Returns namespaces declared in the document                       |
| `getName()`                | Returns the name of an element                                    |
| `getNamespaces()`          | Returns namespaces used in the document                           |
| `registerXPathNamespace()` | Creates a namespace context for the next XPath query              |
| `saveXML()`                | Alias of `asXML()`, returns XML as a string                       |
| `simplexml_import_dom()`   | Converts a DOM node to a `SimpleXMLElement` object                |
| `simplexml_load_file()`    | Loads an XML file and returns it as a `SimpleXMLElement` object   |
| `simplexml_load_string()`  | Parses an XML string into a `SimpleXMLElement` object             |
| `xpath()`                  | Runs an XPath query on XML data                                   |

---

## 🔁 PHP SimpleXML Iteration Functions

| Function        | Description                                             |
| --------------- | ------------------------------------------------------- |
| `current()`     | Returns the current element in the iteration            |
| `getChildren()` | Returns the child elements of the current element       |
| `hasChildren()` | Checks whether the current element has children         |
| `key()`         | Returns the XML tag name (key) of the current element   |
| `next()`        | Moves the internal pointer to the next element          |
| `rewind()`      | Rewinds the internal pointer to the first element       |
| `valid()`       | Checks if the current element in the iteration is valid |

---

# Question: What are PHP Stream functions and how are they used?

---

## 🔍 PHP Stream Introduction

**Streams** in PHP provide a way to **generalize file, network, compression**, and other I/O operations using a **unified set of functions**.

* A **stream** is a resource object that can be **read from or written to in a linear fashion**.
* A **wrapper** provides protocol-specific behavior, telling the stream how to handle protocols like `http://`, `ftp://`, `php://`, etc.

---

## ⚙️ Installation

All **PHP stream functions** are **built into the PHP core**.
No additional installation is needed.

---

## 🛠️ PHP Stream Functions

| Function                         | Description                                                                               |
| -------------------------------- | ----------------------------------------------------------------------------------------- |
| `set_socket_blocking()`          | **Deprecated** in PHP 5.4 and **removed** in PHP 7.0. Use `stream_set_blocking()` instead |
| `stream_bucket_prepend()`        | Prepends a bucket to a stream filter chain                                                |
| `stream_context_create()`        | Creates a stream context                                                                  |
| `stream_context_get_default()`   | Retrieves the default stream context                                                      |
| `stream_context_get_options()`   | Gets options from a stream context                                                        |
| `stream_context_get_params()`    | Retrieves parameters from a context                                                       |
| `stream_context_set_default()`   | Sets the default stream context                                                           |
| `stream_context_set_options()`   | Sets options on a stream context                                                          |
| `stream_context_set_params()`    | Sets parameters on a stream context                                                       |
| `stream_copy_to_stream()`        | Copies data from one stream to another                                                    |
| `stream_filter_append()`         | Appends a filter to a stream                                                              |
| `stream_filter_prepend()`        | Prepends a filter to a stream                                                             |
| `stream_filter_register()`       | Registers a user-defined stream filter                                                    |
| `stream_filter_remove()`         | Removes a filter from a stream                                                            |
| `stream_get_contents()`          | Reads remainder of a stream into a string                                                 |
| `stream_get_filters()`           | Lists all registered filters                                                              |
| `stream_get_line()`              | Gets a line from the stream                                                               |
| `stream_get_meta_data()`         | Retrieves metadata about a stream                                                         |
| `stream_get_transports()`        | Lists available socket transports                                                         |
| `stream_get_wrappers()`          | Lists all registered stream wrappers                                                      |
| `stream_is_local()`              | Checks if a stream is local                                                               |
| `stream_isatty()`                | Checks if a stream is a terminal                                                          |
| `stream_notification_callback()` | A callback for stream notifications during operations like `fopen()`                      |
| `stream_register_wrapper()`      | Alias of `stream_wrapper_register()`                                                      |
| `stream_resolve_include_path()`  | Resolves a filename against the include path                                              |
| `stream_select()`                | Runs `select()` system call on streams to detect readability or writability               |
| `stream_set_blocking()`          | Sets blocking or non-blocking mode on a stream                                            |
| `stream_set_chunk_size()`        | Sets the chunk size of a stream                                                           |
| `stream_set_read_buffer()`       | Sets read buffer size on a stream                                                         |
| `stream_set_timeout()`           | Sets timeout on a stream                                                                  |
| `stream_set_write_buffer()`      | Sets write buffer size on a stream                                                        |
| `stream_socket_accept()`         | Accepts a connection on a socket created by `stream_socket_server()`                      |
| `stream_socket_client()`         | Opens a socket connection to a remote address                                             |
| `stream_socket_enable_crypto()`  | Turns encryption on/off for a stream                                                      |
| `stream_socket_get_name()`       | Gets local or remote name of a socket                                                     |
| `stream_socket_pair()`           | Creates a pair of connected sockets                                                       |
| `stream_socket_recvfrom()`       | Receives data from a socket                                                               |
| `stream_socket_sendto()`         | Sends a message to a socket                                                               |
| `stream_socket_server()`         | Creates a server socket                                                                   |
| `stream_socket_shutdown()`       | Shuts down a socket connection                                                            |
| `stream_supports_lock()`         | Checks if a stream supports locking via `flock()`                                         |
| `stream_wrapper_register()`      | Registers a custom stream wrapper                                                         |
| `stream_wrapper_restore()`       | Restores a previously unregistered wrapper                                                |
| `stream_wrapper_unregister()`    | Unregisters a wrapper                                                                     |

---

# 📄 PHP XML Parser Functions

---

## ❓ What are PHP XML Parser Functions?

The **PHP XML Parser** functions allow developers to **parse** (but not validate) **XML documents** using an event-driven model provided by the **Expat** parser.

XML is a structured data format commonly used for data interchange. PHP’s XML extension is ideal for reading and processing such documents efficiently.

---

## ⚙️ Parser Engine: Expat

* **Expat** is an **event-based** XML parser.
* It triggers callback functions when certain parsing events occur (like start tags, end tags, and character data).
* **Note**: Expat is a **non-validating** parser and **ignores DTDs**.
* If the XML is **not well-formed**, an **error** will occur.

---

## 🧩 Installation

These functions are **part of PHP core**, so **no installation** is required.

---

## 🔧 PHP XML Parser Functions

| Function                                   | Description                                              |
| ------------------------------------------ | -------------------------------------------------------- |
| `utf8_decode()`                            | Converts a UTF-8 string to ISO-8859-1                    |
| `utf8_encode()`                            | Converts an ISO-8859-1 string to UTF-8                   |
| `xml_error_string()`                       | Returns a string description of an XML parser error code |
| `xml_get_current_byte_index()`             | Returns the current byte index from the parser           |
| `xml_get_current_column_number()`          | Returns the current column number of the parser          |
| `xml_get_current_line_number()`            | Returns the current line number of the parser            |
| `xml_get_error_code()`                     | Gets the current error code from the parser              |
| `xml_parse()`                              | Parses an XML document                                   |
| `xml_parse_into_struct()`                  | Parses XML into an associative array                     |
| `xml_parser_create()`                      | Creates a new XML parser instance                        |
| `xml_parser_create_ns()`                   | Creates an XML parser with namespace support             |
| `xml_parser_free()`                        | Frees the memory associated with a parser                |
| `xml_parser_get_option()`                  | Retrieves parser configuration options                   |
| `xml_parser_set_option()`                  | Sets parser configuration options                        |
| `xml_set_character_data_handler()`         | Sets the handler for character data                      |
| `xml_set_default_handler()`                | Sets a default handler for all events                    |
| `xml_set_element_handler()`                | Sets handlers for start and end XML elements             |
| `xml_set_end_namespace_decl_handler()`     | Sets the handler for ending a namespace declaration      |
| `xml_set_external_entity_ref_handler()`    | Sets the handler for external entity references          |
| `xml_set_notation_decl_handler()`          | Sets the handler for notation declarations               |
| `xml_set_object()`                         | Binds parser events to methods of an object              |
| `xml_set_processing_instruction_handler()` | Sets the handler for processing instructions             |
| `xml_set_start_namespace_decl_handler()`   | Sets the handler for starting namespace declarations     |
| `xml_set_unparsed_entity_decl_handler()`   | Sets the handler for unparsed entity declarations        |

---

## 🧮 PHP XML Parser Constants

### 🔴 Error Constants

| Constant                                  | Meaning                               |
| ----------------------------------------- | ------------------------------------- |
| `XML_ERROR_NONE`                          | No error                              |
| `XML_ERROR_NO_MEMORY`                     | Out of memory                         |
| `XML_ERROR_SYNTAX`                        | Syntax error in XML                   |
| `XML_ERROR_NO_ELEMENTS`                   | No elements found                     |
| `XML_ERROR_INVALID_TOKEN`                 | Invalid token found                   |
| `XML_ERROR_UNCLOSED_TOKEN`                | Token was not properly closed         |
| `XML_ERROR_PARTIAL_CHAR`                  | Partial character read                |
| `XML_ERROR_TAG_MISMATCH`                  | Mismatched tag                        |
| `XML_ERROR_DUPLICATE_ATTRIBUTE`           | Duplicate attribute in tag            |
| `XML_ERROR_JUNK_AFTER_DOC_ELEMENT`        | Garbage after document element        |
| `XML_ERROR_PARAM_ENTITY_REF`              | Invalid parameter entity reference    |
| `XML_ERROR_UNDEFINED_ENTITY`              | Reference to undefined entity         |
| `XML_ERROR_RECURSIVE_ENTITY_REF`          | Recursive entity reference            |
| `XML_ERROR_ASYNC_ENTITY`                  | Asynchronous entity                   |
| `XML_ERROR_BAD_CHAR_REF`                  | Bad character reference               |
| `XML_ERROR_BINARY_ENTITY_REF`             | Binary entity reference               |
| `XML_ERROR_ATTRIBUTE_EXTERNAL_ENTITY_REF` | External entity in attribute          |
| `XML_ERROR_MISPLACED_XML_PI`              | Misplaced XML processing instruction  |
| `XML_ERROR_UNKNOWN_ENCODING`              | Unknown character encoding            |
| `XML_ERROR_INCORRECT_ENCODING`            | Incorrect encoding                    |
| `XML_ERROR_UNCLOSED_CDATA_SECTION`        | CDATA section was not properly closed |
| `XML_ERROR_EXTERNAL_ENTITY_HANDLING`      | External entity handling error        |

---

### ⚙️ Option Constants

| Constant                     | Description                                  |
| ---------------------------- | -------------------------------------------- |
| `XML_OPTION_CASE_FOLDING`    | Toggles uppercasing of element names         |
| `XML_OPTION_TARGET_ENCODING` | Sets output encoding (e.g., UTF-8)           |
| `XML_OPTION_SKIP_TAGSTART`   | Skips characters from the start of tag names |
| `XML_OPTION_SKIP_WHITE`      | Ignores whitespace                           |

---

### ℹ️ Other Constants

| Constant       | Description                                                            |
| -------------- | ---------------------------------------------------------------------- |
| `XML_SAX_IMPL` | The SAX parser implementation name (usually `"expat"` on most systems) |

---
