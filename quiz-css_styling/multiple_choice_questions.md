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

# Question: What is a CSS preprocessor?

Answer:  
A CSS preprocessor is a tool that compiles a more advanced syntax (similar to CSS) into standard CSS, adding features like variables, nesting, and more.

---

# Question: Name some key advantages of using a CSS preprocessor.

Answer:  
Advantages include:
- Code nesting  
- Use of variables  
- Creation of mixins  
- Mathematical and logical operations  
- Loops and conditions  
- Joining multiple files

---

# Question: How does nesting in preprocessors differ from regular CSS?

Answer:  
In preprocessors, you can nest selectors inside other selectors in a structured way, reducing repetition and improving readability. This is not possible in standard CSS.

---

# Question: What is an example of how nesting works in a CSS preprocessor?

Answer:  
```scss
.class {
  property: value;

  .insideClass {
    property: value;
  }
}

This compiles to:

.class {
  property: value;
}
.class .insideClass {
  property: value;
}
```


---

# Question: Why is using variables helpful in CSS preprocessors?

Answer:
Variables allow you to store values like colors, font sizes, or spacing, making it easier to update styles consistently across a project with just one change.

---

# Question: Why is using variables in pure CSS limited?

Answer:
Not all browsers fully support native CSS variables, and older CSS does not allow variable use, which limits flexibility compared to preprocessors.

---

# Question: What is a mixin in the context of CSS preprocessors?

Answer:
A mixin is a reusable block of CSS declarations that can be included in other selectors, helping to avoid duplication and increase modularity.

---

# Question: What’s an example of nesting in SASS using indentation?

Answer:

.class
  property: value

  .insideClass
    property: value



---

# Question: What is one major benefit of proper nesting usage in preprocessors?

Answer:
Proper nesting keeps the stylesheet organized and scalable while minimizing redundancy and enhancing maintainability.

---

# Question: What happens to preprocessor code after compilation?

Answer:
It is converted into standard CSS that browsers can understand and render.

---

# Question: What is the purpose of using `repeat(9, 1fr)` in grid template?

**Answer:** It creates nine equally sized columns across the page layout.

---

# Question: How are the row sizes defined in the grid layout?

**Answer:** Using `grid-auto-rows: 75px auto 75px;`.

---

# Question: What does the row configuration `75px auto 75px` imply in grid layout?

**Answer:** The first and last rows are fixed at 75 pixels, and the middle row will expand automatically based on content.

---

# Question: What is the default font size in most browsers?

**Answer:** 16 pixels.

---

# Question: How do you convert rem values to pixels in a media query condition?

**Answer:** Multiply the rem value by 16 pixels (e.g., `31.25rem * 16 = 500px`), since media query conditions use the **default font size** of 16px for `rem` units.

---

# Question: If `html { font-size: 62.5%; }` is used, how many pixels is `1rem` in the body of the CSS (outside media queries)?

**Answer:** 10 pixels.

---

# Question: Why does changing the `html` font size not affect the rem value inside media query conditions?

**Answer:** Because media query conditions do not inherit the CSS-defined `font-size` of the root `html` element; they continue to use the browser's default (16px) for `rem` calculations.

---

# Question: How would you write a media query for `max-width: 1000px` using `rem`?

**Answer:** `@media (max-width: 62.5rem)` because `1000px / 16 = 62.5rem`.

---

# Question: Why is using `rem` inside media query conditions potentially confusing?

**Answer:** Because developers might assume the rem value is based on the adjusted `html` font size (e.g., 10px), but it still uses the default 16px, which can lead to incorrect calculations if not understood.

---

# Question: What mistake might a developer make if they forget that media query rems use 16px as the base?

**Answer:** They might divide by 10 (the adjusted `html` font size) instead of 16, resulting in a media query that applies at the wrong screen width.

---

# Question: If a developer writes `@media (max-width: 100rem)` after setting `html { font-size: 62.5%; }`, what is the actual pixel value this refers to?

**Answer:** `100rem * 16 = 1600px`, not `1000px`.

---

# Question: How do you properly convert `500px` into `rem` for a media query?

**Answer:** Divide 500 by 16, resulting in `31.25rem`.

---

# Question: Why is using `62.5%` instead of setting `font-size: 10px` directly considered better practice?

**Answer:** Because it maintains responsiveness and respects browser accessibility settings instead of overriding them.

