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


