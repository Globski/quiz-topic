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

## ✅ PHP Predefined Date/Time Constants

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

