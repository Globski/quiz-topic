# Question: What is an f-string in Python?

**Answer:**
An f-string in Python is a string literal prefixed with `f` or `F` that allows embedding expressions within curly braces `{}`. These expressions are evaluated at runtime, making string interpolation concise and efficient.

---

# Question: How do you include dynamic content in an f-string?

**Answer:**
To include dynamic content in an f-string, you place variables or expressions inside curly braces `{}` within the string literal prefixed with `f`. Python evaluates and replaces the expressions with their values at runtime.

---

# Question: What causes a typical f-string error in Python?

**Answer:**
F-string errors often occur due to syntax issues like unmatched braces `{}` or invalid expressions inside the curly braces.

---

# Question: What are some improvements made to f-strings in Python 3.12?

**Answer:**
Python 3.12 improved f-strings by allowing nested expressions and the use of backslashes within the curly braces, removing previous parser limitations.

---

# Question: What were the two main ways to interpolate strings before Python 3.6?

**Answer:**
Before Python 3.6, Python primarily used the modulo operator `%` and the `str.format()` method for string interpolation.

---

# Question: How does the modulo operator `%` work for string interpolation?

**Answer:**
The `%` operator takes a string with conversion specifiers (like `%s`) and an object or tuple of objects. It replaces the specifiers with string representations of the objects.

---

# Question: What is a common limitation or issue when using the `%` operator for tuples?

**Answer:**
When using `%` with a tuple directly, Python may raise a `TypeError` because it treats the tuple as multiple values. Wrapping the tuple in another tuple (single-item tuple) fixes this but is awkward.

---

# Question: What is an advantage of the `.format()` method over the `%` operator?

**Answer:**
The `.format()` method supports Python’s string formatting mini-language and allows positional and keyword arguments for clearer and more flexible interpolation.

---

# Question: How can you specify the order of arguments in `.format()`?

**Answer:**
You can specify order using zero-based indices inside the curly braces, like `{1}` or `{0}`, to change the interpolation order.

---

# Question: How do you use a dictionary with `.format()` for string interpolation?

**Answer:**
You can pass a dictionary and unpack it with `**` in `.format()`, then reference keys inside curly braces, e.g., `"{name} {age}".format(**person_dict)`.

---

# Question: How do f-strings improve readability compared to `.format()`?

**Answer:**
F-strings allow direct embedding of expressions within the string literal without needing method calls, making the code more concise and readable.

---

# Question: Can you embed complex expressions inside f-strings?

**Answer:**
Yes, you can embed any valid Python expression inside `{}`, including function calls, method calls, and comprehensions.

---

# Question: How do you use format specifiers inside an f-string?

**Answer:**
After the expression inside `{}`, include a colon `:` followed by the format specifier, e.g., `{value:.2f}` formats a number with two decimals.

---

# Question: Give an example of formatting a date with an f-string.

**Answer:**
Using a `datetime` object, you can format it like: `f"Date: {date:%m/%d/%Y}"`, which outputs the date as "MM/DD/YYYY".

---

# Question: What do the `!s` and `!r` flags do in f-strings?

**Answer:**
`!s` calls the object's `__str__()` method to get a user-friendly string, while `!r` calls `__repr__()` to get a developer-friendly representation.

---

# Question: What is a self-documenting expression in f-strings and why is it useful?

**Answer:**
Using `{variable=}` in an f-string outputs both the variable name and its value, which is helpful for quick debugging.

---

# Question: How does the performance of f-strings compare to `%` and `.format()`?

**Answer:**
F-strings are generally faster than both the `%` operator and the `.format()` method, making them both concise and efficient.

---

# Question: Can format specifiers themselves be dynamic in f-strings?

**Answer:**
Yes, you can use variables inside format specifiers like `{value:{sep}}`, where `sep` defines the format dynamically.

---


# Question: Why is it important to use different types of quotation marks in f-strings?

**Answer:**
Using different quotation marks (single, double, triple-single, and triple-double) allows flexibility in nesting and inserting strings within f-strings. This helps when embedding quotes or dictionary keys, and supports nested f-strings.

---

# Question: What was the quotation mark limitation in f-strings before Python 3.12?

**Answer:**
Before Python 3.12, you couldn’t reuse the same type of quotation mark in both the f-string and its embedded expressions, leading to syntax errors due to unmatched brackets.

---

# Question: What limited the nesting depth of f-strings before Python 3.12?

**Answer:**
The number of available string delimiters limited f-string nesting depth. You could only nest f-strings as deep as the number of different quote types you could use to differentiate levels.

---

# Question: How did Python 3.12 improve f-string nesting?

