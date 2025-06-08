# Question: What does Tailwind CSS provide to speed up development?

**Answer:**
Tailwind CSS provides pre-written utility classes that can be applied directly to HTML elements to dynamically update the design without writing custom CSS.

---

# Question: What are the available installation methods for Tailwind CSS?

**Answer:**
You can install Tailwind CSS using its CLI, through a framework guide (e.g., Next.js, Angular, Gatsby), or by using a CDN script for single HTML files.

---

# Question: Give a Tailwind utility class to give padding left of size 10 to a container.

```html
<div class="pl-10">
```

**Answer:**
Use the Tailwind utility class `pl-10` to apply padding-left of size 10.

Explanation:
In Tailwind CSS, `pl-10` sets the padding-left to the spacing value corresponding to `10`, which typically equals `2.5rem` (depending on your configuration).

---

# Question: Give a Tailwind class which is used to specify that elements are not allowed to float on the right side in relation to another element.

```html
<div class="clear-right">
```

**Answer:**
The Tailwind utility class `clear-right` prevents elements from floating on the right side, forcing them to clear any right floats before appearing.

Explanation:
`clear-right` ensures the element will be displayed below any floated elements on the right side.

---

# Question: Which class places the div one after another vertically?

```html
<element class="block">...</element>
```

**Answer:**
The Tailwind class `block` places elements one after another vertically by making them block-level elements.

Explanation:
Block-level elements take up the full width available and stack vertically by default, unlike inline or inline-block elements that flow horizontally.
