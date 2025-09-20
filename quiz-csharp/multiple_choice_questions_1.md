# Question: What do C# bitwise operators allow you to do?

**Answer:** They allow operations at the binary level by manipulating individual bits of numbers.

---

# Question: What are bitwise operators in C# commonly used for?

**Answer:** Efficient computations, flag operations, hardware interactions, performance optimization, encryption, networking, and system programming.

---

# Question: What does the `&` (Binary AND) operator do in C#?

**Answer:** It copies a bit to the result if it exists in both operands.

---

# Question: Given `A = 60` and `B = 13`, what is `(A & B)` and its binary representation?

**Answer:** `12`, which is `0000 1100`.

---

# Question: What does the `|` (Binary OR) operator do in C#?

**Answer:** It copies a bit if it exists in either operand.

---

# Question: Given `A = 60` and `B = 13`, what is `(A | B)` and its binary representation?

**Answer:** `61`, which is `0011 1101`.

---

# Question: What does the `^` (Binary XOR) operator do in C#?

**Answer:** It sets a bit if it is set in one operand but not both.

---

# Question: Given `A = 60` and `B = 13`, what is `(A ^ B)` and its binary representation?

**Answer:** `49`, which is `0011 0001`.

---

# Question: What does the `~` (Binary Ones Complement) operator do in C#?

**Answer:** It flips all bits (unary operation).

---

# Question: Given `A = 60`, what is `(~A)` and its binary representation?

**Answer:** `-61`, represented as `1100 0011` in 2’s complement.

---

# Question: What does the `<<` (Left Shift) operator do in C#?

**Answer:** It moves the left operand’s value left by the number of bits specified, effectively multiplying by 2^n.

---

# Question: Given `A = 60`, what is `A << 2` and its binary representation?

**Answer:** `240`, which is `1111 0000`.

---

# Question: What does the `>>` (Right Shift) operator do in C#?

**Answer:** It moves the left operand’s value right by the number of bits specified, effectively dividing by 2^n.

---

# Question: Given `A = 60`, what is `A >> 2` and its binary representation?

**Answer:** `15`, which is `0000 1111`.

---

# Question: In the example `a = 5`, `b = 3`, what does `(a & b)` output?

**Answer:** `1`.

---

# Question: In the example `a = 5`, `b = 3`, what does `(a | b)` output?

**Answer:** `7`.

---

# Question: In the example `a = 5`, `b = 3`, what does `(a ^ b)` output?

**Answer:** `6`.

---

# Question: In the example `a = 5`, what does `~a` output?

**Answer:** `-6`.

---

# Question: In the example `a = 5`, what does `a << 2` output?

**Answer:** `20`.

---

# Question: In the example `a = 20`, what does `a >> 2` output?

**Answer:** `5`.

---

# Question: How can you use bitwise operators to check if a number is even or odd?

**Answer:** Use `(number & 1) == 0`; if true, the number is even; otherwise, odd.

---

# Question: What output is produced when checking if `number = 10` is even or odd using bitwise AND?

**Answer:** `Even`.

---

# Question: How can you swap two numbers without a temporary variable using bitwise operators?

**Answer:** Use XOR:

```
a = a ^ b;  
b = a ^ b;  
a = a ^ b;
```

---

# Question: After swapping `a = 5` and `b = 10` using XOR, what are the new values?

**Answer:** `a = 10`, `b = 5`.

---

# Question: Why is `a << -1` a mistake in C#?

**Answer:** Because negative shift counts are invalid.

---

# Question: How should you correct the mistake `a << -1`?

**Answer:** Use `a << 0` or `a >> 0`.

---

# Question: Why is `a = a & 0` a mistake in C#?

**Answer:** Because it always sets `a` to 0.

---

# Question: How can you avoid the mistake `a = a & 0`?

**Answer:** Use `a & mask` with a properly defined mask.

---

# Question: Why can `b = ~b` produce unexpected negative values?

**Answer:** Because integers are stored in two’s complement format.

---

# Question: What should you understand when using the `~` operator to avoid errors?

**Answer:** How negative numbers are represented in two’s complement.

---

# Question: What operator should you use for flag operations and bit masking in C#?

**Answer:** Bitwise AND (`&`).

---

# Question: Which operator is useful for swapping values efficiently without extra memory?

**Answer:** Bitwise XOR (`^`).

---

# Question: Which operators can be used for fast multiplication and division by powers of 2?

**Answer:** Left shift (`<<`) for multiplication, right shift (`>>`) for division.

---

# Question: What is an important concept to understand when using bitwise operations with signed numbers?

**Answer:** Two’s complement representation of negative numbers.

---
