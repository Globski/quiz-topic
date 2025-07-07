# Question: What does API stand for?

**Answer:** API stands for Application Programming Interface.

---

# Question: Why does the letter 'I' in API?

**Answer:** Interface.

---

# Question: What is meant by saying the interface abstracts away the complexity?

**Answer:** The interface hides the internal implementation details and only exposes usable options to the user.

---

# Question: What role does an interface play in technology as it evolves?

**Answer:** Interfaces abstract away complex details while incorporating new features, allowing users to control new functionalities without understanding their inner workings.

---

# Question: What is a GUI, and how is it related to physical interfaces?

**Answer:** A GUI (Graphical User Interface) is a visual interface that allows users to interact with software. Physical interfaces often inspire GUI design by mimicking familiar, recognizable components like buttons.

---

# Question: What is the role of the Play button in a streaming music app, and how does abstraction apply to it?

**Answer:** The Play button allows users to start music playback without needing to understand how it works internally. Abstraction hides the implementation details, making it user-friendly.

---

# Question: What kind of code does a developer write to make a button functional?

**Answer:** The developer writes an event handler, such as `onClick`, that triggers an action—like playing music—when the button is clicked.

---

# Question: What button behavior does the developer **not** have to code manually?

**Answer:** The developer does not need to code the physical interaction effects, such as visual feedback or clicking sounds, as these are abstracted by the interface.

---

# Question: In the context of app development, what is the button considered to be?

**Answer:** The button is an interface—specifically, part of the API provided by the application framework.

---

# Question: What does an application framework provide to developers?

**Answer:** It provides ready-made interfaces, like buttons, that abstract implementation details and allow developers to easily add functionality to their apps.

---

# Question: What does a media player API provided by an operating system do?

**Answer:** It abstracts the process of sending audio data to hardware, allowing developers to simply call methods like `play()` without handling low-level audio processing.

---

# Question: What kind of API interaction occurs when a song is streamed over the internet?

**Answer:** A web-based API call is made over the internet to fetch the song data.

---

# Question: What does the phrase "APIs all the way down" imply?

**Answer:** It suggests that APIs exist at every level of abstraction, from high-level user interactions to low-level binary data processing.

---

# Question: What common characteristic do all interfaces share?

**Answer:** They define how to interact or communicate with an object without revealing or requiring knowledge of its internal implementation.

---

# Question: What does a UI (User Interface) enable?

**Answer:** A UI allows **users** to interact with applications in a user-friendly way, abstracting the implementation details.

---

# Question: What does an API (Application Programming Interface) enable?

**Answer:** An API allows **developers** to interact with and extend an application's functionality without needing to know its underlying implementation.

---

# Question: How is an API like a contract?

**Answer:** An API defines expected usage and outputs, setting clear rules for how developers can interact with it and what results they can expect.

---

# Question: What advantages do APIs offer to software developers?

**Answer:** APIs simplify development by providing access to complex functionality and data, often enabling powerful features with just a few lines of code.

---

# Question: What is a common modern-day misunderstanding about the term "API"?

**Answer:** The term "API" is often incorrectly assumed to refer only to web-based APIs, though it actually applies to many types of programmatic interfaces.

---

# Question: Why is it important to understand all types of APIs, not just web-based ones?

**Answer:** Understanding all types of APIs helps developers see how abstraction works across software systems and why web-based APIs are so widespread and useful.

---

# Question: What kinds of APIs are typically provided by programming languages?

**Answer:** Programming languages offer APIs for common tasks like working with strings, handling files, and manipulating data.

---

# Question: How would you make a string all uppercase using a programming language?

**Answer:** By calling a string API method that transforms the string to uppercase, without needing to perform low-level character manipulation.

---

# Question: Why do programming languages offer APIs for string manipulation?

**Answer:** String manipulation is a common task, so APIs provide an abstracted, reusable way to perform these actions efficiently.

---

# Question: How can the same code run on both Windows and MacOS despite differences in file systems?

**Answer:** The programming language provides a single file system API, while the underlying OS supplies the appropriate implementation for its environment.

---

# Question: Why are language specifications considered interfaces?

**Answer:** Because they define consistent APIs that abstract implementation details, allowing different systems to implement the functionality in platform-specific ways.

---

# Question: Why is it significant that web code works across different browsers like Chrome, Edge, Safari, Firefox, and Brave?

**Answer:** Because all web browsers implement a set of common web APIs that ensure consistent behavior, allowing developers to write code once and have it work across all major browsers.

---

# Question: What is the main benefit of APIs in terms of operating system differences?

**Answer:** APIs abstract away the differences between operating systems, making it easier for developers to build software without worrying about OS-specific implementations.

---

# Question: What role do libraries play in software development?

**Answer:** Libraries package up code to solve common problems, allowing developers to import and use complex functionality (e.g., image processing) without needing to implement it themselves.

