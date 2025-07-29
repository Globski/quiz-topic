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

# Question: Why might a CSS rule not be applied even if it is written in the stylesheet?

**Answer:** Because another rule with higher specificity (e.g. a class selector) is overriding it.

---

# Question: What is an example of a CSS class having higher specificity than an element selector?

**Answer:** If a paragraph has the class `gray`, the rule for `.gray` will override a general `p` selector.

---

# Question: What tool in Chrome allows you to inspect and debug CSS rules?

**Answer:** Chrome DevTools, accessed by right-clicking and choosing **Inspect**.

---

# Question: In Chrome DevTools, where can you see the CSS rules applied to an element?

**Answer:** In the **Elements** tab under the **Styles** section.

---

# Question: What does it mean when a CSS rule appears crossed out in the Styles tab of DevTools?

**Answer:** It means the rule is being overridden by a more specific rule.

---

# Question: What should you do when a CSS rule you wrote doesn’t appear to apply as expected?

**Answer:** Use Chrome DevTools to inspect the element and review which rules are applied or overridden.

---

# Question: What is the rule of specificity in CSS?

**Answer:** CSS applies the most specific rule among competing styles, overriding less specific ones.

---

# Question: What is CSS inheritance?

**Answer:** Inheritance is when child elements receive CSS properties from their parent elements.

---

# Question: Which HTML element is typically the parent to all others and thus a source for inheritance?

**Answer:** The `<body>` element.

---

# Question: Which types of CSS properties are typically inherited?

**Answer:** Properties related to font and typography, such as `font-size`, `color`, `line-height`, and `text-align`.

---

# Question: Which types of CSS properties are **not** inherited?

**Answer:** Properties unrelated to font and typography, such as `border`.

---

# Question: If a `border` property is set on the body, why doesn’t it apply to all child elements?

**Answer:** Because `border` is not an inheritable property.

---

# Question: What is the difference between using the universal selector and relying on inheritance?

**Answer:** The universal selector (`*`) directly selects and applies styles to all elements, while inheritance passes properties from parent to child elements.

---

# Question: How do you apply a border to all elements on the page using the universal selector?

**Answer:** Use `* { border: 1px solid red; }`.

---

# Question: Why does a CSS rule using the universal selector (`*`) apply to all elements?

**Answer:** Because the universal selector directly targets all elements on the page, not through inheritance but by explicit selection.

---

# Question: Does the universal selector cause inheritance?

**Answer:** No, it selects all elements directly; it does not rely on or trigger inheritance.

---

# Question: What does the acronym DRY stand for in coding best practices?

**Answer:** Don't Repeat Yourself.

---

# Question: How does CSS inheritance support the DRY principle?

**Answer:** Inheritance allows shared properties (like font settings) to be written once on a parent element and automatically apply to child elements, reducing repetitive code.

---

# Question: Which CSS properties do form elements typically not inherit?

**Answer:** Font size and other typography-related settings.

---

# Question: Which form elements typically need to have `font: inherit` explicitly set to receive font styles?

**Answer:** `button`, `input`, `textarea`, and `select`.

---

# Question: How can you make form elements like input and button inherit font styles?

**Answer:** By explicitly setting `font: inherit;` in their CSS rule.

---

# Question: Which two HTML elements are commonly used to apply inherited CSS properties site-wide?

**Answer:** The `body` element and the `html` element.

---

# Question: Which HTML element appears only once per page and is often used for setting global styles?

**Answer:** Both the `html` and `body` elements appear once and can be used for setting global inherited styles.

---

# Question: Why might someone prefer using the `html` selector over the `body` selector for font settings?

**Answer:** Because `html` applies inheritance from the root and keeps font settings separate from the body’s default styles, offering better organization and clarity.

---

# Question: What is the purpose of the `main` semantic element in HTML?

**Answer:** To represent the main content of the document, and it should appear only once per page.

---

# Question: What is the least specific type of CSS selector?

**Answer:** The element selector (e.g., `p`, `div`).

---

# Question: Which CSS selector type is more specific than an element selector but less specific than an ID selector?

**Answer:** A class selector (e.g., `.gray`).

---

# Question: What is the most specific CSS selector type among element, class, and ID selectors?

**Answer:** The ID selector (e.g., `#main-heading`).

---

# Question: What is the `!important` flag in CSS used for?

**Answer:** To force a CSS rule to override all other rules, regardless of specificity.

---

# Question: Why is using `!important` in CSS generally discouraged?

**Answer:** It bypasses normal specificity rules and can lead to code that is difficult to debug and maintain.

---

# Question: What happens when a CSS rule uses the `!important` flag?

**Answer:** It overrides all other rules, regardless of specificity, and applies the declared style forcefully.

---

# Question: Why should the `!important` flag be avoided in CSS?

**Answer:** Because it disrupts normal specificity rules, can lead to messy and unmanageable code, and is often a sign of poor CSS organization.

---

# Question: When is it acceptable to use `!important` in CSS?

**Answer:** Only when you fully understand CSS specificity and have no better option; it should be used sparingly by experienced developers.

---

# Question: What learning tool can help understand CSS specificity?

**Answer:** The Specificity Calculator.

---

# Question: In the specificity calculator, what is the score of an element selector like `h2`?

**Answer:** 0-0-1 (or simply 1).

---

# Question: What is the specificity score of a class selector like `.gray`?

**Answer:** 0-1-0 (or 10).

---

# Question: What is the specificity score of an ID selector like `#second`?

**Answer:** 1-0-0 (or 100).

---

# Question: If an element has multiple classes, how does that affect its specificity score?

**Answer:** The specificity score adds up per class. For example, two classes (`.highlight.gray`) result in a score of 0-2-0 (or 20).

---

# Question: Can multiple class selectors combined ever override an ID selector based on specificity?

**Answer:** No, even multiple class selectors (e.g., 0-2-0 = 20) do not override an ID selector (1-0-0 = 100).

---

# Question: What is the purpose of using a specificity calculator?

**Answer:** To compare selectors and understand why certain CSS rules override others based on specificity scoring.

---

# Question: What are the default colors of most browsers for web pages?

**Answer:** A white background and black text.

---

# Question: What CSS property is used to change the background color of an element?

**Answer:** `background-color`.

---

# Question: What HTML structure was used in the example webpage?

**Answer:** An `h1` heading and three `article` elements, each containing an `h2` heading and a paragraph.

---

# Question: Which CSS declarations were already applied to make the sample page more readable?

**Answer:** Larger font size, a specified font family, and line height.

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

---

# Question: What property must be set on a container to start using Flexbox?

**Answer:** The container must have `display: flex` set in the CSS.

---

# Question: What does setting `display: flex` do to a container's layout?

**Answer:** It creates two invisible axes: a main axis and a cross axis, and aligns child items along the main axis by default.

---

# Question: What is the default direction of the main axis in Flexbox?

**Answer:** Horizontal (left to right).

---

# Question: How do you change the main axis direction in Flexbox to vertical?

**Answer:** Use the `flex-direction` property and set it to `column`.

---

# Question: What value of `flex-direction` sets the main axis to horizontal?

**Answer:** `row`, which is also the default value.

---

# Question: What property is used to align items along the main axis?

