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

# Question: What are the three main ways to add CSS to an HTML document?

**Answer:**
CSS can be added to HTML documents in **three** main ways:

1. **External CSS** – Linked through a separate `.css` file
2. **Internal CSS** – Written within a `<style>` tag in the HTML document's `<head>`
3. **Inline CSS** – Applied directly to HTML elements via the `style` attribute

---

# Question: How does External CSS work and why is it recommended?

**Answer:**
**External CSS** involves linking an external `.css` file using the `<link>` tag in the HTML `<head>` section.
It is recommended because it allows you to control the look of **multiple web pages** with one style sheet.

### Example:

**HTML (`index.html`)**

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="mystyle.css">
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```

**CSS (`mystyle.css`)**

```css
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
```

> ✅ **Tip:** Don't insert a space between numbers and units:
> `margin-left: 20px;` is correct,
> `margin-left: 20 px;` is incorrect.

---

# Question: When should you use Internal CSS?

**Answer:**
Use **Internal CSS** when a **single page** has a unique style that does not need to be reused elsewhere.

### Example:

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: linen;
    }
    h1 {
      color: maroon;
      margin-left: 40px;
    }
  </style>
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```

---

# Question: What is Inline CSS and when should it be used?

**Answer:**
**Inline CSS** is applied directly on an HTML element using the `style` attribute.
It is best used **sparingly** for **quick, one-off styles**, since it mixes content and presentation.

### Example:

```html
<h1 style="color:blue; text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

> ⚠️ **Note:** Inline styles override both internal and external styles due to higher specificity.

---

# Question: What happens when multiple style sheets apply to the same element?

**Answer:**
When multiple styles apply to the same element, **CSS follows a "cascading" order** to determine which rule wins:

### Cascading Order (highest to lowest priority):

1. **Inline styles**
2. **Internal or embedded styles** (within `<style>`)
3. **External styles** (linked via `<link>`)
4. **Browser defaults**

> The **last loaded rule** of equal specificity wins if there are conflicts.

---

# Question: What determines the final style when both internal and external styles are used?

**Answer:**
The **order of the stylesheets** matters. The **last one loaded** (internal or external) will override earlier ones if they target the same element with the same specificity.

### Example – Internal overrides External:

```html
<head>
  <link rel="stylesheet" href="mystyle.css">
  <style>
    h1 { color: orange; }
  </style>
</head>
```

### Example – External overrides Internal:

```html
<head>
  <style>
    h1 { color: orange; }
  </style>
  <link rel="stylesheet" href="mystyle.css">
</head>
```

---

# Question: What are CSS comments and how are they used?

**Answer:**
CSS comments are used to explain code or leave notes for future reference. They are **ignored by the browser** and do **not affect** how styles are applied.

### Syntax:

CSS comments start with `/*` and end with `*/`.

### Example (Single-line comment):

```css
/* This is a single-line comment */
p {
  color: red;
}
```

### Example (Inline comment):

```css
p {
  color: red;  /* Set text color to red */
}
```

### Example (Within a value – not recommended):

```css
p {
  color: /*red*/blue;
}
```

### Example (Multi-line comment):

```css
/* This is
a multi-line
comment */
```

---

# Question: Can HTML and CSS comments be used together?

**Answer:**
Yes. HTML uses a different syntax for comments: `<!-- comment -->`.

You can use both in the same document, typically HTML comments in the body and CSS comments in `<style>` or `.css` files.

### Example:

```html
<!DOCTYPE html>
<html>
<head>
<style>
  p {
    color: red; /* Set text color to red */
  }
</style>
</head>
<body>

<h2>My Heading</h2>

<!-- These paragraphs will be red -->
<p>Hello World!</p>
<p>This paragraph is styled with CSS.</p>
<p>HTML and CSS comments are not shown in the output.</p>

</body>
</html>
```

**Tip:** Use comments to improve code readability and maintainability, especially in large stylesheets.

---

# Question: How can you specify colors in CSS?

**Answer:**
In CSS, colors can be specified using:

* **Predefined color names** (e.g., `Tomato`, `SlateBlue`, `MediumSeaGreen`)
* **RGB values** (e.g., `rgb(255, 99, 71)`)
* **HEX values** (e.g., `#ff6347`)
* **HSL values** (e.g., `hsl(9, 100%, 64%)`)
* **RGBA values** (e.g., `rgba(255, 99, 71, 0.5)`) — includes transparency
* **HSLA values** (e.g., `hsla(9, 100%, 64%, 0.5)`) — includes transparency

---

# Question: How do you set the background color of an element in CSS?

**Answer:**
Use the `background-color` property to set an element's background color.

### Example:

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

---

# Question: How do you change the text color in CSS?

**Answer:**
Use the `color` property to change the text color of HTML elements.

### Example:

```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

---

# Question: How do you set the border color of an element in CSS?

**Answer:**
Use the `border` property and specify the color along with width and style.

### Example:

```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

---

# Question: What is the difference between `rgb()` and `rgba()` in CSS?

**Answer:**

* `rgb(r, g, b)` specifies a color using red, green, and blue components.
* `rgba(r, g, b, a)` adds an **alpha (a)** parameter for **transparency**, where `0` is fully transparent and `1` is fully opaque.

### Example:

```html
<h1 style="background-color:rgba(255, 99, 71, 0.5);">Transparent Tomato</h1>
```

---

# Question: What does `hsl()` and `hsla()` mean in CSS?

**Answer:**

* `hsl(hue, saturation, lightness)` is another way to define colors using hue, saturation, and lightness.
* `hsla()` includes an alpha parameter to control transparency.

### Example:

