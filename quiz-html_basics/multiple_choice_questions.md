# Question: How can you optimize website asset loading to improve load time?

**Answer:**  
To optimize website load time by improving asset loading, the following methods are used:

- **CDN Hosting:** Use geographically distributed servers to reduce latency.  
- **File Compression:** Compress files to reduce their size and data transfer.  
- **File Concatenation:** Combine multiple files to reduce the number of HTTP requests.  
- **Minify Scripts:** Remove unnecessary characters from JavaScript and CSS files to reduce file size.  
- **Parallel Downloads:** Host assets on multiple subdomains to bypass browser download limits per domain.  
- **Lazy Loading:** Load non-critical assets only when needed instead of all at once.

---

# Question: What are the different kinds of Doctypes available in HTML?

**Answer:**

There are three main kinds of Doctypes traditionally used in HTML 4, plus a modern HTML5 Doctype. Each defines how the HTML document is parsed by the browser.

---

## 1. Strict Doctype

- Disallows deprecated tags and attributes.
- Promotes clean, modern coding.

**Example:**
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
  "http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head>
    <title>Strict Doctype Example</title>
  </head>
  <body>
    <p>This follows strict HTML 4.01 rules.</p>
  </body>
</html>
````

---

## 2. Transitional Doctype

* Allows deprecated elements (like `<font>`, `<center>`).
* Useful for legacy HTML being modernized slowly.

**Example:**

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
  "http://www.w3.org/TR/html4/loose.dtd">
<html>
  <head>
    <title>Transitional Doctype Example</title>
  </head>
  <body>
    <center>This uses some deprecated tags like center.</center>
  </body>
</html>
```

---

## 3. Frameset Doctype

* Used when the page uses `<frameset>` instead of `<body>`.
* Completely deprecated in HTML5.

**Example:**

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
  "http://www.w3.org/TR/html4/frameset.dtd">
<html>
  <head>
    <title>Frameset Doctype Example</title>
  </head>
  <frameset cols="50%,50%">
    <frame src="left.html">
    <frame src="right.html">
  </frameset>
</html>
```

---

## ✅ Modern: HTML5 Doctype

* Short and simple.
* Used in all modern web development.

**Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Doctype</title>
  </head>
  <body>
    <p>This is HTML5!</p>
  </body>
</html>
```

> Use HTML5 Doctype for all modern web projects.


---

# Question: What tag is used to render an image on a webpage?

**Answer:**
The `<img>` tag is used to render an image on a webpage. It is a self-closing tag and requires the `src` attribute to specify the image source URL, and often the `alt` attribute for alternative text.
Example: `<img src="image.jpg" alt="Description of image">`

---

# Question: Which of the following colors contain equal amounts of RGB?

**Answer:**
Colors that contain equal amounts of Red, Green, and Blue (RGB) are shades of gray, including black, white, and all grays in between. For example, RGB values like (0,0,0) for black, (255,255,255) for white, or (128,128,128) for medium gray have equal amounts of RGB.

---

# Question: Can extra spaces affect how HTML is displayed in the browser?

**Answer:**
No, extra spaces generally do not affect how HTML is displayed in the browser because HTML collapses multiple whitespace characters (spaces, tabs, newlines) into a single space when rendering content. This means you can use extra spaces in your HTML code for readability without changing the visual output.

---

# Question: What is the basic structure of a standard HTML file?

**Answer:**  
A standard HTML file includes the following structure:

```html
<!DOCTYPE html>
<html>
<head>
<title>Title Page</title>
</head>
<body>

<h1>Heading Line</h1>
<p>Paragraph Lines</p>