**Answer:** `justify-content`.

---

# Question: What does `justify-content: flex-start` do?

**Answer:** Aligns items to the start of the main axis. This is the default.

---

# Question: What does `justify-content: flex-end` do?

**Answer:** Pushes items to the end of the main axis.

---

# Question: What does `justify-content: center` do?

**Answer:** Centers items along the main axis.

---

# Question: What does `justify-content: space-between` do?

**Answer:** Distributes items evenly along the main axis, placing the first and last items at the ends with space in between.

---

# Question: What does `justify-content: space-around` do?

**Answer:** Distributes items with equal space around them, including space on the outer edges.

---

# Question: What does `justify-content: space-evenly` do?

**Answer:** Evenly distributes items so that the spacing between any two items (and the container edges) is equal.

---

# Question: What property is used to align items along the cross axis?

**Answer:** `align-items`.

---

# Question: What does `align-items: flex-start` do?

**Answer:** Aligns items at the start of the cross axis.

---

# Question: What does `align-items: flex-end` do?

**Answer:** Aligns items at the end of the cross axis.

---

# Question: What does `align-items: center` do?

**Answer:** Centers items along the cross axis.

---

# Question: What does `align-items: baseline` do?

**Answer:** Aligns the baseline of text across items, so their text baselines line up.

---

# Question: How can you see the effect of `align-items: baseline` clearly?

**Answer:** By increasing the font size of some items, you can see that the text baselines still align.

---

# Question: If `flex-direction` is not defined, what is the default value?

**Answer:** `row`.

---

# Question: What is the default direction of the cross axis?

**Answer:** Vertical (top to bottom), when `flex-direction` is `row`.

---

# Question: What happens to the main and cross axes when `flex-direction: column` is set?

**Answer:** The main axis becomes vertical, and the cross axis becomes horizontal.

---

# Question: In Flexbox, which property determines how items behave when they exceed the container width?

**Answer:** `flex-wrap`.

---

# Question: What is the default value of the `flex-wrap` property?

**Answer:** `nowrap`.

---

# Question: What does setting `flex-wrap: wrap` do?

**Answer:** Allows Flex items to wrap onto multiple lines instead of trying to fit into one.

---

# Question: What property enables wrapping behavior in a Flexbox container?

**Answer:** `flex-wrap`.

---

# Question: What must be true for the `align-content` property to have any effect?

**Answer:** The container must have `flex-wrap` set to `wrap`, and items must actually wrap to multiple lines.

---

# Question: What does the `align-content` property do in Flexbox?

**Answer:** It aligns multiple lines of Flex items along the cross axis.

---

# Question: What values can `align-content` take?

**Answer:** `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`.

---

# Question: How can you add spacing between Flex items?

**Answer:** Use the `gap` property on the container.

---

# Question: Where should the `gap` property be applied to affect Flex items?

**Answer:** On the Flex container.

---

# Question: Which Flexbox properties are applied to the **children** (Flex items) instead of the container?

**Answer:** `flex-grow`, `flex-shrink`, `flex-basis`, `flex`, and `align-self`.

---

# Question: What does the `flex-grow` property do?

**Answer:** It allows a Flex item to grow and take up remaining space in the container based on a proportional value.

---

# Question: What type of value does `flex-grow` accept?

**Answer:** A unitless number representing proportion.

---

# Question: What happens if three Flex items all have `flex-grow: 1`?

**Answer:** They will each grow equally and share the remaining space evenly.

---

# Question: What does the `flex-shrink` property control?

**Answer:** It defines how quickly an item shrinks relative to other items when space is limited.

---

# Question: What value should `flex-shrink` be set to in order to prevent shrinking?

**Answer:** `0`.

---

# Question: If `flex-shrink: 5` is applied to an item, what will happen?

**Answer:** That item will shrink five times faster than items with `flex-shrink: 1`.

---

# Question: What does the `flex-basis` property define?

**Answer:** The initial size of a Flex item before remaining space is distributed.

---

# Question: What happens if an item has both a `width` and a `flex-basis` value?

**Answer:** The `flex-basis` value will override the `width`.

---

# Question: What happens if `flex-basis` is set to `0`?

**Answer:** The item will shrink as much as possible before growing or distributing space.

---

# Question: What is the shorthand property for `flex-grow`, `flex-shrink`, and `flex-basis`?

**Answer:** `flex`.

---

# Question: How many parameters can the `flex` shorthand accept?

**Answer:** Up to three: `flex-grow`, `flex-shrink`, and `flex-basis`. The second and third are optional.

---

# Question: What happens when `flex` is set to a single value, like `flex: 1`?

**Answer:** The `flex-shrink` and `flex-basis` values are automatically set to intelligent defaults.

---

# Question: What does the `align-self` property do?

**Answer:** It overrides the `align-items` value on the container for a specific Flex item.

---

# Question: How would you align just one Flex item (e.g., the first item) to the center of the cross axis while others follow the container rule?

**Answer:** Set `align-self: center` on that item.

---

# Question: What Flexbox property allows individual items to override the `align-items` value set on the container?

**Answer:** `align-self`.

---

# Question: What values can be used with the `align-self` property?

**Answer:** `flex-start`, `flex-end`, `center`, and `baseline`.

---

# Question: What Flexbox property allows changing the visual order of items regardless of their order in the HTML?

**Answer:** `order`.

---

# Question: What is the default value of the `order` property in Flexbox?

**Answer:** `0`.

---

# Question: How can you make the last item appear first using the `order` property?

**Answer:** Set its `order` value to `-1`.

---

# Question: What happens if an item is given an `order` value of `1` while all other items remain at the default?

**Answer:** That item will appear after the others in the layout.

---

# Question: Why should the `order` property be used cautiously?

**Answer:** Because it can break the semantic structure and accessibility of the HTML document.

---

# Question: What is the first step when using Flexbox to create a layout in HTML?

**Answer:** Define a reference point in HTML, such as the `<body>` or a specific container element.

---

# Question: What happens to elements when `display: flex` is applied to their parent container?

**Answer:** The child elements are aligned side by side (horizontally), rather than stacked vertically.

---

# Question: What are the default display values for most HTML elements?

**Answer:** `block` or `inline`.

---

# Question: What behavior do block-level elements have by default?

**Answer:** Block-level elements take up the entire width of the screen and force subsequent elements onto the next line.

---

# Question: What property initiates the Flexbox layout system?

**Answer:** `display: flex`.

---

# Question: What are the two axes used in Flexbox to position items?

**Answer:** The **main axis** and the **cross axis**.

---

# Question: Which property controls positioning along the main axis in Flexbox?

**Answer:** `justify-content`.

---

# Question: What does the `justify-content: flex-start` value do?

**Answer:** Aligns items to the start of the main axis (default behavior, aligns items to the left).

---

# Question: What does the `justify-content: flex-end` value do?

**Answer:** Aligns items to the end of the main axis (right side).

---

# Question: What does the `justify-content: center` value do?

**Answer:** Aligns items to the center of the main axis.

---

# Question: What two lines of CSS are needed to center elements horizontally using Flexbox?

**Answer:**

```css
display: flex;  
justify-content: center;
```

---

# Question: What common CSS layout problems can Flexbox help solve easily?

