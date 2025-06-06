# Question: How do you apply an external CSS stylesheet to an HTML document?

**Answer:**
You apply an external CSS stylesheet by placing a `<link>` element inside the `<head>` section of the HTML document. The `<link>` tag should have the attribute `rel="stylesheet"` and `href` set to the path of the CSS file.

---

# Question: Why is it recommended to place the `<link>` tag inside the `<head>` tag of an HTML file?

**Answer:**
Placing the `<link>` tag inside the `<head>` ensures that styles are loaded before the page content, preventing users from seeing a flash of unstyled content.

---

# Question: Can the `type` attribute be omitted in the `<link>` tag when linking a CSS file in HTML5?

**Answer:**
Yes, in HTML5 the `type="text/css"` attribute can be omitted since it is the default for stylesheets.

---

# Question: What is the advantage of using relative paths over absolute paths in the `href` attribute of the `<link>` tag?

**Answer:**
Relative paths are generally preferred because they are more flexible when moving files or deploying websites across different environments, while absolute paths are fixed and can break if the file location changes.

---

# Question: What is the benefit of using an external stylesheet when managing a website with many pages?

**Answer:**
Using an external stylesheet allows you to make a single change in the CSS file that cascades across all pages, making maintenance easier and avoiding repetitive edits in every individual HTML file.

---

# Question: How does the browser handle CSS files when a user navigates between pages on the same website?

**Answer:**
The browser downloads the CSS file only once and caches it, so subsequent page loads do not require downloading the CSS again, which speeds up page loading times.

---

# Question: Can multiple external CSS files be linked in one HTML document? If so, does the order of these files matter?

**Answer:**
Yes, multiple external CSS files can be linked by using multiple `<link>` tags. The order matters because later files can override styles defined in earlier files.

---

# Question: Given the following CSS in `main.css`:

```css
p.green { color: #00FF00; }
```

and the following in `override.css`:

```css
p.green { color: #006600; }
```

If both files are linked in order (`main.css` first, then `override.css`), what will be the color of paragraphs with the class "green"?

**Answer:**
The paragraphs will be colored `#006600` (darker green) because the styles in `override.css` come after and override those in `main.css`.

---

# Question: Besides order, what other CSS principles affect how rules are applied?

**Answer:**
Other principles include specificity (how specific a selector is), inheritance (how styles are passed down from parent elements), and the `!important` declaration which can force a rule to override others.

---

# Question: If the CSS file is stored in a folder called `styles`, how should you reference it in the `href` attribute?

**Answer:**
You should specify the relative path including the folder name, for example: `href="styles/style.css"`.

---

# Question: What is the difference between internal styles and external stylesheets in CSS?

**Answer:**
Internal styles are CSS rules enclosed within `<style></style>` tags inside the HTML document they style, typically placed inside the `<head>` element. They only apply to the document in which they live. External stylesheets are separate CSS files linked to HTML documents and can be reused across multiple pages.

---

# Question: Where must the `<style>` element be placed in an HTML document for proper validation?

**Answer:**
The `<style>` element must be placed inside the `<head>` element of the HTML document for proper HTML validation.

---

# Question: What is the purpose of the CSS `@import` at-rule?

**Answer:**
The `@import` at-rule is used to import style rules from other CSS style sheets into the current stylesheet.

---

# Question: Where must `@import` rules be placed within a CSS file?

**Answer:**
`@import` rules must precede all other types of CSS rules except for `@charset` rules.

---

# Question: Can `@import` be used inside conditional group at-rules?

**Answer:**
No, `@import` is not a nested statement and cannot be used inside conditional group at-rules.

---

# Question: How do you use the `@import` rule inside an internal style tag?

**Answer:**
Inside a `<style>` tag, you use `@import` like this:

```css
<style>
  @import url('/css/styles.css');
</style>
```

---

# Question: How can you import an external CSS file into another CSS file?

**Answer:**
You can import it by writing `@import '/additional-styles.css';` at the top of the CSS file.

---

# Question: What is a common use case for importing external CSS files with `@import`?

**Answer:**
A common use case is importing font files, such as Google Fonts.

---

# Question: How do you specify media queries when using `@import`?

