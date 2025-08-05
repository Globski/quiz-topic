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

# Question: List all Sass list functions with their descriptions and examples.

### Sass List Functions

| Function                                     | Description & Example                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `append(list, value, [separator])`           | Adds a single `value` to the end of the `list`. `separator` can be `auto`, `comma`, or `space` (default is `auto`).<br>**Example:** `append((a b c), d)` → `a b c d`<br>**Example:** `append((a b c), (d), comma)` → `a, b, c, d`                                                                                                                            |
| `index(list, value)`                         | Returns the index position of `value` in `list`.<br>**Example:** `index(a b c, b)` → `2`<br>**Example:** `index(a b c, f)` → `null`                                                                                                                                                                                                                          |
| `is-bracketed(list)`                         | Checks whether the `list` has square brackets.<br>**Example:** `is-bracketed([a b c])` → `true`<br>**Example:** `is-bracketed(a b c)` → `false`                                                                                                                                                                                                              |
| `join(list1, list2, [separator, bracketed])` | Appends `list2` to the end of `list1`. `separator` can be `auto`, `comma`, or `space`. `bracketed` can be `auto`, `true`, or `false` (default is `auto`).<br>**Example:** `join(a b c, d e f)` → `a b c d e f`<br>**Example:** `join((a b c), (d e f), comma)` → `a, b, c, d, e, f`<br>**Example:** `join(a b c, d e f, $bracketed: true)` → `[a b c d e f]` |
| `length(list)`                               | Returns the length of the `list`.<br>**Example:** `length(a b c)` → `3`                                                                                                                                                                                                                                                                                      |
| `list-separator(list)`                       | Returns the separator used in the `list` as a string. Can be `"space"` or `"comma"`.<br>**Example:** `list-separator(a b c)` → `"space"`<br>**Example:** `list-separator(a, b, c)` → `"comma"`                                                                                                                                                               |
| `nth(list, n)`                               | Returns the `n`th element in the `list`.<br>**Example:** `nth(a b c, 3)` → `c`                                                                                                                                                                                                                                                                               |
| `set-nth(list, n, value)`                    | Sets the `n`th list element to the specified `value`.<br>**Example:** `set-nth(a b c, 2, x)` → `a x c`                                                                                                                                                                                                                                                       |
| `zip(lists)`                                 | Combines multiple lists into a single multidimensional list.<br>**Example:** `zip(1px 2px 3px, solid dashed dotted, red green blue)` → `1px solid red, 2px dashed green, 3px dotted blue`                                                                                                                                                                    |

---

# Question: List all Sass map functions with their descriptions and examples.

### Sass Map Functions

| Function                   | Description & Example                                                                                                                                                                                                                                                                                      |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `map-get(map, key)`        | Returns the value for the specified `key` in the `map`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`map-get($font-sizes, "small")` → `12px`                                                                                                                       |
| `map-has-key(map, key)`    | Checks whether `map` has the specified `key`. Returns `true` or `false`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`map-has-key($font-sizes, "big")` → `false`                                                                                                   |
| `map-keys(map)`            | Returns a list of all keys in the `map`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`map-keys($font-sizes)` → `"small", "normal", "large"`                                                                                                                        |
| `map-merge(map1, map2)`    | Appends `map2` to the end of `map1`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`$font-sizes2: ("x-large": 30px, "xx-large": 36px)`<br>`map-merge($font-sizes, $font-sizes2)` → `"small": 12px, "normal": 18px, "large": 24px, "x-large": 30px, "xx-large": 36px` |
| `map-remove(map, keys...)` | Removes the specified `keys` from the `map`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`map-remove($font-sizes, "small")` → `("normal": 18px, "large": 24px)`<br>`map-remove($font-sizes, "small", "large")` → `("normal": 18px)`                                |
| `map-values(map)`          | Returns a list of all values in the `map`.<br>**Example:**<br>`$font-sizes: ("small": 12px, "normal": 18px, "large": 24px)`<br>`map-values($font-sizes)` → `12px, 18px, 24px`                                                                                                                              |


---

# Question: List all Sass selector functions with their descriptions and examples.

### Sass Selector Functions

| Function                                            | Description & Example                                                                                                                                                                                                                                    |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `is-superselector(super, sub)`                      | Checks whether the `super` selector matches all the elements that `sub` matches.<br>**Example:**<br>`is-superselector("div", "div.myInput")` → `true`<br>`is-superselector("div.myInput", "div")` → `false`<br>`is-superselector("div", "div")` → `true` |
| `selector-append(selectors)`                        | Appends the second (and third, fourth, etc.) selector to the first selector.<br>**Example:**<br>`selector-append("div", ".myInput")` → `div.myInput`<br>`selector-append(".warning", "__a")` → `.warning__a`                                             |
| `selector-extend(selector, extendee, extender)`     | Extends `extendee` in `selector` with `extender`. *(No example provided)*                                                                                                                                                                                |
| `selector-nest(selectors)`                          | Returns a new selector containing a nested list of CSS selectors based on the list provided.<br>**Example:**<br>`selector-nest("ul", "li")` → `ul li`<br>`selector-nest(".warning", "alert", "div")` → `.warning div, alert div`                         |
| `selector-parse(selector)`                          | Returns a list of strings contained in `selector`, using the same format as the parent selector.<br>**Example:**<br>`selector-parse("h1 .myInput .warning")` → `('h1', '.myInput', '.warning')`                                                          |
| `selector-replace(selector, original, replacement)` | Returns a new selector with `original` replaced by `replacement`.<br>**Example:**<br>`selector-replace("p.warning", "p", "div")` → `div.warning`                                                                                                         |
| `selector-unify(selector1, selector2)`              | Returns a new selector that matches only elements matched by both `selector1` and `selector2`.<br>**Example:**<br>`selector-unify("myInput", ".disabled")` → `myInput.disabled`<br>`selector-unify("p", "h1")` → `null`                                  |
| `simple-selectors(selectors)`                       | Returns a list of the individual selectors in `selectors`.<br>**Example:**<br>`simple-selectors("div.myInput")` → `div`, `.myInput`<br>`simple-selectors("div.myInput:before")` → `div`, `.myInput`, `:before`                                           |

---
