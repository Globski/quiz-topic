# Question: What HTML tag is use to group e.g four paragraphs?

**Answer:** The `<section>` tag.

---

# Question: What is the purpose of assigning a `class` to the section element?

**Answer:** The class e.g `columns` was assigned to apply CSS styling that enables column-based layout for the section's content.

---

# Question: What does the `.columns` CSS class define?

**Answer:** It defines `column-count: 4;`, which attempts to create four columns within the section.

---

# Question: What visual behavior occurs in the browser when `column-count: 4` is applied?

**Answer:** The first four paragraphs are displayed in four separate columns, while the fifth paragraph (outside the section) is not affected and remains in a single column.

---

# Question: How does the column layout behave when the browser window is resized?

**Answer:** The number of visible columns adjusts responsively; initially one paragraph per column, but changes dynamically as the viewport width changes.

---

# Question: What property ensures that a column does not become smaller than a specific width?

**Answer:** The `column-width` property ensures each column is not smaller than a specified width (e.g., 250px).

---

# Question: What happens when both `column-count` and `column-width` are specified?

**Answer:** The browser respects the `column-width` and only creates as many columns as the available width allows, up to the maximum defined by `column-count`.

---

# Question: What is the expected behavior when the screen can only fit columns narrower than 250px?

**Answer:** The browser reduces the number of columns shown, adhering to the minimum width of 250px per column.

---

# Question: What shorthand property can replace both `column-count` and `column-width`?

**Answer:** The `columns` shorthand property can replace both, e.g., `columns: 4 250px;`.

---

# Question: What is the result of replacing `column-count` and `column-width` with the shorthand `columns`?

**Answer:** The visual result remains the same; it simplifies the CSS while maintaining column behavior.

---

# Question: How can you add visual dividers between columns?

**Answer:** By using the `column-rule` property, e.g., `column-rule: 3px solid black;`.

---

# Question: How does `column-rule` behave in CSS?

**Answer:** It works similarly to a `border` property, combining width, style, and color to create lines between columns.

---






# Question: What are media queries in CSS3?

**Answer:**
Media queries are a CSS3 feature that allows developers to apply styles to a web page based on the width and height of the destination browser, enabling responsive design for different devices like phones, tablets, and desktops.

---

# Question: What is the main goal of responsive web design?

**Answer:**
The goal of responsive design is to provide the most readable and attractive presentation possible for visitors, by customizing the layout and styling based on different browser widths and devices.

---

# Question: Which three device categories do designers usually target when planning responsive layouts?

**Answer:**
Designers typically target smartphones, tablets, and desktop computers, as these are the most common categories of web browsing devices.

---

# Question: Why is there no single ideal width for devices like phones and tablets?

**Answer:**
Because there is a wide variety of device sizes—such as small phones, large phones, 7" tablets, and 10" tablets—there is no universal width that fits all. Therefore, designs must adapt fluidly to various screen sizes.

---

# Question: What is one of the most common uses of media queries in web design?

**Answer:**
One common use is adjusting the number of columns in a layout. For example, reducing from four columns on a desktop to two or one column on tablets and phones to improve readability and usability.

---

# Question: Why should designers avoid using floats in mobile-targeted media query styles?

**Answer:**
Avoiding floats in mobile-targeted styles allows content containers to stack vertically, which improves readability and layout on smaller screens.

---

# Question: How do designers typically handle widths for different devices?

**Answer:**
Designers may use fixed-width layouts for desktop browsers but must use flexible widths for narrower screens like phones and tablets because a fixed-width layout (e.g., 960px) won’t fit smaller windows properly.

---

# Question: Why is a 960-pixel-wide fixed layout problematic for phones?

**Answer:**
A 960-pixel-wide fixed layout does not fit well on smaller phone screens that are typically 320 or 480 pixels wide, resulting in horizontal scrolling and poor user experience.

---

# Question: How can you convert a fixed-width layout into a liquid or flexible design?

**Answer:**
You can set the widths of your content `<div>` elements to `auto` or `100%`, allowing them to resize automatically to fit the width of the device's screen.

---

# Question: What happens when a user rotates a phone from portrait to landscape mode and the page uses `width: auto` or `width: 100%`?

**Answer:**
The `<div>` elements automatically resize to fit the new screen width, ensuring the layout remains responsive and readable.

---

# Question: Why should you tighten up whitespace in responsive design?

**Answer:**
On small screens like phones, too much whitespace between headlines, graphics, and other elements can waste space and force excessive scrolling. Reducing margins and padding helps fit more content and improve readability.

---

# Question: How should font sizes be adjusted for smaller screens?

**Answer:**
Large headlines may need to be reduced, and body text may need to be increased slightly to enhance readability on small screens. Proper font sizing ensures text remains legible and doesn't waste screen space.