**Answer:** Centering elements and creating responsive layouts with minimal code.

---

# Question: What Flexbox axis must be used to align elements vertically?

**Answer:** The cross axis.

---

# Question: Which CSS property is used to align elements along the cross axis?

**Answer:** `align-items`.

---

# Question: What CSS value for `align-items` positions elements at the top of the container?

**Answer:** `flex-start`.

---

# Question: What CSS value for `align-items` positions elements at the bottom of the container?

**Answer:** `flex-end`.

---

# Question: What CSS value for `align-items` centers elements vertically in the container?

**Answer:** `center`.

---

# Question: What three lines of CSS are needed to center elements both horizontally and vertically using Flexbox?

**Answer:**

```css
display: flex;  
justify-content: center;  
align-items: center;
```

---

# Question: Why does a Flexbox layout remain centered even when resizing the layout?

**Answer:** Because Flexbox is inherently flexible and adapts to the size changes of the container.

---

# Question: What are the three advanced values for `justify-content` and `align-items`?

**Answer:** `space-between`, `space-around`, and `space-evenly`.

---

# Question: What does the `space-between` value do?

**Answer:** Distributes items evenly from left to right with the first and last items touching the edges of the container.

---

# Question: What is the behavior of `space-around` in Flexbox?

**Answer:** Gives equal space on both sides of each element, but results in doubled spacing between adjacent elements compared to the edges.

---

# Question: What issue can arise when using `space-around` in Flexbox?

**Answer:** The spacing between elements is twice as large as the space between the elements and the container's edges.

---

# Question: What is the advantage of using `space-evenly` in Flexbox?

**Answer:** It distributes equal space between all items and between the items and container edges, resulting in perfectly balanced spacing.

---

# Question: Do `justify-content` and `align-items` automatically adjust to container size changes?

**Answer:** Yes, all values adjust dynamically with container resizing.

---

# Question: Can the same values used in `justify-content` also be used in `align-items`?

**Answer:** Yes, but they may not be meaningful if there is only one row of content.

---

# Question: What Flexbox property controls the direction of the main axis?

**Answer:** `flex-direction`.

---

# Question: What is the default value of `flex-direction`?

**Answer:** `row`.

---

# Question: What does `flex-direction: row` do?

**Answer:** Sets the main axis to run from left to right.

---

# Question: What effect does `flex-direction: row-reverse` have?

**Answer:** Reverses the main axis to run from right to left, with items ordered accordingly.

---

# Question: What effect does `flex-direction: row-reverse` have on `justify-content` values?

**Answer:** It reverses the main axis direction, so `flex-start` aligns items to the right and `flex-end` to the left.

---

# Question: What does `flex-direction: column` do?

**Answer:** It changes the main axis to run from top to bottom, stacking elements vertically.

---

# Question: When using `flex-direction: column`, which property centers elements **horizontally**?

**Answer:** `align-items: center`.

---

# Question: Why is it important to remember the `flex-direction` of your layout?

**Answer:** Because it changes the orientation of the main and cross axes, which directly affects how alignment properties like `justify-content` and `align-items` behave.

---

# Question: What is the default value of `flex-direction` in Flexbox?

**Answer:** `row`.

---

# Question: What Flexbox configuration would you use to align all elements vertically while centering them horizontally?

**Answer:**

```css
display: flex;
flex-direction: column;
align-items: center;
```

---

# Question: What does the `gap` property do in a Flexbox layout?

**Answer:** It creates consistent spacing between items without needing to use margins.

---

# Question: Why is the `gap` property preferred over using margins in Flexbox?

**Answer:** Because it simplifies spacing between items and avoids issues like collapsing margins or asymmetric gaps.

---

# Question: What does the `flex-wrap` property control?

**Answer:** It determines whether Flexbox items stay in one line or wrap onto multiple lines when there isn't enough space.

---

# Question: What are the two main values of the `flex-wrap` property?

**Answer:** `wrap` and `nowrap`.

---

# Question: What happens when you use `flex-wrap: wrap`?

**Answer:** Items will wrap onto new lines when there isn't enough space in one line, creating a responsive layout.

---

# Question: What happens when you use `flex-wrap: nowrap`?

**Answer:** Items stay on a single line and shrink to fit the container, even if they overflow.

---

# Question: What Flexbox configuration can create a responsive layout that centers content and wraps items as needed?

**Answer:**

```css
display: flex;
flex-wrap: wrap;
justify-content: center;
align-items: center;
```

---

# Question: Why might there be a large gap between wrapped lines when using `flex-wrap`?

**Answer:** Because each wrapped line becomes its own flex container with its own main and cross axes, and spacing is controlled per line.

---

# Question: How does the number of items affect layout behavior when using `flex-wrap`?

**Answer:** More items can lead to multiple line breaks, with each line having its own main and cross axes, which impacts alignment.

---

# Question: How does `align-items` behave when multiple flex lines are present due to `flex-wrap`?

**Answer:** It controls the alignment of items within **each individual line**, not across all lines.

---

# Question: What does `align-items: flex-start` do in a multi-line Flexbox layout?

**Answer:** Aligns items at the start of each cross axis for each individual flex line.

---

# Question: What does `align-items: flex-end` do in a multi-line Flexbox layout?

**Answer:** Aligns items at the end of each cross axis for each individual flex line.

---

# Question: What does `align-items: center` do in a multi-line Flexbox layout?

**Answer:** Aligns items to the center of each cross axis for each individual flex line.

---

# Question: What does the `align-content` property control in Flexbox?

**Answer:** It controls the alignment of **all lines together** in a multi-line flex container along the cross axis.

---

# Question: What is the default value of the `align-content` property?

**Answer:** `space-around`.

---

# Question: How does `align-items` differ from `align-content`?

**Answer:** `align-items` aligns **individual items** within each line on the cross axis, while `align-content` aligns **all lines as a group** on the cross axis.

---

# Question: What three Flexbox properties must be centered to achieve a perfectly centered layout that adapts to wrapping?

**Answer:**

```css
justify-content: center;
align-items: center;
align-content: center;
```

---

# Question: How can you apply different vertical and horizontal gaps between Flexbox items?

**Answer:** Use `row-gap` for vertical spacing and `column-gap` for horizontal spacing.

---

# Question: What does `row-gap: 20px; column-gap: 10px;` do in a Flexbox layout?

**Answer:** It sets a 20px gap between rows and a 10px gap between columns.

---

# Question: Why is `gap` usually preferred over `row-gap` and `column-gap` in Flexbox layouts?

**Answer:** Because most layouts only need uniform spacing, making the single `gap` property simpler and more efficient to use.

---

# Question: Why are `row-gap` and `column-gap` more relevant to Grid layouts than Flexbox?

**Answer:** Because Grid layouts typically involve both row and column structures, making separate control of horizontal and vertical gaps more useful.

---

# Question: Can Flexbox be used on any HTML element or only on the `<body>`?

**Answer:** It can be used on **any HTML element**, not just the `<body>`.

---

# Question: How can you center the numbers **inside each box** using Flexbox?

**Answer:**

```css
display: flex;
justify-content: center;
align-items: center;
```

---

