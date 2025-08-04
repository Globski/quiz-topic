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