**Answer:**
Python 3.12 removed the limitation on reusing quotes, allowing unlimited nesting of f-strings regardless of the type or number of quote delimiters.

---

# Question: What was the limitation of using backslashes in f-strings before Python 3.12?

**Answer:**
Backslashes weren’t allowed inside f-string expressions before Python 3.12, causing syntax errors when using escape sequences like `\n` in curly braces.

---

# Question: How did Python 3.12 change the use of backslashes in f-strings?

**Answer:**
Python 3.12 allowed backslashes in f-string expressions, enabling the use of escape sequences like newline characters directly within the expressions.

---

# Question: Could you use inline comments in f-string expressions before Python 3.12?

**Answer:**
No, using the `#` symbol inside f-string expressions before Python 3.12 would result in a syntax error. Python 3.12 now allows inline comments within expressions.

---

# Question: How did Python 3.12 improve error messages for f-strings?

**Answer:**
Python 3.12, using the PEG parser, provides clearer and more specific error messages for f-string issues, including exact error location and helpful suggestions.

---

# Question: Why might using `.format()` be preferred over f-strings for dictionary interpolation?

**Answer:**
`.format()` can unpack a dictionary using `**` and reference keys by name, resulting in cleaner and more readable code than using dictionary lookups in f-strings.

---

# Question: Why should you avoid f-strings in logging statements?

**Answer:**
F-strings are eagerly evaluated even if the logging level is too low to show the message. Using `%` with logging enables lazy evaluation, improving performance.

---

# Question: Why should f-strings be avoided in SQL query construction?

**Answer:**
Using f-strings or other interpolation methods to build SQL queries directly invites SQL injection. The recommended approach is to use parameterized queries via `%s` placeholders and pass arguments separately.

---

# Question: What’s the safe way to pass parameters in SQL queries in Python?

**Answer:**
Use `%s` placeholders in the query string and pass the parameters as a separate tuple to the `.execute()` method, allowing the database driver to safely handle them.

---

# Question: Which string interpolation method is recommended for internationalization?

**Answer:**
The `.format()` method is recommended because it works well with string templates and allows dynamic insertion of localized content based on user locale.

---

# Question: What tool can help convert old Python strings to f-strings?

**Answer:**
The `flynt` tool can automatically convert `%` and `.format()`-based strings into f-strings in a Python codebase, aiding modernization.

---

# Question: How does the `flynt` tool help in modernizing code?

**Answer:**
`flynt` scans Python files and rewrites older string formatting styles (`%` and `.format()`) as f-strings, improving readability and performance with minimal effort.

---

# Question: Why is Python considered an awesome programming language?

**Answer:**
Python is considered awesome because it's simple, readable, and versatile. It supports multiple programming paradigms, has a large standard library, and is widely used in fields like web development, data science, automation, and AI.

---

# Question: Who created the Python programming language?

**Answer:**
Python was created by Guido van Rossum in the late 1980s and released in 1991.

---

# Question: Who is Guido van Rossum?

**Answer:**
Guido van Rossum is a Dutch programmer best known as the creator of the Python programming language. He served as Python’s "Benevolent Dictator For Life" (BDFL) until stepping down in 2018.

---

# Question: Where does the name ‘Python’ come from?

**Answer:**
The name "Python" was inspired by the British comedy group Monty Python. Guido van Rossum was a fan of their work and wanted a name that was short, unique, and slightly mysterious.

---

# Question: What is the Zen of Python?

**Answer:**
The Zen of Python is a collection of guiding principles for writing computer programs in Python. You can view it by running `import this` in the Python interpreter. It emphasizes simplicity, readability, and explicitness.

---

# Question: How do you use the Python interpreter?

**Answer:**
You can start the Python interpreter by typing `python` or `python3` in the terminal. It allows you to write and execute Python code interactively.

---

# Question: How do you print text and variables in Python?

**Answer:**
You use the `print()` function. For example: `print("Hello")` prints text, and `print(f"Age: {age}")` prints a variable using an f-string.

---

# Question: How do you use strings in Python?

**Answer:**
Strings are sequences of characters enclosed in single, double, or triple quotes. You can concatenate them with `+`, repeat with `*`, and manipulate them with methods like `.upper()`, `.lower()`, and `.split()`.

---

# Question: What are indexing and slicing in Python?

**Answer:**
Indexing accesses a specific character in a string using its position (e.g., `s[0]`). Slicing retrieves a substring using a range of positions (e.g., `s[1:4]`).

---

# Question: What is the official Python coding style and how do you check your code?

**Answer:**
The official style guide for Python is PEP 8. You can check your code for style compliance using the `pycodestyle` tool (formerly known as `pep8`).

---

# Question: What is `pycodestyle` and how is it used?

