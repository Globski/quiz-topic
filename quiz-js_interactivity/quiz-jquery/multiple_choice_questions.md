# Question: What does the following HTML file display when opened in a web browser?

```html
<!DOCTYPE html>
<html>
<head>
 <title>Hello, World!</title>
</head>
<body>
 <div>
 <p id="hello">Some random text</p>
 </div>
 <script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
 <script>
 $(document).ready(function() {
 $('#hello').text('Hello, World!');
 });
 </script>
</body>
</html>
```

**Answer:**
The page displays the text: **Hello, World!** The jQuery code changes the paragraph text with id "hello" from "Some random text" to "Hello, World!" once the DOM is ready.

---

# Question: What is the purpose of including `<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>` in the HTML file?

**Answer:**
It loads the jQuery library from the jQuery CDN, introducing the `$` global variable, which is an alias for the jQuery function and namespace, allowing you to use jQuery functions in your script.

---

# Question: Why must the jQuery library be loaded before any other scripts that depend on it?

**Answer:**
Because if jQuery is not loaded first, other scripts that rely on `$` or jQuery functions will fail to work since the jQuery namespace and functions won’t be available yet.

---

# Question: What does the following jQuery code do?

```js
$(document).ready(function() {
  $('#hello').text('Hello, World!');
});
```

**Answer:**
It defers execution of the callback function until the DOM is fully loaded. Once ready, it selects the element with the id "hello" and sets its text content to "Hello, World!".

---

# Question: What is a shorthand version of `$(document).ready(function() { ... });` in jQuery?

**Answer:**
The shorthand is:

```js
$(function() { ... });
```

It behaves the same way, executing the callback once the DOM is ready.

---

# Question: In jQuery, what does the selector `$('#hello')` do?

**Answer:**
It selects the HTML element with the id attribute equal to "hello". This selector syntax is core to jQuery’s functionality.

---

# Question: What is the purpose of the `.text()` method in jQuery?

**Answer:**
The `.text()` method sets or returns the text content of the selected element(s). In this case, it sets the text inside the element with id "hello" to "Hello, World!".

---

