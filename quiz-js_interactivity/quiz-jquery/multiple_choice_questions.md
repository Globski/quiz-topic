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

# Question: What are the two ways to use jQuery in code?

**Answer:**
jQuery can be used as a function `jQuery(...)` or as a variable/property like `jQuery.foo`. The `$` symbol is an alias for `jQuery` and can usually be used interchangeably unless `jQuery.noConflict();` has been called.

---

# Question: How can you add text content to a `<div>` with id `demo_div` using jQuery?

**Answer:**
You can use the `text()` function with either `jQuery` or `$` selector like this:
`jQuery("#demo_div").text("Demo Text!");` or `$("#demo_div").text("Demo Text!");`
Both will set the inner text of the div to "Demo Text!".

---

# Question: Why is the `$` alias generally preferred over using `jQuery`?

**Answer:**
Because `$` is more concise and shorter to write, making the code simpler and quicker to type.

---

# Question: What does the jQuery selector `$("#demo_div")` use internally to select elements?

**Answer:**
It uses CSS selectors internally; in this case, an ID selector (`#demo_div`).

---

# Question: How can you load jQuery on a webpage that does not already include it using the Chrome Developer Tools console?

**Answer:**
By running the following code in the console:

```javascript
var j = document.createElement('script');
j.onload = function(){ jQuery.noConflict(); };
j.src = "https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js";
document.getElementsByTagName('head')[0].appendChild(j);
```

---

# Question: What does the function `jQuery.noConflict();` do when loading jQuery manually?

**Answer:**
It releases the `$` alias so it does not conflict with other libraries that might use `$`.

---

# Question: Where is the recommended place to include the jQuery `<script>` tag in your HTML?

**Answer:**
It is recommended to place the `<script>` tag inside the `<head>` section of the HTML.

---

# Question: What is the purpose of using the `async` attribute in the script tag when loading jQuery?

**Answer:**
The `async` attribute allows the script to be loaded and executed asynchronously as soon as it is available, without blocking the HTML parsing.

---

# Question: What is a potential risk of loading multiple JavaScript libraries asynchronously when one depends on another?

**Answer:**
If the dependent library loads and executes before the library it depends on, it may throw errors and break the application.

---

# Question: How do you get the official jQuery CDN URL for a specific version?

**Answer:**
You visit the jQuery website, choose the version you want, and copy the uncompressed or minified script tag provided.

---
