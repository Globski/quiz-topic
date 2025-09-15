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

# Question: List Bootstrap 4 CSS classes for dropdowns and collapsibles grouped by their category.

### Dropdown Classes

| Class                  | Description                                        |
| ---------------------- | -------------------------------------------------- |
| `.dropdown`            | Indicates a dropdown menu container                |
| `.dropdown-menu`       | Builds the actual dropdown menu                    |
| `.dropdown-menu-right` | Aligns the dropdown menu to the right              |
| `.dropdown-header`     | Adds a non-clickable header inside the dropdown    |
| `.dropup`              | Indicates a dropup menu (dropdown opens upwards)   |
| `.disabled`            | Disables an item in the dropdown (non-clickable)   |
| `.divider`             | Adds a horizontal separator between dropdown items |

---

### Collapsible Classes

| Class             | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| `.collapse`       | Marks content as collapsible (can be hidden or shown dynamically) |
| `.collapse.in`    | Makes collapsible content visible by default                      |
| `.panel-collapse` | Used for collapsible panels (accordion behavior)                  |

---

# Question: List Bootstrap 4 CSS navigation component classes grouped by their category.

### Tabs and Pills Navigation

| Class                          | Description                                                             |
| ------------------------------ | ----------------------------------------------------------------------- |
| `.nav .nav-tabs`               | Creates navigation tabs                                                 |
| `.nav .nav-pills`              | Creates navigation pills                                                |
| `.nav .nav-pills .nav-stacked` | Creates vertical navigation pills                                       |
| `.nav-justified`               | Makes tabs/pills span full width in viewports ≥768px; stacked otherwise |
| `.disabled`                    | Indicates a disabled (unclickable) tab/pill                             |
| `.tab-content`                 | Used with `.tab-pane` and `data-toggle="tab"` or `data-toggle="pill"`   |
| `.tab-pane`                    | Used within `.tab-content` to toggle tab/pill contents                  |

---

### Navbar Classes

| Class                  | Description                                                               |
| ---------------------- | ------------------------------------------------------------------------- |
| `.navbar`              | Creates a responsive navigation bar                                       |
| `.navbar-brand`        | Represents logo or brand name in the navbar                               |
| `.navbar-btn`          | Vertically aligns buttons inside navbar                                   |
| `.navbar-collapse`     | Collapses the navbar into a toggleable menu on small screens              |
| `.navbar-default`      | Applies default light-grey navbar styling                                 |
| `.navbar-fixed-bottom` | Makes the navbar stay fixed at the bottom of the screen                   |
| `.navbar-fixed-top`    | Makes the navbar stay fixed at the top of the screen                      |
| `.navbar-form`         | Applies correct spacing for form elements inside the navbar               |
| `.navbar-header`       | Container for branding/logo/link inside the navbar                        |
| `.navbar-inverse`      | Applies black background styling to navbar                                |
| `.navbar-left`         | Aligns navbar items (links, forms, etc.) to the left                      |
| `.navbar-link`         | Styles text as a link inside the navbar                                   |
| `.navbar-nav`          | Used on `<ul>` to contain navigation list items                           |
| `.navbar-right`        | Aligns navbar items (links, forms, etc.) to the right                     |
| `.navbar-static-top`   | Removes border-radius and borders from the top navbar                     |
| `.navbar-text`         | Vertically aligns non-link elements inside the navbar                     |
| `.navbar-toggle`       | Styles toggle button (usually with `.icon-bar` inside for hamburger menu) |

---

### Breadcrumbs and Pagination

| Class            | Description                                            |
| ---------------- | ------------------------------------------------------ |
| `.breadcrumb`    | Displays breadcrumb navigation                         |
| `.pager`         | Displays simple Previous/Next pagination               |
| `.previous`      | Aligns `.pager` link to the left                       |
| `.next`          | Aligns `.pager` link to the right                      |
| `.disabled`      | Indicates an unclickable navigation or pagination item |
| `.pagination`    | Displays pagination links                              |
| `.pagination-lg` | Enlarges pagination items                              |
| `.pagination-sm` | Shrinks pagination items                               |
| `.active`        | Highlights current pagination page                     |

---

### Labels and Badges

| Class                   | Description                                                                |
| ----------------------- | -------------------------------------------------------------------------- |
| `.label .label-default` | Grey default label                                                         |
| `.label .label-primary` | Blue label (primary)                                                       |
| `.label .label-success` | Green label (success)                                                      |
| `.label .label-info`    | Light blue label (info)                                                    |
| `.label .label-warning` | Yellow label (warning)                                                     |
| `.label .label-danger`  | Red label (danger)                                                         |
| `.badge`                | Small indicator used for counts/notifications                              |
| `.jumbotron`            | Creates a large box for calling attention to content                       |
| `.jumbotron` (extra)    | When placed outside `.container`, spans full width without rounded corners |

---

# Bootstrap Glyphicon Components

