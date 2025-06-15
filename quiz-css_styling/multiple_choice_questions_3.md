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