</body>
</html>
```

- The `<!DOCTYPE html>` acts as a declaration that this document is an HTML5 document.
- The `<html>` element is the root element of the HTML page.
- The `<head>` element contains metadata for the HTML page.
- The `<title>` tag produces a title for the webpage we are currently rendering(our HTML page).
- The `<body>` defines the body of the document, and is basically a container for all the contents which is visible in the HTML page like hyperlinks, headings, titles, paragraphs, etc.
- The `<h1>` tag is basically a heading. The ‘1’ represents the size of the heading, 1 being the largest and 6 being the smallest.
- The `<p>` tag basically defines a paragraph.

---

# Question: What does HTML stand for and what is its purpose?

**Answer:**  
**HTML** stands for **HyperText Markup Language**. It is a language interpreted by web browsers to define the structure and content of web pages. HTML uses “tags” to mark up text, images, and other elements, instructing the browser what to display and how to display it. It is the standardized system used to create and design web pages.

 An HTML document is a plaintext document formatted using elements. These elements are surrounded by opening and closing tags, which use angle brackets (`<>`).  
- Tags like `<image>`, `<p>`, etc., can be empty or void and do not contain any text.  
- Attributes can be added to HTML tags to provide additional information that affects how the browser interprets the element.

---

# Question: What is the root element in an HTML document and what is its significance?

**Answer:**  
The root element of an HTML page is the `<html>` element. It is the top-level element and must be the ancestor of all other elements in the document.

Example structure:  
```html
<!DOCTYPE html>
<html lang="en">
  <head>...</head>
  <body>...</body>
</html>
```

- The <html> tag encloses the entire content of the HTML document.

---

# Question: How do you indicate the character set being used by an HTML document?

**Answer:**

The character set of an HTML document is specified using the `<meta>` tag inside the `<head>` section. This tells the browser how to interpret the characters in the document, ensuring correct display of text.

The most common character set used today is **UTF-8**, which supports virtually all characters from all languages.

**Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Example Document</title>
  </head>
  <body>
    <p>This document uses UTF-8 character encoding.</p>
  </body>
</html>
```

> By including `<meta charset="UTF-8">`, you ensure that the browser correctly interprets the document's character encoding.

---

# Question: What is the latest version of HTML, and what are its two main components?
**Answer:**  
The latest version of HTML is **HTML5**. The two main components of HTML are **Tags** and **Attributes**.

- **Tags** are the primary components in HTML that define how the content will be structured or formatted. they define the elements on the webpage. For example, `<a>` is a tag used to create a hyperlink.

- **Attributes** are used with HTML tags to define the characteristics or properties of the element. they provide extra information about tags. For example, the `href` attribute specifies the link destination in an `<a>` tag.

Example:  
```html
<a href="https://www.example.com">Visit Example</a>
```

```html
<p align="center">Interview questions</p>
````

- Here, `<p>` is the tag, and align="center" is the attribute that centers the paragraph content.

---

# Question: What are the various formatting tags in HTML? List and describe them.

**Answer:**  
HTML provides several formatting tags to change the appearance and meaning of text:

- `<b>`: Makes text **bold**.  
- `<i>`: Makes text *italic*.  
- `<em>`: Makes text *italic* with added semantic emphasis.  
- `<big>`: Increases the font size by one unit.  
- `<small>`: Decreases the font size by one unit.  
- `<sub>`: Displays text as a subscript.  
- `<sup>`: Displays text as a superscript.  
- `<del>`: Displays text with a strike-through (deleted text).  
- `<strong>`: Marks text as important (typically bold).  
- `<mark>`: Highlights text.  
- `<ins>`: Displays text as inserted (usually underlined).

---

# Question: Describe the HTML layout structure and its common components.

**Answer:**  
Every web page has different components to display content and UI, but there are some standard, globally accepted layout elements:

- `<header>`: Contains the starting information about the web page.
- `<footer>`: Represents the last section of the page.
- `<nav>`: Contains the navigation menu of the page.
- `<article>`: Represents a self-contained set of information.
- `<section>`: Used inside an article to define a specific section or block of content.
- `<aside>`: Contains sidebar content or tangentially related information.

---

# Question: What are the different types of lists in HTML?

**Answer:**  
There are three main types of lists in HTML:

1. **Ordered List (`<ol>`)**  
   Displays list items in a numbered sequence.

2. **Unordered List (`<ul>`)**  
   Displays list items with bullet points.

3. **Description List (`<dl>`)**  
   Used for a list of terms and their descriptions.

Example:  
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>

<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
```
---

# Question: What are HTML Entities?

**Answer:**  
HTML Entities are special codes used to display reserved characters in HTML, such as `<`, `>`, and `&`, which otherwise have special meanings in HTML.

| Character         | Entity Name | Entity Number |
|-------------------|-------------|---------------|
| <                 | &lt;        | &#60;         |
| >                 | &gt;        | &#62;         |
| &                 | &amp;       | &#38;         |
| (Non-breaking space) Eg. 10 PM | &nbsp;      | &#160;        |

Example:  
```html
<p>10&nbsp;PM</p>
```
- This displays as: 10 PM (with a non-breaking space).

