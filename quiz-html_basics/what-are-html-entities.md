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
