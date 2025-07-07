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

# Question: How can authentication information be embedded in a request?

**Answer:** By including it in the request headers, which allows the client to stay logged in across requests.

---

# Question: What is the purpose of HTTP status codes in a response?

**Answer:** They indicate what happened on the server side, such as success (200 OK), missing documents (404), or moved pages.

---

# Question: What types of information can HTTP headers provide in a response?

**Answer:** Content type, size of returned data, status codes, and other metadata about the response.

---

# Question: Why is it important to understand HTTP when working with REST?

**Answer:** Because REST is built on top of web technologies like HTTP and relies on these foundational concepts to expose and manipulate resources.

---

# Question: What does REST stand for?

**Answer:** Representational State Transfer.

---

# Question: What qualifies an API as RESTful?

**Answer:** It must meet the constraints defined by the REST architectural style.

---

# Question: How does a REST API utilize web technology?

**Answer:** Like the web, the client sends a request to a server over HTTP, and the server responds accordingly.

---

# Question: What is the role of the client in a RESTful architecture?

**Answer:** It makes HTTP requests to the server, usually using a library, and receives responses.

---

# Question: What protocol does REST use, and what is its key property?

**Answer:** It uses HTTP, which is stateless, meaning the server does not retain any information about the client between requests.

---

# Question: How is state maintained in a stateless HTTP protocol?

**Answer:** By including necessary state information, such as login details, in every request using headers.

---

# Question: What is a resource in the context of REST?

**Answer:** An abstract representation of an object, typically identified by a URI or URL, which can be anything meaningful to the application.

---

# Question: What is the significance of resources in a RESTful API?

**Answer:** Resources are the core entities that APIs expose and manipulate; everything in the system can be modeled as a resource.

---

# Question: What common operations can be performed on resources in a RESTful API?

**Answer:** Creating, reading, updating, and deleting (CRUD).

---

# Question: What does the acronym CRUD stand for in REST?

**Answer:** Create, Read, Update, Delete.

---

# Question: In e-book store example, what kind of request was made to get the author page?

**Answer:** A GET request.

---

# Question: What does a RESTful GET request do?

**Answer:** It retrieves a resource from a specific URI without modifying it.

---

# Question: What is typically included in the response from a RESTful GET request?

**Answer:** Data about the requested resource and HTTP headers.

---

# Question: What format is most commonly used for the body of REST API responses today?

**Answer:** JSON (JavaScript Object Notation).

---

# Question: Why is JSON widely used in REST APIs?

**Answer:** Because it provides a structured and nestable way to represent data and is easily parsed into native objects in most programming languages.

---

# Question: What is the role of content-type headers in REST responses?

**Answer:** They specify the format of the data being returned, such as `application/json`.

---

# Question: What HTTP method is used to add an author in a REST API?

**Answer:** The `POST` method is used to add an author, typically sent to the `/authors` endpoint with data in the request body.

---

# Question: Which HTTP verb is typically used to remove a resource like an author?

**Answer:** The `DELETE` method is used to remove a specific resource.

---

# Question: Which HTTP method is typically used for updates in REST APIs?

**Answer:** The `PATCH` method is typically used for updates in REST APIs.

---

# Question: What does CRUD stand for, and how is it represented in REST?

**Answer:** CRUD stands for Create, Read, Update, Delete and is represented in REST using HTTP methods: POST (Create), GET (Read), PATCH/PUT (Update), and DELETE (Delete).

---

# Question: What is a mashup in the context of REST APIs?

**Answer:** A mashup refers to combining data or functionality from multiple APIs to create a new application or service.

---

# Question: What makes RESTful APIs feel similar to use across different services?

**Answer:** RESTful APIs follow consistent HTTP methods and principles, making them intuitive and familiar across services.

---

# Question: What music streaming service is highlighted as an example of a RESTful API?

**Answer:** Spotify is used as the example RESTful API.

---

# Question: Where on a typical website can developers often find links to technical resources like APIs?

**Answer:** Developer-related links are often located at the bottom of the webpage.

---

