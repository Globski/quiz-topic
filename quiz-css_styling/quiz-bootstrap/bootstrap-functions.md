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
