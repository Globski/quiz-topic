# Question: List some built-in modules in Node.js and their descriptions.

### Node.js Built-in Modules

| Module         | Description                                               |
|----------------|-----------------------------------------------------------|
| assert         | Provides a set of assertion tests                         |
| buffer         | To handle binary data                                     |
| child_process  | To run a child process                                    |
| cluster        | To split a single Node process into multiple processes    |
| crypto         | To handle OpenSSL cryptographic functions                 |
| dgram          | Provides implementation of UDP datagram sockets          |
| dns            | To do DNS lookups and name resolution functions          |
| domain         | Deprecated. To handle unhandled errors                    |
| events         | To handle events                                          |
| fs             | To handle the file system                                 |
| http           | To make Node.js act as an HTTP server                     |
| https          | To make Node.js act as an HTTPS server                    |
| net            | To create servers and clients                             |
| os             | Provides information about the operating system           |
| path           | To handle file paths                                      |
| punycode       | Deprecated. A character encoding scheme                   |
| querystring    | To handle URL query strings                               |
| readline       | To handle readable streams one line at the time           |
| stream         | To handle streaming data                                  |
| string_decoder | To decode buffer objects into strings                     |
| timers         | To execute a function after a given number of milliseconds|
| tls            | To implement TLS and SSL protocols                        |
| tty            | Provides classes used by a text terminal                  |
| url            | To parse URL strings                                      |
| util           | To access utility functions                               |
| v8             | To access information about V8 (the JavaScript engine)    |
| vm             | To compile JavaScript code in a virtual machine           |
| zlib           | To compress or decompress files                           |

---

# Question: What is the Node.js EventEmitter object and what are its main methods and properties?

### EventEmitter

The `EventEmitter` is a core class in Node.js used to handle events and facilitate communication between objects. Many core Node.js modules (like `http`, `fs`, `net`, etc.) inherit from it.

### Importing EventEmitter

```js
// Method 1: Using require
const EventEmitter = require('events');

// Method 2: Using destructuring
const { EventEmitter } = require('events');
````

### Creating an EventEmitter

```js
// Create an instance
const myEmitter = new EventEmitter();

// Extend the class
class MyEmitter extends EventEmitter {
  constructor() {
    super();
  }
}
const myExtendedEmitter = new MyEmitter();
```

---

### EventEmitter Methods

| Method                        | Description                                                                                  |
| ----------------------------- | -------------------------------------------------------------------------------------------- |
| addListener(event, listener)  | Adds a listener to the end of the listeners array for the specified event. Alias for `on()`. |
| emit(event, \[...args])       | Synchronously calls each listener registered for the event, with the supplied arguments.     |
| eventNames()                  | Returns an array of event names with registered listeners.                                   |
| getMaxListeners()             | Returns the max number of listeners allowed for the emitter.                                 |
| listenerCount(event)          | Returns the number of listeners listening to the event.                                      |
| listeners(event)              | Returns a copy of listeners array for the event.                                             |
| off(event, listener)          | Alias for `removeListener()`.                                                                |
| on(event, listener)           | Adds a listener to the end of the listeners array.                                           |
| once(event, listener)         | Adds a one-time listener that is removed after it is called.                                 |
| prependListener(event, fn)    | Adds a listener to the beginning of the listeners array.                                     |
| prependOnceListener(event,fn) | Adds a one-time listener to the beginning of the listeners array.                            |
| removeAllListeners(\[event])  | Removes all listeners, or only those for the specified event.                                |
| removeListener(event, fn)     | Removes the specified listener from the listener array.                                      |
| setMaxListeners(n)            | Sets the max number of listeners for the instance.                                           |
| rawListeners(event)           | Returns a copy of listeners including wrappers like `once()`.                                |

---

### EventEmitter Properties

| Property                         | Description                                                                   |
| -------------------------------- | ----------------------------------------------------------------------------- |
| EventEmitter.defaultMaxListeners | Sets default maximum listeners for all instances (default: 10).               |
| emitter.errorMonitor             | Static symbol used to monitor `'error'` events without consuming them.        |
| emitter.captureRejections        | When `true`, promise rejections are captured and emitted as `'error'` events. |

---

### Common EventEmitter Use Cases

#### Registering & Emitting Events

```js
myEmitter.on('event', () => {
  console.log('An event occurred!');
});
myEmitter.emit('event');
```

#### Passing Arguments

```js
myEmitter.on('status', (code, msg) => {
  console.log(`Status: ${code} - ${msg}`);
});
myEmitter.emit('status', 200, 'OK');
```

#### One-Time Event Listeners

```js
myEmitter.once('onetime', () => {
  console.log('Only once');
});
myEmitter.emit('onetime');
myEmitter.emit('onetime');
```

#### Handling Errors

```js
myEmitter.on('error', (err) => {
  console.error('Error:', err.message);
});
myEmitter.emit('error', new Error('Failure!'));
```

---

### Introspecting EventEmitter

```js
myEmitter.on('event1', () => {});
myEmitter.on('event2', () => {});
console.log(myEmitter.eventNames());
console.log(myEmitter.listeners('event2'));
console.log(myEmitter.listenerCount('event2'));
```

---

### Removing Listeners

```js
function handler() { console.log('Listener'); }

myEmitter.on('event', handler);
myEmitter.removeListener('event', handler);
myEmitter.removeAllListeners('event');
```

---

### Setting Max Listeners

```js
EventEmitter.defaultMaxListeners = 15;
myEmitter.setMaxListeners(20);
```

---

### Listener Execution Order

```js
myEmitter.on('event', () => console.log('Second'));
myEmitter.prependListener('event', () => console.log('First'));
myEmitter.prependOnceListener('event', () => console.log('Very First'));

myEmitter.emit('event');
// Output:
// Very First
// First
// Second
```

---

### Extending EventEmitter

```js
class MyApp extends EventEmitter {
  process(data) {
    if (data.length > 10) this.emit('large', data);
    else this.emit('small', data);
    this.emit('done', data);
  }
}

const app = new MyApp();
app.on('large', d => console.log('Large:', d));
app.on('small', d => console.log('Small:', d));
app.on('done', () => console.log('Done'));
app.process('Short');
app.process('A very long string...');
```

---

### Synchronous vs. Asynchronous Execution

```js
console.log('Before emit');
myEmitter.on('event', () => console.log('Listener'));
myEmitter.emit('event');
console.log('After emit');
```

Use `setImmediate()` or `process.nextTick()` for async listeners:

```js
myEmitter.on('async', () => {
  setImmediate(() => console.log('Async'));
});
myEmitter.emit('async');
```

---

### Promise Rejection Handling

```js
const emitter = new EventEmitter({ captureRejections: true });

emitter.on('async-op', async () => {
  throw new Error('Failed!');
});
emitter.on('error', err => {
  console.error('Caught:', err.message);
});
emitter.emit('async-op');
```

---

### Real-World Example: HTTP Server

```js
const http = require('http');
const server = http.createServer();

server.on('request', (req, res) => {
  res.writeHead(200);
  res.end('Hello World');
});

server.listen(8080, () => console.log('Listening on port 8080'));
```

---

### Best Practices

1. **Always handle `'error'` events**
2. **Clean up listeners to avoid memory leaks**
3. **Use named functions for removable listeners**

```js
// Good
function handle() {}
emitter.on('event', handle);
emitter.removeListener('event', handle);
```

---
