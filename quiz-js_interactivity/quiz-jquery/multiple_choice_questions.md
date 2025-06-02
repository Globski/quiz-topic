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

# Question: Why might the `$` alias in jQuery cause problems when using multiple JavaScript libraries?

**Answer:**
Because other libraries may also use `$` as an alias, which can cause conflicts and interference between jQuery and those libraries.

---

# Question: What does the function `jQuery.noConflict()` do?

**Answer:**
It releases the `$` alias so that it no longer refers to jQuery, allowing other libraries to use `$`. You can still access jQuery functions using the full `jQuery` variable.

---

# Question: How can you assign a new alias to jQuery after calling `jQuery.noConflict()`?

**Answer:**
By assigning the return value of `jQuery.noConflict()` to a new variable, for example:

```js
var jqy = jQuery.noConflict();
```

Then you can use `jqy` as an alias for jQuery.

---

# Question: What is the purpose of wrapping jQuery code inside an Immediately Invoked Function Expression (IIFE) like this?

```js
(function($) {
  $(document).ready(function() {
    $('#hello').text('Hello, World!');
  });
})(jQuery);
```

**Answer:**
To locally alias `$` to jQuery inside the IIFE, preventing interference with other libraries outside that scope.

---

# Question: How can you ensure `$` safely refers to jQuery only inside a function without polluting the global namespace?

**Answer:**
By using this pattern:

```js
jQuery(function($) {
  // DOM is ready, and $ is safely an alias for jQuery here
  $('#hello').text('Hello, World!');
});
```

---

# Question: What happens when you call `var jQuery2 = jQuery.noConflict(true);`?

**Answer:**
Neither `$` nor `jQuery` refer to jQuery anymore, but `jQuery2` holds the jQuery reference. This is useful when multiple jQuery versions are loaded.

---

# Question: How can you use multiple versions of jQuery on the same page without conflict?

**Answer:**
Load one jQuery version, call `jQuery.noConflict(true)` to assign it to a unique variable (e.g., `jQuery1`), then load the second version normally. For example:

```html
<script src='https://code.jquery.com/jquery-1.12.4.min.js'></script>
<script>
  var jQuery1 = jQuery.noConflict(true);
</script>
<script src='https://code.jquery.com/jquery-3.1.0.min.js'></script>
<script>
  // jQuery1 refers to 1.12.4, while $ and jQuery refer to 3.1.0
</script>
```

---

