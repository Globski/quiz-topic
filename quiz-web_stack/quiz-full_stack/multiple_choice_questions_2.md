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

# Question: What does the FARM stack stand for?

**Answer:** FastAPI, React, MongoDB.

---

# Question: What are the key advantages of using the FARM stack for web development?

**Answer:** Flexibility, simplicity, high development speed, extensibility, maintainability, and scalability.

---

# Question: Why is scalability a key benefit of the FARM stack?

**Answer:** Because MongoDB is distributed and FastAPI is asynchronous, which allows the system to grow efficiently.

---

# Question: What kind of applications is the FARM stack ideal for?

**Answer:** Small-to-medium-scale web apps that require experimentation and potential future growth.

---

# Question: How does Python’s ecosystem contribute to the FARM stack?

**Answer:** It offers extensibility with a rich module ecosystem for various computing tasks.

---

# Question: What data format does MongoDB use?

**Answer:** JSON.

---

# Question: What are MongoDB's schema characteristics?

**Answer:** Schema-less and supports flexible schemas that allow iterative and rapid development.

---

# Question: Why is MongoDB well-suited for REST API frameworks like FastAPI?

**Answer:** Because of its flexible schema, JSON data format, and support for complex data structures.

---

# Question: What Python driver is commonly used with MongoDB?

**Answer:** Motor.

---

# Question: What are the advantages of MongoDB's nested document structures?

**Answer:** They allow embedding documents and arrays, enabling denormalization and intuitive data modeling (e.g., comments inside a blog post).

---

# Question: What is MongoDB Compass?

**Answer:** A desktop GUI application for managing and administering MongoDB databases.

---

# Question: What is a common concern with MongoDB's schema-less design?

**Answer:** It can lead to data integrity issues unless strong validation is implemented on the backend.

---

# Question: Which library helps with data integrity validation in MongoDB when using Python?

**Answer:** Pydantic.

---

# Question: What important SQL-like feature is missing in MongoDB?

**Answer:** Complex joins.

---

# Question: What is FastAPI?

**Answer:** A modern, high-performance Python framework for building APIs.

---

# Question: Who created FastAPI?

**Answer:** Sebastian Ramirez.

---

# Question: What modern Python features does FastAPI leverage?

**Answer:** Type hinting, async–await, Pydantic models, and annotations.

---

# Question: What protocol do APIs generally use to communicate?

**Answer:** HTTP.

---

# Question: What are the three key characteristics of REST APIs?

**Answer:** Statelessness, layered structure, and client-server architecture.

---

# Question: Why is FastAPI considered highly performant?

**Answer:** It is built on Starlette and achieves performance levels similar to Node.js and Go.

---

# Question: How does FastAPI help with data validation?

**Answer:** Through Pydantic models that allow complex and nested validation using standard Python types.

---

# Question: What standards does FastAPI support?

**Answer:** OpenAPI and JSON Schema.

---

# Question: What CLI command installs FastAPI?

**Answer:** `pip install fastapi`

---

# Question: What does the minimal FastAPI app look like?

**Answer:**

```python
from fastapi import FastAPI
app = FastAPI()

@app.get("/")
async def root():
    return {"message": "Hello World"}
```

---

# Question: What server is typically used to run FastAPI asynchronously?

**Answer:** Uvicorn or Hypercorn.

---

# Question: What is FastAPI's approach to dependency injection?

**Answer:** It provides a built-in system that allows easily reusable, testable, and pluggable components.

---

# Question: What does FastAPI generate automatically thanks to OpenAPI?

**Answer:** Interactive API documentation using Swagger.

---

# Question: How does FastAPI allow for modular API design?

**Answer:** By structuring applications into multiple routers.

---

# Question: What are two popular Python tools for building REST APIs before FastAPI?

**Answer:** Django REST Framework (DRF) and Flask.

---

# Question: What is DRF?

**Answer:** A plugin system for Django that enables highly customizable REST APIs based on Django models.

---

# Question: What are some other Python frameworks/tools for REST APIs?

**Answer:** Tornado, Bottle.py, CherryPy, Starlette.

---

# Question: What is Starlette?

**Answer:** A lightweight ASGI framework used as the foundation for FastAPI.

---

# Question: What distinguishes React from a framework?

**Answer:** React is a library (or a set of libraries), not a full-fledged framework.

---

# Question: What major companies use React?

**Answer:** Facebook, Uber, X (formerly Twitter), Airbnb.

---

# Question: What are the key advantages of React?

**Answer:** Performance via virtual DOM, component reusability, and ease of use.

---

# Question: What is JSX?

**Answer:** A JavaScript syntax extension that mixes XML-like tags with JavaScript to create React components.

---

# Question: What are Hooks in React?

**Answer:** Functions that allow function components to use state and other React features without classes.

---

# Question: What Hook is used to manage a stateful value in a functional component?

**Answer:** `useState`

---

# Question: What does the following React code do?

```javascript
const [brand, setBrand] = useState("");
```

**Answer:** It creates a state variable `brand` and a function `setBrand` to update its value.

---

# Question: What is the `useContext` Hook used for?

**Answer:** To access context values and functions without passing props through every component.

---

# Question: How does React improve developer understanding of JavaScript?

**Answer:** It emphasizes modern ES6/ES7 features and functional programming patterns.

---

# Question: What is Tailwind CSS?

**Answer:** A CSS utility-first framework used with React to create styled components quickly and intuitively.

---

# Question: What frameworks are built on top of React?

**Answer:** Next.js, Gatsby.js, React Remix.

---

# Question: What is a single-page application (SPA)?

**Answer:** A web app that loads a single HTML page and dynamically updates content without reloading.

---

# Question: What is the benefit of server-side rendering (SSR) in React frameworks like Next.js?

**Answer:** Improved performance and search engine optimization (SEO).

---

# Question: Why is the FARM stack a strong choice for web development?

**Answer:** It combines FastAPI’s async performance and documentation, React’s dynamic UI capabilities, and MongoDB’s flexibility to build scalable and maintainable apps.

---