---

# Question: What is the primary goal of responsive design?

**Answer:** To ensure web pages adapt to different screen sizes for a more functional user experience.

---

# Question: Why did web pages originally not consider different screen sizes?

**Answer:** Because they were designed only for desktop computers, which were the only devices available to access the internet at the time.

---

# Question: What are examples of devices that require responsive design due to varying screen sizes?

**Answer:** Desktops, laptops, tablets, and smart mobile devices.

---

# Question: How can developers simulate different screen sizes in a browser?

**Answer:** By using DevTools and clicking the toggle device icon to change the browser width.

---

# Question: What are the visible changes in a web page as the browser width decreases?

**Answer:** Changes in layout, image positioning, button widths, font sizes, and spacing properties like margin and padding.

---

# Question: What are the three main pillars of responsive design?

**Answer:** 1. Relative units (like rems and percentages), 2. Fluid layouts (like Flexbox and CSS Grid), 3. Media queries.

---

# Question: What is the role of media queries in responsive design?

**Answer:** Media queries apply styles to a web page based on specific conditions, such as screen width.

---

# Question: How is a media query written in CSS?

**Answer:** Using `@media` followed by a condition in parentheses (e.g., `(max-width: 500px)`) and CSS rules inside curly brackets.

---

# Question: What does the following media query do?

```css
@media (max-width: 500px) {
  h2 {
    font-size: 14px;
  }
}
```

**Answer:** It applies a font size of 14px to all `<h2>` elements when the screen width is less than 500 pixels.

---

# Question: What is an `@media` rule in CSS?

**Answer:** A special at-rule used to apply styles based on conditions like screen width or device type.

---

# Question: How do global styles differ from media query styles?

**Answer:** Global styles apply regardless of screen size and are defined outside media queries.

---

# Question: Why is the order of media queries in CSS important?

**Answer:** Because multiple media queries can apply simultaneously, and due to the CSS Cascade, the last matching rule overrides earlier ones.

---

# Question: What order should media queries be written in to ensure correct overrides?

**Answer:** In descending order of max-width values (e.g., 1500px, 1000px, 500px).

---

# Question: How does the CSS Cascade affect media query application?

**Answer:** Later rules in the CSS override earlier ones when multiple conditions are met.

---


# Question: In DevTools, why are some CSS rules crossed out when media queries apply?

**Answer:** They are overridden by later media query rules that match the current browser width.

---

# Question: How do you activate CSS Grid on a container using CSS?

**Answer:** By setting the container’s `display` property to `grid`.

---

# Question: How do you define two equally spaced columns in a CSS Grid layout?

**Answer:** Use `grid-template-columns: 1fr 1fr;`.

---

# Question: What property is used to define spacing between columns and rows in a grid?

**Answer:** The `gap` property.

---

# Question: How do you center a grid within a page while limiting its maximum width?

**Answer:** Set `max-width: 1200px` on the grid and use `margin: 100px auto;`.

---

# Question: What does the value `auto` do in the `margin` property?

**Answer:** It distributes the remaining horizontal space equally to the left and right, centering the element.

---

# Question: How is responsiveness introduced to the layout using media queries?

**Answer:** By applying style changes based on screen width breakpoints using `@media`.

---

# Question: What happens visually when the screen width is reduced below 1000px?

**Answer:** Padding and font sizes are reduced, improving the layout for medium-sized screens.

---

# Question: What breakpoint is used for smaller screens after 1000px?

**Answer:** `@media (max-width: 500px)`

---

# Question: How does the UI behavior change when resizing to under 500px width?

**Answer:** Font sizes, padding, and spacing reduce again, making the layout suitable for small mobile screens.

---

# Question: What is the main drawback of manually adjusting all properties in media queries?

**Answer:** It's time-consuming and repetitive to manually change sizes for each breakpoint and every property.

---

# Question: What design approach can reduce the need for manual media queries?

**Answer:** Using **relative units** such as percentages and `rem`.

---

# Question: What are the two main types of relative units in responsive design?

**Answer:**

1. Based on **parent container size** (e.g., percentages)
2. Based on **scalable reference points** (e.g., `rem` units)

---

# Question: How do percentage-based units help with layout on smaller screens?

**Answer:** They allow elements like containers and images to scale down while maintaining margin, preventing content from touching screen edges.

---

# Question: What are rem units commonly used for in responsive design?

