# Question: What are XSS and HTML Injection vulnerabilities?

**Answer:**
XSS (Cross-Site Scripting) and HTML Injection are input validation vulnerabilities where an application processes user inputs without proper restriction or sanitization, potentially allowing attackers to inject malicious scripts or HTML code.

---

# Question: What can happen if an application processes XSS and HTML Injection inputs without restriction?

**Answer:**
If inputs are processed without restriction, it can lead to various attacks such as injection attacks, data leakage, and security bypasses.

---

# Question: Why is input validation important in preventing XSS and HTML Injection attacks?

**Answer:**
Input validation is important because it restricts or sanitizes user inputs to prevent malicious code from being executed or injected, thereby protecting the application from security breaches.

---

# Question: What types of security issues can XSS and HTML Injection lead to?

**Answer:**
They can lead to injection attacks, unauthorized data access or leakage, and bypassing of security controls.

---

# Question: What is Cross-site Scripting (XSS)?

**Answer:**
Cross-site Scripting (XSS) is a security vulnerability where attackers inject malicious scripts into web pages viewed by other users. These scripts execute in the user’s browser, potentially compromising sensitive information, user sessions, or control over user accounts.

---

# Question: What are the three main types of XSS?

**Answer:**
The three main types of XSS are Stored (Persistent) XSS, Reflected (Non-Persistent) XSS, and DOM-Based XSS.

---

# Question: What is Stored XSS and how does it work?

**Answer:**
Stored XSS occurs when malicious code is permanently saved on the server, such as in databases or files (e.g., comments or profiles). The injected script executes automatically whenever a user accesses the affected page.

---

# Question: What is an example of Stored XSS?

**Answer:**
An example is an attacker placing malicious JavaScript in a blog comment. Every user reading the comment triggers the script execution in their browser.

---

# Question: How does Reflected XSS differ from Stored XSS?

**Answer:**
Reflected XSS involves malicious scripts included in URLs or form inputs, which are immediately reflected back by the server in the response without being stored. The script executes only when the user clicks a specially crafted link or submits data.

---

# Question: What is DOM-Based XSS?

**Answer:**
DOM-Based XSS is a client-side vulnerability where malicious scripts execute directly in the browser through the Document Object Model (DOM), without involving server-side reflection or storage.

---
