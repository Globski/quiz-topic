# Question: What property must be set on a container to start using Flexbox?

**Answer:** The container must have `display: flex` set in the CSS.

---

# Question: What does setting `display: flex` do to a container's layout?

**Answer:** It creates two invisible axes: a main axis and a cross axis, and aligns child items along the main axis by default.

---

# Question: What is the default direction of the main axis in Flexbox?

**Answer:** Horizontal (left to right).

---

# Question: How do you change the main axis direction in Flexbox to vertical?

**Answer:** Use the `flex-direction` property and set it to `column`.

---

# Question: What value of `flex-direction` sets the main axis to horizontal?

**Answer:** `row`, which is also the default value.

---

# Question: What property is used to align items along the main axis?

**Answer:** `justify-content`.

---

# Question: What does `justify-content: flex-start` do?

**Answer:** Aligns items to the start of the main axis. This is the default.

---

# Question: What does `justify-content: flex-end` do?

**Answer:** Pushes items to the end of the main axis.

---

# Question: What does `justify-content: center` do?

**Answer:** Centers items along the main axis.

---

# Question: What does `justify-content: space-between` do?

**Answer:** Distributes items evenly along the main axis, placing the first and last items at the ends with space in between.

---

# Question: What does `justify-content: space-around` do?

**Answer:** Distributes items with equal space around them, including space on the outer edges.

---

# Question: What does `justify-content: space-evenly` do?

**Answer:** Evenly distributes items so that the spacing between any two items (and the container edges) is equal.

---

# Question: What property is used to align items along the cross axis?

**Answer:** `align-items`.

---

# Question: What does `align-items: flex-start` do?

**Answer:** Aligns items at the start of the cross axis.

---

# Question: What does `align-items: flex-end` do?

**Answer:** Aligns items at the end of the cross axis.

---

# Question: What does `align-items: center` do?

**Answer:** Centers items along the cross axis.

---

# Question: What does `align-items: baseline` do?

**Answer:** Aligns the baseline of text across items, so their text baselines line up.

---

# Question: How can you see the effect of `align-items: baseline` clearly?

**Answer:** By increasing the font size of some items, you can see that the text baselines still align.

---

# Question: If `flex-direction` is not defined, what is the default value?

**Answer:** `row`.

---

# Question: What is the default direction of the cross axis?

**Answer:** Vertical (top to bottom), when `flex-direction` is `row`.

---

# Question: What happens to the main and cross axes when `flex-direction: column` is set?

**Answer:** The main axis becomes vertical, and the cross axis becomes horizontal.

---

# Question: In Flexbox, which property determines how items behave when they exceed the container width?

**Answer:** `flex-wrap`.

---

# Question: What is the default value of the `flex-wrap` property?

**Answer:** `nowrap`.

---

# Question: What does setting `flex-wrap: wrap` do?

**Answer:** Allows Flex items to wrap onto multiple lines instead of trying to fit into one.

---

# Question: What property enables wrapping behavior in a Flexbox container?

**Answer:** `flex-wrap`.

---

# Question: What must be true for the `align-content` property to have any effect?

**Answer:** The container must have `flex-wrap` set to `wrap`, and items must actually wrap to multiple lines.

---

# Question: What does the `align-content` property do in Flexbox?

**Answer:** It aligns multiple lines of Flex items along the cross axis.

---

# Question: What values can `align-content` take?

**Answer:** `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`.

---

# Question: How can you add spacing between Flex items?

**Answer:** Use the `gap` property on the container.

---

# Question: Where should the `gap` property be applied to affect Flex items?

**Answer:** On the Flex container.

---

# Question: Which Flexbox properties are applied to the **children** (Flex items) instead of the container?

**Answer:** `flex-grow`, `flex-shrink`, `flex-basis`, `flex`, and `align-self`.

---

# Question: What does the `flex-grow` property do?

**Answer:** It allows a Flex item to grow and take up remaining space in the container based on a proportional value.

---

# Question: What type of value does `flex-grow` accept?

**Answer:** A unitless number representing proportion.

---

# Question: What happens if three Flex items all have `flex-grow: 1`?