**Answer:** For defining scalable spacing such as font size, padding, and margins.

---

# Question: What is one advantage of using relative units over fixed pixel values?

**Answer:** They scale proportionally across devices, reducing the need for frequent media queries.

---

# Question: What effect does margin have between a navigation bar and a heading on a desktop vs. mobile layout?

**Answer:** On desktop, there is more margin between the navigation bar and heading; on mobile, the margin is reduced to better fit the smaller screen.

---

# Question: Why are `rem` units commonly used for text sizing?

**Answer:** `Rem` units scale proportionally and provide consistent sizing across devices, making it easier to maintain layout responsiveness and readability.

---

# Question: How is content centered within a main container using CSS?

**Answer:** By setting `margin: 0 auto;` on the container, it is centered horizontally with no vertical margin.

---

# Question: What max-width value is used to prevent content from stretching too wide on large screens?

**Answer:** A max-width of `1200px` is used.

---

# Question: What width percentage is applied to the main container and why?

**Answer:** A width of `90%` is applied to ensure that on smaller browser windows, there is spacing on both sides of the content.

---

# Question: What visual issue is fixed by applying a max-width and percentage width to the main container?

**Answer:** It prevents the content from going all the way to the edges of the screen on smaller devices, improving the viewing experience.

---

# Question: Why is using `rem` values preferred over `px` in media query conditions?

**Answer:** Because `rem` values maintain consistency throughout the project and adapt to changes in root font size, whereas pixel values do not scale dynamically.

---

# Question: How does a max-width media query of `62.5rem` translate in pixels, and why?

**Answer:** It equals `1000px` because `62.5 * 16 = 1000`. Media query conditions are based on the browser’s default font size, not the user-defined `rem`.

---

# Question: What happens to a font size of `10rem` and padding of `5rem` when the root font size is reduced to 50% inside a media query?

**Answer:** The font size shrinks from `100px` to `80px`, and padding from `50px` to `40px`, as `1rem` now equals `8px`.

---

# Question: How are pre-defined CSS properties using `rem` affected inside a media query when the root font size is reduced?

**Answer:** They automatically scale down in proportion to the new `rem` size.

---

# Question: Why is updating the root font size inside a media query a better approach than manually adjusting each property?

**Answer:** It avoids repetitive manual resizing for every element, making the CSS more maintainable, especially in large projects.

---

# Question: Which CSS properties are commonly left in `px` rather than changed to `rem`?

**Answer:** Border width and border radius are typically left in pixels.

---

# Question: What is the converted `rem` value for a `20px` gap?

**Answer:** `2rem`, assuming `1rem = 10px`.

---

# Question: How is `100px` margin converted using rem units?

**Answer:** It is converted to `10rem`.

---

# Question: What is the `rem` equivalent of a `20px` corner radius for review cards?

**Answer:** It remains `20px`, as border-radius is usually not converted to rem.

---

# Question: Why is it not advisable to manually calculate rem values for every media query?

**Answer:** Because the rem value changes with each media query, manually recalculating is error-prone and unnecessary. The browser scales it automatically.

---

# Question: How should you define rem values for new properties in a media query?

**Answer:** Use the same values as in the base case (1rem = 10px), and let the scaling happen automatically based on the root font size.

---

# Question: What is the best mental approach when fine-tuning existing properties using rem inside a media query?

**Answer:** Think in terms of base case (10px per rem), tweak the values, preview results in the browser, and adjust as needed.

---

# Question: If padding is changed to 3rem inside a media query where 1rem = 8px, what is the resulting pixel value?

**Answer:** 3rem × 8px = 24px

---

# Question: If you set a card’s padding to 4rem in a media query where 1rem = 8px, what is the resulting padding?

**Answer:** 4rem × 8px = 32px

---

# Question: Why is rem considered ideal for responsive design compared to using fixed pixels?

**Answer:** Rem allows all spacing, font size, and layout dimensions to scale dynamically with the root font size, making responsiveness easier.

---

# Question: What CSS property is used to create rounded corners on an element?

**Answer:** `border-radius`

---

# Question: What value was set for `border-radius` to create slightly rounded corners?

**Answer:** `2rem`

---

# Question: What effect does setting `margin-left` and `margin-right` to `auto` have when combined with a fixed `max-width`?

**Answer:** It centers the element horizontally within its container.

---