---

# Question: Why do we use HTML?

**Answer:**  
HTML ensures the proper formatting of text and images so that web browsers can display them correctly. Without HTML, browsers wouldn’t know how to display text as elements or load images and other content. HTML provides the basic structure (the "bones") of a web page, while CSS adds styling (the "skin") to change its appearance.

The basic skeleton of an HTML document looks like this:

```html
<html>
<head>
<title> Title </title>
</head>
<body>
..........................
....Body contents here....
..........................
</body>
</html>
```

---

# Question: What is the ‘class’ attribute in HTML?

**Answer:**  
The `class` attribute is used to specify a class name for an HTML element. Multiple elements can share the same class name. It is mainly used to link HTML elements with CSS styles defined in stylesheets.

---

# Question: Why is HTML important in web development, and why is it not sufficient alone?

**Answer:**  
HTML is important because it defines the structure of web content and is essential for web designers and developers. However, HTML alone is not sufficient because it only structures the data. To make web pages visually appealing and functional, CSS (for styling) and JavaScript (for interactivity) are also needed.

---

# Question: What are HTML elements?

**Answer:**  
HTML elements are building blocks that define and label parts of a webpage, like headings, paragraphs, and links.

---

# Question: What does HTML do in a web browser?

**Answer:**  
- HTML informs the web browser on how to display the content of the website when the user loads it.
- It consists of a series of elements that label pieces of content as “heading”, “paragraph”, “link”, and more.

---

# Question: Who is making the Web standards?

**Answer:**  
Web standards are primarily developed and maintained by the World Wide Web Consortium (W3C), along with contributions from other groups like the Web Hypertext Application Technology Working Group (WHATWG) and various standards bodies.

---

# Question: What file extensions are used for HTML files, and how are they viewed?

**Answer:**  
An HTML file is saved with the `.htm` or `.html` extension. It is usually provided by a web server and can be viewed in any web browser.

---

# Question: When was HTML released

**Answer:**  
HTML was released in 1993.

---

# Question: What is HTML used for?

**Answer:**  
HTML is the standard go-to language to make web pages and is used to create the general structure of a website or webpage.

---

# Question: What is the general syntax of an HTML element?

**Answer:**  
An HTML element generally consists of a start tag, some content, and an end tag. For example:  
```html
<tagname>Content</tagname>
```
---

# Question: Can we display a web page inside another web page? How?

**Answer:**  
Yes, we can display a web page inside another HTML web page using the `<iframe>` tag.

Example:  
```html
<iframe src="url-of-the-web-page-to-embed"></iframe>
```
- This tag embeds the specified webpage inside the current page.

---

# Question: What are void elements in HTML?

**Answer:**  
Void elements in HTML are elements that do not have closing tags or do not need to be closed.

Examples include:  
```html
<br />
<img />
<hr />
```
---

# Question: What does HTML stand for?

**Answer:**  
HTML stands for **HyperText Markup Language**.

---

# Question: What is the advantage of collapsing white space in HTML?

**Answer:**  
In HTML, a sequence of whitespace characters (spaces, tabs, newlines) is treated as a single space. This collapsing of white space helps developers indent and format their HTML code for readability without affecting how the content is displayed in the browser.

---

# Question: Which of the following colors contain equal amounts of RGB?

**Answer:**
Colors that contain equal amounts of Red, Green, and Blue (RGB) are shades of gray, including black, white, and all grays in between. For example, RGB values like (0,0,0) for black, (255,255,255) for white, or (128,128,128) for medium gray have equal amounts of RGB.

---

# Question: Choose the correct HTML element for the largest heading.

**Answer:**  
The `<h1>` element is used for the largest heading in HTML.

---

# Question: What is the correct HTML element for inserting a line break?

**Answer:**  
The `<br>` element inserts a line break in HTML.

---

# Question: What is the correct HTML for adding a background color?

**Answer:**  
You can add a background color in HTML using the `style` attribute, for example: `<body style="background-color:yellow;">`

---

# Question: Choose the correct HTML element to define important text.

**Answer:**  
The `<strong>` element is used to define important text.

# Question: Choose the correct HTML element to define emphasized text.

**Answer:**  
The `<em>` element is used to define emphasized text.

---

# Question: What is the correct HTML for creating a hyperlink?

**Answer:**  
The `<a>` element is used to create a hyperlink, e.g. `<a href="https://example.com">link</a>`.

