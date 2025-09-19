# Question: What do logical operators in C# return when evaluating multiple conditions?

**Answer:** They return a Boolean value (`true` or `false`).

---

# Question: Why are logical operators useful in C#?

**Answer:** They help evaluate multiple conditions in decision-making, loops, and data validation.

---

# Question: What does the `&&` operator do in C#?

**Answer:** It performs a logical AND; returns `true` if both operands are true.

---

# Question: What does the `||` operator do in C#?

**Answer:** It performs a logical OR; returns `true` if at least one operand is true.

---

# Question: What does the `!` operator do in C#?

**Answer:** It performs a logical NOT; reverses the logical state of its operand.

---

# Question: If `A = true` and `B = false`, what is `(A && B)`?

**Answer:** False.

---

# Question: If `A = true` and `B = false`, what is `(A || B)`?

**Answer:** True.

---

# Question: If `A = true` and `B = false`, what is `!(A && B)`?

**Answer:** True.

---

# Question: In the example with `a = true` and `b = true`, what is printed when `(a && b)` is evaluated?

**Answer:** `Line 1 - Condition is true`.

---

# Question: In the example with `a = true` and `b = true`, what is printed when `(a || b)` is evaluated?

**Answer:** `Line 2 - Condition is true`.

---

# Question: After changing `a = false` and `b = true`, what output is produced for `(a && b)`?

**Answer:** `Line 3 - Condition is not true`.

---

# Question: After changing `a = false` and `b = true`, what output is produced for `!(a && b)`?

**Answer:** `Line 4 - Condition is true`.

--

# Question: In the scholarship example with `score = 85` and `passedExam = true`, what is printed?

**Answer:** `Eligible for scholarship.`

---

# Question: In the login validation example with `username = "admin"` and `password = "pass123"`, what is printed?

**Answer:** `Login successful.`

---

# Question: What is the recommended way to group multiple logical conditions?

**Answer:** Use parentheses, e.g., `((x && y) || z)`.

---

# Question: How should `if (isReady == false)` be simplified?

**Answer:** `if (!isReady)`.

---

# Question: Why should redundant checks like `if (x == true)` be avoided?

**Answer:** Because `if (x)` is simpler and equivalent.

---

# Question: What should always be tested when combining multiple conditions with logical operators?

**Answer:** Edge cases.

---
