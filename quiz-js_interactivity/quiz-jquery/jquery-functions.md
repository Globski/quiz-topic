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

# Question: List commonly used jQuery effect methods.

### Effect & Animation Methods

| Method          | Description                                                       |
| --------------- | ----------------------------------------------------------------- |
| `animate()`     | Runs a custom animation on the selected elements                  |
| `clearQueue()`  | Removes all remaining queued functions from the selected elements |
| `delay()`       | Sets a delay for all queued functions on the selected elements    |
| `dequeue()`     | Removes the next function from the queue, and then executes it    |
| `fadeIn()`      | Fades in the selected elements                                    |
| `fadeOut()`     | Fades out the selected elements                                   |
| `fadeTo()`      | Fades in/out the selected elements to a given opacity             |
| `fadeToggle()`  | Toggles between the `fadeIn()` and `fadeOut()` methods            |
| `finish()`      | Stops, removes, and completes all queued animations               |
| `hide()`        | Hides the selected elements                                       |
| `queue()`       | Shows the queued functions on the selected elements               |
| `show()`        | Shows the selected elements                                       |
| `slideDown()`   | Slides down (shows) the selected elements                         |
| `slideToggle()` | Toggles between the `slideUp()` and `slideDown()` methods         |
| `slideUp()`     | Slides up (hides) the selected elements                           |
| `stop()`        | Stops the currently running animation                             |
| `toggle()`      | Toggles between the `hide()` and `show()` methods                 |

---

# Question: List commonly used jQuery methods for HTML and CSS manipulation.

### HTML / CSS Manipulation Methods

| Method           | Description                                                        |
| ---------------- | ------------------------------------------------------------------ |
| `addClass()`     | Adds one or more class names to selected elements                  |
| `after()`        | Inserts content after selected elements                            |
| `append()`       | Inserts content at the end of selected elements                    |
| `appendTo()`     | Inserts HTML elements at the end of selected elements              |
| `attr()`         | Sets or returns attributes/values of selected elements             |
| `before()`       | Inserts content before selected elements                           |
| `clone()`        | Makes a copy of selected elements                                  |
| `css()`          | Sets or returns one or more style properties for selected elements |
| `detach()`       | Removes selected elements (keeps data and events)                  |
| `empty()`        | Removes all child nodes and content from selected elements         |
| `hasClass()`     | Checks if any selected element has a specified class               |
| `height()`       | Sets or returns the height of selected elements                    |
| `html()`         | Sets or returns the content of selected elements                   |
| `innerHeight()`  | Returns the height (including padding) of an element               |
| `innerWidth()`   | Returns the width (including padding) of an element                |
| `insertAfter()`  | Inserts HTML elements after selected elements                      |
| `insertBefore()` | Inserts HTML elements before selected elements                     |
| `offset()`       | Sets or returns the offset coordinates relative to the document    |
| `offsetParent()` | Returns the first positioned parent element                        |
| `outerHeight()`  | Returns the height (including padding and border) of an element    |
| `outerWidth()`   | Returns the width (including padding and border) of an element     |
| `position()`     | Returns the position relative to the parent element                |
| `prepend()`      | Inserts content at the beginning of selected elements              |
| `prependTo()`    | Inserts HTML elements at the beginning of selected elements        |
| `prop()`         | Sets or returns properties/values of selected elements             |
| `remove()`       | Removes the selected elements (including data and events)          |
| `removeAttr()`   | Removes one or more attributes from selected elements              |
| `removeClass()`  | Removes one or more classes from selected elements                 |
| `removeProp()`   | Removes a property set by `prop()`                                 |
| `replaceAll()`   | Replaces selected elements with new HTML elements                  |
| `replaceWith()`  | Replaces selected elements with new content                        |
| `scrollLeft()`   | Sets or returns the horizontal scroll position                     |
| `scrollTop()`    | Sets or returns the vertical scroll position                       |
| `text()`         | Sets or returns the text content of selected elements              |
| `toggleClass()`  | Toggles adding/removing one or more classes                        |
| `unwrap()`       | Removes the parent element of the selected elements                |
| `val()`          | Sets or returns the value of form elements                         |
| `width()`        | Sets or returns the width of selected elements                     |
| `wrap()`         | Wraps HTML element(s) around each selected element                 |
| `wrapAll()`      | Wraps HTML element(s) around all selected elements                 |
| `wrapInner()`    | Wraps HTML element(s) around the content of each element           |

---

# Question: List commonly used jQuery traversing methods.

### Traversing Methods

