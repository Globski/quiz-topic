# Question: What is HTML?

> * **Answer:** HTML is used to create web pages. 

---

# Question: How is HTML used?
> * **Answer:** You start by writing down the words you want to appear on your page. Then, you add tags or elements to the words so that the browser knows what is a heading, where a paragraph begins and ends, and so on.

---

# **Question:** How does CSS control the styling and layout of web pages?

> * **Answer:** CSS uses rules to control the styling and layout of web pages. 

---

# **Question:** CSS properties fall into two categories

> * **Answer:** Presentation and Layout
> * Presentation: Controls aspects like text color, font styles and sizes, background colors, and background images.
> * Layout: Controls the positioning of elements on the screen.

---

# **Question:** What is HTML5?

> * **Answer:** HTML5 is the latest version of HTML and introduces new tags to enhance web development.

---

# **Question:** What are some key considerations when putting a website on the web?

> * **Answer:** Key considerations include search engine optimization (SEO) and using analytics software to track who visits your site and what they are looking at.

---

# **Question:** How do people access the web?

> * **Answer:** People access websites using web browsers like Firefox, Internet Explorer, Safari, Chrome, and Opera. They might type a web address, follow a link, or use a bookmark.

---

# **Question:** What should you consider when designing website for different browsers?

> * **Answer:** It's important to consider that software manufacturers release new browser versions regularly, but many users may not have the latest versions. Therefore, you can't rely on all visitors having access to the newest features in every browser.

---

# **Question:** What happens when you visit a website?

> * **Answer:** When you visit a website, your browser receives HTML and CSS from the web server hosting the site. The browser then interprets this code to display the webpage you see.

---

# **Question:** What is the purpose of different versions of HTML and CSS?

> * **Answer:** Since the web was first created, there have been several versions of HTML and CSS, each intended to improve upon the previous version.

---

# **Question:** How does a browser find a website when you enter a domain name?

> * **Answer:** When you enter a domain name into your browser, it contacts a DNS (Domain Name System) server. The DNS server acts like a phonebook, providing the IP address associated with the domain name. This IP address is a unique number for the web server hosting the site, allowing your browser to connect to it. A web server is a computer constantly connected to the web and set up to send webpages to users. Once the browser contacts the web server, it sends the requested page back to your browser.

---

# **Question:** How does your browser find the location of a web server when visiting a site?

> * **Answer:** When you visit a website, your browser connects to a Domain Name System (DNS) server. The DNS server tells the browser the location of the web server hosting the site, allowing it to find and access the website.

---

# **Question:** How does your computer find the IP address of a website when you type in a domain name?

> * **Answer:** When you connect to the web through an ISP and type a domain name (like google.com) into your browser, your computer contacts a network of DNS servers. These servers act like a phonebook, providing the IP address associated with the requested domain name, which allows your browser to connect to the website.

---

# **Question:** What is an IP address and how is it used?

> * **Answer:** An IP address is a unique number consisting of 12 digits, separated by periods (e.g., 192.168.1.1). Every device connected to the web has its own IP address, which functions like a phone number for that device, allowing it to be identified and contacted on the network.

---

# **Question:** How does the DNS server help your browser connect to a website?

> * **Answer:** The unique IP address returned by the DNS server allows your browser to contact the web server that hosts the website you requested, enabling it to load the page.

---

# **Question:** What is a web server and how does it work?

> * **Answer:** A web server is a computer that is constantly connected to the web and is specifically set up to send webpages to users. Once your browser contacts the server, it sends the requested page back to your browser.

---

# **Question:** Why is it important to understand how to structure documents when learning to write web pages?

> * **Answer:** Understanding how to structure documents is essential for writing web pages. Learn how HTML describes the structure of a web page, how tags or elements are added to your document, and write your first web page.

---

# **Question:** Why is understanding structure important when writing web pages, and how is it applied?

> * **Answer:** Understanding structure is crucial for writing web pages because it helps convey messages clearly and allows readers to navigate the content easily. Just like newspapers or insurance forms, web pages use structure to organize information with headings, subheadings, and sections. Learn how HTML describes the structure of a web page, how tags and elements are used to organize content, and how to write your first web page. The structure in web pages mirrors the structure in documents like newspapers or Word files, where different sections, paragraphs, and headings help readers understand the content.