**Answer:** They will each grow equally and share the remaining space evenly.

---

# Question: What does the `flex-shrink` property control?

**Answer:** It defines how quickly an item shrinks relative to other items when space is limited.

---

# Question: What value should `flex-shrink` be set to in order to prevent shrinking?

**Answer:** `0`.

---

# Question: If `flex-shrink: 5` is applied to an item, what will happen?

**Answer:** That item will shrink five times faster than items with `flex-shrink: 1`.

---

# Question: What does the `flex-basis` property define?

**Answer:** The initial size of a Flex item before remaining space is distributed.

---

# Question: What happens if an item has both a `width` and a `flex-basis` value?

**Answer:** The `flex-basis` value will override the `width`.

---

# Question: What happens if `flex-basis` is set to `0`?

**Answer:** The item will shrink as much as possible before growing or distributing space.

---

# Question: What is the shorthand property for `flex-grow`, `flex-shrink`, and `flex-basis`?

**Answer:** `flex`.

---

# Question: How many parameters can the `flex` shorthand accept?

**Answer:** Up to three: `flex-grow`, `flex-shrink`, and `flex-basis`. The second and third are optional.

---

# Question: What happens when `flex` is set to a single value, like `flex: 1`?

**Answer:** The `flex-shrink` and `flex-basis` values are automatically set to intelligent defaults.

---

# Question: What does the `align-self` property do?

**Answer:** It overrides the `align-items` value on the container for a specific Flex item.

---

# Question: How would you align just one Flex item (e.g., the first item) to the center of the cross axis while others follow the container rule?

**Answer:** Set `align-self: center` on that item.

---










# Question: What does CSS stand for?

**Answer:**
*CSS* stands for *Cascading Style Sheets*. It is used to control the layout and design of web pages.

---

# Question: What can you do with CSS?

**Answer:**
With *CSS*, you can style text with eye-catching headlines, drop caps, and borders, arrange images precisely, create columns and banners, highlight links with rollover effects, and apply dynamic behaviors like fading elements, moving objects, or animating buttons on mouse hover.

---

# Question: Is CSS difficult to use?

**Answer:**
No. Despite its powerful features, *CSS* is designed to streamline the process of styling web pages, making it easier and more efficient to use.

---

# Question: What is the relationship between HTML and CSS?

**Answer:**
*HTML* provides the structural framework of a web page, such as organizing content into headers, paragraphs, and lists. *CSS*, on the other hand, works with the browser to style and visually enhance that structure.

---

# Question: How does CSS enhance a heading created with HTML?

**Answer:**
*CSS* can format an HTML heading by applying styles such as making the text big, bold, red, and positioning it 50 pixels from the left edge of the window.

---

# Question: What is a “style” in CSS?

**Answer:**
A *style* in CSS is a rule that defines how a particular element on a web page should look, such as its font, color, spacing, or position.

---

# Question: What is a style sheet?
**Answer:**
A *style sheet* is a collection of CSS styles (rules) that collectively determine the appearance of an HTML document.

---

# Question: How can CSS be used to style images?

**Answer:**
*CSS* can align images along the edges of a web page (such as the right edge), add colorful borders around them, and place margins (like a 50-pixel space) between the image and surrounding text.

---

# Question: What elements can CSS styles be applied to?

**Answer:**
*CSS* styles can be applied to various elements on a web page including text, images, headings, paragraphs, and other HTML elements.

---

# Question: How can CSS be used with HTML tags?

**Answer:**
You can create CSS styles specifically for HTML tags, such as making all `<h1>` tags on a site share the same font, size, and formatting, ensuring consistent styling across all pages.

---

# Question: What limitations did web designers face before CSS?

**Answer:**
Before *CSS*, web designers were restricted to HTML's basic formatting options, which made web pages look plain and often required complex, bulky code to achieve decent layout and styling.

---

# Question: What are some key advantages of CSS over HTML?

**Answer:**
*CSS* offers more formatting choices, such as magazine-style paragraphs, control over line spacing (leading), background image tiling, and compact styling code compared to HTML’s heavy tags like `<font>`. CSS also helps pages load faster and makes updates easier.

---

