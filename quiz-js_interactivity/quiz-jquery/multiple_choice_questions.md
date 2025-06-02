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


# Question: What happens internally every time jQuery is called using `$()` or `jQuery()`?

**Answer:**
Internally, jQuery creates a new instance of the jQuery object by calling `new jQuery.fn.init(selector, context)`. This allows jQuery to return a new object without the caller needing to use the `new` keyword explicitly.

---

# Question: What is `jQuery.fn` in the jQuery source code?

**Answer:**
In the jQuery source code, `jQuery.fn` is an alias for `jQuery.prototype`. This means that all jQuery methods (like `.each()`, `.filter()`, `.children()`, etc.) are attached to `jQuery.fn`, making them available to every jQuery object instance. It exposes the prototype methods so they can be accessed or extended easily.

**Source code snippet from the material:**

```javascript
jQuery = function( selector, context ) {
  // The jQuery object is actually just the init constructor 'enhanced'
  // Need init if jQuery is called (just allow error to be thrown if not included)
  return new jQuery.fn.init( selector, context );
}
```

Here, `jQuery.fn` refers to the prototype object where jQuery's methods are defined, enabling the creation of new jQuery instances without explicitly calling `new`.

---

# Question: How does jQuery internally structure the result of a selector?

**Answer:**
jQuery creates an array-like structure that holds the elements matched by the selector. If only one element is matched, the array-like structure contains just that single item.

---

# Question: How can you access the underlying native DOM element from a jQuery object?

**Answer:**
You can access the underlying DOM element by referencing the zero index of the jQuery object, for example:

```javascript
var $div = $("#myDiv");  
var div = $div[0]; // native DOM element
```

---

# Question: Why doesn’t a caller need to use the `new` keyword when creating a jQuery object?

**Answer:**
Because internally, jQuery’s main function returns a new instance of `jQuery.fn.init`, so the caller gets a new object without explicitly calling `new`.

---

# Question: What does a jQuery selector do?

**Answer:**
A jQuery selector selects or finds DOM elements in an HTML document based on id, name, types, attributes, class, etc., using syntax similar to CSS selectors.

---

# Question: How do you select all elements in a document using jQuery?

**Answer:**
Using the wildcard selector `"*"` like this: `$(" * ")` selects all elements in the document.

---

# Question: What jQuery selector would you use to select all `<div>` elements?

**Answer:**
`$("div")` selects all `<div>` elements in the document.

---

# Question: How do you select elements that have both class "blue" and class "red"?

**Answer:**
You use the combined class selector: `$(".blue.red")`.

---

# Question: What is the difference between `$(".blue.red")` and `$(".blue, .red")`?

**Answer:**
`$(".blue.red")` selects elements that have both classes "blue" AND "red", while `$(".blue, .red")` selects elements that have either class "blue" OR class "red".

---

# Question: How would you select the element with id "headline"?

**Answer:**
Using the ID selector: `$("#headline")`.

---

# Question: How do you select all elements that have an `href` attribute?

**Answer:**
Using the attribute presence selector: `$("[href]")`.

---

# Question: What jQuery selector selects elements with an `href` attribute exactly equal to "example.com"?

**Answer:**
`$("[href='example.com']")` selects all elements with `href="example.com"`.

---

# Question: How do you select all `<span>` elements that are descendants of a `<div>`?

**Answer:**
Using the descendant selector: `$("div span")`.

---

# Question: How do you select all `<span>` elements that are direct children of a `<div>`?

**Answer:**
Using the child selector: `$("div > span")`.

---

# Question: What does the selector `$("a + span")` select?

**Answer:**
It selects all `<span>` elements that are immediately following an `<a>` element as an adjacent sibling.

---

# Question: What types of selectors can you use in jQuery?

**Answer:**
You can select elements by type, class, ID, possession of attribute, attribute value, indexed position, exclusion, and pseudo-states.

---

# Question: What does the selector `$("a:eq(1)")` do?

**Answer:**
It selects the second `<a>` element in the document because jQuery uses zero-based indexing.

---

# Question: How do you exclude an element by its index in a selection?

**Answer:**
Use the `.not()` method with an indexed selector, for example: `$("a").not(":eq(0)")` excludes the first `<a>` element.

---

# Question: What does `$("a:not(.example)")` select?

**Answer:**
It selects all `<a>` elements except those with the class `example`.

---

# Question: How do you select the first `<a>` element of its type?

**Answer:**
Using the pseudo-state selector: `$("a:first-of-type")`.

---

# Question: How would you select an `<a>` element with multiple classes, a specific ID, attributes, and pseudo-states all at once?

**Answer:**
By combining selectors like:
`$("a.class1.class2.class3#someID[attr1][attr2='something'][attr3='something']:first-of-type:first-child")`

---

# Question: How do you select multiple different elements or classes with a single jQuery selector?

**Answer:**
By separating selectors with commas, for example:
`$("a, .class1, #someID")` selects all `<a>` elements, all elements with class `class1`, and the element with id `someID`.

---

# Question: What jQuery selector syntax selects all elements inside an element with id "wrapper"?

**Answer:**
`$("#wrapper *")` selects all elements inside the element with id "wrapper".

---

# Question: Why should you cache a jQuery selector by assigning it to a variable?

**Answer:**
Because each time a selector is used, jQuery searches the DOM, which can reduce performance if done repeatedly. Caching the selector in a variable avoids repeated DOM searches and improves efficiency.

---

# Question: How do you cache the selector `$('#navigation')` in a variable?

**Answer:**
By assigning it to a variable like this: `var nav = $('#navigation');`

---

# Question: What happens if there are multiple elements matching a selector and you cache it in a variable?

**Answer:**
The variable will hold an array (or jQuery collection) of all matched elements.

---

# Question: What is the issue with assigning a selector to a variable before the matching elements exist in the DOM?

**Answer:**
The variable will store an empty array or collection because no elements with that selector exist yet in the DOM at the time of assignment.

---

# Question: After dynamically adding elements matching a selector to the DOM, what must you do with the cached selector variable?

**Answer:**
You must reassign the selector to the variable again to include the newly added elements.

---

# Question: Why do many developers prefix cached jQuery selector variables with a `$`?

**Answer:**
To indicate that the variable holds a jQuery object, making the code easier to read and understand.

---

# Question: How would you cache and show an element with id "navigation" using best practices for variable naming?

**Answer:**

```javascript
var $nav = $('#navigation');
$nav.show();
```

---

