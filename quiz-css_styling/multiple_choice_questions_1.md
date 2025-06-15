# Question: What does CSS stand for?

**Answer:** CSS stands for Cascading Style Sheets.

---

# Question: What is CSS primarily used for?

**Answer:** CSS is used to describe the presentation of a document.

---

# Question: Which markup language is CSS most commonly used with?

**Answer:** CSS is most commonly used with HTML.

---

# Question: Besides HTML, name three other media or document types CSS can be applied to.

**Answer:** CSS can be applied to XML, SVG, and MathML.

---

# Question: What are the three ways to apply CSS to an HTML document?

**Answer:** External stylesheet, internal stylesheet, and inline styles.

---

# Question: What HTML tag is used to link an external CSS file?

**Answer:** The `<link>` tag.

---

# Question: What attribute value does the `<link>` tag use to specify the type of relationship?

**Answer:** `rel="stylesheet"`

---

# Question: What filename given to the CSS file?

**Answer:** `style.css`

---

# Question: What selector?

**Answer:** `p` (paragraph element).

---

# Question: What CSS property and value?

**Answer:** `color: purple;`

---

# Question: What character ends a CSS declaration?

**Answer:** A semicolon (`;`).

---

# Question: Where should the `href` in the `<link>` tag point to when referencing the external stylesheet?

**Answer:** To `CSS/style.css`, reflecting the folder and file path.

---

# Question: Why is the `type` attribute in the `<link>` tag generally avoided today?

**Answer:** It is considered outdated and no longer required; including it is frowned upon in modern HTML practices.

---

# Question: What CSS property was added to increase the size of the paragraph text?

**Answer:** `font-size: 64px;`

---

# Question: What is the purpose of using `<style>` tags inside the `<head>` section of an HTML file?

**Answer:** To define an internal stylesheet directly within the HTML document.

---

# Question: What happened when both external and internal stylesheets defined the same CSS property?

**Answer:** The last-read stylesheet took precedence, so the internal style's `color: limegreen` overrode the external one.

---

# Question: What is the browser’s interpretation of multiple stylesheets?

**Answer:** The browser treats both internal and external stylesheets equally; it follows the cascade order based on the sequence they appear in the HTML.

---

# Question: What determines which CSS rule takes precedence when the same selector is styled in multiple places?

**Answer:** The cascade order—whichever rule appears last in the HTML is applied.

---

# Question: What was the result of moving the `<link>` tag below the internal `<style>` tag?

**Answer:** The external stylesheet was applied last, so the `color: purple` rule took precedence over the internal `color: limegreen` rule.

---

# Question: What is the third method of applying CSS in HTML, after external and internal stylesheets?

**Answer:** Inline CSS.

---

# Question: What is inline CSS?

**Answer:** Inline CSS is a method of styling by adding the `style` attribute directly to an HTML element.

---

# Question: Why should inline CSS generally be avoided?

**Answer:** Inline CSS mixes content with presentation, reduces reusability, and overrides other styles, making it harder to maintain.

---

# Question: What does the `p` selector target in a CSS rule?

**Answer:** The `p` selector targets all `<p>` (paragraph) elements in the HTML document.

---

# Question: When is it acceptable to omit a semicolon in a CSS declaration?

**Answer:** A semicolon can be omitted if there's only one declaration in a rule set.

---

# Question: Why does inline CSS take precedence over internal or external stylesheets?

**Answer:** Inline CSS takes precedence because it is applied directly to the HTML element, overriding styles from internal or external sources.

---

# Question: Why is external CSS considered best practice over inline or internal CSS?

**Answer:** External CSS promotes separation of concerns by keeping the style rules in a separate file, making code easier to manage and reuse.

---

# Question: What two elements should be removed from an HTML document to transition fully to using external CSS?

**Answer:** The inline styles on elements and the internal `<style>` element should be removed.

---

# Question: What is the result in the browser when inline and internal CSS are removed and only external CSS is used?

**Answer:** The styles defined in the external stylesheet take effect, such as text color returning to purple if specified there.

---

# Question: What are the three main parts of a CSS rule set according to the MDN (Mozilla Developer Network)?

**Answer:** Selector, property, and property value.

---

# Question: What constitutes a CSS declaration?

**Answer:** A CSS declaration consists of a property and its corresponding value (e.g., `color: red`).

---

# Question: What is a CSS rule or rule set?

**Answer:** A CSS rule set (often just called a "rule") includes the selector and all declarations within its block.

---

# Question: How is "color" spelled in CSS, and why is this important?

**Answer:** "Color" must be spelled using American English (without the "u"). Misspelling it (e.g., "colour") causes the declaration to be ignored.

