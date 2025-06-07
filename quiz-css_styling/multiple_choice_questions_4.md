# Question: What are some common and less common text-formatting properties that CSS allows you to apply?

**Answer:**
CSS lets you apply common text-formatting properties like bold and italic, as well as less common ones such as small caps and letter spacing.

---

# Question: Why should you avoid overusing multiple text properties in CSS formatting?

**Answer:**
Using too many busy formatting styles makes your page harder to read and diminishes the impact of your hard work.

---

# Question: Which HTML tags do browsers display as italicized text by default?

**Answer:**
Browsers display text inside the `<em>` and `<i>` tags in italicized type.

---

# Question: Which HTML tags do browsers display as bold text by default?

**Answer:**
Text inside `<strong>`, `<b>`, `<th>` (table header), and header tags like `<h1>` is displayed in bold by default.

---

# Question: How can you control italicizing and bolding of text using CSS properties?

**Answer:**
You can control italicizing using the `font-style` property and bolding using the `font-weight` property.

---

# Question: How do you italicize text with CSS?

**Answer:**
By adding the style `font-style: italic;` to the text.

---

# Question: How do you ensure text is not italicized using CSS?

**Answer:**
By setting `font-style: normal;`.

---

# Question: What is the third option for the `font-style` property besides normal and italic, and how does it behave?

**Answer:**
The third option is `oblique`, which behaves identically to italic.

---

# Question: How many numeric values does the `font-weight` property accept, and what do they represent?

**Answer:**
`font-weight` accepts nine numeric values (100 to 900) representing subtle gradations of boldness, from nearly invisible-light (100) to super-extra-heavy (900).

---

# Question: When can you use the numeric values for `font-weight` effectively?

**Answer:**
You can only use the numeric font-weight values effectively if the fonts you use support nine different weights, typically available with web fonts like those from Google Web Fonts.

---

# Question: What font-weight specification method do Google Web Fonts use?

**Answer:**
Google Web Fonts use numeric values exclusively for specifying font weights.

---

# Question: How can you apply multiple text decoration effects using CSS?

**Answer:**
By combining multiple keywords in the `text-decoration` property, such as `text-decoration: underline overline;`.

---

# Question: Why should you avoid underlining non-link text on a web page?

**Answer:**
Because users instinctively associate underlined text with hyperlinks and may try to click it, which leads to confusion and poor user experience.

---

# Question: What is the visual effect of the `overline` value in the `text-decoration` property?

**Answer:**
It draws a line above the text.

---

# Question: What does the `line-through` value of the `text-decoration` property do?

**Answer:**
It draws a line through the center of the text, often used to indicate that text has been removed or edited out.

---

# Question: What is a major reason to avoid using the `blink` value in `text-decoration`?

**Answer:**
It makes text blink like a neon sign and looks unprofessional—so much so that most modern browsers ignore it entirely.

---

# Question: What is the CSS keyword to remove all text decorations?

**Answer:**
`text-decoration: none;`

---

# Question: What is a better alternative to using `underline` or `overline` for styling text?

**Answer:**
Using CSS borders (like `border-top` or `border-bottom`), which offer more control over placement, size, and color without making text appear as clickable links.

---

# Question: What advantage does using borders (instead of text decoration) provide?

**Answer:**
Borders allow designers to control the placement, size, and color of lines more precisely, creating more attractive and intentional designs.

---

# Question: Why is it useful to have the `text-decoration: none;` property in CSS?

**Answer:**
It allows you to remove default decorations, such as the underline that typically appears under hyperlinks.

---

# Question: What CSS property allows you to adjust the spacing between letters in text?

**Answer:**
The `letter-spacing` property.

---

# Question: How can you make letters appear closer together using CSS?

**Answer:**
By using a negative value with the `letter-spacing` property, for example:
`letter-spacing: -1px;`

---

# Question: How can you increase the space between letters in CSS?

**Answer:**
By using a positive value with the `letter-spacing` property, for example:
`letter-spacing: .7em;`