# Question: When centering content **inside flex items**, where should the Flexbox properties be applied?

**Answer:** On the **individual item containers** (e.g., the box selectors), not the outer parent container.

---

# Question: What is the first step to create a layout where boxes resize responsively without wrapping?

**Answer:** Set `display: flex` on the container and **do not use** `flex-wrap`.

---

# Question: What Flexbox property enables boxes to shrink when the viewport gets too small?

**Answer:** `flex-shrink`.

---

# Question: On which elements is the `flex-shrink` property applied?

**Answer:** On the **flex items**, not the container.

---

# Question: What are the only two properties required on the container for a basic responsive resizing layout?

**Answer:**

```css
display: flex;
gap: 10px;
```
---

# Question: What does the `flex-shrink` property do?

**Answer:** It allows flex items to **shrink** when the container becomes too small to fit all items.

---

# Question: What is the default value of `flex-shrink`?

**Answer:** `1` — this means all flex items shrink by default if necessary.

---

# Question: What happens when you set `flex-shrink: 0` on a flex item?

**Answer:** The item will **not shrink**, even if there's not enough space, which may cause it to overflow.

---

# Question: When should you disable `flex-shrink` on a flex item?

**Answer:** When you don’t want the item to distort — for example, an image or icon.

---

# Question: What is the primary difference between `flex-shrink` and `flex-grow`?

**Answer:**

* `flex-shrink` controls **how much an item can shrink** if needed.
* `flex-grow` controls **how much an item can grow** to fill extra space.

---

# Question: What is the default value of `flex-grow`?

**Answer:** `0`, meaning items do **not grow** unless explicitly allowed.

---

# Question: What happens if you set `flex-grow: 1` on all flex items?

**Answer:** All items will **share the available space equally**, growing to fill the parent container.

---

# Question: What happens if one flex item has `flex-grow: 5` and others have `flex-grow: 1`?

**Answer:** The item with `flex-grow: 5` will grow **five times faster** than the others, taking up more space proportionally.

---

# Question: Do `flex-grow` and `flex-shrink` work as simple on/off switches?

**Answer:** No, they act as **multipliers** and determine the proportion of growing or shrinking **relative to other items**.

---

# Question: How can you prevent only the **first box** from shrinking in a layout?

**Answer:** Assign `flex-shrink: 0` to the first box and leave the others at `flex-shrink: 1`.

---

# Question: How do you make a text element grow while its sibling elements (like buttons) stay the same size?

**Answer:** Apply `flex-grow: 1` to the text element and `flex-grow: 0` to the others.

---

# Question: In the context of responsive design, why is `flex-grow` useful?

**Answer:** It helps **dynamically allocate available space** to specific items, allowing layouts to **adapt smoothly to different screen sizes**.

---

# Question: Does setting `flex-grow: 5` guarantee that the item will be five times bigger?

**Answer:** No, it means the item will grow **five times faster than other items**, not necessarily be five times the size.

---

# Question: What does the `flex-shrink` property do?

**Answer:** It allows flex items to **shrink** when the container becomes too small to fit all items.

---

# Question: What is the default value of `flex-shrink`?

**Answer:** `1` — this means all flex items shrink by default if necessary.

---

# Question: What happens when you set `flex-shrink: 0` on a flex item?

**Answer:** The item will **not shrink**, even if there's not enough space, which may cause it to overflow.

---

# Question: When should you disable `flex-shrink` on a flex item?

**Answer:** When you don’t want the item to distort — for example, an image or icon.

---

# Question: What is the primary difference between `flex-shrink` and `flex-grow`?

**Answer:**

* `flex-shrink` controls **how much an item can shrink** if needed.
* `flex-grow` controls **how much an item can grow** to fill extra space.

---

# Question: What is the default value of `flex-grow`?

**Answer:** `0`, meaning items do **not grow** unless explicitly allowed.

---

# Question: What happens if you set `flex-grow: 1` on all flex items?

**Answer:** All items will **share the available space equally**, growing to fill the parent container.

---

# Question: What happens if one flex item has `flex-grow: 5` and others have `flex-grow: 1`?

**Answer:** The item with `flex-grow: 5` will grow **five times faster** than the others, taking up more space proportionally.

---

# Question: Do `flex-grow` and `flex-shrink` work as simple on/off switches?

**Answer:** No, they act as **multipliers** and determine the proportion of growing or shrinking **relative to other items**.

---

# Question: How can you prevent only the **first box** from shrinking in a layout?

**Answer:** Assign `flex-shrink: 0` to the first box and leave the others at `flex-shrink: 1`.

---

# Question: How do you make a text element grow while its sibling elements (like buttons) stay the same size?

**Answer:** Apply `flex-grow: 1` to the text element and `flex-grow: 0` to the others.

---

# Question: In the context of responsive design, why is `flex-grow` useful?

**Answer:** It helps **dynamically allocate available space** to specific items, allowing layouts to **adapt smoothly to different screen sizes**.

---

# Question: Does setting `flex-grow: 5` guarantee that the item will be five times bigger?

**Answer:** No, it means the item will grow **five times faster than other items**, not necessarily be five times the size.

---

# Question: When does a flex item with a higher `flex-grow` value take up more space?

**Answer:** When **extra space becomes available**, the item with the higher `flex-grow` value takes a larger portion relative to others.

---

# Question: If a flex item has `flex-shrink: 5`, what does it mean?

**Answer:** It will shrink **five times faster** than items with `flex-shrink: 1` when space is limited.

---

# Question: Why would you use `min-width` and `max-width` with Flexbox?

**Answer:** To **limit how much an item can grow or shrink**, ensuring it doesn’t become too large or too small when resizing.

---

# Question: What happens if a flex item grows beyond its `max-width`?

**Answer:** It **stops growing** once it reaches the `max-width` and will not get larger.

---

# Question: What happens if a flex item shrinks below its `min-width`?

**Answer:** It will **overflow** the container instead of shrinking further.

---

# Question: How can you prevent shrinking but still allow items to wrap when the screen gets too small?

**Answer:** Use `flex-shrink` with `min-width`, and then apply `flex-wrap: wrap` inside a **media query** when overflow starts.

---

# Question: Which CSS property lets you align a **single flex item** differently along the **cross axis**?

**Answer:** `align-self`

---

# Question: How is `align-self` different from `align-items`?

**Answer:**

* `align-items` applies to **all flex items**,
* `align-self` overrides that setting **for individual items**.

---

# Question: Can you use `justify-self` to align a single flex item along the **main axis**?

**Answer:** No, `justify-self` **does not work in Flexbox** — it's a property used in **CSS Grid**.

---

# Question: If you want to position only the **first flex item** at the bottom while others stay at the top, which property do you use?

**Answer:** `align-self: flex-end` on the first item (with `align-items: flex-start` on the container).

---

# Question: How can you isolate alignment of individual flex items?

**Answer:** By applying the `align-self` property on the **specific item** you want to align differently.

---

# Question: Why is `justify-self` not available in Flexbox?

**Answer:** Because Flexbox is designed to **distribute space across the main axis** using group-based properties like `justify-content`, and individual item justification is handled differently — such as with **margins**.

---

# Question: What is the "old school" CSS technique to push all other elements to the right in a navigation bar?

