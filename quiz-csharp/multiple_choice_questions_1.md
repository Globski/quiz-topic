# Question: What do relational operators in C# return when comparing two operands?

**Answer:** They return a Boolean value (`true` or `false`).

---

# Question: Why are relational operators useful in C#?

**Answer:** They are useful for decision-making, loops, and data validation.

---

# Question: What does the `==` operator do in C#?

**Answer:** It checks if the values of two operands are equal; returns `true` if they are equal.

---

# Question: What does the `!=` operator do in C#?

**Answer:** It checks if the values of two operands are not equal; returns `true` if they differ.

---

# Question: What does the `>` operator do in C#?

**Answer:** It checks if the left operand is greater than the right operand; returns `true` if it is.

---

# Question: What does the `<` operator do in C#?

**Answer:** It checks if the left operand is less than the right operand; returns `true` if it is.

---

# Question: What does the `>=` operator do in C#?

**Answer:** It checks if the left operand is greater than or equal to the right operand; returns `true` if the condition is met.

---

# Question: What does the `<=` operator do in C#?

**Answer:** It checks if the left operand is less than or equal to the right operand; returns `true` if the condition is met.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A == B)`?

**Answer:** False.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A != B)`?

**Answer:** True.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A > B)`?

**Answer:** False.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A < B)`?

**Answer:** True.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A >= B)`?

**Answer:** False.

---

# Question: Given `A = 10` and `B = 20`, what is the result of `(A <= B)`?

**Answer:** True.

---

# Question: In the example with `a = 21` and `b = 10`, what output does `(a == b)` produce?

**Answer:** `Line 1 - a is not equal to b`.

---

# Question: In the example with `a = 21` and `b = 10`, what output does `(a < b)` produce?

**Answer:** `Line 2 - a is not less than b`.

---

# Question: In the example with `a = 21` and `b = 10`, what output does `(a > b)` produce?

**Answer:** `Line 3 - a is greater than b`.

---

# Question: After changing `a = 5` and `b = 20`, what does `(a <= b)` output?

**Answer:** `Line 4 - a is either less than or equal to b`.

---

# Question: After changing `a = 5` and `b = 20`, what does `(b >= a)` output?

**Answer:** `Line 5 - b is either greater than or equal to b`.

---

# Question: What is the output of the example with `a = 10` and `b = 5` when using all relational operators in `Console.WriteLine`?

**Answer:**

* `a == b: False`
* `a != b: True`
* `a > b: True`
* `a < b: False`
* `a >= b: True`
* `a <= b: False`

---

# Question: How are relational operators used in a `for` loop example with `for (int i = 1; i <= 5; i++)`?

**Answer:** The operator `<=` controls the loop iterations, printing numbers 1 through 5.

---

# Question: What output is produced by the for-loop example using `i <= 5`?

**Answer:**

* Iteration: 1
* Iteration: 2
* Iteration: 3
* Iteration: 4
* Iteration: 5

---

# Question: What operator should always be used for comparison instead of `=` in C#?

**Answer:** `==`

---

# Question: How should range checks like `5 < x < 10` be written in C#?

**Answer:** Using logical operators: `(x > 5 && x < 10)`.

---

# Question: What method is recommended for checking if a string is empty or null?

**Answer:** `string.IsNullOrEmpty(x)`

---

# Question: Why should you avoid redundant comparisons like `if (x == true)`?

**Answer:** Because `if (x)` is sufficient and more concise.

---
