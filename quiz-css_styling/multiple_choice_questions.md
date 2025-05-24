# Question: What does CSS stand for?

**Answer:**  
Cascading Style Sheets

---

# Question: What is the primary purpose of CSS?

**Answer:**  
CSS is used to style and control the layout of HTML documents by describing how HTML elements should be displayed.

---

# Question: How can you set the background color of the entire page using CSS?

**Answer:**  
By applying a background-color property to the `body` selector:
```css
body {
  background-color: lightblue;
}
````

---

# Question: How can you center-align the text in an `<h1>` element using CSS?

**Answer:**

```css
h1 {
  text-align: center;
}
```

# Question: Where in an HTML document is the correct place to refer to an external style sheet?

**Answer:**
In the `<head>` section of the HTML document.

---

# Question: Which HTML tag is used to define an internal style sheet?

**Answer:**
The `<style>` tag.

---

# Question: Which HTML attribute is used to define inline styles?

**Answer:**
The `style` attribute.

---

# Question: Which is the correct CSS syntax?

**Answer:**
`selector { property: value; }`
Example: `p { color: red; }`

---

# Question: How do you insert a comment in a CSS file?

**Answer:**
`/* This is a comment */`

---

# Question: Which property is used to change the background color?

**Answer:**
The `background-color` property.

---

# Question: How do you add a background color for all `<h1>` elements?

**Answer:**

```css
h1 {
  background-color: yellow;
}
```

---

# Question: Which CSS property is used to change the text color of an element?

**Answer:**
The `color` property.

---

# Question: Which CSS property controls the text size?

**Answer:**
The `font-size` property.

---

# Question: What is the correct CSS syntax for making all the `<p>` elements bold?

**Answer:**

```css
p {
  font-weight: bold;
}
```

---

# Question: How do you display hyperlinks without an underline?

**Answer:**

```css
a {
  text-decoration: none;
}
```

---

# Question: How do you make each word in a text start with a capital letter?

**Answer:**

```css
text-transform: capitalize;
```

---

# Question: Which property is used to change the font of an element?

**Answer:**
The `font-family` property.

---

# Question: How do you make the text bold?

**Answer:**

```css
font-weight: bold;
```

---

# Question: How do you display a border like this:

**Answer:**

```css
border: 1px solid black;
```

---

# Question: Which property is used to change the left margin of an element?

**Answer:**
The `margin-left` property.

---

# Question: When using the padding property; are you allowed to use negative values?

**Answer:**
No, padding cannot have negative values.

---

# Question: How do you make a list that lists its items with squares?

**Answer:**

```css
ul {
  list-style-type: square;
}
```

---

# Question: How do you select an element with id 'demo'?

**Answer:**

```css
#demo {
  /* styles */
}
```

---

# Question: How do you select elements with class name 'test'?

**Answer:**

```css
.test {
  /* styles */
}
```

---

# Question: How do you select all `<p>` elements inside a `<div>` element?

**Answer:**

```css
div p {
  /* styles */
}
```

---

# Question: How do you group selectors?

**Answer:**

```css
h1, h2, p {
  color: blue;
}
```

---

# Question: What is the default value of the `position` property?

**Answer:**
The default value is `static`.

---

# Question: Which CSS property is used to change the font of a paragraph?

**Answer:**
The `font-family` property.

---


# Question: Which CSS selectors will correctly target the `<p>` element only if it's inside a `<div>` with the ID `"container"`?

**Answer:**

```css
#container p {
  /* styles */
}
```

---

# Question: What is the correct HTML for referring to an external style sheet?

**Answer:**

```html
<link rel="stylesheet" href="styles.css">
```

---

# Question: The `overflow` property accepts two keywords. The first keyword is for which axis?

**Answer:**
The horizontal axis (x-axis).

---

# Question: Which display values create a flexible box layout?

**Answer:**
`display: flex;` and `display: inline-flex;`

---

# Question: Which of the following are valid CSS pseudo-classes?

**Answer:**

* `:hover`
* `:focus`
* `:nth-child()`
* `:first-child`

---

# Question: Which techniques are used to create a responsive design using CSS?

**Answer:**

* Media queries
* Relative units (%, em, rem, vw, vh)
* Flexbox and Grid layouts
* Responsive images
* CSS container queries (modern approach)

---

# Question: Which of the following properties control the stacking order of elements?

**Answer:**
The `z-index` property.

---

# Question: Which of these are valid units for specifying font sizes in CSS?

**Answer:**

* `px`
* `em`
* `rem`
* `%`
* `vw`, `vh`
* `pt`, `cm`, `mm` (less commonly used for screen)

---

# Question: Which of the following CSS properties influence the visual layout of a table?

**Answer:**

* `border-collapse`
* `table-layout`
* `caption-side`
* `empty-cells`

---

# Question: What are some ways to improve the accessibility of CSS-styled web pages?

**Answer:**

* Use high contrast between text and background
* Ensure font sizes are readable and scalable
* Avoid using color as the only means of conveying information
* Use semantic HTML along with CSS
* Avoid animations that can trigger motion sickness (use `prefers-reduced-motion`)

---

# Question: What is CSS and what is its purpose?

**Answer:**
CSS (Cascading Style Sheets) is the language used to describe the presentation of an HTML document. It controls how HTML elements are displayed, allowing developers to style web pages with colors, fonts, layouts, and more.

---

# Question: How does CSS improve web development?

**Answer:**
CSS separates content (HTML) from design, making it easier to maintain and update the look of a website. It enhances consistency across pages and allows for responsive and visually appealing layouts.

---

# Question: In the CSS example below, what does each rule do?

```css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```

**Answer:**

* The `body` selector sets the background color of the entire page to light blue.
* The `h1` selector changes the heading color to white and centers it.
* The `p` selector sets the font family to Verdana and the font size to 20 pixels for all paragraphs.

---

# Question: What does CSS stand for, and what is its purpose?

**Answer:**
CSS stands for **Cascading Style Sheets**. It is used to describe how HTML elements should be displayed on screen, paper, or other media, allowing for the design and layout of web pages to be managed separately from their content.

---

# Question: How does CSS benefit web development?

**Answer:**
CSS saves time and effort by enabling developers to control the layout of multiple web pages from a single stylesheet. It allows for consistent styling across a site and makes maintenance easier, especially for large websites.

---

# Question: What is one major problem that CSS solved?

**Answer:**
Before CSS, HTML included tags like `<font>` for styling, which made maintaining large websites difficult. CSS solved this by separating content (HTML) from presentation (CSS), making code cleaner and easier to manage.

---

# Question: How can one HTML page be styled differently using CSS?

**Answer:**
By linking the HTML page to different external stylesheets, you can apply multiple visual themes. Changing the linked CSS file alters the page's appearance without modifying the HTML structure.

---

# Question: Why is it recommended to use external stylesheets in CSS?

**Answer:**
External stylesheets allow you to apply consistent styles across multiple web pages. You can update the design of an entire website by modifying a single `.css` file, enhancing efficiency and scalability.

---

# Question: What is the correct syntax structure of a CSS rule?

**Answer:**
A CSS rule consists of a **selector** and a **declaration block**. The declaration block is enclosed in curly braces `{}` and contains one or more declarations, each made up of a **property** and a **value**, separated by a colon (`:`) and ending with a semicolon (`;`).
Example:

```css
p {
  color: red;
  text-align: center;
}
```

In this example:

* `p` is the **selector**
* `color` and `text-align` are **properties**
* `red` and `center` are the corresponding **values**

---

# Question: Which CSS selector is used to select an element with a specific id?

**Options:**

* A) `*`
* B) `.`
* C) `#`
* D) `%`

**Answer:**
**C) `#`**

---

# Summary of Basic CSS Selectors:

| Selector             | Example      | Description                                |
| -------------------- | ------------ | ------------------------------------------ |
| `#id`                | `#firstname` | Selects the element with id="firstname"    |
| `.class`             | `.intro`     | Selects all elements with class="intro"    |
| `*`                  | `*`          | Selects all elements                       |
| `element`            | `p`          | Selects all `<p>` elements                 |
| `element,element,..` | `div, p`     | Selects all `<div>` and all `<p>` elements |

---
