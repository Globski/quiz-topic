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

## PHP Directory Functions

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

## PHP Error Handling & Logging Configuration

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

## PHP Exception Object

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

## 🛠️ PHP Runtime Configuration (Filesystem Functions)

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