---

# Question: What effect does reducing letter spacing have on a headline’s appearance?

**Answer:**
It tightens up the headline, making it appear bolder and heavier, and allows more letters to fit on a single line.

---

# Question: What effect does increasing letter spacing have on a headline?

**Answer:**
It gives the headline a calmer and more majestic appearance.

---

# Question: What CSS property controls the spacing between words (not letters)?

**Answer:**
The `word-spacing` property.

---

# Question: How do you increase the space between words using CSS?

**Answer:**
By assigning a positive value to `word-spacing`, such as:
`word-spacing: 2px;`

---

# Question: Can you use negative values with the `word-spacing` property?

**Answer:**
Yes, both positive and negative values are allowed with `word-spacing`, just like with `letter-spacing`.

---

# Question: What units can be used with `letter-spacing` and `word-spacing`?

**Answer:**
You can use pixels (`px`), ems (`em`), percentages (`%`), or any standard CSS text sizing units.

---

# Question: Why should you use `letter-spacing` and `word-spacing` carefully?

**Answer:**
Because too much or too little spacing can make the text difficult or even impossible to read.

---

# Question: What happens if you use overly large negative values for `letter-spacing` or `word-spacing`?

**Answer:**
Letters and words may overlap, making the text unreadable.

---

# Question: Why is it important to use `letter-spacing` and `word-spacing` with care?

**Answer:**
Because improper spacing can make your text difficult or impossible to read, which undermines the clarity and effectiveness of your content.

---

# Question: What CSS property allows you to add a drop shadow to text?

**Answer:**
The `text-shadow` property.

---

# Question: What four values must you specify when using the `text-shadow` property?

**Answer:**

1. Horizontal offset (e.g., `-4px`)
2. Vertical offset (e.g., `4px`)
3. Blur radius (e.g., `3px`)
4. Shadow color (e.g., `#999999`)

---

# Question: What does a negative horizontal offset in `text-shadow` do?

**Answer:**
It places the shadow to the **left** of the text.

---

# Question: What does a positive vertical offset in `text-shadow` do?

**Answer:**
It places the shadow **below** the text.

---

# Question: What effect does the blur radius in `text-shadow` control?

**Answer:**
It controls how blurry or sharp the shadow appears; `0px` results in a sharp shadow, while higher values increase blur.

---

# Question: How do you apply multiple text shadows in CSS?

**Answer:**
By separating each set of `text-shadow` values with a comma.
Example:
`text-shadow: -4px 4px 3px #666, 1px -1px 2px #000;`

---

# Question: Does the `text-shadow` property work in Internet Explorer 9 or earlier?

**Answer:**
No, the `text-shadow` property is not supported in Internet Explorer 9 or earlier versions.

---

# Question: What is the only limit to how many text shadows you can add?

**Answer:**
Good taste—there’s no technical limit, but overuse can make text look messy or unprofessional.

---

# Question: Why shouldn't you rely on `text-shadow` to make text readable?

**Answer:**
Because some browsers (like Internet Explorer 9 and earlier) don’t support it. If your text color is white and only the shadow outlines the text, it may be completely invisible on a white background in those browsers.

---

# Question: Which version of Internet Explorer first supported `text-shadow`?

**Answer:**
Internet Explorer 10.

---

# Question: What is the CSS property used to adjust the vertical space between lines of text?

**Answer:**
`line-height`

---

# Question: What happens when you increase the value of `line-height`?

**Answer:**
It increases the space between lines, spreading them farther apart.

---

# Question: What does a smaller percentage in `line-height` do?

**Answer:**
It tightens the lines, reducing the vertical space between them.

---

# Question: What is the default (normal) value of `line-height` in CSS?

**Answer:**
Approximately **120%** of the font size.

---

# Question: Can the `line-height` property be applied to entire paragraphs?

**Answer:**
Yes, it’s commonly applied to full paragraphs, headlines, and blocks of text to improve readability.

---

 
