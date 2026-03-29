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

