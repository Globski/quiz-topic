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
