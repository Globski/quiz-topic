# Question: List all Sass string functions with their descriptions and examples.

### Sass String Functions

| Function                            | Description & Example                                                                                                                                                              |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `quote(string)`                     | Adds quotes to `string`, and returns the result.<br>**Example:** `quote(Hello world!)`<br>**Result:** `"Hello world!"`                                                             |
| `str-index(string, substring)`      | Returns the index of the first occurrence of the `substring` within `string`.<br>**Example:** `str-index("Hello world!", "H")`<br>**Result:** `1`                                  |
| `str-insert(string, insert, index)` | Returns `string` with `insert` inserted at the specified `index` position.<br>**Example:** `str-insert("Hello world!", " wonderful", 6)`<br>**Result:** `"Hello wonderful world!"` |
| `str-length(string)`                | Returns the length of `string` (in characters).<br>**Example:** `str-length("Hello world!")`<br>**Result:** `12`                                                                   |
| `str-slice(string, start, end)`     | Extracts characters from `string`; starts at `start` and ends at `end`, and returns the slice.<br>**Example:** `str-slice("Hello world!", 2, 5)`<br>**Result:** `"ello"`           |
| `to-lower-case(string)`             | Returns a copy of `string` converted to lower case.<br>**Example:** `to-lower-case("Hello World!")`<br>**Result:** `"hello world!"`                                                |
| `to-upper-case(string)`             | Returns a copy of `string` converted to upper case.<br>**Example:** `to-upper-case("Hello World!")`<br>**Result:** `"HELLO WORLD!"`                                                |
| `unique-id()`                       | Returns a unique randomly generated unquoted string (guaranteed to be unique within the current Sass session).<br>**Example:** `unique-id()`<br>**Result:** `tyghefnsv`            |
| `unquote(string)`                   | Removes quotes around `string` (if any), and returns the result.<br>**Example:** `unquote("Hello world!")`<br>**Result:** `Hello world!`                                           |

---

# Question: List all Sass numeric functions with their descriptions and examples.

### Sass Numeric Functions

| Function                 | Description & Example                                                                                                                                                                                  |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `abs(number)`            | Returns the absolute value of `number`.<br>**Example:** `abs(15)` → `15`<br>**Example:** `abs(-15)` → `15`                                                                                             |
| `ceil(number)`           | Rounds `number` up to the nearest integer.<br>**Example:** `ceil(15.20)` → `16`                                                                                                                        |
| `comparable(num1, num2)` | Returns whether `num1` and `num2` are comparable.<br>**Example:** `comparable(15px, 10px)` → `true`<br>**Example:** `comparable(20mm, 1cm)` → `true`<br>**Example:** `comparable(35px, 2em)` → `false` |
| `floor(number)`          | Rounds `number` down to the nearest integer.<br>**Example:** `floor(15.80)` → `15`                                                                                                                     |
| `max(number...)`         | Returns the highest value of several numbers.<br>**Example:** `max(5, 7, 9, 0, -3, -7)` → `9`                                                                                                          |
| `min(number...)`         | Returns the lowest value of several numbers.<br>**Example:** `min(5, 7, 9, 0, -3, -7)` → `-7`                                                                                                          |
| `percentage(number)`     | Converts `number` to a percentage (multiplies by 100).<br>**Example:** `percentage(1.2)` → `120`                                                                                                       |
| `random()`               | Returns a random number between 0 and 1.<br>**Example:** `random()` → `0.45673`                                                                                                                        |
| `random(number)`         | Returns a random integer between 1 and `number`.<br>**Example:** `random(6)` → `4`                                                                                                                     |
| `round(number)`          | Rounds `number` to the nearest integer.<br>**Example:** `round(15.20)` → `15`<br>**Example:** `round(15.80)` → `16`                                                                                    |

---
