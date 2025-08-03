# Question: List commonly used jQuery selectors grouped by their category.

### Basic Selectors

| Selector        | Example             | Selects                                       |
| --------------- | ------------------- | --------------------------------------------- |
| `*`             | `$("*")`            | All elements                                  |
| `#id`           | `$("#lastname")`    | The element with `id="lastname"`              |
| `.class`        | `$(".intro")`       | All elements with `class="intro"`             |
| `.class,.class` | `$(".intro,.demo")` | All elements with the class `intro` or `demo` |
| `element`       | `$("p")`            | All `<p>` elements                            |
| `el1,el2,el3`   | `$("h1,div,p")`     | All `<h1>`, `<div>` and `<p>` elements        |

---

### Hierarchy Selectors

| Selector             | Example        | Selects                                                         |
| -------------------- | -------------- | --------------------------------------------------------------- |
| `parent > child`     | `$("div > p")` | All `<p>` elements that are a direct child of a `<div>` element |
| `parent descendant`  | `$("div p")`   | All `<p>` elements that are descendants of a `<div>` element    |
| `element + next`     | `$("div + p")` | The `<p>` element that is next to each `<div>` element          |
| `element ~ siblings` | `$("div ~ p")` | All `<p>` elements that appear after the `<div>` element        |

---

### Basic Filters

| Selector | Example        | Selects                  |
| -------- | -------------- | ------------------------ |
| `:first` | `$("p:first")` | The first `<p>` element  |
| `:last`  | `$("p:last")`  | The last `<p>` element   |
| `:even`  | `$("tr:even")` | All even `<tr>` elements |
| `:odd`   | `$("tr:odd")`  | All odd `<tr>` elements  |

---

### Content Filters

| Selector          | Example                   | Selects                                           |
| ----------------- | ------------------------- | ------------------------------------------------- |
| `:contains(text)` | `$(":contains('Hello')")` | All elements that contain the text `Hello`        |
| `:has(selector)`  | `$("div:has(p)")`         | All `<div>` elements that contain a `<p>` element |
| `:empty`          | `$(":empty")`             | All elements that are empty                       |
| `:parent`         | `$(":parent")`            | All elements that are a parent of another element |

---

### Visibility Filters

| Selector   | Example              | Selects                        |
| ---------- | -------------------- | ------------------------------ |
| `:hidden`  | `$("p:hidden")`      | All hidden `<p>` elements      |
| `:visible` | `$("table:visible")` | All visible `<table>` elements |

---

### Attribute Selectors