---

# Question: Which character is used to indicate an end tag?

**Answer:**  
A forward slash `/` is used to indicate an end tag, e.g. `</tagname>`.

---

# Question: How can you open a link in a new tab/browser window?

**Answer:**  
Use the attribute `target="_blank"` in the `<a>` tag, e.g. `<a href="url" target="_blank">`.

---

# Question: Which of these elements are all `<table>` elements?

**Answer:**  
Common table elements include `<table>`, `<tr>`, `<th>`, and `<td>`.

---

# Question: Inline elements are normally displayed without starting a new line. True or False?

**Answer:**  
True. Inline elements do not start on a new line.

---

# Question: How can you make a numbered list?

**Answer:**  
Use the `<ol>` element to create a numbered list.

---

# Question: How can you make a bulleted list?

**Answer:**  
Use the `<ul>` element to create a bulleted (unordered) list.

---

# Question: What is the correct HTML for making a checkbox?

**Answer:**  
`<input type="checkbox">` creates a checkbox.

---

# Question: What does the file path `<img src="images/picture.jpg">` indicate about the location of the image file?

**Answer:**  
It indicates that the image file "picture.jpg" is located inside the "images" folder, which is inside the current folder of the webpage.

---

# Question: What is the difference between a relative file path and an absolute file path in HTML?

**Answer:**  
- A **relative file path** points to a file location relative to the current page’s folder (e.g., `images/picture.jpg` or `../picture.jpg`).  
- An **absolute file path** specifies the full URL to the file, including the domain (e.g., `https://www.w3schools.com/images/picture.jpg`).

---

# Question: What does the file path `<img src="../picture.jpg">` mean?

**Answer:**  
It means the file "picture.jpg" is located one folder level up from the current page’s folder.

---

# Question: How do you specify an image located in the root folder of the website?

**Answer:**  
You use a path starting with a slash `/`, for example: `<img src="/images/picture.jpg">`.

---

# Question: What is the correct HTML for making a text input field?

**Answer:**  
`<input type="text">` creates a text input field.

---

# Question: What is the correct HTML for making a drop-down list?

**Answer:**  
Use the `<select>` element with nested `<option>` elements, e.g.:
```html
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```

---

# Question: How do you add a favicon to an HTML document?

**Answer:**  
You add a favicon by including a `<link>` element inside the `<head>` section of your HTML, like this:

```html
<link rel="icon" href="path/to/favicon.ico" type="image/x-icon">
````

or

```html
<link rel="shortcut icon" href="path/to/favicon.ico" type="image/x-icon">
```

---

# Question: What is the correct HTML for making a text area?

**Answer:**
Use the `<textarea></textarea>` element.

---

# Question: What is the correct HTML for inserting an image?

**Answer:**
Use the `<img>` element with the `src` attribute, e.g. `<img src="image.jpg" alt="description">`.

---

# Question: What is the correct HTML for inserting a background image?

**Answer:**
Use CSS with the `style` attribute or a stylesheet, e.g. `<body style="background-image: url('image.jpg');">`.

---

# Question: What is an `<iframe>` used for?

**Answer:**
An `<iframe>` is used to display a web page within another web page.

---

# Question: How do HTML comments start and end?

**Answer:**
HTML comments start with `<!--` and end with `-->`.

---

# Question: Block elements are normally displayed without starting a new line. True or False?

**Answer:**  
False. Block elements **do** normally start on a new line and take up the full width available.

---

# Question: Which HTML element defines the title of a document?

**Answer:**  
The `<title>` element defines the title of a document, which appears in the browser's title bar or tab.

---

# Question: Which HTML attribute specifies an alternate text for an image, if the image cannot be displayed?

**Answer:**  
The `alt` attribute specifies alternate text for an image.

---

# Question: Which doctype is correct for HTML5?

**Answer:**  
The correct doctype declaration for HTML5 is: `<!DOCTYPE html>`

---

# Question: Which HTML element is used to specify a footer for a document or section?

**Answer:**  
The `<footer>` element is used for specifying a footer.

---

# Question: In HTML, you can embed SVG elements directly into an HTML page. True or False?

**Answer:**  
True. SVG elements can be embedded directly using the `<svg>` tag.

---

# Question: What is the correct HTML element for playing video files?

**Answer:**  
The `<video>` element is used for playing video files.

---

# Question: What is the correct HTML element for playing audio files?

**Answer:**  
The `<audio>` element is used for playing audio files.

---

# Question: The HTML global attribute "contenteditable" is used to:

**Answer:**  
It makes the content of an element editable by the user.

---

# Question: In HTML, onblur and onfocus are:

**Answer:**  
Event attributes used to handle focus events in HTML elements (e.g., input fields).

---

# Question: Graphics defined by SVG are in which format?

**Answer:**  
SVG graphics are defined in XML format.

---

# Question: The HTML `<canvas>` element is used to:

**Answer:**  
Draw graphics on the fly via scripting (usually JavaScript).

---

# Question: In HTML, which attribute is used to specify that an input field must be filled out?

**Answer:**  
The `required` attribute.

---

# Question: Which input type defines a slider control?

**Answer:**  
`<input type="range">` defines a slider control.

---

# Question: Which HTML element is used to display a scalar measurement within a range?

**Answer:**  
The `<meter>` element.

---

# Question: Which HTML element defines navigation links?

**Answer:**  
The `<nav>` element.

---

# Question: In HTML, what does the `<aside>` element define?

**Answer:**  
Content that is tangentially related to the main content, often used for sidebars.

---

# Question: What is the font-size of the h1 heading tag?

**Answer:**  
By default, the font size of the `<h1>` tag is 2em or approximately 32px, though it can vary based on the browser's stylesheet.

---

# Question: How many heading tags are there in HTML5?

**Answer:**  
There are six heading tags in HTML5: `<h1>` through `<h6>`.

---

# Question: Which of the following attributes is used to add a link to any element?

**Answer:**  
The `href` attribute is used to specify the URL in anchor (`<a>`) tags. For adding link behavior to any element, JavaScript or wrapping it in an `<a>` tag is used.

---

# Question: How many attributes are there in HTML5?

**Answer:**  
HTML5 includes over 100 global and specific attributes. The number can vary depending on how they are categorized, but there is no fixed total count.

---

# Question: Which of the following is the correct way of creating a hyperlink in HTML?

**Answer:**  
`<a href="https://example.com">Link</a>`

---

# Question: What is the purpose of using `<div>` tags in HTML?

**Answer:**  
The `<div>` tag is a container used to group elements for styling (with CSS) or scripting (with JavaScript).

---

# Question: Which of the following tags is used to make a portion of text italic in HTML?

**Answer:**  
The `<i>` or `<em>` tags can be used to italicize text, with `<em>` also conveying emphasis.

---

# Question: Which of the following attributes is used to open a hyperlink in a new tab?

**Answer:**  
The `target="_blank"` attribute.

---

# Question: Which of the following elements can be used in HTML to create a table?

**Answer:**  
The main elements are `<table>`, `<tr>`, `<td>`, and `<th>`.

---

# Question: Which tag is used to add a header in an HTML5 table?

**Answer:**  
The `<th>` tag is used for table headers.

---

# Question: Which HTML element is used to specify a header for a document or section?

**Answer:**  
The `<header>` element.


# Question: What is the purpose of the HTML `<main>` element?

**Answer:**  
It represents the dominant content of the `<body>` of a document, unique and excluding repeated sections like navigation, headers, or footers.

---

# Question: Which attribute is used to specify the language of the content?

**Answer:**  
The `lang` attribute.

---

# Question: What does the `<figure>` element represent?

**Answer:**  
It represents self-contained content, like illustrations, diagrams, photos, or code snippets, often with a caption.

---

# Question: Which HTML element is used to define a tooltip for an image?

**Answer:**  
The `title` attribute is used to add a tooltip to any element, including images.

---

# Question: What is the purpose of the `<time>` element?

**Answer:**  
It represents a specific time (or date), optionally with a machine-readable format.

---

# Question: Which attribute is used to specify the target of a link?

**Answer:**  
The `target` attribute.

---

# Question: What is the purpose of the `<mark>` element?

**Answer:**  
To highlight or mark text as relevant or important.

---

# Question: Which HTML element is used to define a progress bar?

**Answer:**  
The `<progress>` element.

---

# Question: What is the purpose of the `<details>` element?

**Answer:**  
To create a disclosure widget that users can open and close to show or hide additional information.

---

# Question: Which HTML element is used to define a dialog box?

**Answer:**  
The `<dialog>` element.

---

# Question: Which HTML element is used to define a section of a document?

**Answer:**  
The `<section>` element.

---

# Question: What is the purpose of the `<figcaption>` element?

**Answer:**  
To provide a caption or legend for the content of the `<figure>` element.

---

# Question: Which HTML element is used to define keyboard input?

**Answer:**  
The `<kbd>` element.

---

# Question: What is the purpose of the `<samp>` element?

**Answer:**  
To represent sample output from a computer program.

---

# Question: Which HTML element is used to define a variable?

**Answer:**  
The `<var>` element.

---

# Question: What is the purpose of the `<ruby>` element?

**Answer:**  
To represent ruby annotations, which are short runs of text presented alongside base text, often for pronunciation guides.

---

# Question: Which HTML element is used to define a definition term?

**Answer:**  
The `<dt>` element.

---

# Question: What is the purpose of the `<q>` element?

**Answer:**  
To enclose short inline quotations.

---

# Question: Which HTML element is used to define a generic container for styling purposes?

**Answer:**  
The `<div>` element.

---

# Question: What is the purpose of the `<abbr>` element?

**Answer:**  
To represent an abbreviation or acronym, optionally with an expansion.

---

# Question: What is an HTML element?

**Answer:**
An HTML element consists of a start tag, content, and an end tag (e.g., `<p>Hello</p>`). It defines the structure and content of a webpage.

---

# Question: Why is browser support important in web development?

**Answer:**
Browser support ensures that web pages and features work consistently across different web browsers, providing a good user experience for all visitors.

---

# Question: What are HTML attributes?

**Answer:**
Attributes provide additional information about HTML elements, usually in name/value pairs inside the start tag (e.g., `<img src="image.jpg" alt="My Image">`).

---

# Question: What are global attributes in HTML?

**Answer:**
Global attributes are attributes that can be applied to any HTML element, such as `id`, `class`, `style`, and `title`.

---

# Question: What are event attributes in HTML?

**Answer:**
Event attributes specify event handlers for user interactions like clicks or key presses (e.g., `onclick`, `onmouseover`).

---

# Question: What are color names in HTML?

**Answer:**
Color names are predefined color keywords recognized by browsers, such as `red`, `blue`, `green`, which can be used instead of hex or RGB values.

---

# Question: What is the `<canvas>` element used for in HTML?

**Answer:**
The `<canvas>` element is used to draw graphics on the fly via scripting (usually JavaScript), enabling dynamic rendering of shapes, images, and animations.

---

# Question: What is the Audio/Video DOM in HTML?

**Answer:**
The Audio/Video DOM provides JavaScript interfaces to control audio and video elements for playback, volume, events, and other media features.

---

# Question: What is a character set in HTML?

**Answer:**
A character set defines the encoding used to display text, such as UTF-8, which supports a wide range of characters from multiple languages.

---

# Question: What is URL encoding?

**Answer:**
URL encoding converts characters into a format that can be transmitted over the Internet by replacing unsafe ASCII characters with `%` followed by hexadecimal values.

---

# Question: What does the `lang` attribute specify in HTML?

**Answer:**
The `lang` attribute specifies the language of the content, aiding browsers and assistive technologies in correctly processing the text.

---

# Question: What are country codes used for in web development?

**Answer:**
Country codes are used in language tags (e.g., `en-US`) to specify regional variations of a language for localization.

---

# Question: What is an HTTP message?

**Answer:**
An HTTP message is a request or response sent between a client (browser) and server that follows the HTTP protocol to communicate data.

---

# Question: What is a px to em converter used for?

**Answer:**
It converts pixel units (px) to relative font size units (em), which scale better across different screen sizes and devices.

---

# Question: What are common keyboard shortcuts for web development?

**Answer:**
Examples include `Ctrl + U` to view source, `F12` to open developer tools, and `Ctrl + Shift + I` to inspect elements.

---

# Question: What is a URL?

**Answer:**
A URL (Uniform Resource Locator) is the address used to access resources on the internet, such as web pages, images, or files. It specifies the location of the resource and the protocol used to retrieve it (e.g., `https://www.example.com`).

---

# Question: What is used for specifying an email to be sent in HTML?

**Answer:**
The `mailto:` protocol is used in the `href` attribute of an `<a>` tag to specify an email address that opens the user's default email client for sending an email. For example: `<a href="mailto:example@example.com">Send Email</a>`.


---

