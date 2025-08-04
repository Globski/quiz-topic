# Question: List the Bootstrap JS Alert components grouped by their category.

### Alert CSS Classes

| Class                | Description                                                                 |
| -------------------- | --------------------------------------------------------------------------- |
| `.alert`             | Creates an alert message box                                                |
| `.alert-danger`      | Red alert. Indicates a dangerous or potentially negative action             |
| `.alert-dark`        | Dark alert. Dark grey alert box                                             |
| `.alert-dismissible` | Indicates a closable alert box. Used with `.close` to close the alert       |
| `.alert-heading`     | Adds `color: inherit` to the specified element                              |
| `.alert-info`        | Light-blue alert. Indicates a neutral informative change or action          |
| `.alert-light`       | Light alert. Light grey alert box                                           |
| `.alert-link`        | Used on links inside alerts to provide matching colored links               |
| `.alert-primary`     | Blue alert. Indicates an important action                                   |
| `.alert-secondary`   | Grey alert. Indicates a "less" important action                             |
| `.alert-success`     | Green alert. Indicates a successful or positive action                      |
| `.alert-warning`     | Yellow alert. Indicates caution should be taken with this action            |
| `.close`             | Styles the close button (floats right with specific font-size, color, etc.) |

---

### Close Alerts Via `data-*` Attributes

| Attribute              | Description                                                  |
| ---------------------- | ------------------------------------------------------------ |
| `data-dismiss="alert"` | Added to a link or button element to close the alert message |

**Example:**

```html
<a href="#" class="close" data-dismiss="alert">&times;</a>
```

---

### Close Alerts Via JavaScript

| Method                       | Description               |
| ---------------------------- | ------------------------- |
| `$('.close').alert("close")` | Closes the alert manually |

---

### Alert Methods

| Method              | Description                 |
| ------------------- | --------------------------- |
| `.alert("close")`   | Closes the alert message    |
| `.alert("dispose")` | Destroys an element’s alert |

---

### Alert Events

| Event             | Description                                                               |
| ----------------- | ------------------------------------------------------------------------- |
| `close.bs.alert`  | Occurs when the alert message is about to be closed                       |
| `closed.bs.alert` | Occurs when the alert message has been closed (waits for CSS transitions) |

---

# Question: List Bootstrap CSS Typography elements and classes grouped by their category.

### Bootstrap's Default Typography Settings

| Target Element | Description                                                          |
| -------------- | -------------------------------------------------------------------- |
| `<body>`       | Global default font-size is **14px** with a **line-height of 1.428** |
| `<p>`          | Bottom margin equals half the line-height (**10px by default**)      |

---

### Headings and Text Styling

| Element/Class     | Description                                                         |
| ----------------- | ------------------------------------------------------------------- |
| `<h1>` - `<h6>`   | Standard HTML headings, styled by Bootstrap                         |
| `.h1` - `.h6`     | Classes that apply heading styles without using actual heading tags |
| `<small>`         | Creates lighter, secondary text inside headings                     |
| `.small`          | Makes text 85% the size of the parent                               |
| `.lead`           | Makes a paragraph stand out                                         |
| `<mark>`, `.mark` | Highlights text                                                     |
| `<del>`           | Indicates deleted text                                              |
| `<s>`             | Indicates no longer relevant text                                   |
| `<ins>`           | Indicates inserted text                                             |
| `<u>`             | Indicates underlined text                                           |
| `<strong>`        | Indicates bold text                                                 |
| `<em>`            | Indicates italic text                                               |

---

### Text Alignment and Transformation

| Class              | Description         |
| ------------------ | ------------------- |
| `.text-left`       | Left-aligned text   |
| `.text-center`     | Center-aligned text |
| `.text-right`      | Right-aligned text  |
| `.text-justify`    | Justified text      |
| `.text-nowrap`     | No wrap text        |
| `.text-lowercase`  | Lowercased text     |
| `.text-uppercase`  | Uppercased text     |
| `.text-capitalize` | Capitalized text    |

---

### Abbreviations and Contact Info

| Element/Class | Description                                                                        |
| ------------- | ---------------------------------------------------------------------------------- |
| `<abbr>`      | Defines abbreviations; with `title` attribute shows a dotted underline and tooltip |
| `.initialism` | Displays `<abbr>` in a slightly smaller font size                                  |
| `<address>`   | Displays contact information                                                       |

---

### Quotes and Lists

| Element/Class         | Description                                                   |
| --------------------- | ------------------------------------------------------------- |
| `<blockquote>`        | Indicates a block of content from another source              |
| `.blockquote-reverse` | Right-aligns the blockquote text                              |
| `<ul>`                | Unordered list                                                |
| `<ol>`                | Ordered list                                                  |
| `.list-unstyled`      | Removes default list-style and margin from immediate children |
| `.list-inline`        | Places list items in a single line                            |
| `<dl>`                | Description list                                              |
| `.dl-horizontal`      | Horizontally aligns terms and descriptions (responsive)       |

---

### Code Formatting

| Element/Class                  | Description                                           |
| ------------------------------ | ----------------------------------------------------- |
| `<var>`                        | Indicates variables (e.g., `x = ab + y`)              |
| `<kbd>`                        | Indicates keyboard input (e.g., `CTRL + P`)           |
| `<pre>`                        | Displays preformatted text (multiple lines)           |
| `<pre class="pre-scrollable">` | Preformatted text with a scrollbar (when overflowing) |
| `<samp>`                       | Indicates sample output from a program                |
| `<code>`                       | Inline snippets of code (e.g., `span`, `div`)         |

---
