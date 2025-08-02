# Question: What is the JavaScript Fetch API and how is it used?

### Fetch API

| Feature    | Description                                                   |
| ---------- | ------------------------------------------------------------- |
| `fetch()`  | Starts the process of fetching a resource. Returns a Promise. |
| `Response` | The object resolved by the Promise returned by `fetch()`.     |

---

### Syntax

```js
fetch(file)
```

---

### Parameters

| Parameter | Description                                           |
| --------- | ----------------------------------------------------- |
| `file`    | *(Optional)* The name or URL of the resource to fetch |

---

### Return Value

| Type    | Description                     |
| ------- | ------------------------------- |
| Promise | Resolves to a `Response` object |

---

### Usage Example (Promise-based)

```js
fetch("example.txt")
  .then(response => response.text())
  .then(data => myDisplay(data));
```

---

### Usage Example (Async/Await-based)

```js
async function getText(file) {
  let response = await fetch(file);
  let text = await response.text();
  myDisplay(text);
}
```

---

### Browser Support

| Browser | Version | Release Date   |
| ------- | ------- | -------------- |
| Chrome  | 51      | May 2016       |
| Edge    | 15      | April 2017     |
| Firefox | 54      | June 2017      |
| Safari  | 10      | September 2016 |
| Opera   | 38      | June 2016      |

---

