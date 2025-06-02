# Question: How do you apply an external CSS stylesheet to an HTML document?

**Answer:**
You apply an external CSS stylesheet by placing a `<link>` element inside the `<head>` section of the HTML document. The `<link>` tag should have the attribute `rel="stylesheet"` and `href` set to the path of the CSS file.

---

# Question: Why is it recommended to place the `<link>` tag inside the `<head>` tag of an HTML file?

**Answer:**
Placing the `<link>` tag inside the `<head>` ensures that styles are loaded before the page content, preventing users from seeing a flash of unstyled content.

---

# Question: Can the `type` attribute be omitted in the `<link>` tag when linking a CSS file in HTML5?

**Answer:**
Yes, in HTML5 the `type="text/css"` attribute can be omitted since it is the default for stylesheets.

---

# Question: What is the advantage of using relative paths over absolute paths in the `href` attribute of the `<link>` tag?

**Answer:**
Relative paths are generally preferred because they are more flexible when moving files or deploying websites across different environments, while absolute paths are fixed and can break if the file location changes.

---

# Question: What is the benefit of using an external stylesheet when managing a website with many pages?

**Answer:**
Using an external stylesheet allows you to make a single change in the CSS file that cascades across all pages, making maintenance easier and avoiding repetitive edits in every individual HTML file.

---

# Question: How does the browser handle CSS files when a user navigates between pages on the same website?

**Answer:**
The browser downloads the CSS file only once and caches it, so subsequent page loads do not require downloading the CSS again, which speeds up page loading times.

---

# Question: Can multiple external CSS files be linked in one HTML document? If so, does the order of these files matter?

**Answer:**
Yes, multiple external CSS files can be linked by using multiple `<link>` tags. The order matters because later files can override styles defined in earlier files.

---

# Question: Given the following CSS in `main.css`:

```css
p.green { color: #00FF00; }
```

and the following in `override.css`:

```css
p.green { color: #006600; }
```

If both files are linked in order (`main.css` first, then `override.css`), what will be the color of paragraphs with the class "green"?

**Answer:**
The paragraphs will be colored `#006600` (darker green) because the styles in `override.css` come after and override those in `main.css`.

---

# Question: Besides order, what other CSS principles affect how rules are applied?

**Answer:**
Other principles include specificity (how specific a selector is), inheritance (how styles are passed down from parent elements), and the `!important` declaration which can force a rule to override others.

---

# Question: If the CSS file is stored in a folder called `styles`, how should you reference it in the `href` attribute?

**Answer:**
You should specify the relative path including the folder name, for example: `href="styles/style.css"`.

---