**Answer:** Use `margin-right: auto` on the leftmost element (e.g., company logo) to push all other elements to the right.

---

# Question: In a navigation bar, how does `margin-right: auto` help with layout?

**Answer:** It forces the element with the margin to stay on the left while pushing the subsequent elements to the right.

---

# Question: What are the main axes used in CSS Flexbox for layout alignment?

**Answer:** The **main axis** and the **cross axis**.

---

# Question: Which Flexbox properties align elements along the main and cross axes?

**Answer:** `justify-content` aligns along the main axis, and `align-items` aligns along the cross axis.

---

# Question: How can you wrap elements to the next line using Flexbox?

**Answer:** Use `flex-wrap: wrap`.

---

# Question: What Flexbox properties control element resizing?

**Answer:** `flex-grow` and `flex-shrink`.

---

# Question: How can you apply different sizing behaviors to each element in a flex container?

**Answer:** Assign different values to `flex-grow` and `flex-shrink` for each element.

---

# Question: Which additional CSS techniques can be combined with Flexbox for layout control?

**Answer:** Use **minimum and maximum sizes** and **media queries**.

---

# Question: What layout scenarios make CSS Grid a better choice than Flexbox?

**Answer:** CSS Grid is better for creating **more complex layouts** or **simplifying code** with **fewer lines**.

---

# Question: What is the common Flexbox approach to center a `<div>`?

**Answer:** Use `display: flex; justify-content: center; align-items: center;`.

---

# Question: What is the CSS Grid equivalent to center a `<div>` in fewer lines?

**Answer:** Use `display: grid; place-content: center;`.

---

# Question: How many lines of CSS are typically required to center a div using Flexbox vs. Grid?

**Answer:** Flexbox requires **3 lines**; Grid requires **2 lines**.

---

# Question: What is the key difference between Flexbox and CSS Grid in terms of layout dimensions?

**Answer:** CSS Grid is two-dimensional, allowing positioning both horizontally and vertically at the same time.

---

# Question: What do the numbers on a CSS Grid represent?

**Answer:** They represent **grid lines** — row lines and column lines used for positioning elements.

---

# Question: What are the three key components of a CSS Grid layout?

**Answer:** **Cells**, **grid lines** (row and column lines), and **tracks** (rows and columns).

---

# Question: How do you begin creating a grid layout in HTML?

**Answer:** By creating a container `<div>` with a class (e.g., `container`) and child `<div>`s with item classes (e.g., `item`, `item-1`, `item-2`, etc.).

---

# Question: What CSS property turns a container into a grid?

**Answer:** `display: grid`

---

# Question: Why does setting `display: grid` not visually change anything by itself?

**Answer:** Because no **rows** or **columns** have been defined yet.

---

# Question: How do you define rows and columns in a grid?

**Answer:** Using the `grid-template-rows` and `grid-template-columns` properties.

---

# Question: How do `grid-template-rows` and `grid-template-columns` work?

**Answer:** Each value defines one **track** (row or column); multiple values create multiple tracks.

---

# Question: What happens if you define `grid-template-columns: 100px 100px`?

**Answer:** It creates two columns, each 100 pixels wide.

---

# Question: How do you create a grid with 6 rows and 6 columns of equal size?

**Answer:** Set both `grid-template-rows` and `grid-template-columns` to six `100px` values.

---

# Question: How can you position an item using individual line number properties?

**Answer:** Use `grid-row-start`, `grid-row-end`, `grid-column-start`, and `grid-column-end`.

---

# Question: How would you place an item starting on row line 1 and column line 1, ending at row line 3 and column line 5?

**Answer:**

```css
grid-row-start: 1;  
grid-row-end: 3;  
grid-column-start: 1;  
grid-column-end: 5;
```

---

# Question: What happens to other items when you explicitly position one item in the grid?

**Answer:** The unpositioned items are pushed out of the way automatically.

---

# Question: What is the shorthand for defining grid row and column start/end positions?

**Answer:** Use the `grid-row` and `grid-column` shorthand properties.

---

# Question: What syntax is used with `grid-row` and `grid-column` shorthands?

**Answer:** Two values separated by a slash: the **starting line** and the **ending line** (e.g., `grid-row: 1 / 3;`).

---

# Question: How do you use `grid-row` and `grid-column` to make an item span two rows and two columns?

**Answer:**

```css
grid-row: 1 / 3;  
grid-column: 5 / 7;
```

---

# Question: What is the purpose of the `span` keyword in grid positioning?

**Answer:** It allows an item to span a specific number of tracks from its current position without specifying start/end lines.

---

# Question: How would you use `span` to make an item span two columns?

**Answer:** `grid-column: span 2;`

---

# Question: What is a downside of using the `span` keyword?

**Answer:** You can't **explicitly define start and end positions**, so items may shift if nearby items change.

---

# Question: What can happen if you use `span` and a nearby item's size increases?

**Answer:** The item using `span` can be pushed away from its intended position.

---

# Question: When is it okay to use the `span` keyword in CSS Grid?

**Answer:** When you don’t need to anchor the item to a specific position.

---

# Question: What is the fastest way to position an item using four grid line values?

**Answer:** Use the `grid-area` property.

---

# Question: What are the four values required for the `grid-area` shorthand?

**Answer:** `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end`, in that order.

---

# Question: What is the syntax to make a grid item start at row 3, end at row -1, and span columns from 1 to -1?

**Answer:** Use `grid-area: 3 / 1 / -1 / -1;` which sets start-row, start-column, end-row, and end-column respectively.

---

# Question: What do negative numbers like `-1` represent in CSS Grid positioning?

**Answer:** Negative numbers count from the end of the grid, so `-1` refers to the last line of the grid in either rows or columns.

---

# Question: How many CSS properties does the `grid-area` shorthand replace?

**Answer:** It replaces six properties: `grid-row-start`, `grid-column-start`, `grid-row-end`, `grid-column-end`, and optionally positioning-related values.

---

# Question: How was layering done before CSS Grid, and what were its limitations?

**Answer:** It required `position: absolute` and manually adjusting `top`, `right`, `bottom`, and `left`, making it difficult to maintain and position elements precisely.

---

# Question: How does CSS Grid simplify layering of items?

**Answer:** By allowing items to occupy the same grid cells naturally, and controlling which is on top using `z-index`.

---

# Question: What grid-area values would position an item from row 2 to 4 and column 4 to 6?

**Answer:** `grid-area: 2 / 4 / 4 / 6;`

---

# Question: How do you ensure an item appears on top of others in CSS Grid?

**Answer:** Use `z-index: 1` or any higher value to bring it above other elements.

---

# Question: What happens if you place an item in the grid when all defined cells are already occupied?

**Answer:** The grid automatically creates a new row, forming an **implicit grid**.

---

# Question: Why might a new item in an implicit grid appear smaller than other grid items?

**Answer:** Because implicit grids don’t inherit the sizing defined in `grid-template-rows` and `grid-template-columns`.

---

# Question: How can you control the size of newly added rows in an implicit grid?

**Answer:** Use the `grid-auto-rows` property on the container, e.g., `grid-auto-rows: 100px;`

---

# Question: What does the `grid-auto-flow: column;` property do?