# Question: Why is `margin: 0 auto 1rem` not visually noticeable when the `nav` element is set to `display: block` and takes full width?

**Answer:** Because a block-level element takes 100% width by default, there is no remaining space for the auto margins to distribute unless `max-width` is also set.

---

# Question: What happens when a `max-width` of `600px` is applied to a `nav` element?

**Answer:** The `nav` no longer expands to the full width of the page and is limited to a maximum width of 600px.

---

# Question: How does setting `margin: 0 auto` on an element with a `max-width` of 600px affect its layout?

**Answer:** It centers the element within its parent container horizontally.

---

# Question: Why do list items (`li`) show bullet points by default in a `nav`?

**Answer:** Because unordered lists (`ul`) have a default `list-style` of `disc`, and bullets are placed outside the content area by default.

---

# Question: What must be done to remove bullet points from a list in a `nav`?

**Answer:** The `list-style` property should be set to `none`.

---

# Question: Why does an `h2` inside the `nav` take up the full width of the `nav` container?

**Answer:** Because it is a block-level element, which defaults to 100% width of its parent.

---

# Question: What CSS property is used to change the font used throughout the page?

**Answer:** `font-family`

---

# Question: What property is used to align all text content on the page to the center?

**Answer:** `text-align: center;`

---

# Question: What CSS property is used to apply a border around the `<nav>` element?

**Answer:** `border`

---

# Question: Why was color `#333` used instead of `#000` for the border?

**Answer:** To use a slightly lighter shade of black.

---

# Question: What property controls the position of bullet points in a list?

**Answer:** `list-style-position`

---

# Question: What property and value remove bullet points from an unordered list?

**Answer:** `list-style-type: none;`

---

# Question: How was a visual separation added between list items in the navigation?

**Answer:** By applying `border-top: 1px solid #333;` to each `<li>` element.

---

# Question: Why was `border-top` used instead of `border` or `border-bottom` for list items?

**Answer:** To create a consistent visual separation between each item without adding borders to all sides.

---

# Question: How are anchor tags inside only list items selected in CSS?

**Answer:** Using the selector `li a` (and `li a:visited` for visited links).

---

# Question: What text decoration is removed from the anchor tags inside the list?

**Answer:** `text-decoration: none;`

---

# Question: What color is applied to anchor tags and visited links inside list items?

**Answer:** `#333`

---

# Question: What effect was demonstrated when visiting a link, then returning to the page?

**Answer:** The link’s color remained the same due to the `:visited` styling.

---

# Question: What is the key layout behavior of block-level elements?

**Answer:** Block-level elements stack vertically and always create a new line.

---

# Question: What is the key layout behavior of inline elements?

**Answer:** Inline elements do not create a new line and only take up as much width as their content.

---

# Question: When does an inline element take up more space than its content?

**Answer:** When padding is added, which increases the element's visible width.

---

# Question: What layout behavior does `inline-block` offer?

**Answer:** It allows the element to remain inline with surrounding content while accepting block-level properties like `margin`, `padding`, and `height`.

---

# Question: Give two practical use cases for using `inline-block`.

**Answer:** Styling links as buttons and displaying list items in a horizontal row.

---

# Question: What elements were used to create navigation links?

**Answer:** A `<nav>` element containing an unordered list `<ul>` with `<li>` items, each holding an anchor `<a>` tag.

---

# Question: What is the default display behavior of an anchor `<a>` tag?

**Answer:** It is an inline element.

---

# Question: What is the default display behavior of list items `<li>`?

**Answer:** They are block-level elements, each occupying 100% of the parent container's width.

---

# Question: What default spacing does the `<ul>` have that needed to be removed?

**Answer:** Left padding.

---

# Question: What CSS property and value were used to remove default padding from the list?

**Answer:** `padding-left: 0;`

---

# Question: What CSS property was used to align list items to the right?

**Answer:** `text-align: right;`

---

# Question: How was the `ul`’s full width visually confirmed?

**Answer:** By setting a background color (light gray) to make the full width visible.

---

# Question: Why did aligning the text to the right affect all the list items?

**Answer:** Because the `<ul>` spans 100% width and `text-align: right` aligns its child content accordingly.

---

# Question: What CSS property was applied last to the unordered list for spacing?

**Answer:** `margin: 0;`

---

# Question: What three CSS properties are commonly used together to center content in a flex container?