# Question: What section of the Spotify site is recommended for developers?

**Answer:** The "Spotify for Developers" section.

---

# Question: What can you use the Spotify API to find out about a song?

**Answer:** You can use the API to retrieve data such as beats, sections, bars, and even whether a song is danceable.

---

# Question: What are SDKs and how are they related to APIs?

**Answer:** SDKs (Software Development Kits) are tools that provide APIs and other utilities to build applications for specific platforms.

---

# Question: Which version of the Spotify API?

**Answer:** The Web API.

---

# Question: What data format does the Spotify Web API return?

**Answer:** JSON (JavaScript Object Notation).

---

# Question: What types of data can be retrieved from the Spotify Web API?

**Answer:** Data about music, artists, albums, and tracks.

---

# Question: What is the base URL for Spotify’s Web API?

**Answer:** `https://api.spotify.com`

---

# Question: How are different resources accessed in the Spotify Web API?

**Answer:** Via unique endpoints and URIs appended to the base URL.

---

# Question: Why is authorization necessary when using the Spotify API?

**Answer:** To prevent unauthorized changes like adding to someone else’s playlist.

---

# Question: What are examples of resources in the Spotify API?

**Answer:** Songs, artists, tracks, and playlists.

---

# Question: What HTTP method is used to retrieve resources?

**Answer:** `GET`

---

# Question: What HTTP method is used to create resources in Spotify’s API?

**Answer:** `POST`

---

# Question: What HTTP method is used to change existing resources?

**Answer:** `PUT`

---

# Question: What HTTP method deletes a resource in Spotify’s API?

**Answer:** `DELETE`

---

# Question: What is a Spotify URI and what does it typically include?

**Answer:** A Spotify URI uniquely identifies a resource like a track and includes the Spotify ID.

---

# Question: What is a Spotify URL used for?

**Answer:** It allows users to view or access the resource (e.g., track, artist) directly in a browser.

---

# Question: In what format are the responses from the Spotify Web API returned?

**Answer:** JSON

---

# Question: What command-line tool is introduced for testing API requests?

**Answer:** Curl

---

# Question: What symbol is used to indicate command-line input when using curl?

**Answer:** `$`

---

# Question: How does Spotify handle large sets of data like many artists in API responses?

**Answer:** By paginating the results.

---

# Question: What does pagination in API responses mean?

**Answer:** It breaks down the data into manageable chunks or pages instead of returning everything at once.

---

# Question: What is caching in the context of API responses?

**Answer:** A method to check if the resource has changed or not, reducing unnecessary data transfer.

---

# Question: What HTTP status code indicates a successful API request?

**Answer:** `200`

---

# Question: What status code is returned for a bad API request?

**Answer:** `400` (Bad Request)

---

# Question: What does a 404 status code mean in an API response?

**Answer:** The requested resource was not found.

---

# Question: What does a 401 status code indicate in an API response?

**Answer:** Unauthorized access due to missing or invalid credentials.

---

# Question: What does a 500 error in the context of using an API typically indicate?

**Answer:** A 500 error indicates that the developer made an error on the server side.

---

# Question: What HTTP method is used when searching the Spotify API?

**Answer:** The HTTP method used is `GET`.

---

# Question: What is the endpoint used when performing a search in the Spotify API?

**Answer:** The endpoint used is `/search`.

---

# Question: In the Spotify API search query, what does the `type` parameter specify?

**Answer:** The `type` parameter specifies what kind of result to search for, such as `artist` or `track`.

---

# Question: When constructing a Spotify API search query for an artist like Beyonce, which parameter is used to pass the search term?

**Answer:** The `q` parameter is used to pass the search term, such as `q=Beyonce`.

---

# Question: Why is the OAuth token necessary when using the Spotify API?

**Answer:** The OAuth token is required to authenticate and authorize API requests.

---

# Question: Can a developer use the Spotify API without having a Spotify account?

**Answer:** Yes, a developer can still generate an OAuth token and use the API without having a Spotify account.

---

# Question: What is one feature of the Spotify API console that makes it user-friendly for developers?

