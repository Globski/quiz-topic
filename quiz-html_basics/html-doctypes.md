# Question: What are the different kinds of Doctypes available in HTML?

**Answer:**

There are three main kinds of Doctypes traditionally used in HTML 4, plus a modern HTML5 Doctype. Each defines how the HTML document is parsed by the browser.

---

## 1. Strict Doctype

- Disallows deprecated tags and attributes.
- Promotes clean, modern coding.

**Example:**
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
  "http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head>
    <title>Strict Doctype Example</title>
  </head>
  <body>
    <p>This follows strict HTML 4.01 rules.</p>
  </body>
</html>
````

---

## 2. Transitional Doctype

* Allows deprecated elements (like `<font>`, `<center>`).
* Useful for legacy HTML being modernized slowly.

**Example:**

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
  "http://www.w3.org/TR/html4/loose.dtd">
<html>
  <head>
    <title>Transitional Doctype Example</title>
  </head>
  <body>
    <center>This uses some deprecated tags like center.</center>
  </body>
</html>
```

---

## 3. Frameset Doctype

* Used when the page uses `<frameset>` instead of `<body>`.
* Completely deprecated in HTML5.

**Example:**

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
  "http://www.w3.org/TR/html4/frameset.dtd">
<html>
  <head>
    <title>Frameset Doctype Example</title>
  </head>
  <frameset cols="50%,50%">
    <frame src="left.html">
    <frame src="right.html">
  </frameset>
</html>
```

---

## ✅ Modern: HTML5 Doctype

* Short and simple.
* Used in all modern web development.

**Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Doctype</title>
  </head>
  <body>
    <p>This is HTML5!</p>
  </body>
</html>
```

> Use HTML5 Doctype for all modern web projects.