**Answer:** `display: flex;`, `justify-content: center;`, and `align-items: center;`

---

# Question: What happens when you apply `display: flex; justify-content: center; align-items: center;` to a container?

**Answer:** The child elements are centered both vertically and horizontally within the container.

---

# Question: Can the `<body>` tag be used as a flex container for centering elements on the entire page?

**Answer:** Yes, the `<body>` can act as a flex container to center elements on the page.

---

# Question: What does setting `display: flex` on a child element do?

**Answer:** It makes the child element a flex container itself, allowing it to control its own children.

---

# Question: What is the effect of not setting a width or min-width on flex items?

**Answer:** The items only take up the width of their content.

---

# Question: What does the CSS `flex-basis` property control?

**Answer:** It defines the initial main size of a flex item before any extra space is distributed.

---

# Question: What type of values can `flex-basis` accept?

**Answer:** Absolute values (e.g., `100px`) or percentages.

---

# Question: How does `flex-basis` behave similarly to `min-width`?

**Answer:** It sets an initial size the item will not shrink below, though it is not exactly the same as `min-width`.

---

# Question: What is the role of the `flex-grow` property?

**Answer:** It defines how much a flex item will grow relative to the rest of the flex items when there is extra space.

---

# Question: What kind of value does `flex-grow` accept?

**Answer:** A unitless number.

---

# Question: What happens when all flex items have the same `flex-grow` value?

**Answer:** They grow at the same rate and fill the remaining space equally.

---

# Question: How is a specific `.box` element targeted in CSS using a pseudo-class?

**Answer:** By combining the class selector with `:nth-child()`, e.g., `.box:nth-child(2)`.

---

# Question: What happens when one `.box` has `flex-grow: 2` and another has `flex-grow: 1`?

**Answer:** After applying their flex-basis, the remaining space is divided such that the second box gets twice as much space as the first.

---

# Question: Does `flex-grow: 2` make a box exactly twice as wide as one with `flex-grow: 1`?

**Answer:** No, it only applies to the **extra space** after flex-basis; not the total width.

---

# Question: What is the purpose of the `flex-shrink` property?

**Answer:** It defines how much a flex item will shrink relative to other items when there's not enough space.

---

# Question: What must be done to observe the effect of `flex-shrink`?

**Answer:** Set `flex-wrap: nowrap` on the container to prevent wrapping.

---

# Question: How is `flex-shrink` behavior observed in an example?

**Answer:** By setting `flex-shrink: 2` on one item and `flex-shrink: 1` on another, the first item will shrink twice as much when needed.

---

# Question: Why might increasing the box size help observe `flex-shrink` better?

**Answer:** Larger boxes will more clearly demonstrate how the items shrink relative to one another when space is constrained.

---

# Question: What is the purpose of media queries in CSS?

**Answer:** Media queries allow CSS to adapt the layout and styling of a webpage based on characteristics of the user's device, such as screen width, enabling mobile-responsive design.

---

# Question: What is the basic syntax of a media query in CSS?

**Answer:** `@media [media-type] and ([media-feature]) { CSS rules }`

---

# Question: What are the three main media types used in media queries?

**Answer:** `screen`, `print`, and `speech`.

---

# Question: What does the `screen` media type refer to?

**Answer:** Devices with a screen display, such as desktops, tablets, and phones.

---

# Question: What does the `print` media type refer to?

**Answer:** Devices that render content for print output, such as when printing a webpage.

---

# Question: What does the `speech` media type refer to?

**Answer:** Devices that convert text to speech, such as screen readers.

---

# Question: What is the purpose of the `all` keyword in media queries?

**Answer:** It targets all media types (screen, print, speech) simultaneously.

---

# Question: Why is the `all` keyword often omitted in media queries?

**Answer:** It is the default media type, so specifying it is not necessary for most use cases.

---

# Question: What is the syntax to combine a media type with a media feature in a media query?

**Answer:** `@media [media-type] and ([media-feature]) { CSS rules }`, e.g., `@media all and (max-width: 500px) { ... }`

---

# Question: What does the media feature `max-width: 500px` mean?

**Answer:** It applies the styles when the viewport width is **500 pixels or less**.

---

# Question: What happens when a media query's condition is **not** met?

**Answer:** The CSS rules inside the media query are ignored.

---

# Question: In the example `@media all and (max-width: 500px) { body { color: blue; } }`, when will the text color be blue?