**Answer:** The console allows developers to build and test queries directly with a visual interface, including auto-generating curl commands.

---

# Question: What is the significance of the "Get Token" button in the Spotify API console?

**Answer:** It allows the user to generate an OAuth token required for making authenticated API requests.

---

# Question: What happens after signing up or logging into a Spotify account in the developer console?

**Answer:** An OAuth token is created and inserted into the console to be used for making API calls.

---

# Question: Why should a developer avoid sharing their OAuth token?

**Answer:** If someone else obtains the token, they can perform actions on behalf of the developer, potentially compromising their account.

---

# Question: After obtaining Beyonce’s artist ID from a search, what endpoint can be used to retrieve more information about her?

**Answer:** The `/artists/{id}` endpoint can be used to retrieve more information using her artist ID.

---

# Question: What kind of data is returned when searching for an artist in the Spotify API?

**Answer:** The API returns a list of artist objects including name, genre, followers, external URLs, and Spotify ID.

---

# Question: What is the endpoint used to retrieve all of an artist's albums?

**Answer:** `artists/{id}/albums` is used to retrieve all albums of a specific artist by ID.

---

# Question: How is the artist ID passed into the albums endpoint during an API call?

**Answer:** The artist ID is piped into the `artists/{id}/albums` URL from a previously retrieved ID.

---

# Question: What is the default format of data returned by Spotify's API when requesting albums?

**Answer:** JSON.

---

# Question: What does the Spotify API allow developers to access?

**Answer:** Spotify’s entire music library, including data on artists, albums, tracks, playlists, and audio features like danceability.

---

# Question: What is one of the advantages of Spotify’s fast API responses?

**Answer:** Results are cacheable, improving performance by reducing redundant requests.

---

# Question: Why might the Spotify API return results quickly even without frequent updates?

**Answer:** Because the data is often cacheable and likely served from a server-side cache.

---

# Question: What caching behavior does Spotify likely implement?

**Answer:** Server-side caching of frequently accessed data to improve response time.

---

# Question: What does “cacheable” mean in the context of Spotify API results?

**Answer:** The data can be stored temporarily and reused, avoiding repeated fetching of the same data.

---

# Question: What command-line tool is recommended for sending API requests locally?

**Answer:** `curl`.

---

# Question: What is `curl`?

**Answer:** An open-source command-line tool used to send and receive data over various protocols, commonly used to test APIs.

---

# Question: On macOS, what application allows you to run `curl`?

**Answer:** Terminal.

---

# Question: What is the purpose of the Terminal on macOS?

**Answer:** It allows users to run command-line operations, such as using `curl` or other system-level commands.

---

# Question: What command can be used to verify that `curl` is installed on your machine?

**Answer:** `curl --help`

---

# Question: What is `curl` primarily used for?

**Answer:** Transferring data over HTTP from the command line

---

# Question: What test URL is used to confirm that `curl` is working properly?

**Answer:** `https://icanhazdadjoke.com`

---

# Question: What type of data is returned from `https://icanhazdadjoke.com` using curl?

**Answer:** A random dad joke

---

# Question: What is the API endpoint used to search Spotify from the command line?

**Answer:** `https://api.spotify.com/v1/search`

---

# Question: What query string parameters are passed in the Spotify curl search command?

**Answer:** `q=Beyonce&type=artist`

---

# Question: What does the `-H` flag represent in a curl command?

**Answer:** It specifies an HTTP header

---

# Question: What type of header is used to authenticate with Spotify's API?

**Answer:** `Authorization` header containing a token

---

# Question: What does the `Accept: application/json` header indicate in the curl request?

**Answer:** The client expects the response to be in JSON format

---

# Question: What tool is used to format the JSON output of curl commands?

**Answer:** `jq`

---

# Question: What does the pipe `|` symbol do in a shell command?

**Answer:** It sends the output of the command on the left as input to the command on the right

---

# Question: What does the `jq` command do when used as `jq '.items[].name'`?

**Answer:** It extracts and displays the `name` field from each item in the JSON `items` array

---