---

# Question: What is a common issue with horizontal navigation bars on small screens?

**Answer:**
As the screen narrows, buttons in a horizontal navigation bar may no longer fit in a single row, causing them to wrap onto multiple lines and take up too much vertical space.

---

# Question: What is a common solution to handle complex navigation menus on smaller devices?

**Answer:**
Many sites use JavaScript to convert horizontal navigation menus into HTML drop-down menus, which take up less space and work better on small screens.

---

# Question: What are two recommended resources for learning about responsive navigation patterns?

**Answer:**

* [http://css-tricks.com/convert-menu-to-dropdown/](http://css-tricks.com/convert-menu-to-dropdown/)
* [http://bradfrostweb.com/blog/web/responsive-nav-patterns/](http://bradfrostweb.com/blog/web/responsive-nav-patterns/)

---

# Question: Why might a designer choose to hide content on handheld devices?

**Answer:**
To reduce visual clutter and avoid overwhelming mobile users with too much information. Hiding non-essential content makes the site cleaner and easier to navigate on small screens.

---

# Question: What is the downside of hiding content for mobile users?

**Answer:**
Hiding content may prevent users from accessing important information they expected to find, especially if they previously saw it on a desktop version of the site.

---

# Question: What is a major drawback of hiding content using CSS on mobile devices?

**Answer:**
Even though the content is hidden visually, the HTML is still downloaded by the mobile browser, which wastes bandwidth and processing time.

---

# Question: Why should designers consider using background images instead of inline `<img>` tags for large graphics?

**Answer:**
Background images can be more easily swapped for smaller versions using CSS media queries, allowing for optimized loading and better fitting on small screens without zooming.

---

# Question: How can you use different background images for desktop and mobile in CSS?

**Answer:**
By assigning a class (e.g., `.logo`) to a `<div>` and defining different styles in the media queries, such as:

```css
.logo {
    width: 960px;
    height: 120px;
    background-image: url(images/large_logo.png);
}
```

Then overriding it in a mobile-specific media query with:

```css
.logo {
    width: 320px;
    height: 60px;
    background-image: url(images/small_logo.png);
}
```

---

# Question: What is a breakpoint in responsive design?

**Answer:**
A breakpoint is a specific screen width at which a web design begins to visually break down or look awkward, signaling the need to apply new styles using a media query.

---

# Question: How can you determine a good breakpoint in your layout?

**Answer:**
By loading your design in a desktop browser and slowly narrowing the window until the layout starts to look cramped or broken—this point is a good candidate for a breakpoint.

---

# Question: What kind of screen width might you use as a media query condition?

**Answer:**
Common examples include:

* `max-width: 480px` for mobile phones
* `min-width: 481px and max-width: 768px` for tablets

---

# Question: Where can you find an overview of different layout strategies for responsive design?

**Answer:**
At [www.lukew.com/ff/entry.asp?1514](http://www.lukew.com/ff/entry.asp?1514)

---

# Question: What is a breakpoint in responsive web design?

**Answer:**
A breakpoint is a specific screen width at which a web design starts to look bad or cramped, signaling that a new set of styles should be applied using a media query.

---

# Question: What are the three most common breakpoints used in responsive design?

**Answer:**

* Less than 480 pixels: smartphones
* Between 481 and 768 pixels: tablets
* Greater than 768 pixels: desktops
  (Some designers extend the tablet range up to 1024 pixels.)

---

# Question: Is it necessary to create a separate complete stylesheet for each breakpoint?

**Answer:**
No. You start with a default stylesheet and then use media queries to override or add to the default styles for specific screen widths.

---

# Question: What is the “desktop-first” design approach?

**Answer:**
The desktop-first approach means designing and styling the site primarily for desktop screens, then using media queries to adjust the design for tablets and smartphones. It’s beneficial because older desktop browsers that don’t support media queries will still display the site correctly.

---

# Question: What is the “mobile-first” design approach?

**Answer:**
The mobile-first approach involves designing the site initially for small screens, then using media queries to add styles for tablets and desktops. The base stylesheet contains mobile styles, with larger screen styles added through media queries.

---

# Question: What is one advantage of using the desktop-first approach?

**Answer:**
It ensures that older desktop browsers (like Internet Explorer 8) that don’t support media queries still get the full desktop styling.

---

# Question: What should your main stylesheet include regardless of your breakpoint strategy?

**Answer:**
It should include styles that are shared across all devices, such as:

* Color schemes
* Font choices
* Link styling
* Image appearance
* General layout rules

---

# Question: What is a media query in web design?

**Answer:**
A media query is a question asked of a web browser, such as “Is your screen 480 pixels wide?” If the answer is yes, the browser loads a specific style sheet designed for that device size.

---

# Question: How do you link a CSS file to a webpage with a media query for a specific width?

**Answer:**
You use the `<link>` tag with the `media` attribute, for example:
`<link href="css/small.css" rel="stylesheet" media="(width: 480px)">`
This tells the browser to load `small.css` only if the screen width is exactly 480 pixels.

---

# Question: Why are parentheses required around the media query condition in the `media` attribute?

**Answer:**
Parentheses around the query, like `(width: 480px)`, are required because if you leave them out, the browser will ignore the media query and not apply the conditional style sheet.

---

# Question: What browsers do not support media queries by default, and how can support be added?

**Answer:**
Internet Explorer 8 and earlier versions do not understand media queries. To make them understand, you can include a JavaScript file called `respond.js` and link it with a conditional comment targeting IE 8 and lower, like so:

```
<!--[if lte IE 8]>
<script src="respond.min.js"></script>
<![endif]-->
```

---

# Question: Where can you get the `respond.js` file to add media query support for older IE versions?

**Answer:**
You can download `respond.js` from the URL: [http://tinyurl.com/7w49a6z](http://tinyurl.com/7w49a6z)

---

# Question: Why is using an exact width like 480 pixels in media queries often not ideal?

**Answer:**
Because devices can have different screen widths, using an exact width like 480 pixels won’t cover smaller or larger screens. For example, a phone with a 300-pixel-wide screen would not match a query for exactly 480 pixels.

---

# Question: How do you specify a range for screen widths in a media query?

**Answer:**
You use `max-width` or `min-width` in the media query. For example:

* `(max-width: 480px)` applies to screens that are at most 480 pixels wide.
* `(min-width: 769px)` applies to screens that are at least 769 pixels wide.

---

# Question: What does the media query `(max-width: 480px)` mean?

**Answer:**
It means the style sheet applies to all screens that are 480 pixels wide or narrower, such as 480px, 320px, or even 200px wide screens.

---

# Question: What is the purpose of using `(min-width: 769px)` in a media query?

**Answer:**
It targets devices with screens wider than 768 pixels, such as many tablets or desktops, ensuring the style sheet applies only to screens at least 769 pixels wide.

---

# Question: What is the significance of using `769px` instead of `768px` in `(min-width: 769px)`?

**Answer:**
Using 769 pixels ensures that the style sheet applies only to screens wider than 768 pixels, avoiding overlap with devices exactly 768 pixels wide (like some tablets).

---

# Question: How can you target devices that fall between phone and desktop screen sizes using media queries?

**Answer:**
You can combine `min-width` and `max-width` in a media query to target devices within a range. For example:
`<link href="css/medium.css" rel="stylesheet" media="(min-width:481px) and (max-width:768px)">`
This applies styles only if the screen width is between 481 and 768 pixels, such as many tablets.

---

# Question: Would the media query `(min-width:481px) and (max-width:768px)` apply to a 320-pixel-wide smartphone or a 1024-pixel desktop screen?

**Answer:**
No, it would not apply to a 320-pixel smartphone because the minimum width is 481px. It also wouldn’t apply to a 1024-pixel desktop screen because the maximum width is 768px.

---

# Question: Besides width, what other features can CSS3 media queries check?

**Answer:**
CSS3 media queries can check height, orientation (portrait or landscape), and whether the device screen is color or monochrome. There are additional browser characteristics that media queries can test, but support varies between browsers.

---

# Question: Where can you learn more about the CSS3 media query standard?

**Answer:**
You can learn more at the W3C website: [www.w3.org/TR/css3-mediaqueries](http://www.w3.org/TR/css3-mediaqueries)

---

# Question: What is an alternative way to include media queries besides using multiple `<link>` tags?

**Answer:**
You can include media queries directly inside a single style sheet, either internal or external, to keep all styles in one place and avoid multiple `<link>` tags.

---

# Question: How can you load additional external style sheets inside a style sheet using media queries?

**Answer:**
You can use the `@import` directive combined with a media query. For example:
`@import url(css/small.css) (max-width:320px);`
This loads the `small.css` file only if the screen width is 320 pixels or smaller.

---

# Question: Why might using `@import` with media queries be problematic in older Internet Explorer versions?

**Answer:**
Internet Explorer 8 and earlier only support media queries if you use the JavaScript polyfill `respond.js`, but `respond.js` does not work with media queries loaded via the `@import` directive. Therefore, media queries using `@import` won’t work in IE 8 and earlier.

---

# Question: Why is the lack of `@import` media query support in IE 8 and earlier not a major concern?

**Answer:**
Because desktop browsers, which IE 8 and earlier generally run on, don’t necessarily need media queries as much, so the lack of support for media queries via `@import` is less impactful.

---




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

 
