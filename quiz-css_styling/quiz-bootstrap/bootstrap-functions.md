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

# Question: List Bootstrap CSS form elements and classes grouped by their category.

### Bootstrap's Default Form Settings

| Target Element                      | Description                                                             |
| ----------------------------------- | ----------------------------------------------------------------------- |
| `<input>`, `<textarea>`, `<select>` | When used with `.form-control`, these are styled with `width: 100%`     |
| `<div class="form-group">`          | Wraps a label and a form control for proper spacing                     |
| `.form-control`                     | Applies to input, textarea, and select elements to make them responsive |

**Example:**

```html
<form>
  <div class="form-group">
    <label for="email">Email address:</label>
    <input type="email" class="form-control" id="email">
  </div>
  <div class="form-group">
    <label for="pwd">Password:</label>
    <input type="password" class="form-control" id="pwd">
  </div>
  <div class="checkbox">
    <label><input type="checkbox"> Remember me</label>
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>
```

---

### Form Layout Classes

| Class                    | Description                                                               |
| ------------------------ | ------------------------------------------------------------------------- |
| `.form-inline`           | Makes the form left-aligned with inline-block controls (≥768px viewports) |
| `.form-horizontal`       | Aligns labels and controls in a horizontal layout                         |
| `.form-control`          | Used on input, textarea, and select elements to make them full-width      |
| `.form-control-feedback` | Used for displaying form validation feedback                              |
| `.form-control-static`   | Displays plain static text alongside a label in a horizontal form         |
| `.form-group`            | Container for form controls and labels                                    |

---

### Input Group Classes

| Class                | Description                                                      |
| -------------------- | ---------------------------------------------------------------- |
| `.input-group`       | Wraps inputs to add icons, text, or buttons as "help text"       |
| `.input-group-lg`    | Large-sized input group                                          |
| `.input-group-sm`    | Small-sized input group                                          |
| `.input-group-addon` | Adds an icon or help text next to an input inside `.input-group` |
| `.input-group-btn`   | Adds a button next to the input inside `.input-group`            |

---

### Input Size Modifier Classes

| Class       | Description                   |
| ----------- | ----------------------------- |
| `.input-lg` | Increases the height of input |
| `.input-sm` | Decreases the height of input |

---

# Question: List Bootstrap CSS helper classes grouped by their category.

### Text Color Classes

| Class           | Description                             |
| --------------- | --------------------------------------- |
| `.text-muted`   | Applies muted (gray) color to text      |
| `.text-primary` | Applies primary (blue) color to text    |
| `.text-success` | Applies green color to indicate success |
| `.text-info`    | Applies light-blue color for info       |
| `.text-warning` | Applies yellow color for warning        |
| `.text-danger`  | Applies red color for danger            |

---

### Background Color Classes

| Class         | Description                      |
| ------------- | -------------------------------- |
| `.bg-primary` | Applies primary background color |
| `.bg-success` | Applies success background color |
| `.bg-info`    | Applies info background color    |
| `.bg-warning` | Applies warning background color |
| `.bg-danger`  | Applies danger background color  |

---

### Miscellaneous Utility Classes

| Class                | Description                                                         |
| -------------------- | ------------------------------------------------------------------- |
| `.pull-left`         | Floats an element to the left                                       |
| `.pull-right`        | Floats an element to the right                                      |
| `.center-block`      | Sets element to `display: block` and centers with auto margins      |
| `.clearfix`          | Clears floated elements                                             |
| `.show`              | Forces element to be shown (`display: block`)                       |
| `.hidden`            | Hides element (`display: none`)                                     |
| `.invisible`         | Hides element (`visibility: hidden`), but retains layout space      |
| `.sr-only`           | Hides element visually, but remains accessible to screen readers    |
| `.sr-only-focusable` | Makes `.sr-only` element visible on focus (for keyboard-only users) |
| `.text-hide`         | Hides text and replaces it with a background image                  |
| `.close`             | Styles close icon/button (× symbol)                                 |
| `.caret`             | Indicates dropdown functionality (changes direction in dropup)      |

---

### Responsive Visibility Utilities