| Method           | Description                                                               |
| ---------------- | ------------------------------------------------------------------------- |
| `add()`          | Adds elements to the set of matched elements                              |
| `addBack()`      | Adds the previous set of elements to the current set                      |
| `andSelf()`      | **Deprecated (v1.8)**. Alias for `addBack()`                              |
| `children()`     | Returns all direct children of the selected element                       |
| `closest()`      | Returns the first ancestor of the selected element                        |
| `contents()`     | Returns all direct children, including text and comment nodes             |
| `each()`         | Executes a function for each matched element                              |
| `end()`          | Ends the most recent filtering operation and reverts to the previous set  |
| `eq()`           | Returns the element at the specified index                                |
| `filter()`       | Filters matched elements based on a selector or function                  |
| `find()`         | Returns descendant elements of the selected element                       |
| `first()`        | Returns the first element from the set                                    |
| `has()`          | Returns elements that contain specified descendant elements               |
| `is()`           | Checks if any matched element matches the selector/element/jQuery object  |
| `last()`         | Returns the last element from the set                                     |
| `map()`          | Applies a function to each element and returns a jQuery object of results |
| `next()`         | Returns the next sibling element                                          |
| `nextAll()`      | Returns all next sibling elements                                         |
| `nextUntil()`    | Returns all next siblings between two selectors                           |
| `not()`          | Returns elements that do not match a given criteria                       |
| `offsetParent()` | Returns the first positioned parent element                               |
| `parent()`       | Returns the direct parent element                                         |
| `parents()`      | Returns all ancestor elements                                             |
| `parentsUntil()` | Returns all ancestor elements between two selectors                       |
| `prev()`         | Returns the previous sibling element                                      |
| `prevAll()`      | Returns all previous sibling elements                                     |
| `prevUntil()`    | Returns all previous siblings between two selectors                       |
| `siblings()`     | Returns all sibling elements                                              |
| `slice()`        | Reduces the set of matched elements to a subset defined by indices        |

---

# Question: List commonly used jQuery AJAX methods.

### AJAX Methods

| Method              | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `$.ajax()`          | Performs an asynchronous AJAX request                        |
| `$.ajaxPrefilter()` | Modify or pre-process options before an AJAX request is sent |
| `$.ajaxSetup()`     | Sets default values for future AJAX requests                 |
| `$.ajaxTransport()` | Creates the transport mechanism for data transfer in AJAX    |
| `$.get()`           | Loads data using an AJAX HTTP GET request                    |
| `$.getJSON()`       | Loads JSON-encoded data using an HTTP GET request            |
| `$.parseJSON()`     | **Deprecated** in v3.0 — use `JSON.parse()` instead          |
| `$.getScript()`     | Loads and executes a JavaScript file via AJAX                |
| `$.param()`         | Serializes an array or object for use in a query string      |
| `$.post()`          | Loads data using an AJAX HTTP POST request                   |
| `ajaxComplete()`    | Triggered when an AJAX request completes                     |
| `ajaxError()`       | Triggered when an AJAX request fails                         |
| `ajaxSend()`        | Triggered before an AJAX request is sent                     |
| `ajaxStart()`       | Triggered when the first AJAX request starts                 |
| `ajaxStop()`        | Triggered when all AJAX requests have completed              |
| `ajaxSuccess()`     | Triggered when an AJAX request is successful                 |
| `load()`            | Loads data from a server into the selected element           |
| `serialize()`       | Serializes form data for submission                          |
| `serializeArray()`  | Serializes form data into an array of name/value pairs       |


---

# Question: What are the jQuery miscellaneous methods?

### Miscellaneous Methods

| Method           | Description                                                    |
| ---------------- | -------------------------------------------------------------- |
| `data()`         | Attaches data to, or retrieves data from, selected elements    |
| `each()`         | Executes a function for each matched element                   |
| `get()`          | Retrieves the DOM elements matched by the selector             |
| `index()`        | Finds the index of an element within a set of matched elements |
| `$.noConflict()` | Releases jQuery’s control of the `$` variable                  |
| `$.param()`      | Serializes an array or object for use in a query string        |
| `removeData()`   | Removes a previously stored piece of data                      |
| `size()`         | **Removed** in v3.0 — use `.length` instead                    |
| `toArray()`      | Converts the jQuery object into a plain array of DOM elements  |

---

# Question: What are the jQuery properties?

### jQuery Properties

| Property             | Description                                                            |
| -------------------- | ---------------------------------------------------------------------- |
| `context`            | **Removed** in v3.0 — originally held the context passed to `jQuery()` |
| `jquery`             | Contains the jQuery version number                                     |
| `jQuery.fx.interval` | Sets the animation firing rate in milliseconds                         |
| `jQuery.fx.off`      | Globally disables/enables all animations                               |
| `jQuery.support`     | Internal jQuery object representing browser features/bugs              |
| `length`             | Returns the number of elements in the jQuery object                    |

---
