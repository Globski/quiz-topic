# Question: What is Sass?

**Answer:** Sass is a CSS pre-processor that reduces repetition in CSS and saves time.

---

# Question: What is the purpose of using Sass in web development?

**Answer:** Sass helps reduce repetition of CSS rules, making stylesheets more maintainable and efficient.

---

# Question: What feature does the "Show Sass" tool offer?

**Answer:** It displays both the Sass code and the compiled result to help users learn effectively.

---

# Question: In Sass, how are variables defined?

**Answer:** Variables in Sass are defined using the dollar sign (`$`) followed by the variable name and a colon-separated value.

---

# Question: What does the `$bgcolor` variable represent in the given Sass example?

**Answer:** `$bgcolor` represents the background color of the website and is set to `lightblue`.

---

# Question: What value is assigned to the `$textcolor` variable?

**Answer:** The value assigned to `$textcolor` is `darkblue`.

---

# Question: What is the value of the `$fontsize` variable in the Sass example?

**Answer:** The `$fontsize` variable is set to `18px`.

---

# Question: How are variables used in the `body` selector in the Sass example?

**Answer:** The `body` selector uses the variables for its `background-color`, `color`, and `font-size` properties.

---

# Question: What output CSS would be generated from the Sass example provided?

**Answer:** The compiled CSS would be:

```css
body {
  background-color: lightblue;
  color: darkblue;
  font-size: 18px;
}
```

---


# Question: What prior knowledge should you have before learning Sass?

**Answer:** You should have a basic understanding of HTML and CSS.

---

# Question: What does Sass stand for?

**Answer:** Sass stands for Syntactically Awesome Stylesheet.

---

# Question: What type of technology is Sass in relation to CSS?

**Answer:** Sass is a CSS pre-processor and an extension to CSS.

---

# Question: Is Sass compatible with all versions of CSS?

**Answer:** Yes, Sass is completely compatible with all versions of CSS.

---

# Question: How does Sass improve the CSS development process?

**Answer:** Sass reduces repetition in CSS and therefore saves time.

---

# Question: Who designed and developed Sass?

**Answer:** Sass was designed by Hampton Catlin and developed by Natalie Weizenbaum in 2006.

---

# Question: Why is Sass particularly useful as stylesheets grow in size?

**Answer:** Sass helps manage larger, more complex, and harder-to-maintain stylesheets by offering advanced features not available in regular CSS.

---

# Question: Name some features that Sass adds beyond regular CSS.

**Answer:** Sass adds variables, nested rules, mixins, imports, inheritance, built-in functions, and more.

---

# Question: Why is using variables in Sass beneficial when dealing with color values?

**Answer:** It avoids the need to repeat HEX values multiple times and allows easy updates by changing the value in one place.

---

# Question: What is the main advantage of using Sass variables in terms of maintainability?

**Answer:** When a primary color changes, you only need to update it in one place instead of multiple locations in the stylesheet.

---

# Question: Can web browsers interpret Sass code directly?

**Answer:** No, browsers cannot understand Sass code directly.

---

# Question: What is the name of the process used to convert Sass to standard CSS?

**Answer:** The process is called transpiling.

---

# Question: What is transpiling in the context of Sass?

**Answer:** Transpiling is the process of transforming source code written in one language (Sass) into another language (CSS).

---

# Question: What is the file extension used for Sass files?

**Answer:** Sass files use the `.scss` file extension.

---

# Question: What types of comments does Sass support?

**Answer:** Sass supports standard CSS block comments `/* comment */` and inline comments `// comment`.

---

# Question: In the Sass example, where is an inline comment used?

**Answer:** An inline comment is used on the line setting the background color in `.main-header`:

```scss
background-color: $primary_1; // here you can put an inline comment
```

---

# Question: Is Sass platform-dependent?

**Answer:** No, Sass is platform-independent.

---

# Question: Which browsers support Sass?

**Answer:** Sass works in Edge/Internet Explorer (from IE 8), Firefox, Chrome, Safari, and Opera.

---

# Question: From which version of Internet Explorer is Sass supported?

**Answer:** Sass is supported from Internet Explorer 8.

---

# Question: What programming language is Sass based on?

**Answer:** Sass is based on the Ruby programming language.

---

# Question: What is the official website for Sass?