| Selector             | Example                      | Selects                                           |                  |                                                               |
| -------------------- | ---------------------------- | ------------------------------------------------- | ---------------- | ------------------------------------------------------------- |
| `[attribute]`        | `$("[href]")`                | All elements with a `href` attribute              |                  |                                                               |
| `[attribute=value]`  | `$("[href='default.htm']")`  | Elements where `href="default.htm"`               |                  |                                                               |
| `[attribute!=value]` | `$("[href!='default.htm']")` | Elements where `href` is not `"default.htm"`      |                  |                                                               |
| `[attribute$=value]` | `$("[href$='.jpg']")`        | Elements with `href` ending in `.jpg`             |                  |                                                               |
| \`\[attribute        | =value]\`                    | \`\$("\[title                                     | ='Tomorrow']")\` | Elements with `title='Tomorrow'` or starting with `Tomorrow-` |
| `[attribute^=value]` | `$("[title^='Tom']")`        | Elements with `title` starting with `Tom`         |                  |                                                               |
| `[attribute~=value]` | `$("[title~='hello']")`      | Elements with `title` containing the word `hello` |                  |                                                               |
| `[attribute*=value]` | `$("[title*='hello']")`      | Elements with `title` containing `hello` anywhere |                  |                                                               |

---

### Form Selectors

| Selector    | Example          | Selects                                |
| ----------- | ---------------- | -------------------------------------- |
| `:input`    | `$(":input")`    | All input elements                     |
| `:text`     | `$(":text")`     | Input elements with `type="text"`      |
| `:password` | `$(":password")` | Input elements with `type="password"`  |
| `:radio`    | `$(":radio")`    | Input elements with `type="radio"`     |
| `:checkbox` | `$(":checkbox")` | Input elements with `type="checkbox"`  |
| `:submit`   | `$(":submit")`   | Input elements with `type="submit"`    |
| `:reset`    | `$(":reset")`    | Input elements with `type="reset"`     |
| `:button`   | `$(":button")`   | Input elements with `type="button"`    |
| `:image`    | `$(":image")`    | Input elements with `type="image"`     |
| `:file`     | `$(":file")`     | Input elements with `type="file"`      |
| `:enabled`  | `$(":enabled")`  | All enabled input elements             |
| `:disabled` | `$(":disabled")` | All disabled input elements            |
| `:selected` | `$(":selected")` | All selected options                   |
| `:checked`  | `$(":checked")`  | All checked inputs (radio or checkbox) |

---

### Child Filters

| Selector               | Example                      | Selects                                                           |
| ---------------------- | ---------------------------- | ----------------------------------------------------------------- |
| `:first-child`         | `$("p:first-child")`         | All `<p>` elements that are the first child of their parent       |
| `:first-of-type`       | `$("p:first-of-type")`       | All `<p>` elements that are the first `<p>` of their parent       |
| `:last-child`          | `$("p:last-child")`          | All `<p>` elements that are the last child of their parent        |
| `:last-of-type`        | `$("p:last-of-type")`        | All `<p>` elements that are the last `<p>` of their parent        |
| `:nth-child(n)`        | `$("p:nth-child(2)")`        | All `<p>` elements that are the 2nd child of their parent         |
| `:nth-last-child(n)`   | `$("p:nth-last-child(2)")`   | All `<p>` elements that are the 2nd child, counting from the last |
| `:nth-of-type(n)`      | `$("p:nth-of-type(2)")`      | All `<p>` elements that are the 2nd `<p>` of their parent         |
| `:nth-last-of-type(n)` | `$("p:nth-last-of-type(2)")` | All `<p>` elements that are the 2nd `<p>`, counting from the last |
| `:only-child`          | `$("p:only-child")`          | All `<p>` elements that are the only child of their parent        |
| `:only-of-type`        | `$("p:only-of-type")`        | All `<p>` elements that are the only `<p>` of their parent        |

---

### Other Filters

| Selector          | Example                  | Selects                                                       |
| ----------------- | ------------------------ | ------------------------------------------------------------- |
| `:eq(index)`      | `$("ul li:eq(3)")`       | The 4th item in a list (`index` starts at 0)                  |
| `:gt(no)`         | `$("ul li:gt(3)")`       | List items with an index greater than 3                       |
| `:lt(no)`         | `$("ul li:lt(3)")`       | List items with an index less than 3                          |
| `:not(selector)`  | `$("input:not(:empty)")` | All input elements that are not empty                         |
| `:header`         | `$(":header")`           | All header elements `<h1>` to `<h6>`                          |
| `:animated`       | `$(":animated")`         | All elements currently being animated                         |
| `:focus`          | `$(":focus")`            | The element that currently has focus                          |
| `:root`           | `$(":root")`             | The document's root element                                   |
| `:lang(language)` | `$("p:lang(de)")`        | All `<p>` elements with a `lang` attribute starting with `de` |

---

# Question: List commonly used jQuery event methods grouped by their category.

### Event Attachment & Triggering Methods

| Method / Property  | Description                                                                                    |
| ------------------ | ---------------------------------------------------------------------------------------------- |
| `bind()`           | **Deprecated (v3.0)**. Use `on()` instead. Attaches event handlers to elements                 |
| `blur()`           | Attaches/Triggers the blur event                                                               |
| `change()`         | Attaches/Triggers the change event                                                             |
| `click()`          | Attaches/Triggers the click event                                                              |
| `dblclick()`       | Attaches/Triggers the double click event                                                       |
| `delegate()`       | **Deprecated (v3.0)**. Use `on()` instead. Attaches a handler to current/future child elements |
| `die()`            | **Removed (v1.9)**. Removes handlers added with `live()`                                       |
| `error()`          | **Removed (v3.0)**. Attaches/Triggers the error event                                          |
| `focus()`          | Attaches/Triggers the focus event                                                              |
| `focusin()`        | Attaches an event handler to the focusin event                                                 |
| `focusout()`       | Attaches an event handler to the focusout event                                                |
| `hover()`          | Attaches two handlers to the hover event                                                       |
| `keydown()`        | Attaches/Triggers the keydown event                                                            |
| `keypress()`       | Attaches/Triggers the keypress event                                                           |
| `keyup()`          | Attaches/Triggers the keyup event                                                              |
| `live()`           | **Removed (v1.9)**. Adds handlers to current/future elements                                   |
| `load()`           | **Removed (v3.0)**. Attaches handler to load event                                             |
| `mousedown()`      | Attaches/Triggers the mousedown event                                                          |
| `mouseenter()`     | Attaches/Triggers the mouseenter event                                                         |
| `mouseleave()`     | Attaches/Triggers the mouseleave event                                                         |
| `mousemove()`      | Attaches/Triggers the mousemove event                                                          |
| `mouseout()`       | Attaches/Triggers the mouseout event                                                           |
| `mouseover()`      | Attaches/Triggers the mouseover event                                                          |
| `mouseup()`        | Attaches/Triggers the mouseup event                                                            |
| `off()`            | Removes handlers attached with `on()`                                                          |
| `on()`             | Attaches event handlers to elements                                                            |
| `one()`            | Attaches handlers that trigger only once per element                                           |
| `ready()`          | Executes a function when the DOM is fully loaded                                               |
| `resize()`         | Attaches/Triggers the resize event                                                             |
| `scroll()`         | Attaches/Triggers the scroll event                                                             |
| `select()`         | Attaches/Triggers the select event                                                             |
| `submit()`         | Attaches/Triggers the submit event                                                             |
| `toggle()`         | **Removed (v1.9)**. Attaches multiple toggle functions for click events                        |
| `trigger()`        | Triggers all events bound to selected elements                                                 |
| `triggerHandler()` | Triggers handlers for a specified event, without bubbling                                      |
| `unbind()`         | **Deprecated (v3.0)**. Use `off()` instead. Removes an event handler                           |
| `undelegate()`     | **Deprecated (v3.0)**. Use `off()` instead. Removes delegated handler                          |
| `unload()`         | **Removed (v3.0)**. Use `on()` or `trigger()` instead                                          |

---

### Event Object Properties and Methods

| Method / Property                       | Description                                                   |
| --------------------------------------- | ------------------------------------------------------------- |
| `event.currentTarget`                   | The current DOM element during the bubbling phase             |
| `event.data`                            | Optional data passed to the event method                      |
| `event.delegateTarget`                  | Element where the handler was attached                        |
| `event.isDefaultPrevented()`            | Returns whether `event.preventDefault()` was called           |
| `event.isImmediatePropagationStopped()` | Returns whether `event.stopImmediatePropagation()` was called |
| `event.isPropagationStopped()`          | Returns whether `event.stopPropagation()` was called          |
| `event.namespace`                       | Namespace specified when the event was triggered              |
| `event.pageX`                           | Mouse X position relative to the document                     |
| `event.pageY`                           | Mouse Y position relative to the document                     |
| `event.preventDefault()`                | Prevents the default action for the event                     |
| `event.relatedTarget`                   | Element being entered/exited on mouse movement                |
| `event.result`                          | Last value returned by an event handler                       |
| `event.stopImmediatePropagation()`      | Prevents further handlers from being called                   |
| `event.stopPropagation()`               | Stops the event from bubbling up the DOM                      |
| `event.target`                          | The element that triggered the event                          |
| `event.timeStamp`                       | Time (ms) when the event was triggered                        |
| `event.type`                            | Type of the triggered event                                   |
| `event.which`                           | Keyboard key or mouse button pressed                          |

---

### Utility Methods

| Method / Property | Description                                                              |
| ----------------- | ------------------------------------------------------------------------ |
| `$.proxy()`       | Returns a new function with a specific context from an existing function |

---


