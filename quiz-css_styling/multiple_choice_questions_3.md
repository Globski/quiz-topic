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