---

# Question: What happens in CSS if a property is misspelled?

**Answer:** The declaration is silently ignored without throwing an error, potentially making debugging harder.

---

# Question: Why doesn’t CSS throw errors like traditional programming languages?

**Answer:** CSS silently ignores invalid or unrecognized rules or properties, meaning mistakes don't cause execution errors but just fail to apply.

---

# Question: How can you detect silent errors or ignored declarations in your CSS?

**Answer:** By using a CSS validation tool like the W3C CSS Validation Service to check for errors or invalid properties.

---

# Question: What is the W3C CSS Validation Service used for?

**Answer:** It is used to validate CSS files to ensure they follow proper syntax and standards, helping detect issues in styling.

---

# Question: How do you use the W3C CSS Validation Service for local CSS files?

**Answer:** By selecting the "File Upload" option and uploading the `style.css` file from your project folder.

---

# Question: How do you use the W3C CSS Validator with a local CSS file?

**Answer:** Select the “File Upload” option on the validator site, browse to your CSS file (e.g., `style.css` in the CSS folder), choose the file, then click the “Check” button.

---

# Question: What message do you see if your CSS file has no errors in the W3C CSS Validator?

**Answer:** “Congratulations! No Error Found.”

---

# Question: What are the three most common levels of CSS selectors?

**Answer:** Element selectors, class selectors, and ID selectors.

---

# Question: What is an element selector in CSS?

**Answer:** An element selector targets all instances of a specific HTML tag, such as `body`, `p`, or `h1`.

---

# Question: Why did other elements’ text size increase when only the `body` was targeted?

**Answer:** Because child elements inherit the font size from the `body` element due to CSS inheritance.

---

# Question: What happens when you apply the `p` element selector with `color: purple`?

**Answer:** All paragraph (`<p>`) elements on the page are colored purple.

---

# Question: What is the second type of selector after element selectors?

**Answer:** Class selectors.

---

# Question: How do you define a class selector in CSS?

**Answer:** Use a period (`.`) followed by the class name (e.g., `.gray`).

---

# Question: How do you apply a class to an HTML element?

**Answer:** Use the `class` attribute in the HTML tag, like `<p class="gray">`.

---

# Question: Can the same class be applied to multiple HTML elements?

**Answer:** Yes, classes are reusable and can be applied to multiple elements on the same page.

---

# Question: Why should class names be meaningful in CSS?

**Answer:** To make the code easier to understand and maintain for others as well as yourself.

---

# Question: Why did the gray class override the purple color set for all paragraph elements?

**Answer:** Because class selectors are more specific than element selectors, so the `.gray` class overrode the `p` selector's `color: purple` rule.

---

# Question: What is the most commonly used selector type in CSS?

**Answer:** Class selectors are the most common type used in CSS.

---

# Question: What is more specific than a class selector in CSS?

**Answer:** An ID selector is more specific than a class selector.

---

# Question: How do you define and use an ID selector in CSS?

**Answer:** Use a hash symbol (`#`) followed by the ID name (e.g., `#second`) and apply it to an element with the `id="second"` attribute in HTML.

---

# Question: Why should ID selectors be used sparingly in CSS?

**Answer:** Because IDs should be unique in an HTML document, and it's considered bad practice to use them for styling. Classes or element selectors are preferred.

---

# Question: What are some valid non-styling uses of the `id` attribute in HTML?

**Answer:** Linking a form input to a label, or referencing elements via JavaScript.
	•	Linking a form input to its <label> for better accessibility.
	•	Referencing and manipulating elements via JavaScript.
	•	Creating internal page navigation (anchor links).

Examples:

1. Linking a label to an input
```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```
The for attribute in the label connects to the input’s id, improving accessibility and allowing the user to click the label to focus the input.

---

2. JavaScript reference
```js
<button id="myButton" onclick="alert('Button clicked!')">Click Me</button>

<script>
  document.getElementById('myButton').innerText = 'New Button Text';
</script>
```
JavaScript uses the id to select and manipulate the element.

---

3. Internal page navigation
```html
<a href="#section2">Go to Section 2</a>

<h2 id="section2">Section 2</h2>
<p>This is the content of section 2.</p>
```
Clicking the link scrolls the page to the element with the matching id.

---

# Question: What happens when you set a style for `h1` in CSS?

**Answer:** The style applies to the single `h1` element on the page.

---

# Question: How do you apply the same CSS rule to multiple selectors?

**Answer:** Group selectors with a comma (`,`) between them (e.g., `h1, h2`).

---

# Question: What happens if you omit the comma when writing grouped selectors like `h1 h2`?

