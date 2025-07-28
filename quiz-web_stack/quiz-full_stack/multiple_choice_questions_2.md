# Question: What is a "stack" in web development?

**Answer:** A stack is a set of technologies that cover different parts of a modern web application, working together in an integrated manner to reduce development time and effort.

---

# Question: What is the FARM stack composed of?

**Answer:** The FARM stack includes FastAPI for the backend (REST API layer), React for the frontend (UI), and MongoDB for the database layer.

---

# Question: What are the key benefits of using the FARM stack?

**Answer:** The FARM stack offers agility, reduced development time, and modern capabilities, making it suitable for applications with fluid data and evolving feature requirements.

---

# Question: What does FastAPI contribute to the FARM stack?

**Answer:** FastAPI provides a high-performance, modern Python web framework for building REST APIs efficiently and asynchronously.

---

# Question: What does React contribute to the FARM stack?

**Answer:** React handles the frontend, creating dynamic and responsive UI using a virtual DOM for efficient updates.

---

# Question: What role does MongoDB play in the FARM stack?

**Answer:** MongoDB serves as the NoSQL database layer, storing and retrieving data in a flexible document-based format.

---

# Question: Which server is typically used to serve FastAPI applications?

**Answer:** Uvicorn, a fast Python-based ASGI server, is commonly used to serve FastAPI applications.

---

# Question: What is Motor in the context of the FARM stack?

**Answer:** Motor is an asynchronous Python driver for MongoDB used by FastAPI to perform database operations asynchronously.

---

# Question: What is BSON and how is it used in the FARM stack?

**Answer:** BSON is a binary-encoded serialization of JSON-like documents; MongoDB uses it internally, and FastAPI converts it to Python data structures before outputting JSON responses.

---

# Question: What happens when a user interacts with a React-based UI in the FARM stack?

**Answer:** A user action triggers an HTTP request, which FastAPI processes; it interacts with MongoDB, and the resulting data is returned as JSON to React to update the UI.

---

# Question: What type of HTTP methods are typically triggered by frontend user actions?

**Answer:** Common HTTP methods include GET, POST, PUT, and other HTTP verbs, often with associated payloads.

---

# Question: Why is React suitable for the frontend layer?

**Answer:** React is a popular UI library known for its performance, component-based architecture, and synchronization with the virtual DOM.

---

# Question: Why use MongoDB over traditional SQL databases in the FARM stack?

**Answer:** MongoDB is flexible, schema-less, and ideal for applications with changing data structures, making it suitable for fluid web applications.

---

# Question: What are some popular frontend frameworks other than React?

**Answer:** Vue.js, Angular, and Svelte are other widely used frontend frameworks.

---

# Question: What are some popular alternatives to FastAPI for Python web development?

**Answer:** Django and Flask are popular Python frameworks, with Django offering a mature ecosystem and built-in admin interface.

---

# Question: What is the Django REST Framework (DRF)?

**Answer:** DRF is an extension for Django that allows developers to build REST APIs in a structured and logical way.

---

# Question: What are the components of the LAMP stack?

**Answer:** Linux, Apache, MySQL, and PHP.

---

# Question: What are the components of the MERN stack?

**Answer:** MongoDB, Express.js, React, and Node.js.

---

# Question: What are the components of the MEAN stack?

**Answer:** MongoDB, Express.js, Angular.js, and Node.js.

---

# Question: What is the role of Express.js in MERN and MEAN stacks?

**Answer:** Express.js serves as the backend web framework for handling server-side logic and routing.

---

# Question: What platforms do the MEAN and MERN stacks run on?

**Answer:** Both run on the Node.js platform, which is based on the JavaScript V8 engine.

---

# Question: What is the purpose of using a frontend framework or library in modern web development?

**Answer:** Frontend frameworks improve consistency, development speed, user experience, and compliance with UI/UX standards.

---

# Question: Why is FastAPI considered modern and performant?

**Answer:** FastAPI supports asynchronous request handling, is built with Python type hints for validation, and offers automatic documentation.

---

# Question: What optional environments or tools are recommended for FARM stack development?

**Answer:** Latest Python version, FastAPI library, MongoDB Atlas account, Visual Studio Code (or any IDE), and a local development environment.

---

# Question: What is Uvicorn, and how does it relate to FastAPI?

**Answer:** Uvicorn is an ASGI server used to serve FastAPI applications efficiently.

---

# Question: What types of actions on the client side can trigger HTTP requests?

**Answer:** Mouse clicks, form submissions, and other user interactions.

---

# Question: How does the FARM stack handle database operations?

**Answer:** FastAPI uses Motor to perform async database calls (e.g., findOne, create, update), processes BSON from MongoDB, and returns JSON responses.

---

# Question: What is the output format from the FastAPI REST server to the frontend?

**Answer:** Plain JSON.

---

# Question: What does the integration flow look like in the FARM stack ?

**Answer:** User action → React UI → HTTP request → FastAPI (served by Uvicorn) → MongoDB via Motor → BSON → JSON → React updates UI.

---

# Question: What kind of applications is the FARM stack especially suitable for?

**Answer:** Web applications with fluid specifications, frequently changing data structures, and modern UI expectations.

---