**Answer:**
You add an optional second argument with media queries, for example:

```css
@import '/print-styles.css' print;
@import url('landscape.css') screen and (orientation:landscape);
```

---

# Question: What are inline styles in CSS and when should they be used?

**Answer:**
Inline styles are CSS rules applied directly to an HTML element via the `style` attribute. They should be used sparingly, usually only when necessary to override other styles or ensure compatibility, such as in emails.

---

# Question: How do inline styles affect CSS specificity?

**Answer:**
Inline styles override any CSS rules defined in `<style>` tags or external stylesheets.

---

# Question: Why is using inline styles generally discouraged?

**Answer:**
Because inline styles reduce maintainability by mixing content and presentation and can be time-consuming and difficult to manage.

---

# Question: Provide an example of applying inline styles to an `<h1>` and a `<p>` element.

**Answer:**

```html
<h1 style="color: green; text-decoration: underline;">Hello world!</h1>
<p style="font-size: 25px; font-family: 'Trebuchet MS';">I ♥ CSS</p>
```

---

# Question: How can JavaScript be used to change CSS styles of an element?

**Answer:**
JavaScript can access and modify an element's styles through the element's `.style` property, for example:

```javascript
var el = document.getElementById("element");
el.style.opacity = 0.5;
el.style.fontFamily = 'sans-serif';
```

---

# Question: How are CSS property names formatted in JavaScript when accessed via `.style`?

**Answer:**
CSS property names are written in lower camel case in JavaScript (e.g., `font-family` becomes `fontFamily`).

---

# Question: Besides modifying styles directly on elements, what else can JavaScript do to affect CSS?

**Answer:**
JavaScript can create new `<style>` or `<link>` elements dynamically and append them to the `<head>` or `<body>` of the document.

---

# Question: How can jQuery be used to modify CSS properties?

**Answer:**
With jQuery, use the `.css()` method, for example:

```javascript
$('#element').css('margin', '5px');
```

---

# Question: How can jQuery modify multiple CSS properties at once?

**Answer:**
By passing an object to `.css()`, for example:

```javascript
$('#element').css({
  margin: "5px",
  padding: "10px",
  color: "black"
});
```

---

# Question: How does jQuery handle CSS property names with hyphens?

**Answer:**
jQuery allows hyphenated property names to be either quoted as strings (e.g., `"background-color"`) or camel-cased (e.g., `fontSize`).

---

# Question: How do you define a mixin in SASS?

Answer:  
You define a mixin using the `@mixin` keyword followed by a name and optional parameters.  
Example:  
@mixin borderRadius($radius) {  
  -webkit-border-radius: $radius;  
  -moz-border-radius: $radius;  
  border-radius: $radius;  
}

---

# Question: How do you use (invoke) a mixin in SASS?

Answer:  
You use the `@include` keyword followed by the mixin name and any required arguments.  
Example:  
@include borderRadius(20px);

---

# Question: What types of mathematical operations can you use in CSS preprocessors?

Answer:  
You can use:  
• Addition  
• Subtraction  
• Multiplication  
• Division

---

# Question: How can you calculate column width in a preprocessor using math?

Answer:  
$wrapperWidth: 1000px;  
$columnsNumber: 10;  
$innerPadding: 10px;  

$widthOfColumn: $wrapperWidth / $columnsNumber;  

.wrapper {  
  width: $wrapperWidth;  
}  

.column {  
  width: $widthOfColumn;  
  padding: 0 10px;  
}

---

# Question: What comparison operators are available in preprocessors?

Answer:  
• `<` (less than)  
• `>` (greater than)  
• `==` (equal to)  
• `!=` (not equal to)  
• `<=` (less than or equal to)  
• `>=` (greater than or equal to)

---

# Question: What logical operators can be used in preprocessors?

Answer:  
• `and`  
• `or`  
• `not`

---

# Question: What loop types are supported in preprocessors?

Answer:  
• `if`  
• `foreach`  
• `while`

---

# Question: Why is joining multiple CSS files using preprocessors more efficient?

Answer:  
In preprocessors, multiple files can be joined and compiled into one CSS file, avoiding multiple HTTP requests. In contrast, importing in plain CSS still causes additional server requests in the browser.

---