```html
<h1 style="background-color:hsl(9, 100%, 64%);">Tomato in HSL</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">Semi-transparent Tomato</h1>
```

---

# Question: What is an RGB color in CSS?

**Answer:**
An **RGB color** in CSS defines colors using the **Red**, **Green**, and **Blue** light model. It is written as:

```
rgb(red, green, blue)
```

Each color component is a number between **0** (no intensity) and **255** (full intensity).

---

# Question: How do you create pure red, black, and white using RGB?

**Answer:**

* **Red:** `rgb(255, 0, 0)`
* **Black:** `rgb(0, 0, 0)`
* **White:** `rgb(255, 255, 255)`

---

# Question: How do you create shades of gray using RGB?

**Answer:**
Shades of gray are created by setting equal values for red, green, and blue.

### Examples:

* `rgb(60, 60, 60)` – dark gray
* `rgb(120, 120, 120)` – medium gray
* `rgb(240, 240, 240)` – light gray

---

# Question: What is the difference between `rgb()` and `rgba()` in CSS?

**Answer:**

* `rgb()` sets the color using red, green, and blue values.
* `rgba()` adds an **alpha** value to control transparency.

### Syntax:

```css
rgba(red, green, blue, alpha)
```

* The **alpha** value ranges from `0.0` (fully transparent) to `1.0` (fully opaque).

---

# Question: Give examples of using `rgba()` in CSS.

**Answer:**

```css
rgba(255, 99, 71, 1.0)   /* Fully opaque */
rgba(255, 99, 71, 0.5)   /* 50% transparent */
rgba(255, 99, 71, 0.2)   /* 20% opaque */
```

---

# Question: What is a HEX color code in CSS?

**Answer:**
A **HEX color** in CSS is specified using the format:

```
#rrggbb
```

Where:

* `rr` is the red component
* `gg` is the green component
* `bb` is the blue component

Each pair is a **hexadecimal** value ranging from `00` (0 in decimal) to `ff` (255 in decimal).

---

# Question: How do you write red, black, and white using HEX?

**Answer:**

* **Red:** `#ff0000`
* **Black:** `#000000`
* **White:** `#ffffff`

---

# Question: How do you create shades of gray using HEX codes?

**Answer:**
Shades of gray use equal red, green, and blue values.

### Examples:

* `#3c3c3c` – dark gray
* `#787878` – medium gray
* `#f0f0f0` – light gray

---

# Question: What is a 3-digit HEX color code in CSS?

**Answer:**
A **3-digit HEX code** is a shorthand form of the 6-digit HEX code. It can be used when each color component has identical pairs.

### Syntax:

```
#rgb
```

It expands to:

```
#rrggbb
```

### Example:

* `#f0c` = `#ff00cc`
* `#fc9` = `#ffcc99`
* `#b58` = `#bb5588`

---

# Question: Why use HEX codes over other color formats?

**Answer:**
HEX codes are concise, easy to read, and widely supported in CSS. They are useful for:

* Defining precise colors
* Matching design systems
* Reducing file size with 3-digit shorthand when possible

---

# Question: What does HSL stand for in CSS?

**Answer:**
**HSL** stands for **Hue**, **Saturation**, and **Lightness**. It's a color model used in CSS to define colors more intuitively.

```css
hsl(hue, saturation, lightness)
```

---

# Question: What is the range of values for each HSL component?

**Answer:**

* **Hue:** A degree on the color wheel (0–360)

  * `0` = red, `120` = green, `240` = blue
* **Saturation:** 0% (gray) to 100% (full color)
* **Lightness:** 0% (black) to 100% (white)

---

# Question: Give examples of using HSL colors in CSS.

**Answer:**

```css
hsl(0, 100%, 50%)      /* Red */
hsl(240, 100%, 50%)    /* Blue */
hsl(147, 50%, 47%)     /* Muted green */
hsl(39, 100%, 50%)     /* Orange-like */
```

---

# Question: How does saturation affect HSL colors?

**Answer:**
**Saturation** controls the intensity of the color.

* `100%`: Full vivid color
* `50%`: Color mixed with 50% gray
* `0%`: Fully gray (no color)

### Examples:

```css
hsl(0, 100%, 50%)   /* Full red */
hsl(0, 60%, 50%)    /* Less intense red */
hsl(0, 0%, 50%)     /* Pure gray */
```

---

# Question: How does lightness affect HSL colors?

**Answer:**
**Lightness** controls how light or dark the color appears.

* `0%`: Black
* `50%`: Pure color
* `100%`: White

### Examples:

```css
hsl(0, 100%, 0%)     /* Black */
hsl(0, 100%, 50%)    /* Red */
hsl(0, 100%, 100%)   /* White */
```

---

# Question: How do you create shades of gray using HSL?

**Answer:**
To create gray shades, set **hue** and **saturation** to `0`, and adjust **lightness**.

### Examples:

```css
hsl(0, 0%, 0%)     /* Black */
hsl(0, 0%, 50%)    /* Medium gray */
hsl(0, 0%, 100%)   /* White */
```

---

# Question: What is the difference between HSL and HSLA in CSS?

**Answer:**
**HSLA** adds an **alpha** channel to HSL to control transparency.

### Syntax:

```css
hsla(hue, saturation, lightness, alpha)
```

* **Alpha** ranges from `0.0` (fully transparent) to `1.0` (fully opaque)

---

# Question: Give examples of HSLA color values.

**Answer:**

```css
hsla(9, 100%, 64%, 0)     /* Fully transparent */
hsla(9, 100%, 64%, 0.5)   /* 50% transparent */
hsla(9, 100%, 64%, 1)     /* Fully opaque */
```

---