---

# Question: What is an example of using a library for image manipulation?

**Answer:** A developer can import an image package and call a method to convert a photo to black and white, without knowing how the transformation works internally.

---

# Question: How do frameworks help developers extend functionality?

**Answer:** Frameworks provide APIs that allow developers to build on top of existing functionality, such as adding routes or dynamic data rendering in web applications.

---

# Question: What is expected from the developer when using a framework’s API?

**Answer:** Developers must write implementations that conform to the API's contract or structure, even if they don’t fully understand the underlying mechanisms.

---

# Question: Are the APIs provided by libraries and frameworks usually local or remote?

**Answer:** They are usually local, existing within the codebase, and used to simplify development by avoiding reimplementation of common tasks.

---

# Question: Why should developers focus on leveraging APIs?

**Answer:** Because APIs handle lower-level complexities, enabling developers to concentrate on solving business problems more efficiently.

---

# Question: What is the key difference between local and remote APIs?

**Answer:** Local APIs run within the codebase, while remote APIs are accessed over a network and can provide functionality or data from external sources.

---

# Question: How is a TV remote an analogy for a remote API?

**Answer:** The remote sends commands to the TV, changing channels or volume without physical interaction—just like a remote API sends commands to another system to control behavior.

---

# Question: What types of objects can remote APIs control?

**Answer:** Both physical objects (like robots, traffic signs, and drones) and software systems can be controlled via remote APIs.

---

# Question: How does a song recognition app demonstrate the value of remote APIs?

**Answer:** It sends a small audio clip to a remote server, which processes the data and returns the song’s identity—something that wouldn’t be feasible to do locally due to space and power limitations.

---

# Question: What is another major benefit of remote APIs besides storage?

**Answer:** Access to vast computational power beyond what the local device can handle.

---

# Question: How does Google Translate’s AR feature demonstrate the power of remote APIs?

**Answer:** It uses the phone’s camera to translate text in real time by offloading the heavy processing to remote servers.

---

# Question: What phrase is used to describe where this remote processing occurs?

**Answer:** "En la Nube," which means "in the Cloud."

---

# Question: What is an essential characteristic of a well-designed remote API interface?

**Answer:** It allows users to interact efficiently with powerful remote systems through a simple and intuitive local interface.

---

# Question: What architectural style became dominant for web-based API development and revolutionized how developers interact with resources?

**Answer:** REST (Representational State Transfer)

---

# Question: What does it mean for an API to be RESTful?

**Answer:** It means the API embraces the style and constraints of REST.

---

# Question: What other remote API approach is mentioned as an evolution beyond REST?

**Answer:** GraphQL

---

# Question: What foundational web technology does REST sit on top of?

**Answer:** REST sits on top of web technologies, such as HTTP.

---

# Question: What is the role of a browser in the context of RESTful API interaction?

**Answer:** The browser acts as a web client that sends HTTP requests to a server.

---

# Question: What is a URL and how does it relate to a URI?

**Answer:** A URL (Uniform Resource Locator) is a specific type of URI (Uniform Resource Identifier).

---

# Question: What does HTTP stand for?

**Answer:** Hypertext Transfer Protocol

---

# Question: In the context of web technologies, what is a protocol?

**Answer:** A protocol defines the expectations of how to communicate; it's like a contract.

---

# Question: What HTTP verb is typically used when requesting data without making changes?

**Answer:** GET

---

# Question: What is the sequence of events in a basic HTTP request and response cycle?

**Answer:** The client sends an HTTP request → the server processes it → the server returns a response → the browser renders the result.

---

# Question: What is the most important part of an HTTP response for a webpage?

**Answer:** The body, which contains the HTML.

---

# Question: What is HTML and what does it allow developers to do?

**Answer:** HTML (HyperText Markup Language) structures content and allows for linking via anchor tags.

---

# Question: What happens when a user clicks a hyperlink in a web page?

**Answer:** A new HTTP GET request is sent, repeating the request-response cycle.

---

# Question: Why is HTTP considered stateless?

**Answer:** Because once a request and its response are completed, no information about that transaction is retained by the protocol.

---

# Question: How is state maintained across multiple HTTP requests?

**Answer:** The client must manage state and send it with each new request.

---

# Question: What HTTP verb is commonly used when submitting form data to a server?

**Answer:** POST

---

# Question: What are query string parameters and where are they located in a URL?

**Answer:** They are key-value pairs used to pass information and appear after the `?` in a URL.

---

# Question: What are headers in the context of HTTP requests and responses?

**Answer:** Headers are key-value pairs that provide additional information about the request or response.

---

# Question: What can request headers specify?

**Answer:** Content type, language preferences, or request conditions (e.g., only if modified since a certain time).

---

# Question: What is caching and how does HTTP support it?

**Answer:** Caching stores responses locally; headers can request data only if it's changed, reducing redundant data transfers.

---