# Question: How does CSS handle background images better than HTML?

**Answer:**
*CSS* allows you to add background images and control whether and how they tile (repeat), a feature HTML does not support.

---

# Question: Why does using CSS result in faster-loading web pages?

**Answer:**
*CSS* reduces file size by replacing bulky HTML formatting tags with compact style rules. This trimming of kilobytes leads to quicker page loads, especially on text-heavy websites.

---

# Question: How does CSS simplify site-wide updates?

**Answer:**
By collecting all styles in a single external *style sheet* and linking it to every page, changes made to one style automatically apply across all linked pages, allowing for quick, global updates to a site’s appearance.

---

# Question: Can CSS work without HTML?

**Answer:**
No. *CSS* cannot function on its own—it requires *HTML* to define the structure of the web page it styles.

---

# Question: What should you know before learning CSS?

**Answer:**
You should know how to create a web page using basic *HTML*, as CSS depends on it to apply styling.

---

# Question: What should you do if your HTML knowledge is rusty?

**Answer:**
If your HTML skills are rusty, you can refresh them using online tutorials like [HTMLDog](https://www.htmldog.com/guides/htmlbeginner) and [W3Schools](https://www.w3schools.com/html), or consult books like *Creating a Website: The Missing Manual* or *Head First HTML and CSS*.

---

# Question: What does HTML stand for?

**Answer:**
*HTML* stands for *Hypertext Markup Language*. It uses simple tags to define the parts of a web page.

---

# Question: What does the following HTML code represent?

```html
<!doctype html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Hey, I am the title of this web page</title>
  </head>
  <body>
    <p>Hey, I am a paragraph on this web page.</p>
  </body>
</html>
```

**Answer:**
This is a complete basic *HTML* web page that includes a doctype declaration, an `<html>` element, a `<head>` with metadata and title, and a `<body>` with content—in this case, a paragraph.

---

# Question: What is a doctype in HTML?

**Answer:**
A *doctype* is a line of code at the beginning of an HTML document that specifies the version (or flavor) of HTML being used, such as HTML 4.01 or XHTML 1.0.

---

# Question: What are some common HTML doctypes?

**Answer:**
Common *HTML* doctypes include *HTML 4.01* and *XHTML 1.0*, each available in two styles: *strict* and *transitional*. An example is:

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

---

# Question: What is the simplified doctype used in HTML5?

**Answer:**
The simplified *HTML5* doctype is:

```html
<!doctype html>
```

It is supported by all major browsers, including older ones like Internet Explorer 6.

---

# Question: Why is the HTML5 doctype preferred over older doctypes?

**Answer:**
*HTML5* is easier to use, more streamlined, and widely supported. It avoids the complexity of earlier doctypes like HTML 4.01 and XHTML and is the future of web development.

---

# Question: Do all browsers support HTML5 features equally?

**Answer:**
No. While older browsers like Internet Explorer 6 and 8 support the *HTML5 doctype*, they do **not** recognize all *HTML5 tags* or features. Styling HTML5 tags in these browsers often requires additional *JavaScript*.

---

# Question: Why must every HTML page include a doctype?

**Answer:**
Including a *doctype* ensures consistent rendering across different browsers. Without it, browsers may display CSS inconsistently, causing your page to look different depending on the visitor’s browser.

---

# Question: What is the HTML 4.01 syntax for a line break?

**Answer:**
In *HTML 4.01*, a line break is written as:

```html
<br>
```

---

# Question: What is the XHTML syntax for a line break?

**Answer:**
In *XHTML*, a line break is written as:

```html
<br />
```

---

# Question: How does HTML5 handle line break syntax?

**Answer:**
*HTML5* is flexible and accepts **both** `<br>` and `<br />` as valid syntax for line breaks.

---

# Question: What do HTML tags do?

**Answer:**
*HTML tags* are instructions enclosed in brackets that tell the browser how to display content. They are the "markup" part of *Hypertext Markup Language*.

---

# Question: What is the structure of most HTML tags?

**Answer:**
Most HTML tags come in *pairs*: an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`). The closing tag includes a forward slash `/`.

---

# Question: What are the four essential elements found in every HTML page?

**Answer:**
The four essential elements are:

1. The *DOCTYPE* declaration.
2. The opening `<html>` tag.
3. The closing `</html>` tag.
4. Content wrapped in HTML structure tags like `<head>`, `<title>`, and `<body>`.

--

# Question: What does the `<html>` tag represent in a web page?

**Answer:**
The `<html>` tag indicates that the content is written in HTML. It encloses all other content and tags in a web page, making it the "root" of the page structure.

---

# Question: What are the two main sections within the `<html>` tag?

**Answer:**

1. The `<head>` section
2. The `<body>` section

These are like two main branches of the HTML tree structure.

---

# Question: What does the `<head>` section of a web page contain?

**Answer:**
The `<head>` section contains:

* The page’s `<title>`
* Metadata (like a page description)
* CSS code or links to external CSS files
* Other non-visible information used by browsers and search engines

---

# Question: What does the `<body>` section of a web page contain?

**Answer:**
The `<body>` section contains all the visible content of the web page, such as:

* Headlines
* Text
* Images
* Paragraphs
* Links

---

# Question: Which tag is used to define a paragraph?

**Answer:**
The `<p>` tag is used to start a paragraph, and the `</p>` tag is used to end it.

---

# Question: What does the `<strong>` tag do?

**Answer:**
The `<strong>` tag is used to emphasize text. It makes the enclosed text appear in **bold**.

---

# Question: How is a hyperlink created in HTML?

**Answer:**
Using the `<a>` (anchor) tag. For example:

```html
<a href="http://www.example.com">Click here!</a>
```

---

# Question: What is an attribute in an HTML tag?

**Answer:**
An attribute provides extra information about an element. In `<a href="http://...">`, `href` is the attribute and the URL is its value.

---

# Question: What is the purpose of the `href` attribute?

**Answer:**
The `href` attribute in an `<a>` tag specifies the destination URL of the hyperlink.

---

# Question: Why was XHTML introduced?

**Answer:**
XHTML was introduced to enforce stricter rules on HTML. It requires:

* Lowercase tag names
* Properly nested and closed tags

This improves compatibility with browsers, mobile devices, and other web technologies.

---

# Question: What are some issues with standard (older) HTML?

**Answer:**
Standard HTML:

* Allows mixed-case tags (`<BODY>`, `<body>`, etc.)
* Permits unclosed tags (e.g., `<p>` without `</p>`)
  This makes HTML easier to write but harder for browsers and smart devices to interpret consistently.

---

# Question: What is xHTML and why was it introduced?

**Answer:**
xHTML, or Extensible HyperText Markup Language, was introduced around 2000 as an improved version of HTML to keep pace with the rise of XML (Extensible Markup Language). It is essentially an "XML-ified" version of HTML intended to be the future standard for web pages by combining HTML's features with XML's stricter syntax rules.

---

# Question: Why did the W3C move away from xHTML towards HTML5?

**Answer:**
The W3C moved away from xHTML because the complexity of fully adopting XML as the web's prime language made browser manufacturers reluctant to follow that path. As a result, the W3C closed the xHTML working group and developed HTML5 instead, which moves away from XML and back to an enhanced version of HTML, supported by all major browsers.

---

# Question: How is HTML5 different from xHTML in terms of its approach to web development?

**Answer:**
Unlike xHTML, which aimed to foster a new way to build web pages with strict XML rules, HTML5 focuses on ensuring the Web continues to work as it always has, maintaining the basics of HTML while adding new elements to support modern web design practices without requiring XML compliance.

---

# Question: What are some new tags introduced in HTML5, and what purposes do they serve?

**Answer:**
HTML5 introduced new semantic tags such as:

* `<header>`: contains content typically found at the top of a page, like logos and navigation links.
* `<nav>`: encloses navigation links for the site.
* `<footer>`: holds content usually placed at the bottom of the page, such as legal notices or contact information.
  Additionally, HTML5 adds tags to embed video and audio, and enhanced form tags with features like sliders, pop-up date pickers, and built-in form validation.

—--

# Question: What challenges are associated with using HTML5's new features?

**Answer:**
Browser support for many new HTML5 features is inconsistent, making it difficult to use them without elaborate workarounds. Older browsers, such as Internet Explorer 8 and earlier, require additional help to properly render HTML5 elements.

—--

# Question: Should developers start using HTML5 now, even though it is not fully supported?

**Answer:**
Yes, developers are encouraged to start using the HTML5 doctype and basic HTML5 elements now, despite some browser compatibility issues, especially with older browsers. HTML5 is widely supported by modern browsers like Google Chrome and Firefox and is becoming the new standard for web development.

—--

# Question: What basic software do you need to create web pages using HTML and CSS?

**Answer:**
You only need a basic text editor like Notepad on Windows or TextEdit on Mac to create web pages made up of HTML and CSS.

—--

# Question: Why might you want to use software other than basic text editors for web development?

**Answer:**
After typing a few hundred lines of HTML and CSS, basic editors can become cumbersome. Specialized software offers features like syntax highlighting, FTP support, and auto-completion that make writing, editing, and managing web pages easier and more efficient.

—--

# Question: Name three free programs for editing HTML and CSS, and one key feature of each.

**Answer:**

* **jEdit** (Windows, Mac, Linux): Java-based and includes syntax highlighting.
* **Notepad++** (Windows): Fast text editor with syntax highlighting to color code HTML and CSS elements.
* **TextWrangler** (Mac): Pared-down version of BBEdit with syntax highlighting and FTP support for uploading files.

—--

# Question: What is the difference between TextWrangler and BBEdit?

**Answer:**
TextWrangler is a free, simplified version of BBEdit. While it lacks some of BBEdit’s built-in HTML tools, it still offers syntax highlighting and FTP capabilities.

—--

# Question: What was introduced in CSS 1, and when was it released?

**Answer:**
CSS 1, introduced in 1996, laid the groundwork for Cascading Style Sheets by establishing the basic structure of styles and the selector concept, along with most of the core CSS properties covered in this book.

—--

# Question: What are some key features added in CSS 2?

**Answer:**
CSS 2 added features such as the ability to target different devices (like printers and monitors), new selectors, and precise positioning of elements on a web page.

—--

# Question: What is CSS 2.1, and how does it relate to CSS 2?

**Answer:**
CSS 2.1 is the current accepted standard that incorporates all of CSS 1, adds several new properties, and corrects some problems found in the CSS 2 guidelines. It is a minor update rather than a radical change from CSS 2, and most browsers have adapted to it smoothly.

—--

# Question: How is CSS3 different from previous versions like CSS 1 and CSS 2.1?

**Answer:**
Unlike previous versions, CSS3 is not a single standard but a collection of separate modules (e.g., Selectors, Values and Units, Box Alignment). Each module develops independently, meaning there is no unified "CSS3" standard. Different modules are at various stages of completion and browser support.

—--

# Question: What is the status of CSS4?

**Answer:**
There will be no single CSS4. Instead, new versions of different CSS modules will continue to be developed and updated independently at different levels.

—--

# Question: How does adding CSS change the way HTML is used on web pages?

**Answer:**
Adding CSS to web design eliminates the need to repurpose awkward HTML tags just to achieve visual effects. It makes writing HTML easier and more semantic by separating content structure from presentation, allowing the use of simpler and cleaner HTML code.

—--

# Question: What happens to old HTML tags like the <font> tag when using CSS-driven web design?

**Answer:**
Old HTML tags and attributes like the <font> tag become obsolete and can be forgotten completely because CSS handles styling and visual effects.

---

# Question: Compare the size and complexity of an HTML-only page to a CSS-styled page with a similar look.

**Answer:**
An HTML-only page with visual effects can be nearly four times larger in file size and contain about three times more lines of code than a CSS-styled page achieving the same look. For example, an HTML-only page might be 14k with 213 lines of code, whereas the CSS version is only 4k with 71 lines.

---

# Question: Why was HTML originally created, and what was its primary purpose?

**Answer:**
HTML was originally created by scientists to structure technical documentation for easy comprehension, not for visual design. Its primary purpose was to organize information logically and semantically, such as using <h1> for main headings and <h2> for subheadings.

---