**Answer:** It changes the direction of implicit grid creation from rows (default) to columns.

---

# Question: How can you set the size of implicit columns when `grid-auto-flow` is set to `column`?

**Answer:** Use `grid-auto-columns`, e.g., `grid-auto-columns: 100px;`

---

# Question: What units can be used inside `grid-template-rows` and `grid-template-columns`?

**Answer:** Pixels (`px`), ems (`em`), root ems (`rem`), percentages (`%`), and fractional units (`fr`).

---

# Question: What does the `fr` unit in CSS Grid represent?

**Answer:** A fractional portion of the available space in the grid container.

---

# Question: What happens if you define three columns with `1fr 1fr 1fr`?

**Answer:** The available space is divided equally among the three columns.

---

# Question: How does changing one of the `fr` values affect column widths?

**Answer:** The column with a higher `fr` value will occupy a larger portion of the available space. For example, `1fr 2fr 1fr` gives the second column twice as much width as the others.

---

# Question: Can you mix `fr` units with other units like `px` or `%` in the same grid definition?

**Answer:** Yes, `fr` units can be mixed with other units without issues.

---

# Question: How can you set a minimum and maximum width for a grid column?

**Answer:** Use the `minmax()` function in `grid-template-columns`, where the first argument is the minimum size and the second is the maximum, e.g., `minmax(100px, 3fr)`.

---

# Question: What problem does `minmax()` solve in CSS Grid layouts?

**Answer:** It prevents items from becoming too small by enforcing a minimum size while still allowing them to grow up to a maximum size.

---

# Question: What is the syntax for repeating values in CSS Grid using the `repeat()` function?

**Answer:** `repeat(n, value)`, where `n` is the number of times to repeat the `value`. For example, `repeat(2, 100px)` creates two 100px rows.

---

# Question: What is the benefit of using the `repeat()` function in grid templates?

**Answer:** It reduces repetition in code and improves readability by avoiding manually repeating the same value multiple times.

---

# Question: How do you add space between grid rows and columns using one value?

**Answer:** Use the `grid-gap` property with a single value, e.g., `grid-gap: 10px;`, which applies equally to rows and columns.

---

# Question: What happens when you assign two values to the `grid-gap` property?

**Answer:** The first value is applied to row gaps, and the second is applied to column gaps, e.g., `grid-gap: 10px 20px;`.

---

# Question: How does each line of `grid-template-areas` correspond to the layout?

**Answer:** Each set of single quotes represents a row, and each word inside them represents a column. For example:

```css
grid-template-areas:
  'header header'
  'main aside'
  'footer footer';
```

---

# Question: How do you assign a grid item to a named section using `grid-template-areas`?

**Answer:** Use the `grid-area` property on the item, assigning it a name like `grid-area: header;`, which corresponds to a name in `grid-template-areas`.

---

# Question: What is the purpose of using `grid-template-areas` in CSS Grid?

**Answer:** It provides a more readable and declarative way to position items in the grid without needing to track line numbers.

---

# Question: How do you determine how many sets of single quotes to use in `grid-template-areas`?

**Answer:** Match the number of sets of quotes to the number of rows defined in `grid-template-rows`.

---

# Question: How many values should be inside each set of quotes in `grid-template-areas`?

**Answer:** Match the number of values to the number of columns defined in `grid-template-columns`.

---

# Question: What visual feedback does the browser give when using `grid-template-areas`?

**Answer:** Developer tools will display the named areas in the layout, showing how elements are mapped visually based on the assigned names.

---

# Question: How would you structure `grid-template-areas` for a 3-row, 2-column layout with a header, main content, aside, and footer?

**Answer:**

```css
grid-template-areas:
  'header header'
  'main aside'
  'footer footer';
```

---

# Question: What does each named area in `grid-template-areas` represent?

**Answer:** Each name (e.g., `header`, `main`, `aside`, `footer`) corresponds to a section of the grid that you can assign to a grid item using `grid-area`.

---

# Question: Is it recommended to use a single grid for the entire webpage?

**Answer:** No, in practice it's better to use multiple grids across different sections and components of the page.

---

# Question: What do the `justify-items` and `align-items` properties control in a CSS Grid container?

**Answer:** They control how items are aligned **inside their grid cells** along the **row axis** (`justify-items`) and the **column axis** (`align-items`).

---

# Question: What are the default values of `justify-items` and `align-items` in a CSS Grid?

**Answer:** Both have a default value of `stretch`, causing items to stretch to fill their grid area.

---

# Question: What effect does changing `justify-items` to `start` have on the layout?

**Answer:** Items align to the **start of the row axis**, but remain stretched along the column axis unless `align-items` is also changed.

---

# Question: What effect does changing `align-items` to `end` have on grid items?

**Answer:** Items align to the **end of the column axis**, allowing vertical positioning within their grid cells.

---

# Question: How do you align a **specific** grid item differently from the rest?

**Answer:** Use the `justify-self` and `align-self` properties on that individual grid item.

---

# Question: What does the `justify-self` property do?

**Answer:** It overrides the horizontal (row axis) alignment of a **single** grid item within its cell.

---

# Question: What does the `align-self` property do?

**Answer:** It overrides the vertical (column axis) alignment of a **single** grid item within its cell.

---

# Question: What properties allow you to align the **entire grid** inside its container?

**Answer:** `justify-content` (aligns along the row axis) and `align-content` (aligns along the column axis).

---

# Question: What values do `justify-content` and `align-content` accept?

**Answer:** `start`, `center`, `baseline`, `space-between`, `space-around`, and `space-evenly`.

---

# Question: What is the difference between `justify-items` and `justify-content`?

**Answer:** `justify-items` aligns items **within** their individual grid cells, while `justify-content` aligns the **entire grid** within the container.

---

# Question: What is a good way to create a responsive CSS grid **without using media queries**?

**Answer:** Use `repeat(auto-fit, minmax(100px, 1fr))` for `grid-template-columns`.

---

# Question: How does `auto-fit` work in CSS Grid?

**Answer:** It fills the row with as many columns as will fit based on the defined minimum size, and automatically wraps extra items to new rows as needed.

---

# Question: What happens if items in a grid using `auto-fit` and `minmax(100px, 1fr)` can no longer fit in a row?

**Answer:** They wrap onto the next row, making the grid automatically responsive.

---

# Question: What is the difference between `repeat(4, 1fr)` and `repeat(auto-fit, minmax(100px, 1fr))`?

**Answer:** `repeat(4, 1fr)` creates exactly four equal-width columns regardless of screen size, while `auto-fit` dynamically adjusts the number of columns based on available space.

---

# Question: How would you write a CSS Grid that has four rows of 100px and columns that automatically wrap when items reach 100px minimum width?

**Answer:**

```css
grid-template-rows: repeat(4, 100px);  
grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
```

---

# Question: What does CSS stand for?

**Answer:**
*CSS* stands for *Cascading Style Sheets*. It is used to control the layout and design of web pages.

---

# Question: What can you do with CSS?

**Answer:**
With *CSS*, you can style text with eye-catching headlines, drop caps, and borders, arrange images precisely, create columns and banners, highlight links with rollover effects, and apply dynamic behaviors like fading elements, moving objects, or animating buttons on mouse hover.