**Answer:**
`pycodestyle` is a tool that checks Python code against the style conventions defined in PEP 8. It was formerly known as `pep8`. It provides parseable output for editors, supports plugin architecture, and includes a test suite. You can install it using `pip install pycodestyle`. To use it, run commands like `pycodestyle yourfile.py` to see style violations, and options like `--show-source` and `--show-pep8` for more context on the errors.

---

# Question: What command installs `pycodestyle` using pip?

**Answer:**
`$ pip install pycodestyle`

---

# Question: How can you upgrade `pycodestyle` to the latest version?

**Answer:**
`$ pip install --upgrade pycodestyle`

---

# Question: What does the `--first` option do when running `pycodestyle`?

**Answer:**
It shows only the first occurrence of each error.

---

# Question: What error does code `E401` represent in `pycodestyle`?

**Answer:**
E401 indicates "multiple imports on one line."

---

# Question: What option makes `pycodestyle` show the source code and PEP 8 explanation for each error?

**Answer:**
Use `--show-source --show-pep8`

---

# Question: How can you see how many times each error occurred in a directory?

**Answer:**
By using the `--statistics -qq` options.

---

# Question: What does the `--format` option in `pycodestyle` control?

**Answer:**
It sets the output format of the error messages. Options include `default`, `pylint`, and custom formats.

---

# Question: What variables are available when using a custom format with `--format`?

**Answer:**
`path`, `row`, `col`, `code`, and `text`

---

# Question: Where does `pycodestyle` look for user-level configuration on a Unix-like system?

**Answer:**
In `~/.config/pycodestyle` or the directory set by `XDG_CONFIG_HOME/pycodestyle`

---

# Question: What are two files that can be used for project-level configuration?

**Answer:**
`setup.cfg` and `tox.ini`

---

# Question: What does error code `E302` indicate?

**Answer:**
E302 means "expected 2 blank lines, found 1."

---

# Question: Which error code is triggered by a line that is too long?

**Answer:**
E501

---

# Question: What does `pycodestyle --help` display?

**Answer:**
It displays usage information and available command-line options.

---

# Question: Which error indicates "whitespace before '(' "?

**Answer:**
E211

---

# Question: What does the `--diff` option do?

**Answer:**
It reports only lines changed according to the unified diff received on STDIN.

---

# Question: What does the `--max-line-length` option control?

**Answer:**
It sets the maximum allowed length of a line. Default is 79 characters.

---

# Question: What is the significance of the `--ignore=errors` option?

**Answer:**
It allows you to skip specific errors and warnings.

---

# Question: What does error code `E301` mean?

**Answer:**
E301 means "expected 1 blank line, found 0."

---

# Question: How can runtime errors be identified in `pycodestyle`?

**Answer:**
They are identified by error codes starting with `E9`, like `E901` for `SyntaxError`.

---

# Question: What special comment can be used to disable specific checks for a line?

**Answer:**
`# noqa`

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[7:-5])
```

**Answer:**
`is`
Explanation: Index 7 is `'i'`, and `-5` is the fifth character from the end (the space before `'cool'`). The slice `a[7:-5]` returns characters from index 7 up to, but not including, index -5.

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[4])
```

**Answer:**
`o`
Explanation: Indexing starts at 0. Index 4 corresponds to `'o'` in `"Python"`.

---

# Question: What does this command line print?

```python
print(f"{98} Battery street, {'San Francisco'}")
```

**Answer:**
`98 Battery street, San Francisco`
Explanation: f-strings evaluate expressions inside `{}` and insert them into the string.

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[-2])
```

**Answer:**
`o`
Explanation: Negative indexing counts from the end. `-2` is the second last character, which is `'o'`.

---

# Question: What does this command line print?

```python
print("Holberton school")
```

**Answer:**
`Holberton school`

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[7:])
```

**Answer:**
`is cool`
Explanation: Slice from index 7 to the end.

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[0:6])
```

**Answer:**
`Python`
Explanation: Slice from index 0 to index 6 (not including index 6).

---

# Question: What does this command line print?

```python
a = "Python is cool"
print(a[:6])
```

**Answer:**
`Python`
Explanation: This is equivalent to `a[0:6]`.

---

# Question: What does this command line print?

```python
print(f"{98} Battery street")
```

**Answer:**
`98 Battery street`
Explanation: f-string inserts the value `98` into the string.

---

# Question: Write a Shell script that runs a Python script. The Python file name will be saved in the environment variable `$PYFILE`

**Answer:**

```bash
#!/bin/bash
python3 "$PYFILE"
```

Explanation: This script uses `python3` to execute the Python file whose name is stored in the environment variable `PYFILE`.

---