**Answer:** The official Sass website is [https://sass-lang.com/](https://sass-lang.com/)

---

# Question: Can Sass be installed on different operating systems?

**Answer:** Yes, Sass can be installed on Mac, Windows, and Linux systems.

---

# Question: Are there both free and paid applications available to install Sass?

**Answer:** Yes, there are both free and paid applications available for installing Sass.

---

# Question: Where can you find installation options and instructions for Sass?

**Answer:** Installation options and instructions can be found at [https://sass-lang.com/install](https://sass-lang.com/install)

---

# Question: What are Sass variables used for?

**Answer:** Sass variables are used to store information that can be reused later, such as strings, numbers, colors, booleans, lists, and nulls.

---

# Question: What symbol is used to declare a variable in Sass?

**Answer:** The dollar sign (`$`) is used to declare a variable in Sass.

---

# Question: What is the correct Sass variable syntax?

**Answer:** `$variablename: value;`

---

# Question: How are variables used in the `body` and `#container` selectors?

**Answer:** Variables are used to set the `font-family`, `font-size`, and `color` in `body`, and the `width` in `#container`.

---

# Question: What is the default scope of a Sass variable?

**Answer:** A Sass variable is only available at the level of nesting where it is defined.

---

# Question: How can you override the default local scope of a Sass variable?

**Answer:** By using the `!global` flag when defining the variable.

---

# Question: What does the `!global` flag do in Sass?

**Answer:** It marks a variable as global, making it accessible on all levels of nesting.

---

# Question: Where is it recommended to define global variables in Sass?

**Answer:** It is recommended to define global variables outside any rule blocks, ideally in a separate file named `_globals.scss`.

---

# Question: How can you include global variables from another file in your Sass project?

**Answer:** By using the `@include` keyword to include the `_globals.scss` file.

---

# Question: What feature does Sass offer for writing CSS selectors in a hierarchical structure?

**Answer:** Sass allows you to nest CSS selectors in the same way as HTML.

---

# Question: What is the advantage of using nested rules in Sass?

**Answer:** It makes the code cleaner and easier to read compared to standard CSS.

---

# Question: What is the equivalent CSS output of the following Sass code?

```scss
nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  li {
    display: inline-block;
  }
  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}
```

**Answer:**

```css
nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
nav li {
  display: inline-block;
}
nav a {
  display: block;
  padding: 6px 12px;
  text-decoration: none;
}
```

---

# Question: What type of CSS properties can be grouped using Sass nested properties?

**Answer:** Properties with the same prefix, such as `font-*` or `text-*` properties.

---

# Question: How do you write `font-family`, `font-size`, and `font-weight` as nested properties in Sass?

**Answer:**

```scss
font: {
  family: Helvetica, sans-serif;
  size: 18px;
  weight: bold;
}
```

---

# Question: How do you write `text-align`, `text-transform`, and `text-overflow` as nested properties in Sass?

**Answer:**

```scss
text: {
  align: center;
  transform: lowercase;
  overflow: hidden;
}
```

---

# Question: What is the CSS output of the following nested Sass properties?

```scss
font: {
  family: Helvetica, sans-serif;
  size: 18px;
  weight: bold;
}

text: {
  align: center;
  transform: lowercase;
  overflow: hidden;
}
```

**Answer:**

```css
font-family: Helvetica, sans-serif;
font-size: 18px;
font-weight: bold;

text-align: center;
text-transform: lowercase;
text-overflow: hidden;
```

---

# Question: What Sass directive allows you to include the content of one file in another?

**Answer:** The `@import` directive.

---

# Question: How is the Sass `@import` directive different from the CSS `@import` directive?

**Answer:** Unlike CSS `@import`, which creates an extra HTTP request, Sass `@import` includes the content at compile time, so no extra HTTP request is made at runtime.

---

# Question: What is the basic syntax for importing a file in Sass?

**Answer:** `@import filename;`

---

# Question: Do you need to include the file extension when importing a file in Sass?

**Answer:** No, Sass automatically assumes the file is a `.sass` or `.scss` file.

---

# Question: Can Sass import regular CSS files?

**Answer:** Yes, Sass can also import CSS files.

---

# Question: What happens to variables and mixins defined in an imported Sass file?

**Answer:** They can be used in the main file after import.

---

# Question: Can you import multiple files into a Sass file?

**Answer:** Yes, you can import as many files as needed.

---

# Question: What is the purpose of placing the `@import` directive at the top of a file?

**Answer:** To ensure that the imported content has a global scope and is available throughout the file.

---

# Question: Given a file named `reset.scss`, what does this Sass code do?

```scss
@import "reset";
```

**Answer:** It includes the content of `reset.scss` into the current file at compile time.

---

# Question: What is the compiled CSS output of importing `reset.scss` and defining body styles like this?

```scss
@import "reset";

body {
  font-family: Helvetica, sans-serif;
  font-size: 18px;
  color: red;
}
```

**Answer:**

```css
html, body, ul, ol {
  margin: 0;
  padding: 0;
}

body {
  font-family: Helvetica, sans-serif;
  font-size: 18px;
  color: red;
}
```

---

# Question: What does Sass do by default with `.scss` files?

**Answer:** Sass transpiles all `.scss` files by default.

---

# Question: What is a Sass partial?

**Answer:** A partial is a Sass file whose filename starts with an underscore (`_`). Sass does not transpile this file directly but allows it to be imported into other files.

---

# Question: How do you name a partial file in Sass?

**Answer:** By prefixing the filename with an underscore, e.g., `_colors.scss`.

---

# Question: Will a file named `_colors.scss` be compiled into `colors.css` directly?

**Answer:** No, Sass will not compile it directly because it is a partial.

---

# Question: When importing a partial file named `_colors.scss`, how should the import statement look?

**Answer:** `@import "colors";` (the underscore is omitted)

---

# Question: What does the following Sass code do?

```scss
@import "colors";

body {
  font-family: Helvetica, sans-serif;
  font-size: 18px;
  color: $myBlue;
}
```

**Answer:** It imports the variables defined in `_colors.scss`, such as `$myBlue`, and uses them in the body styling.

---

# Question: What does the `@mixin` directive do in Sass?

**Answer:** It defines a block of reusable CSS code that can be included in multiple selectors.

---

# Question: What is the purpose of the `@include` directive in Sass?

**Answer:** The `@include` directive is used to include a mixin in a style rule.

---

# Question: What is the correct syntax to define a mixin in Sass?

**Answer:**

```scss
@mixin name {
  property: value;
  ...
}
```
---

# Question: Are hyphens and underscores treated the same in mixin names in Sass?

**Answer:** Yes, `@mixin important-text` and `@mixin important_text` are treated as the same.

---

# Question: How do you include a mixin named `important-text` in a `.danger` class?

**Answer:**

```scss
.danger {
  @include important-text;
  background-color: green;
}
```

---

# Question: Can a mixin include other mixins?

**Answer:** Yes, a mixin can include other mixins using `@include`.

---

# Question: What is the correct syntax to define a mixin that includes other mixins?

**Answer:**

```scss
@mixin special-text {
  @include important-text;
  @include link;
  @include special-border;
}
```

---

# Question: How do you define a mixin that accepts arguments in Sass?

**Answer:**

```scss
@mixin bordered($color, $width) {
  border: $width solid $color;
}
```

---

# Question: How do you include the `bordered` mixin with arguments for `.myArticle` and `.myNotes`?

**Answer:**

```scss
.myArticle {
  @include bordered(blue, 1px);
}

.myNotes {
  @include bordered(red, 2px);
}
```

---

# Question: What is the compiled CSS output for the `bordered` mixin included in `.myArticle` and `.myNotes`?

**Answer:**

```css
.myArticle {
  border: 1px solid blue;
}

.myNotes {
  border: 2px solid red;
}
```

---

# Question: How do you define default values in a mixin’s parameters?

**Answer:**

```scss
@mixin bordered($color: blue, $width: 1px) {
  border: $width solid $color;
}
```

---

# Question: What does the following code output in CSS?

```scss
.myTips {
  @include bordered($color: orange);
}
```

**Answer:**

```css
.myTips {
  border: 1px solid orange;
}
```

---

# Question: What is a good use case of a mixin when dealing with vendor-specific prefixes?

**Answer:** Mixins can be used to apply vendor prefixes like `-webkit-`, `-ms-`, and standard properties in a single reusable block.

---

# Question: What is the correct syntax of a `transform` mixin that handles vendor prefixes?

**Answer:**

```scss
@mixin transform($property) {
  -webkit-transform: $property;
  -ms-transform: $property;
  transform: $property;
}
```

---

# Question: What is the compiled CSS output of the following code?

```scss
.myBox {
  @include transform(rotate(20deg));
}
```

**Answer:**

```css
.myBox {
  -webkit-transform: rotate(20deg);
  -ms-transform: rotate(20deg);
  transform: rotate(20deg);
}
```

---

# Question: What is the purpose of the `@extend` directive in Sass?

**Answer:** To share a set of CSS properties from one selector to another, allowing one selector to inherit the styles of another.

---

# Question: In what scenario is `@extend` particularly useful in Sass?

**Answer:** When you have almost identically styled elements that only differ in small details.

---

# Question: How does the `@extend` directive affect the compiled CSS output?

**Answer:** It merges selectors that use `@extend` with the base selector into a single group sharing common properties, and then appends any unique properties afterward.

---

# Question: How does the `.button-report` class inherit styles in the SCSS example?

**Answer:** It uses `@extend .button-basic;` to inherit all styles from `.button-basic`.

---

# Question: How does the `.button-submit` class inherit styles in the SCSS example?

**Answer:** It uses `@extend .button-basic;` to inherit all styles from `.button-basic`.

---

# Question: How does using `@extend` affect the HTML class usage compared to not using it?

**Answer:** You only need to apply the extended class (e.g., `.button-report`) in the HTML instead of applying multiple classes like `.button-basic button-report`.

---

# Question: What does DRY stand for, and how does `@extend` help achieve it in Sass?

**Answer:** DRY stands for "Don't Repeat Yourself." `@extend` helps by allowing reuse of existing styles without rewriting them.

---

