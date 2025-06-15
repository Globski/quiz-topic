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