---

# **Question:** How do we describe the structure of a web page using HTML?

> * **Answer:** To describe the structure of a web page, we add code to the content we want to display. This code is made up of HTML elements, which are characters inside angled brackets. Each element typically consists of two tags: an opening tag and a closing tag (the closing tag includes an extra forward slash). These elements tell the browser how to display the content between the opening and closing tags.

```html
<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of the page. And if the page is a long one it might be split up into several sub-headings.<p> <h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help you follow the structure of what is being written. There may even be sub-sub-headings (or lower-level headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p> </body>
</html>
```
---

# **Question:** What role do tags play in HTML?

> * **Answer:** Tags act like containers in HTML. They define and describe the information that lies between their opening and closing tags, telling the browser how to display that content. E.g

```
<p>
```
---

# **Question:** What are attributes in HTML, and how do they work with elements?

> * **Answer:** Attributes provide additional information about an element's content and appear on the opening tag. They consist of a name and a value, separated by an equals sign. The attribute name indicates the type of information being provided and is written in lowercase, while the value, enclosed in double quotes, defines the setting for the attribute. For example, the `lang` attribute specifies the language of the content (like US English). Although HTML5 allows uppercase attribute names and omitting quotes, it is not recommended. Most attributes can only be used with specific elements, but some, like `lang`, can be applied to any element. 

**ATTRIBUTE NAME and ATTRIBUTE VALUE**
```html
<p lang="en-us">Paragraph in English</p>
```
---

# **Question:** What does HTML stand for, and what does it do?

> * **Answer:** HTML stands for HyperText Markup Language. "HyperText" refers to the ability of HTML to create links that let users quickly move between pages. A markup language, like HTML, annotates text with tags that add meaning to the document. By adding code around the original text, HTML helps the browser display the page correctly. The tags used in HTML are the markup that structure the content.

---

# **Question:** What is the purpose of the `<head>` and `<title>` elements in HTML?

> * **Answer:** The `<head>` element contains information about the page, such as metadata and links to stylesheets or scripts. Inside the `<head>` element, you’ll find the `<title>` element, which specifies the title of the page. The contents of the `<title>` element are displayed at the top of the browser window or on the tab if the browser uses tabs.

---

# **Question:** What is the purpose of the `<body>` element in HTML?

> * **Answer:** The `<body>` element contains everything that is displayed inside the main browser window. All visible content, such as text, images, and links, is placed within the `<body>` element.

---

# **Question:** What is the role of content management systems in website management?

> **Answer:** Content management systems (CMS) enable users to log into an administration section of a website to control content. These systems often allow users to edit parts of the page instead of the entire page, without needing to interact with the underlying `<html>`, `<head>`, or `<body>` elements.

---

# **Question:** How do CMS tools typically manage website content?

> **Answer:** CMS tools often include fields for entering content, such as a page title, main article, publication date, or product details like title, description, price, and quantity. These details are inserted into pre-defined templates, which control the layout of the site.

---

# **Question:** What is the benefit of using templates in a CMS?

> **Answer:** Using templates allows easier content updates across many pages. If you alter a template, every page using it will automatically update, saving time and effort. This is especially helpful for e-commerce sites with a large number of products.

---

# **Question:** How do text editors in CMS work?

> **Answer:** Text editors in CMS typically offer word processor-like tools to style text, add links, and insert images. These editors convert the formatted content into HTML code behind the scenes, making it easy for non-technical users to create content.

---

# **Question:** Can users edit the HTML code produced by text editors in a CMS?

> **Answer:** Yes, many CMS text editors allow users to view and edit the HTML code they generate, offering more control over the website's content and presentation.

---

# **Question:** Is it safe to edit template files in a CMS?

> **Answer:** While some CMS platforms allow you to edit template files, caution is necessary. Editing these files requires careful attention, as incorrect changes could break the site. Always refer to the CMS documentation and ensure you’re familiar with its structure before making edits.

---

Got it! Here's the formatted content as you requested:

---

# **Question:** How can you learn about HTML by examining the source code of other websites?

> **Answer:** In the early days of the web, one common way to learn about HTML was to view the source code of web pages. While there are now many books and online tutorials available, you can still inspect the HTML code that a web server sends by using the "View Source" option in your browser's menu. This lets you see the underlying code that builds the page.

---