**Answer:** When the viewport width is less than or equal to 500 pixels.

---

# Question: In the example above, what happens to the body text color when the screen is wider than 500px?

**Answer:** The media query does not apply, so the body text color reverts to its default value, such as red if previously defined.

---

# Question: What CSS behavior does the media query demonstrate in terms of condition evaluation?

**Answer:** All conditions in the media query must evaluate to true for the styles to apply; if any condition is false, the entire block is ignored.

---

# Question: What does the `all` keyword in a media query signify?

**Answer:** The `all` keyword targets all device types, but it can be omitted because it is the default behavior of a media query.

---

# Question: How can you write a media query that applies styles for all devices with a maximum width of 500px?

**Answer:** `@media (max-width: 500px) { /* styles here */ }`

---

# Question: What happens when you use `@media (max-width: 500px)` and the screen is less than 500px wide?

**Answer:** The styles inside the media query are applied to the document.

---

# Question: How do you create a media query that targets print styles?

**Answer:** Use `@media print { /* styles here */ }`, leaving out the parentheses section.

---

# Question: In a print media query, how can you change text color for printing?

**Answer:** Use `@media print { body { color: blue; } }` to make text blue when printing.

---

# Question: What does it mean that media queries work “just like other selectors”?

**Answer:** They follow the same cascading rules, where selectors with equal specificity are overridden by the one that appears last.

---

# Question: If two selectors have the same specificity, which one is applied?

**Answer:** The selector that appears later in the stylesheet is applied.

---

# Question: Why might a style inside a media query be ignored, even if its condition is met?

**Answer:** If a selector with the same specificity comes later in the CSS file, it overrides the earlier one due to cascading order.

---

# Question: How can you fix a media query being overridden by a later selector?

**Answer:** Move the overriding selector to appear before the media query in the CSS.

---

# Question: What does the `orientation` media feature detect?

**Answer:** It detects whether the device is in landscape or portrait mode.

---

# Question: How do you write a media query for landscape orientation?

**Answer:** `@media (orientation: landscape) { /* styles */ }`

---

# Question: What happens when the device is in landscape mode according to a media query?

**Answer:** The styles defined in the landscape media query are applied.

---

# Question: How can you target portrait mode using a media query?

**Answer:** `@media (orientation: portrait) { /* styles */ }`

---

# Question: How do you change an element’s color only in portrait orientation?

**Answer:** Use `@media (orientation: portrait) { .subtitle { color: cyan; } }`

---

# Question: What does it mean for a device to be in landscape mode?

**Answer:** The device width is greater than its height.

---

# Question: What does it mean for a device to be in portrait mode?

**Answer:** The device height is greater than its width.

---

# Question: How can you combine two media conditions using AND?

**Answer:** Use the keyword `and`, e.g., `@media (orientation: landscape) and (max-width: 500px) { /* styles */ }`

---

# Question: When are styles applied in a combined media query using AND?

**Answer:** Only when both conditions are true — e.g., in landscape mode **and** width is under 500px.

---

# Question: What happens when you combine media conditions using a comma?

**Answer:** The conditions act as an OR — styles apply if **either** condition is true.

---

# Question: How do you write a media query that applies when the screen is under 500px wide OR in landscape mode?

**Answer:** `@media (max-width: 500px), (orientation: landscape) { /* styles */ }`

---

# Question: What happens when you use a comma-separated media query and only one condition is true?

**Answer:** The styles are still applied, because the comma creates an OR condition.

---

# Question: What are the three main media query features typically used in responsive design?

**Answer:** `orientation`, `print`, and `max-width` / `min-width`.

---

# Question: What is the difference between `max-width` and `min-width` in media queries?

**Answer:** `max-width` applies styles up to a certain width, while `min-width` applies styles from that width upward.

---

# Question: What happens to a `min-width` media query when the screen is narrower than the specified width?

**Answer:** The styles are not applied.

---

# Question: What happens when the screen width crosses the `max-width` threshold in a media query?

**Answer:** The styles inside the media query stop being applied.

---

# Question: What happens when both `min-width` and `orientation` are combined in a media query?

**Answer:** The styles are applied only if both the minimum width and the specified orientation match.

---

# Question: How does the cascade affect media queries with the same specificity?

**Answer:** Later rules in the stylesheet override earlier ones, regardless of media query conditions.

---