| Class           | XS Devices `<768px` | SM Devices `≥768px` | MD Devices `≥992px` | LG Devices `≥1200px` |
| --------------- | ------------------- | ------------------- | ------------------- | -------------------- |
| `.visible-xs-*` | Visible             | Hidden              | Hidden              | Hidden               |
| `.visible-sm-*` | Hidden              | Visible             | Hidden              | Hidden               |
| `.visible-md-*` | Hidden              | Hidden              | Visible             | Hidden               |
| `.visible-lg-*` | Hidden              | Hidden              | Hidden              | Visible              |
| `.hidden-xs`    | Hidden              | Visible             | Visible             | Visible              |
| `.hidden-sm`    | Visible             | Hidden              | Visible             | Visible              |
| `.hidden-md`    | Visible             | Visible             | Hidden              | Visible              |
| `.hidden-lg`    | Visible             | Visible             | Visible             | Hidden               |

**Example:**

```html
<h1 class="hidden-xs bg-danger">This text is hidden on an EXTRA SMALL screen.</h1>
<h1 class="hidden-sm bg-info">This text is hidden on a SMALL screen.</h1>
<h1 class="hidden-md bg-warning">This text is hidden on a MEDIUM screen.</h1>
<h1 class="hidden-lg bg-success">This text is hidden on a LARGE screen.</h1>
```

---

### Display Variants of `.visible-*-*` Classes (as of v3.2.0)

| Group of Classes          | CSS `display` Value     |
| ------------------------- | ----------------------- |
| `.visible-*-block`        | `display: block`        |
| `.visible-*-inline`       | `display: inline`       |
| `.visible-*-inline-block` | `display: inline-block` |

**Example for small screens:**

* `.visible-sm-block`
* `.visible-sm-inline`
* `.visible-sm-inline-block`

> **Note:** `.visible-xs`, `.visible-sm`, `.visible-md`, and `.visible-lg` are **deprecated** as of v3.2.0.

---

# Question: List Bootstrap CSS image classes and their functions.

### `<img>` Classes

| Class             | Description                                                                  |
| ----------------- | ---------------------------------------------------------------------------- |
| `.img-rounded`    | Adds rounded corners to an image (not supported in IE8)                      |
| `.img-circle`     | Shapes the image into a circle (not supported in IE8)                        |
| `.img-thumbnail`  | Adds a border and padding, styles the image like a thumbnail                 |
| `.img-responsive` | Makes the image responsive: `max-width: 100%; height: auto; display: block;` |

---

### Responsive Images

| Method                  | Description                                             |
| ----------------------- | ------------------------------------------------------- |
| `.img-responsive` class | Used in `<img>` to scale images with the parent element |

**Example:**

```html
<img src="cinqueterre.jpg" class="img-responsive" alt="Cinque Terre">
```

---

# Question: List Bootstrap CSS table classes and their functions.

### `<table>` Classes

| Class              | Description                                                     |
| ------------------ | --------------------------------------------------------------- |
| `.table`           | Adds basic styling: light padding and horizontal dividers       |
| `.table-striped`   | Adds zebra-striping to rows in `<tbody>` (not supported in IE8) |
| `.table-bordered`  | Adds borders on all sides of the table and cells                |
| `.table-hover`     | Enables hover state on table rows in `<tbody>`                  |
| `.table-condensed` | Reduces padding to make the table more compact                  |

---

### `<tr>`, `<th>`, and `<td>` Contextual Classes

| Class      | Description                                          |
| ---------- | ---------------------------------------------------- |
| `.active`  | Applies hover color (light-grey) to a row or cell    |
| `.success` | Indicates a successful or positive action            |
| `.info`    | Indicates a neutral informative change or action     |
| `.warning` | Indicates a warning that might need attention        |
| `.danger`  | Indicates a dangerous or potentially negative action |

---

### Responsive Tables

| Class               | Description                                                    |
| ------------------- | -------------------------------------------------------------- |
| `.table-responsive` | Makes tables horizontally scrollable on small screens (<768px) |

**Example:**

```html
<div class="table-responsive">
  <table class="table">
    ...
  </table>
</div>
```

---