Bootstrap includes **260 glyphs** from the **Glyphicon Halflings set**. While Glyphicons Halflings are normally not free, Bootstrap has made them available without cost. If possible, include a link back to [Glyphicons](https://glyphicons.com) as credit.

### ✅ Use in:

* Text
* Buttons
* Toolbars
* Navigation
* Forms

### ✅ Syntax Example:

```html
<!-- Basic Glyphicon Examples -->
<p>Envelope icon: <span class="glyphicon glyphicon-envelope"></span></p>
<p>Search icon: <span class="glyphicon glyphicon-search"></span></p>
<p>Print icon: <span class="glyphicon glyphicon-print"></span></p>
```

---

## 📁 Glyphicon Classes

| Class Name                          | Description     |
| ----------------------------------- | --------------- |
| `glyphicon glyphicon-asterisk`      | Asterisk        |
| `glyphicon glyphicon-plus`          | Plus sign       |
| `glyphicon glyphicon-minus`         | Minus sign      |
| `glyphicon glyphicon-euro`          | Euro currency   |
| `glyphicon glyphicon-cloud`         | Cloud           |
| `glyphicon glyphicon-envelope`      | Envelope        |
| `glyphicon glyphicon-pencil`        | Pencil/edit     |
| `glyphicon glyphicon-glass`         | Glass           |
| `glyphicon glyphicon-music`         | Music note      |
| `glyphicon glyphicon-search`        | Search icon     |
| `glyphicon glyphicon-heart`         | Filled heart    |
| `glyphicon glyphicon-star`          | Filled star     |
| `glyphicon glyphicon-star-empty`    | Empty star      |
| `glyphicon glyphicon-user`          | User/profile    |
| `glyphicon glyphicon-film`          | Film/media      |
| `glyphicon glyphicon-th-large`      | Large grid      |
| `glyphicon glyphicon-th`            | Grid            |
| `glyphicon glyphicon-th-list`       | List view       |
| `glyphicon glyphicon-ok`            | Checkmark/OK    |
| `glyphicon glyphicon-remove`        | Close/remove    |
| `glyphicon glyphicon-zoom-in`       | Zoom in         |
| `glyphicon glyphicon-zoom-out`      | Zoom out        |
| `glyphicon glyphicon-off`           | Power off       |
| `glyphicon glyphicon-signal`        | Signal bars     |
| `glyphicon glyphicon-cog`           | Settings/gear   |
| `glyphicon glyphicon-trash`         | Trash/bin       |
| `glyphicon glyphicon-home`          | Home            |
| `glyphicon glyphicon-file`          | File/document   |
| `glyphicon glyphicon-time`          | Clock/time      |
| `glyphicon glyphicon-road`          | Road/map        |
| `glyphicon glyphicon-download-alt`  | Download (alt)  |
| `glyphicon glyphicon-download`      | Download        |
| `glyphicon glyphicon-upload`        | Upload          |
| `glyphicon glyphicon-inbox`         | Inbox           |
| `glyphicon glyphicon-play-circle`   | Play button     |
| `glyphicon glyphicon-repeat`        | Repeat/loop     |
| `glyphicon glyphicon-refresh`       | Refresh         |
| `glyphicon glyphicon-list-alt`      | Alternate list  |
| `glyphicon glyphicon-lock`          | Lock            |
| `glyphicon glyphicon-flag`          | Flag            |
| `glyphicon glyphicon-headphones`    | Headphones      |
| `glyphicon glyphicon-volume-off`    | Volume off      |
| `glyphicon glyphicon-volume-down`   | Volume down     |
| `glyphicon glyphicon-volume-up`     | Volume up       |
| `glyphicon glyphicon-qrcode`        | QR code         |
| `glyphicon glyphicon-barcode`       | Barcode         |
| `glyphicon glyphicon-tag`           | Tag             |
| `glyphicon glyphicon-tags`          | Multiple tags   |
| `glyphicon glyphicon-book`          | Book            |
| `glyphicon glyphicon-bookmark`      | Bookmark        |
| `glyphicon glyphicon-print`         | Print           |
| `glyphicon glyphicon-camera`        | Camera          |
| `glyphicon glyphicon-font`          | Font/text       |
| `glyphicon glyphicon-bold`          | Bold            |
| `glyphicon glyphicon-italic`        | Italic          |
| `glyphicon glyphicon-text-height`   | Text height     |
| `glyphicon glyphicon-text-width`    | Text width      |
| `glyphicon glyphicon-align-left`    | Align left      |
| `glyphicon glyphicon-align-center`  | Align center    |
| `glyphicon glyphicon-align-right`   | Align right     |
| `glyphicon glyphicon-align-justify` | Justify text    |
| `glyphicon glyphicon-list`          | List icon       |
| `glyphicon glyphicon-indent-left`   | Indent left     |
| `glyphicon glyphicon-indent-right`  | Indent right    |
| `glyphicon glyphicon-picture`       | Picture/image   |
| `glyphicon glyphicon-map-marker`    | Location marker |
| `glyphicon glyphicon-adjust`        | Adjust/contrast |
| `glyphicon glyphicon-tint`          | Tint/drop       |
| `glyphicon glyphicon-edit`          | Edit            |
| `glyphicon glyphicon-share`         | Share           |
| `glyphicon glyphicon-check`         | Checkmark       |
| `glyphicon glyphicon-move`          | Move/drag       |
| `glyphicon glyphicon-play`          | Play icon       |
| `glyphicon glyphicon-pause`         | Pause           |
| `glyphicon glyphicon-stop`          | Stop            |
| `glyphicon glyphicon-forward`       | Forward         |
| `glyphicon glyphicon-eject`         | Eject           |
| `glyphicon glyphicon-chevron-left`  | Chevron left    |
| `glyphicon glyphicon-chevron-right` | Chevron right   |
| `glyphicon glyphicon-question-sign` | Help/question   |
| `glyphicon glyphicon-info-sign`     | Info            |
| `glyphicon glyphicon-remove-sign`   | Remove (circle) |
| `glyphicon glyphicon-ok-sign`       | OK (circle)     |
| `glyphicon glyphicon-log-in`        | Login           |
| `glyphicon glyphicon-log-out`       | Logout          |

*…and many more (total: 260+). For the full reference list, refer to the [official Bootstrap documentation](https://getbootstrap.com/docs/3.4/components/#glyphicons).*

---

### 🧪 Testing Example:

```html
<!-- Bootstrap Glyphicon Buttons -->
<button class="btn btn-default">
  <span class="glyphicon glyphicon-search"></span> Search
</button>

<button class="btn btn-primary">
  <span class="glyphicon glyphicon-cloud-upload"></span> Upload
</button>
```

---


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

# Question: What are the key features and usage patterns of the Bootstrap JS Affix plugin?

### Bootstrap JS Affix Overview

| Feature              | Description                                                               |
| -------------------- | ------------------------------------------------------------------------- |
| Plugin name          | affix.js                                                                  |
| Purpose              | Allows an element to become fixed to an area on the page when scrolling   |
| Toggle behavior      | Changes CSS `position` from `static` to `fixed` based on scroll position  |
| Common use cases     | Sticky navigation bars, social icon buttons                               |
| Related plugin       | Often used with Scrollspy                                                 |
| Required CSS classes | `.affix`, `.affix-top`, `.affix-bottom` (you must define behavior in CSS) |

---

### Bootstrap JS Affix Usage

| Method                  | Syntax                                                                     | Example                                                                         |
| ----------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Via Data Attributes** | `data-spy="affix"` with optional `data-offset-top` or `data-offset-bottom` | `<ul class="nav nav-pills nav-stacked" data-spy="affix" data-offset-top="205">` |
| **Via JavaScript**      | Use `.affix()` method with options                                         | `$('.nav').affix({offset: {top: 150} });`                                       |

---

### Bootstrap JS Affix Options

| Name   | Type                         | Default  | Description                                                                                                             |
| ------ | ---------------------------- | -------- | ----------------------------------------------------------------------------------------------------------------------- |
| offset | number \| object \| function | `10`     | Number of pixels from screen edge. Use object for top/bottom: `{top: 25, bottom: 50}` or a function for dynamic values. |
| target | selector \| node \| element  | `window` | Target element whose scroll is used to trigger affix behavior.                                                          |

---

### Bootstrap JS Affix Events

| Event                     | Description                                                                    |
| ------------------------- | ------------------------------------------------------------------------------ |
| `affix.bs.affix`          | Fires **before** fixed positioning is applied (before `.affix-top` → `.affix`) |
| `affixed.bs.affix`        | Fires **after** fixed positioning is applied (after `.affix-top` → `.affix`)   |
| `affix-top.bs.affix`      | Fires **before** element returns to top (before `.affix` → `.affix-top`)       |
| `affixed-top.bs.affix`    | Fires **after** element returns to top (after `.affix` → `.affix-top`)         |
| `affix-bottom.bs.affix`   | Fires **before** element returns to bottom (before `.affix` → `.affix-bottom`) |
| `affixed-bottom.bs.affix` | Fires **after** element returns to bottom (after `.affix` → `.affix-bottom`)   |

---

### Bootstrap JS Affix Examples

| Example                           | Description                                                                                  |
| --------------------------------- | -------------------------------------------------------------------------------------------- |
| Horizontal navbar with affix      | `<nav class="navbar navbar-inverse" data-spy="affix" data-offset-top="197">`                 |
| jQuery affix with element height  | `$(".navbar").affix({offset: {top: $("header").outerHeight(true)} });`                       |
| Scrollspy with Affix - Horizontal | `<body data-spy="scroll" data-target=".navbar" data-offset="50">` with affixed navbar        |
| Scrollspy with Affix - Vertical   | `<body data-spy="scroll" data-target="#myScrollspy" data-offset="15">` with vertical sidenav |
| CSS Animation on Affix            | Use `.affix`, `.affix-top` for transitions, padding, color                                   |

#### Example CSS: Animated Navbar on Scroll

```css
.affix {
  top: 0;
  width: 100%;
  transition: all .5s ease-in-out;
  background-color: #F44336;
  border-color: #F44336;
}

.affix a {
  color: #fff !important;
  padding: 15px !important;
  transition: all .5s ease-in-out;
}

.affix-top a {
  padding: 25px !important;
}
```

#### Example CSS: Slide-in Navbar

```css
.affix {
  top: 0;
  width: 100%;
  transition: all .5s ease-in-out;
}

.affix-top {
  position: static;
  top: -35px;
}
```

---

# Question: What are the key features and usage patterns of the Bootstrap JS Button plugin?

### Bootstrap JS Button Overview

| Feature             | Description                                                                          |
| ------------------- | ------------------------------------------------------------------------------------ |
| Plugin name         | button.js                                                                            |
| Purpose             | Adds dynamic behavior and control to buttons                                         |
| Compatible elements | `<a>`, `<button>`, `<input>`                                                         |
| Common use cases    | Styling buttons, toggling states, disabling/loading/resetting buttons via JavaScript |

---

### Bootstrap JS Button Classes

| Class          | Description                                                   |
| -------------- | ------------------------------------------------------------- |
| `.btn`         | Adds basic styling to any button                              |
| `.btn-default` | Standard/default button styling                               |
| `.btn-primary` | Highlights the primary action                                 |
| `.btn-success` | Indicates a positive/successful action                        |
| `.btn-info`    | Indicates an informational message                            |
| `.btn-warning` | Indicates caution or warning                                  |
| `.btn-danger`  | Indicates a dangerous/negative action                         |
| `.btn-link`    | Makes the button appear like a link (retains button behavior) |
| `.btn-lg`      | Large button                                                  |
| `.btn-sm`      | Small button                                                  |
| `.btn-xs`      | Extra small button                                            |
| `.btn-block`   | Full-width (block-level) button                               |
| `.active`      | Makes the button appear pressed (active)                      |
| `.disabled`    | Disables the button (non-interactive)                         |

---

### Bootstrap JS Button Usage

| Method             | Syntax                        | Example               |
| ------------------ | ----------------------------- | --------------------- |
| **Via JavaScript** | Use `.button()` to initialize | `$('.btn').button();` |

---

### Bootstrap JS Button Options

| Option   | Type | Default | Description                             |
| -------- | ---- | ------- | --------------------------------------- |
| *(None)* | —    | —       | This plugin has no configurable options |

---

### Bootstrap JS Button Methods

| Method               | Description                                              |
| -------------------- | -------------------------------------------------------- |
| `.button("toggle")`  | Toggles the "active" state, visually pressing the button |
| `.button("loading")` | Disables the button and changes its text to "loading..." |
| `.button("reset")`   | Resets button text to the original content               |
| `.button("string")`  | Changes button text to a specified string                |

> Note: Methods can also be triggered via `data-*` attributes, such as `data-toggle="button"`.

---

### Bootstrap JS Button Examples

#### Example: Customize Button Borders

```css
.btn-default {
  border-radius: 0;
}
```

#### Example: Add Specific Button Colors

```css
.btn-default {
  background: #000;
  color: #fff;
}

.btn-default:hover {
  background: #fff;
  color: #000;
}
```

#### Example: Add Button Shadow

```css
.btn-default {
  box-shadow: 1px 2px 5px #000000;
}
```

---

# Question: What are the key features and usage patterns of the Bootstrap JS Carousel plugin?

### Bootstrap JS Carousel Overview

| Feature          | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Plugin name      | `carousel.js`                                            |
| Purpose          | Cycles through elements like a slideshow                 |
| Typical elements | Images, captions, content in slides                      |
| Browser note     | Not fully supported in IE9 and below (due to CSS3 usage) |

---

### Bootstrap JS Carousel Classes

| Class                     | Description                                        |
| ------------------------- | -------------------------------------------------- |
| `.carousel`               | Creates a carousel                                 |
| `.slide`                  | Adds slide animation effect                        |
| `.carousel-indicators`    | Adds navigation dots at the bottom of the carousel |
| `.carousel-inner`         | Container for slide items                          |
| `.item`                   | Represents a slide item                            |
| `.left.carousel-control`  | Adds left navigation control                       |
| `.right.carousel-control` | Adds right navigation control                      |
| `.carousel-caption`       | Adds caption for each slide                        |
| `.icon-next`              | Right arrow (alternative to glyphicon)             |
| `.icon-prev`              | Left arrow (alternative to glyphicon)              |

---

### Bootstrap JS Carousel Usage

| Method                  | Syntax                                                     | Example                                                          |                                                                     |
| ----------------------- | ---------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Via Data Attributes** | `data-ride="carousel"` to activate <br> \`data-slide="prev | next"`to navigate <br>`data-slide-to="number"\` to jump to slide | `<div id="myCarousel" class="carousel slide" data-ride="carousel">` |
| **Via JavaScript**      | Use `.carousel()` with or without options                  | `$("#myCarousel").carousel();`                                   |                                                                     |

#### Additional JavaScript Examples

```javascript
// Go to slide index 1
$(".item").click(function() {
  $("#myCarousel").carousel(1);
});

// Go to previous slide
$(".left").click(function() {
  $("#myCarousel").carousel("prev");
});
```

---

### Bootstrap JS Carousel Options

| Name       | Type              | Default   | Description                                                                      |
| ---------- | ----------------- | --------- | -------------------------------------------------------------------------------- |
| `interval` | number or `false` | `5000`    | Delay between slides in milliseconds. Set to `false` to disable auto sliding.    |
| `pause`    | string or `false` | `"hover"` | Pause on mouse hover. Set to `false` to disable pause.                           |
| `wrap`     | boolean           | `true`    | Whether to cycle through slides continuously (`true`) or stop at last (`false`). |

---

### Bootstrap JS Carousel Methods

| Method               | Description                                   |
| -------------------- | --------------------------------------------- |
| `.carousel(options)` | Activates the carousel with optional settings |
| `.carousel("cycle")` | Starts auto cycling through items             |
| `.carousel("pause")` | Stops auto cycling                            |
| `.carousel(number)`  | Navigates to a specific slide (0-based index) |
| `.carousel("prev")`  | Goes to the previous slide                    |
| `.carousel("next")`  | Goes to the next slide                        |

---

### Bootstrap JS Carousel Events

| Event               | Description                                      |
| ------------------- | ------------------------------------------------ |
| `slide.bs.carousel` | Triggered **before** a slide transitions         |
| `slid.bs.carousel`  | Triggered **after** a slide transition completes |

---

### Bootstrap JS Carousel Example: Full Structure with Captions

```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">

  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
    <li data-target="#myCarousel" data-slide-to="3"></li>
  </ol>

  <!-- Wrapper for slides -->
  <div class="carousel-inner" role="listbox">
    <div class="item active">
      <img src="img_chania.jpg" alt="Chania">
      <div class="carousel-caption">
        <h3>Chania</h3>
        <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
      </div>
    </div>
    <div class="item">
      <img src="img_chania2.jpg" alt="Chania">
      <div class="carousel-caption">
        <h3>Chania</h3>
        <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
      </div>
    </div>
    <div class="item">
      <img src="img_flower.jpg" alt="Flower">
      <div class="carousel-caption">
        <h3>Flowers</h3>
        <p>Beautiful flowers in Kolymbari, Crete.</p>
      </div>
    </div>
    <div class="item">
      <img src="img_flower2.jpg" alt="Flower">
      <div class="carousel-caption">
        <h3>Flowers</h3>
        <p>Beautiful flowers in Kolymbari, Crete.</p>
      </div>
    </div>
  </div>

  <!-- Left and right controls -->
  <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
```

---

# Question: What are the features and usage of the Bootstrap JS Collapse plugin?

### Collapse Plugin Classes

| Class          | Description                                                   |
| -------------- | ------------------------------------------------------------- |
| `.collapse`    | Hides the content                                             |
| `.collapse.in` | Shows the content                                             |
| `.collapsing`  | Added when the transition starts and removed when it finishes |

---

### Using Collapse via `data-*` Attributes

| Attribute                 | Description                                                                               |
| ------------------------- | ----------------------------------------------------------------------------------------- |
| `data-toggle="collapse"`  | Assigns the element as a collapse trigger                                                 |
| `data-target="#demo"`     | Specifies the ID of the element to collapse/expand                                        |
| `data-parent="#selector"` | Enables accordion-like behavior (collapses others under same parent when one is expanded) |

**Example:**

```html
<button class="btn" data-toggle="collapse" data-target="#demo">Collapsible</button>
<div id="demo" class="collapse">Some text..</div>
```

---

### Using Collapse via JavaScript

| Command                     | Description                                 |
| --------------------------- | ------------------------------------------- |
| `$('.collapse').collapse()` | Enables the collapse functionality manually |

---

### Collapse Options

| Name   | Type     | Default | Description                                          |
| ------ | -------- | ------- | ---------------------------------------------------- |
| parent | selector | false   | Accordion behavior: closes others when one is opened |
| toggle | boolean  | true    | Toggles the collapsible element upon invocation      |

---

### Collapse Methods

| Method                | Description                      |
| --------------------- | -------------------------------- |
| `.collapse(options)`  | Activates with the given options |
| `.collapse("toggle")` | Toggles the element visibility   |
| `.collapse("show")`   | Explicitly shows the element     |
| `.collapse("hide")`   | Explicitly hides the element     |

---

### Collapse Events

| Event                | Description                                                   |
| -------------------- | ------------------------------------------------------------- |
| `show.bs.collapse`   | Triggered when the element is about to be shown               |
| `shown.bs.collapse`  | Triggered when the element is fully shown (after transition)  |
| `hide.bs.collapse`   | Triggered when the element is about to be hidden              |
| `hidden.bs.collapse` | Triggered when the element is fully hidden (after transition) |

---

### Examples

#### 1. Simple Collapsible

```html
<button type="button" class="btn btn-info" data-toggle="collapse" data-target="#demo">
  Simple collapsible
</button>

<div id="demo" class="collapse in">
  Lorem ipsum dolor sit amet, consectetur adipisicing elit...
</div>
```

---

#### 2. Collapsible Panel

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" href="#collapse1">Collapsible panel</a>
      </h4>
    </div>
    <div id="collapse1" class="panel-collapse collapse">
      <div class="panel-body">Panel Body</div>
      <div class="panel-footer">Panel Footer</div>
    </div>
  </div>
</div>
```

---

#### 3. Collapsible List Group

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" href="#collapse1">Collapsible list group</a>
      </h4>
    </div>
    <div id="collapse1" class="panel-collapse collapse">
      <ul class="list-group">
        <li class="list-group-item">One</li>
        <li class="list-group-item">Two</li>
        <li class="list-group-item">Three</li>
      </ul>
      <div class="panel-footer">Footer</div>
    </div>
  </div>
</div>
```

---

#### 4. Accordion

```html
<div class="panel-group" id="accordion">
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse1">
        Collapsible Group 1</a>
      </h4>
    </div>
    <div id="collapse1" class="panel-collapse collapse in">
      <div class="panel-body">Content for group 1</div>
    </div>
  </div>
  
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse2">
        Collapsible Group 2</a>
      </h4>
    </div>
    <div id="collapse2" class="panel-collapse collapse">
      <div class="panel-body">Content for group 2</div>
    </div>
  </div>
  
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapse3">
        Collapsible Group 3</a>
      </h4>
    </div>
    <div id="collapse3" class="panel-collapse collapse">
      <div class="panel-body">Content for group 3</div>
    </div>
  </div>
</div>
```

---

#### 5. Expand and Collapse Toggle Icon & Text

**JavaScript:**

```js
$(document).ready(function(){
  $("#demo").on("hide.bs.collapse", function(){
    $(".btn").html('<span class="glyphicon glyphicon-collapse-down"></span> Open');
  });
  $("#demo").on("show.bs.collapse", function(){
    $(".btn").html('<span class="glyphicon glyphicon-collapse-up"></span> Close');
  });
});
```

**CSS:**

```css
/* Icon when the collapsible content is shown */
.btn:after {
  font-family: "Glyphicons Halflings";
  content: "\e114";
}

/* Icon when the collapsible content is hidden */
.btn.collapsed:after {
  content: "\e080";
}
```

---

# Question: What are the features and usage of the Bootstrap JS Dropdown plugin?

---

### Dropdown Plugin Classes

| Class                  | Description                                     |
| ---------------------- | ----------------------------------------------- |
| `.dropdown`            | Indicates a dropdown menu                       |
| `.dropdown-menu`       | Builds the dropdown menu                        |
| `.dropdown-menu-right` | Right-aligns a dropdown menu                    |
| `.dropdown-header`     | Adds a header inside the dropdown menu          |
| `.dropup`              | Indicates a dropup menu                         |
| `.disabled`            | Disables an item in the dropdown menu           |
| `.divider`             | Separates items inside the dropdown with a line |

---

### Using Dropdown via `data-*` Attributes

| Attribute                | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| `data-toggle="dropdown"` | Applied to a link or button to toggle the dropdown menu |

**Example:**

```html
<a href="#" class="dropdown-toggle" data-toggle="dropdown">Dropdown Example</a>
```

---

### Using Dropdown via JavaScript

| Command                             | Description                             |
| ----------------------------------- | --------------------------------------- |
| `$('.dropdown-toggle').dropdown();` | Manually enables dropdown functionality |

> **Note:** The `data-toggle="dropdown"` attribute is required even when using JavaScript.

---

### Dropdown Options

| Option | Description                                          |
| ------ | ---------------------------------------------------- |
| *None* | Bootstrap dropdowns do not accept additional options |

---

### Dropdown Methods

| Method                | Description          |
| --------------------- | -------------------- |
| `.dropdown("toggle")` | Toggles the dropdown |

---

### Dropdown Events

| Event                | Description                              |
| -------------------- | ---------------------------------------- |
| `show.bs.dropdown`   | Fires just before the dropdown is shown  |
| `shown.bs.dropdown`  | Fires once the dropdown is fully shown   |
| `hide.bs.dropdown`   | Fires just before the dropdown is hidden |
| `hidden.bs.dropdown` | Fires once the dropdown is fully hidden  |

**Tip:** Use jQuery’s `event.relatedTarget` to get the element that triggered the dropdown.

**Example:**

```js
$(".dropdown").on("show.bs.dropdown", function(event){
  var x = $(event.relatedTarget).text();
  alert(x);
});
```

---

### Examples

#### 1. Change the Caret Icon When Toggled

**CSS:**

```css
.caret.caret-up {
  border-top-width: 0;
  border-bottom: 4px solid #fff;
}
```

**JavaScript:**

```js
$(document).ready(function(){
  $(".dropdown").on("hide.bs.dropdown", function(){
    $(".btn").html('Dropdown <span class="caret"></span>');
  });
  $(".dropdown").on("show.bs.dropdown", function(){
    $(".btn").html('Dropdown <span class="caret caret-up"></span>');
  });
});
```

---

#### 2. Navbar With Dropdown

```html
<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">WebSiteName</a>
    </div>
    <div>
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li class="dropdown">
          <a class="dropdown-toggle" data-toggle="dropdown" href="#">Page 1
          <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Page 1-1</a></li>
            <li><a href="#">Page 1-2</a></li>
            <li><a href="#">Page 1-3</a></li>
          </ul>
        </li>
        <li><a href="#">Page 2</a></li>
        <li><a href="#">Page 3</a></li>
      </ul>
    </div>
  </div>
</nav>
```

---

#### 3. Dropdown With Login Form in Navbar

```html
<ul class="nav navbar-nav navbar-right">
  <li class="dropdown">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#">Login 
      <span class="glyphicon glyphicon-log-in"></span></a>
    <div class="dropdown-menu">
      <form id="formlogin" class="form container-fluid">
        <div class="form-group">
          <label for="usr">Name:</label>
          <input type="text" class="form-control" id="usr">
        </div>
        <div class="form-group">
          <label for="pwd">Password:</label>
          <input type="password" class="form-control" id="pwd">
        </div>
        <button type="button" id="btnLogin" class="btn btn-block">Login</button>
      </form>
      <div class="container-fluid">
        <a class="small" href="#">Forgot password?</a>
      </div>
    </div>
  </li>
</ul>
```

---

#### 4. Multi-Level Dropdowns

**JavaScript:**

```js
$(document).ready(function(){
  $('.dropdown-submenu a.test').on("click", function(e){
    $(this).next('ul').toggle();
    e.stopPropagation();
    e.preventDefault();
  });
});
```

**CSS:**

```css
.dropdown-submenu {
  position: relative;
}

.dropdown-submenu .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -1px;
}
```

---

# Question: What are the features and usage of the Bootstrap JS Modal plugin?

---

### Modal Plugin Classes

| Class            | Description                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------ |
| `.modal`         | Creates a modal                                                                            |
| `.modal-content` | Styles the modal with border, background-color, etc. Includes the header, body, and footer |
| `.modal-header`  | Defines the header area of the modal                                                       |
| `.modal-body`    | Defines the main content area of the modal                                                 |
| `.modal-footer`  | Defines the footer area of the modal (right-aligned by default)                            |
| `.modal-sm`      | Specifies a small modal                                                                    |
| `.modal-lg`      | Specifies a large modal                                                                    |
| `.fade`          | Adds fade-in and fade-out transition effect                                                |

---

### Triggering the Modal via `data-*` Attributes

| Attribute                | Description                                     |
| ------------------------ | ----------------------------------------------- |
| `data-toggle="modal"`    | Triggers the modal                              |
| `data-target="#modalID"` | Specifies which modal to open                   |
| `href="#modalID"`        | Used in `<a>` elements instead of `data-target` |

**Example:**

```html
<!-- Buttons -->
<button type="button" data-toggle="modal" data-target="#myModal">Open Modal</button>

<!-- Links -->
<a data-toggle="modal" href="#myModal">Open Modal</a>

<!-- Other elements -->
<p data-toggle="modal" data-target="#myModal">Open Modal</p>
```

---

### Triggering the Modal via JavaScript

| Command                 | Description                    |
| ----------------------- | ------------------------------ |
| `$("#myModal").modal()` | Enables and displays the modal |

---

### Modal Options

| Name     | Type                  | Default | Description                                                                                             |
| -------- | --------------------- | ------- | ------------------------------------------------------------------------------------------------------- |
| backdrop | boolean or `"static"` | true    | Whether modal has a backdrop: `true` (dark), `false` (transparent), `"static"` (click outside disabled) |
| keyboard | boolean               | true    | Whether modal can be closed using the Esc key                                                           |
| show     | boolean               | true    | Whether to show the modal when initialized                                                              |

---

### Modal Methods

| Method             | Description                                |
| ------------------ | ------------------------------------------ |
| `.modal(options)`  | Activates the modal with the given options |
| `.modal("toggle")` | Toggles visibility of the modal            |
| `.modal("show")`   | Displays the modal                         |
| `.modal("hide")`   | Hides the modal                            |

---

### Modal Events

| Event             | Description                                                 |
| ----------------- | ----------------------------------------------------------- |
| `show.bs.modal`   | Triggered when the modal is about to be shown               |
| `shown.bs.modal`  | Triggered when the modal is fully shown (after transition)  |
| `hide.bs.modal`   | Triggered when the modal is about to be hidden              |
| `hidden.bs.modal` | Triggered when the modal is fully hidden (after transition) |

---

### Example: Login Modal

```html
<div class="container">
  <h2>Modal Login Example</h2>
  <!-- Trigger the modal with a button -->
  <button type="button" class="btn btn-default btn-lg" id="myBtn">Login</button>

  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">

      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 style="color:red;"><span class="glyphicon glyphicon-lock"></span> Login</h4>
        </div>
        <div class="modal-body">
          <form role="form">
            <div class="form-group">
              <label for="usrname"><span class="glyphicon glyphicon-user"></span> Username</label>
              <input type="text" class="form-control" id="usrname" placeholder="Enter email">
            </div>
            <div class="form-group">
              <label for="psw"><span class="glyphicon glyphicon-eye-open"></span> Password</label>
              <input type="text" class="form-control" id="psw" placeholder="Enter password">
            </div>
            <div class="checkbox">
              <label><input type="checkbox" value="" checked> Remember me</label>
            </div>
            <button type="submit" class="btn btn-default btn-success btn-block">
              <span class="glyphicon glyphicon-off"></span> Login
            </button>
          </form>
        </div>
        <div class="modal-footer">
          <button type="submit" class="btn btn-default btn-default pull-left" data-dismiss="modal">
            <span class="glyphicon glyphicon-remove"></span> Cancel
          </button>
          <p>Not a member? <a href="#">Sign Up</a></p>
          <p>Forgot <a href="#">Password?</a></p>
        </div>
      </div>
    </div>
  </div>
</div>
```

---

# Question: How does the Bootstrap JS Popover plugin work and what options/methods/events does it support?

### Bootstrap JS Popover Overview

The **Popover** plugin adds small overlay content boxes, similar to tooltips, but with more rich content support. It **requires** the **Tooltip plugin** to be included.

---

### Usage: Data Attributes

| Attribute               | Description                                       |
| ----------------------- | ------------------------------------------------- |
| `data-toggle="popover"` | Activates the popover                             |
| `title`                 | Sets the header text of the popover               |
| `data-content`          | Sets the text displayed inside the popover's body |

**Example:**

```html
<a href="#" data-toggle="popover" title="Popover Header" data-content="Some content inside the popover">Toggle popover</a>
```

---

### Usage: JavaScript Initialization

| Code                                      | Description                                           |
| ----------------------------------------- | ----------------------------------------------------- |
| `$(‘[data-toggle="popover"]’).popover();` | Initializes all elements with `data-toggle="popover"` |
| `$('#myPopover').popover();`              | Initializes popover on a specific element             |

---

### Popover Options

| Name        | Type                 | Default                           | Description                                                            |
| ----------- | -------------------- | --------------------------------- | ---------------------------------------------------------------------- |
| `animation` | `boolean`            | `true`                            | Adds a fade transition when opening/closing                            |
| `container` | `string` or `false`  | `false`                           | Appends the popover to a specific element                              |
| `content`   | `string`             | `""`                              | Content inside the popover body                                        |
| `delay`     | `number` or `object` | `0`                               | Delay in milliseconds to show/hide popover. `{ show: 500, hide: 100 }` |
| `html`      | `boolean`            | `false`                           | Allows HTML content in the popover                                     |
| `placement` | `string`             | `"right"`                         | Position of the popover: `top`, `bottom`, `left`, `right`, or `auto`   |
| `selector`  | `string` or `false`  | `false`                           | Adds the popover to specified selector                                 |
| `template`  | `string`             | Base HTML template of the popover | Customizes the structure and styling                                   |
| `title`     | `string`             | `""`                              | Header text of the popover                                             |
| `trigger`   | `string`             | `"click"`                         | Trigger event: `click`, `hover`, `focus`, `manual`                     |
| `viewport`  | `string` or `object` | `{selector: "body", padding: 0}`  | Element boundary for the popover                                       |

---

### Popover Methods

| Method                | Description                              |
| --------------------- | ---------------------------------------- |
| `.popover(options)`   | Activates the popover with configuration |
| `.popover("show")`    | Shows the popover                        |
| `.popover("hide")`    | Hides the popover                        |
| `.popover("toggle")`  | Toggles the popover                      |
| `.popover("destroy")` | Hides and removes the popover            |

---

### Popover Events

| Event               | Description                                 |
| ------------------- | ------------------------------------------- |
| `show.bs.popover`   | Triggered before the popover is shown       |
| `shown.bs.popover`  | Triggered after the popover is fully shown  |
| `hide.bs.popover`   | Triggered before the popover is hidden      |
| `hidden.bs.popover` | Triggered after the popover is fully hidden |

---

### Custom Popover Design (CSS)

```css
/* Popover container */
.popover {
  border: 2px dotted red;
}

/* Popover header */
.popover-title {
  background-color: #73AD21;
  color: #FFFFFF;
  font-size: 28px;
  text-align: center;
}

/* Popover body */
.popover-content {
  background-color: coral;
  color: #FFFFFF;
  padding: 25px;
}

/* Popover arrow */
.arrow {
  border-right-color: red !important;
}
```

---

## Bootstrap JS Scrollspy

The **Scrollspy** plugin automatically updates navigation links based on scroll position. Often paired with the Affix plugin for sticky navigation.

---

### Basic Usage

#### Via `data-*` Attributes

```html
<body data-spy="scroll" data-target=".navbar" data-offset="50">

  <nav class="navbar navbar-inverse navbar-fixed-top">
    <ul class="nav navbar-nav">
      <li><a href="#section1">Section 1</a></li>
      ...
    </ul>
  </nav>

  <div id="section1">
    <h1>Section 1</h1>
    <p>Try to scroll this page and look at the navigation bar while scrolling!</p>
  </div>

</body>
```

* `data-spy="scroll"`: Activates the scrollspy behavior.
* `data-target=".navbar"`: Connects scrollspy to the nav.
* `data-offset="50"` (optional): Adjusts the offset for activation.
* Note: The scrollable element should use `position: relative`.

#### Via JavaScript

```javascript
$('body').scrollspy({ target: ".navbar" });
```

---

### Options

| Name   | Type   | Default | Description                                                     |
| ------ | ------ | ------- | --------------------------------------------------------------- |
| offset | number | 10      | Pixels to offset from the top when calculating scroll position. |

```html
<body data-spy="scroll" data-target=".navbar" data-offset="50">
```

---

### Methods

| Method                  | Description                                    |
| ----------------------- | ---------------------------------------------- |
| `.scrollspy("refresh")` | Refreshes the document when DOM changes occur. |

```javascript
$('body').scrollspy('refresh');
```

---

### Events

| Event                   | Description                         |
| ----------------------- | ----------------------------------- |
| `activate.bs.scrollspy` | Fires when a new item is activated. |

```javascript
$('#myNavbar').on('activate.bs.scrollspy', function () {
  console.log("New section activated.");
});
```

---

### Example: Smooth Scrolling with Scrollspy

```javascript
$('body').scrollspy({ target: ".navbar", offset: 50 });

$("#myNavbar a").on('click', function(event) {
  if (this.hash !== "") {
    event.preventDefault();
    const hash = this.hash;

    $('html, body').animate({
      scrollTop: $(hash).offset().top
    }, 800, function() {
      window.location.hash = hash;
    });
  }
});
```

---

### Scrollspy + Affix

#### Horizontal Menu (Navbar)

```html
<body data-spy="scroll" data-target=".navbar" data-offset="50">

  <nav class="navbar navbar-inverse" data-spy="affix" data-offset-top="197">
    ...
  </nav>

</body>
```

#### Vertical Menu (Sidenav)

```html
<body data-spy="scroll" data-target="#myScrollspy" data-offset="15">

  <nav class="col-sm-3" id="myScrollspy">
    <ul class="nav nav-pills nav-stacked" data-spy="affix" data-offset-top="205">
      ...
    </ul>
  </nav>

</body>
```

---