**Answer:** It creates a descendant selector, targeting only `h2` elements nested inside `h1` elements, which will likely not match any elements and result in no styles applied.

---

# Question: What is the purpose of using a descendant selector like `h1 h2`?

**Answer:** It selects `h2` elements that are nested within `h1` elements, which is useful when targeting specific child elements inside a parent.

---

# Question: How can you target a `span` element inside a `p` element in CSS?

**Answer:** Use the descendant selector `p span`.

---

# Question: What does applying the `text-transform: uppercase;` property to a span do?

**Answer:** It transforms the text content inside the span to uppercase.

---

# Question: Why might applying inline styles directly to multiple elements not be ideal?

**Answer:** Inline styles are not reusable or scalable; applying them directly makes the CSS disorganized and harder to maintain.

---

# Question: How can you make the styling of multiple span elements reusable and cleaner?

**Answer:** By defining a CSS class (e.g., `.highlight`) and applying it to each span element, making the styling reusable and the CSS more organized.

---

# Question: What is the benefit of using a class like `.highlight` instead of repeating the same inline styles?

**Answer:** It improves code reusability, maintainability, and flexibility by allowing a single change in the CSS file to affect all elements using that class.

---

# Question: What is the universal selector in CSS and how is it written?

**Answer:** The universal selector is written as `*` and selects all elements on the page.

---

# Question: In what scenario is the universal selector commonly used?

**Answer:** It is typically used in a CSS reset to apply base styles to all elements.

---

# Question: What effect does applying a font-family style using the universal selector have?

**Answer:** It changes the font for all text on the page to the specified font (e.g., `monospace`), overriding any default font settings.

---

# Question: Why is the universal selector not commonly used for general styling?

**Answer:** Because it affects every element indiscriminately, which can lead to unintended styling consequences and performance issues.

---

# Question: What does CSS stand for and what does "cascading" refer to?

**Answer:** CSS stands for Cascading Style Sheets; "cascading" refers to the top-down application of styles, where later rules can override earlier ones.

---

# Question: In what order does the browser read and apply CSS rules?

**Answer:** The browser reads CSS from top to bottom; later rules override earlier ones if they have the same specificity.

---

# Question: What happens when two conflicting style rules apply to the same element?

**Answer:** The rule that appears last in the CSS (i.e., read later) is applied unless another rule has higher specificity.

---

# Question: How can class selectors override element selectors in CSS?

**Answer:** Class selectors have higher specificity than element selectors, so they apply even if they appear earlier in the CSS.

---

# Question: If a class with a style appears above an element selector in the CSS file, which style is applied?

**Answer:** The class style is applied because class selectors are more specific than element selectors, regardless of order.

---

# Question: What happens if a paragraph has both a class and an element style applied?

**Answer:** The class style takes precedence due to its higher specificity.

---

# Question: If a class is removed from an element, which style will apply?

**Answer:** The element selector style will apply, assuming there are no more specific styles remaining.

---


















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

# Question: What is Less in the context of CSS preprocessors?

**Answer:**  
Less is a CSS preprocessor mainly used in the Bootstrap framework. It includes typical preprocessor features like mixins, math operations, nesting, and variables. Less allows quick invoking of declared mixins to reuse sets of CSS properties across different selectors.

---

# Question: How do you use a declared mixin in Less with an example?

**Answer:**  
In Less, you first declare a class with some properties, for example:  
```less
.text-settings {
  font-size: 12px;
  font-family: Arial;
  text-align: center;
}
```
Then, you can reuse these properties in another selector by invoking the class name as a mixin, like this:  
```less
p {
  .text-settings;
  color: red;
}
```
This compiles to:  
```css
p {
  font-size: 12px;
  font-family: Arial;
  text-align: center;
  color: red;
}
```

---

# Question: What are the two syntax styles supported by Stylus?

**Answer:**  
Stylus supports two versions of syntax: one that uses braces `{}` and semicolons `;`, and another that omits braces and semicolons. Additionally, Stylus allows omission of colons `:` between property names and values.

---

# Question: How does Stylus compare to SASS in terms of syntax flexibility?

**Answer:**  
Stylus offers more syntax flexibility than SASS by allowing the omission of braces, semicolons, and colons. This makes Stylus code often shorter and cleaner than SASS, which requires stricter syntax rules.

---

# Question: What is predicted about Stylus’s future in relation to SASS?

**Answer:**  
If Stylus continues to be developed and retains its current features, it is predicted to become the biggest competitor to SASS.

---

# Question: Which preprocessor is described as the most mature in the given content?

**Answer:**  
SASS is described as the most mature CSS preprocessor in the given content.
