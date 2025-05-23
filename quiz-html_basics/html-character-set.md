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