---

# Question: Is CSS difficult to use?

**Answer:**
No. Despite its powerful features, *CSS* is designed to streamline the process of styling web pages, making it easier and more efficient to use.

---

# Question: What is the relationship between HTML and CSS?

**Answer:**
*HTML* provides the structural framework of a web page, such as organizing content into headers, paragraphs, and lists. *CSS*, on the other hand, works with the browser to style and visually enhance that structure.

---

# Question: How does CSS enhance a heading created with HTML?

**Answer:**
*CSS* can format an HTML heading by applying styles such as making the text big, bold, red, and positioning it 50 pixels from the left edge of the window.

---

# Question: What is a “style” in CSS?

**Answer:**
A *style* in CSS is a rule that defines how a particular element on a web page should look, such as its font, color, spacing, or position.

---

# Question: What is a style sheet?
**Answer:**
A *style sheet* is a collection of CSS styles (rules) that collectively determine the appearance of an HTML document.

---

# Question: How can CSS be used to style images?

**Answer:**
*CSS* can align images along the edges of a web page (such as the right edge), add colorful borders around them, and place margins (like a 50-pixel space) between the image and surrounding text.

---

# Question: What elements can CSS styles be applied to?

**Answer:**
*CSS* styles can be applied to various elements on a web page including text, images, headings, paragraphs, and other HTML elements.

---

# Question: How can CSS be used with HTML tags?

**Answer:**
You can create CSS styles specifically for HTML tags, such as making all `<h1>` tags on a site share the same font, size, and formatting, ensuring consistent styling across all pages.

---

# Question: What limitations did web designers face before CSS?

**Answer:**
Before *CSS*, web designers were restricted to HTML's basic formatting options, which made web pages look plain and often required complex, bulky code to achieve decent layout and styling.

---

# Question: What are some key advantages of CSS over HTML?

**Answer:**
*CSS* offers more formatting choices, such as magazine-style paragraphs, control over line spacing (leading), background image tiling, and compact styling code compared to HTML’s heavy tags like `<font>`. CSS also helps pages load faster and makes updates easier.

---

# Question: How does CSS handle background images better than HTML?

**Answer:**
*CSS* allows you to add background images and control whether and how they tile (repeat), a feature HTML does not support.

---

# Question: Why does using CSS result in faster-loading web pages?

**Answer:**
*CSS* reduces file size by replacing bulky HTML formatting tags with compact style rules. This trimming of kilobytes leads to quicker page loads, especially on text-heavy websites.

---

# Question: How does CSS simplify site-wide updates?

**Answer:**
By collecting all styles in a single external *style sheet* and linking it to every page, changes made to one style automatically apply across all linked pages, allowing for quick, global updates to a site’s appearance.

---

# Question: Can CSS work without HTML?

**Answer:**
No. *CSS* cannot function on its own—it requires *HTML* to define the structure of the web page it styles.

---

# Question: What should you know before learning CSS?

**Answer:**
You should know how to create a web page using basic *HTML*, as CSS depends on it to apply styling.

---

# Question: What should you do if your HTML knowledge is rusty?

**Answer:**
If your HTML skills are rusty, you can refresh them using online tutorials like [HTMLDog](https://www.htmldog.com/guides/htmlbeginner) and [W3Schools](https://www.w3schools.com/html), or consult books like *Creating a Website: The Missing Manual* or *Head First HTML and CSS*.

---

# Question: What does HTML stand for?

**Answer:**
*HTML* stands for *Hypertext Markup Language*. It uses simple tags to define the parts of a web page.

---

# Question: What does the following HTML code represent?

```html
<!doctype html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Hey, I am the title of this web page</title>
  </head>
  <body>
    <p>Hey, I am a paragraph on this web page.</p>
  </body>
</html>
```

**Answer:**
This is a complete basic *HTML* web page that includes a doctype declaration, an `<html>` element, a `<head>` with metadata and title, and a `<body>` with content—in this case, a paragraph.

---

# Question: What is a doctype in HTML?

**Answer:**
A *doctype* is a line of code at the beginning of an HTML document that specifies the version (or flavor) of HTML being used, such as HTML 4.01 or XHTML 1.0.

---

# Question: What are some common HTML doctypes?

**Answer:**
Common *HTML* doctypes include *HTML 4.01* and *XHTML 1.0*, each available in two styles: *strict* and *transitional*. An example is:

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

---

# Question: What is the simplified doctype used in HTML5?

**Answer:**
The simplified *HTML5* doctype is:

```html
<!doctype html>
```

It is supported by all major browsers, including older ones like Internet Explorer 6.

---

# Question: Why is the HTML5 doctype preferred over older doctypes?

**Answer:**
*HTML5* is easier to use, more streamlined, and widely supported. It avoids the complexity of earlier doctypes like HTML 4.01 and XHTML and is the future of web development.

---

# Question: Do all browsers support HTML5 features equally?

**Answer:**
No. While older browsers like Internet Explorer 6 and 8 support the *HTML5 doctype*, they do **not** recognize all *HTML5 tags* or features. Styling HTML5 tags in these browsers often requires additional *JavaScript*.

---

# Question: Why must every HTML page include a doctype?

**Answer:**
Including a *doctype* ensures consistent rendering across different browsers. Without it, browsers may display CSS inconsistently, causing your page to look different depending on the visitor’s browser.

---

# Question: What is the HTML 4.01 syntax for a line break?

**Answer:**
In *HTML 4.01*, a line break is written as:

```html
<br>
```

---

# Question: What is the XHTML syntax for a line break?

**Answer:**
In *XHTML*, a line break is written as:

```html
<br />
```

---

# Question: How does HTML5 handle line break syntax?

**Answer:**
*HTML5* is flexible and accepts **both** `<br>` and `<br />` as valid syntax for line breaks.

---

# Question: What do HTML tags do?

**Answer:**
*HTML tags* are instructions enclosed in brackets that tell the browser how to display content. They are the "markup" part of *Hypertext Markup Language*.

---

# Question: What is the structure of most HTML tags?

**Answer:**
Most HTML tags come in *pairs*: an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`). The closing tag includes a forward slash `/`.

---

# Question: What are the four essential elements found in every HTML page?

**Answer:**
The four essential elements are:

1. The *DOCTYPE* declaration.
2. The opening `<html>` tag.
3. The closing `</html>` tag.
4. Content wrapped in HTML structure tags like `<head>`, `<title>`, and `<body>`.

--

# Question: What does the `<html>` tag represent in a web page?

**Answer:**
The `<html>` tag indicates that the content is written in HTML. It encloses all other content and tags in a web page, making it the "root" of the page structure.

---

# Question: What are the two main sections within the `<html>` tag?

**Answer:**

1. The `<head>` section
2. The `<body>` section

These are like two main branches of the HTML tree structure.

---

# Question: What does the `<head>` section of a web page contain?

**Answer:**
The `<head>` section contains:

* The page’s `<title>`
* Metadata (like a page description)
* CSS code or links to external CSS files
* Other non-visible information used by browsers and search engines

---

# Question: What does the `<body>` section of a web page contain?

**Answer:**
The `<body>` section contains all the visible content of the web page, such as:

* Headlines
* Text
* Images
* Paragraphs
* Links

---

# Question: Which tag is used to define a paragraph?

**Answer:**
The `<p>` tag is used to start a paragraph, and the `</p>` tag is used to end it.

---

# Question: What does the `<strong>` tag do?

**Answer:**
The `<strong>` tag is used to emphasize text. It makes the enclosed text appear in **bold**.

---

# Question: How is a hyperlink created in HTML?

**Answer:**
Using the `<a>` (anchor) tag. For example:

```html
<a href="http://www.example.com">Click here!</a>
```

---

# Question: What is an attribute in an HTML tag?

**Answer:**
An attribute provides extra information about an element. In `<a href="http://...">`, `href` is the attribute and the URL is its value.

---

# Question: What is the purpose of the `href` attribute?

**Answer:**
The `href` attribute in an `<a>` tag specifies the destination URL of the hyperlink.

---

# Question: Why was XHTML introduced?

**Answer:**
XHTML was introduced to enforce stricter rules on HTML. It requires:

* Lowercase tag names
* Properly nested and closed tags

This improves compatibility with browsers, mobile devices, and other web technologies.

---

# Question: What are some issues with standard (older) HTML?

**Answer:**
Standard HTML:

* Allows mixed-case tags (`<BODY>`, `<body>`, etc.)
* Permits unclosed tags (e.g., `<p>` without `</p>`)
  This makes HTML easier to write but harder for browsers and smart devices to interpret consistently.

---

# Question: What is xHTML and why was it introduced?

**Answer:**
xHTML, or Extensible HyperText Markup Language, was introduced around 2000 as an improved version of HTML to keep pace with the rise of XML (Extensible Markup Language). It is essentially an "XML-ified" version of HTML intended to be the future standard for web pages by combining HTML's features with XML's stricter syntax rules.

---

# Question: Why did the W3C move away from xHTML towards HTML5?

**Answer:**
The W3C moved away from xHTML because the complexity of fully adopting XML as the web's prime language made browser manufacturers reluctant to follow that path. As a result, the W3C closed the xHTML working group and developed HTML5 instead, which moves away from XML and back to an enhanced version of HTML, supported by all major browsers.

---

# Question: How is HTML5 different from xHTML in terms of its approach to web development?

**Answer:**
Unlike xHTML, which aimed to foster a new way to build web pages with strict XML rules, HTML5 focuses on ensuring the Web continues to work as it always has, maintaining the basics of HTML while adding new elements to support modern web design practices without requiring XML compliance.

---

# Question: What are some new tags introduced in HTML5, and what purposes do they serve?

**Answer:**
HTML5 introduced new semantic tags such as:

* `<header>`: contains content typically found at the top of a page, like logos and navigation links.
* `<nav>`: encloses navigation links for the site.
* `<footer>`: holds content usually placed at the bottom of the page, such as legal notices or contact information.
  Additionally, HTML5 adds tags to embed video and audio, and enhanced form tags with features like sliders, pop-up date pickers, and built-in form validation.

—--

# Question: What challenges are associated with using HTML5's new features?

**Answer:**
Browser support for many new HTML5 features is inconsistent, making it difficult to use them without elaborate workarounds. Older browsers, such as Internet Explorer 8 and earlier, require additional help to properly render HTML5 elements.

—--

# Question: Should developers start using HTML5 now, even though it is not fully supported?

**Answer:**
Yes, developers are encouraged to start using the HTML5 doctype and basic HTML5 elements now, despite some browser compatibility issues, especially with older browsers. HTML5 is widely supported by modern browsers like Google Chrome and Firefox and is becoming the new standard for web development.

—--

# Question: What basic software do you need to create web pages using HTML and CSS?

**Answer:**
You only need a basic text editor like Notepad on Windows or TextEdit on Mac to create web pages made up of HTML and CSS.

—--

# Question: Why might you want to use software other than basic text editors for web development?

**Answer:**
After typing a few hundred lines of HTML and CSS, basic editors can become cumbersome. Specialized software offers features like syntax highlighting, FTP support, and auto-completion that make writing, editing, and managing web pages easier and more efficient.

—--

# Question: Name three free programs for editing HTML and CSS, and one key feature of each.

**Answer:**

* **jEdit** (Windows, Mac, Linux): Java-based and includes syntax highlighting.
* **Notepad++** (Windows): Fast text editor with syntax highlighting to color code HTML and CSS elements.
* **TextWrangler** (Mac): Pared-down version of BBEdit with syntax highlighting and FTP support for uploading files.

—--

# Question: What is the difference between TextWrangler and BBEdit?

**Answer:**
TextWrangler is a free, simplified version of BBEdit. While it lacks some of BBEdit’s built-in HTML tools, it still offers syntax highlighting and FTP capabilities.

—--

# Question: What was introduced in CSS 1, and when was it released?

**Answer:**
CSS 1, introduced in 1996, laid the groundwork for Cascading Style Sheets by establishing the basic structure of styles and the selector concept, along with most of the core CSS properties covered in this book.

—--

# Question: What are some key features added in CSS 2?

**Answer:**
CSS 2 added features such as the ability to target different devices (like printers and monitors), new selectors, and precise positioning of elements on a web page.

—--

# Question: What is CSS 2.1, and how does it relate to CSS 2?

**Answer:**
CSS 2.1 is the current accepted standard that incorporates all of CSS 1, adds several new properties, and corrects some problems found in the CSS 2 guidelines. It is a minor update rather than a radical change from CSS 2, and most browsers have adapted to it smoothly.

—--

# Question: How is CSS3 different from previous versions like CSS 1 and CSS 2.1?

**Answer:**
Unlike previous versions, CSS3 is not a single standard but a collection of separate modules (e.g., Selectors, Values and Units, Box Alignment). Each module develops independently, meaning there is no unified "CSS3" standard. Different modules are at various stages of completion and browser support.

—--

# Question: What is the status of CSS4?

**Answer:**
There will be no single CSS4. Instead, new versions of different CSS modules will continue to be developed and updated independently at different levels.

—--

# Question: How does adding CSS change the way HTML is used on web pages?

**Answer:**
Adding CSS to web design eliminates the need to repurpose awkward HTML tags just to achieve visual effects. It makes writing HTML easier and more semantic by separating content structure from presentation, allowing the use of simpler and cleaner HTML code.

—--

# Question: What happens to old HTML tags like the <font> tag when using CSS-driven web design?

**Answer:**
Old HTML tags and attributes like the <font> tag become obsolete and can be forgotten completely because CSS handles styling and visual effects.

---

# Question: Compare the size and complexity of an HTML-only page to a CSS-styled page with a similar look.

**Answer:**
An HTML-only page with visual effects can be nearly four times larger in file size and contain about three times more lines of code than a CSS-styled page achieving the same look. For example, an HTML-only page might be 14k with 213 lines of code, whereas the CSS version is only 4k with 71 lines.

---

# Question: Why was HTML originally created, and what was its primary purpose?

**Answer:**
HTML was originally created by scientists to structure technical documentation for easy comprehension, not for visual design. Its primary purpose was to organize information logically and semantically, such as using <h1> for main headings and <h2> for subheadings.

---
