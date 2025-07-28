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

# Question: What is the purpose of the MongoDB Query API?

**Answer:** The MongoDB Query API enables users to insert, manage, query, and update data stored in a MongoDB database.

---

# Question: What is one of the key benefits of MongoDB’s flexible schema model?

**Answer:** It allows different documents within a collection to have different fields and data types, enabling easy schema evolution.

---

# Question: What can be used in MongoDB to enforce consistent document structure across a collection?

**Answer:** Schema validation rules.

---

# Question: How are documents in MongoDB represented in Python?

**Answer:** As dictionaries.

---

# Question: What must all key/field names in MongoDB documents be?

**Answer:** Strings, and each key must be unique within a document.

---

# Question: Is MongoDB case-sensitive?

**Answer:** Yes.

---

# Question: What is the maximum level of nesting supported in MongoDB documents?

**Answer:** 100 levels.

---

# Question: What field is automatically generated by MongoDB if omitted when inserting a document?

**Answer:** The `_id` field with an `ObjectId` value.

---

# Question: What is BSON, and why is it important in MongoDB?

**Answer:** BSON stands for Binary JSON. It is faster and supports more data types than JSON, and is the format used by MongoDB to store data.

---

# Question: Name four numeric data types supported by MongoDB.

**Answer:** `int` (32-bit), `long` (64-bit), `double` (64-bit floating point), `decimal` (128-bit decimal-based floating point).

---

# Question: What BSON type in MongoDB allows documents to store deeply nested structures?

**Answer:** Embedded documents (Objects).

---

# Question: How are arrays represented in MongoDB, and what can they contain?

**Answer:** Arrays are list-like structures that can contain any MongoDB data type, including other documents and arrays.

---

# Question: How are Boolean values written in MongoDB?

**Answer:** Without quotes, as `true` or `false`.

---

# Question: What BSON type is used to represent unique document identifiers in MongoDB?

**Answer:** `ObjectId`.

---

# Question: What are the properties of ObjectId in MongoDB?

**Answer:** 12 bytes long, unique, fast to generate, ordered, and automatically indexed.

---

# Question: How are dates stored in MongoDB?

**Answer:** As BSON date types representing 64-bit milliseconds since the Unix epoch (January 1, 1970), in UTC.

---

# Question: How can binary data be stored in MongoDB?

**Answer:** Using the binary data type, often with GridFS for large files like images.

---

# Question: What does the `null` type represent in MongoDB?

**Answer:** A null value or a nonexistent field.

---

# Question: What is the equivalent of a table in MongoDB?

**Answer:** A collection.

---

# Question: Why should you avoid using the names `admin`, `local`, or `config` for your MongoDB database?

**Answer:** They are reserved built-in databases and should not be used for application data.

---

# Question: What are three benefits of using separate collections in MongoDB?

**Answer:** Logical data separation, performance optimization, and improved data locality.

---

# Question: What is considered best practice when organizing collections for an application?

**Answer:** Keeping all document collections used in an application inside a single database.

---

# Question: What operating systems are compatible with MongoDB 7.0?

**Answer:** Windows 11, Windows Server 2019/2022 (64-bit), Ubuntu 20.04 LTS, and Ubuntu 22.04 LTS (64-bit).

---

# Question: What system requirements are recommended for running MongoDB?

**Answer:** A modern multi-core processor and at least 8 GB of RAM.

---

# Question: What are the benefits of using MongoDB Atlas over a local setup?

**Answer:** Easy setup, automatic scaling, operational support, backups, high security, and managed availability.

---

# Question: What is MongoDB Compass?

**Answer:** A GUI tool for managing, querying, and analyzing MongoDB data visually.

---

# Question: What is mongosh?

**Answer:** MongoDB Shell—a CLI tool for performing CRUD and administrative operations.

---

# Question: What are MongoDB Database Tools used for?

**Answer:** Exporting/importing data, diagnostics, and manipulating large files in GridFS.

---

# Question: What is MongoDB Community Edition?

**Answer:** A free version of MongoDB that runs on major operating systems for local development.

---

# Question: What is the official GUI tool bundled with MongoDB’s installation wizard on Windows?

**Answer:** MongoDB Compass.

---

# Question: During Windows installation, what setup type should you select in the MongoDB setup wizard?

**Answer:** Complete.

---

# Question: What service type should MongoDB be installed as during Windows setup?

**Answer:** A Windows network service (default option).

---

# Question: Where can you download the latest MongoDB Shell?

**Answer:** From the MongoDB Download Center: [https://www.mongodb.com/try/download/shell](https://www.mongodb.com/try/download/shell)

---

# Question: What are the steps involved in installing MongoDB Community Edition on Windows?

**Answer:**

1. Go to the Download Center and download the installer.
2. Run the executable.
3. Accept the license agreement.
4. Choose "Complete" setup.
5. Accept default settings to run as a network service.
6. Install Compass.
7. Approve UAC prompt.

---

# Question: What website should you visit to verify up-to-date installation instructions for MongoDB on Windows?

**Answer:** [https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/)

---

# Question: What are the built-in databases in MongoDB, and why shouldn’t they be modified?

**Answer:** `admin`, `local`, and `config`; they are essential for MongoDB's internal operations.

---

# Question: How do you begin installing the MongoDB Shell on Windows?

**Answer:** By selecting the Windows version and the `.msi` package from the MongoDB Download Center and clicking "Download."

---

# Question: What do you do after downloading the `.msi` package for MongoDB Shell?

**Answer:** Locate and execute the `.msi` file, confirm any security prompt, and proceed through the MongoDB setup wizard.

---

# Question: During installation via the setup wizard, what should you do when selecting the destination folder?

**Answer:** Either choose a custom destination or leave the default option.

---

# Question: How do you test if MongoDB is installed and running on Windows?

**Answer:** Open the command prompt and enter the command `mongosh`.

---

# Question: What output confirms a successful connection to MongoDB Shell?

**Answer:** A prompt with `>` appears, and running `show dbs` displays the default databases: `admin`, `config`, and `local`.

---

# Question: Where can you find MongoDB Compass on Windows after installation?

**Answer:** In the Start menu under "MongoDBCompass" (no spacing).

---

# Question: What happens if you open Compass and click "Connect" without modifying the connection string?

**Answer:** Compass connects to the local MongoDB service running on port 27017 and shows `admin`, `config`, and `local` databases.

---

# Question: What is `mongoimport` used for?

**Answer:** To import data from extended JSON, CSV, or TSV files into a MongoDB database.

---

# Question: What does `mongoexport` do?

**Answer:** It exports MongoDB data into JSON or CSV formats.

---

# Question: What is the purpose of `mongodump`?

**Answer:** It creates a binary export (backup) of a MongoDB database.

---

# Question: Name additional tools included in MongoDB Database Tools.

**Answer:** `mongorestore`, `bsondump`, `mongostat`, `mongotop`, and `mongofiles`.

---

# Question: Where can you download the MongoDB Database Tools?

**Answer:** From the MongoDB Download Center: [https://www.mongodb.com/try/download/database-tools](https://www.mongodb.com/try/download/database-tools)

---

# Question: What installer formats are available for MongoDB Database Tools?

**Answer:** MSI installer and ZIP archive.

---

# Question: What command installs `gnupg` and `curl` on Ubuntu?

**Answer:** `sudo apt-get install gnupg curl`

---

# Question: How do you import the MongoDB GPG public key for Ubuntu 22.04?

**Answer:**

```bash
curl -fsSL https://www.mongodb.org/static/pgp/server-7.0.asc | \
sudo gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg --dearmor
```

---

# Question: What is the command to create the MongoDB list file for APT?

**Answer:**

```bash
echo "deb [ arch=amd64,arm64 signed-by=/usr/share/keyrings/mongodb-server-7.0.gpg ] https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/7.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-7.0.list
```

---

# Question: What command updates the local package database?

**Answer:** `sudo apt-get update`

---

# Question: How do you install MongoDB on Ubuntu?

**Answer:** Run `sudo apt-get install -y mongodb-org`

---

# Question: What command starts the `mongod` process on Ubuntu?

**Answer:** `sudo systemctl start mongod`

---

# Question: What should you do if you receive "Unit mongod.service not found"?

**Answer:** Run `sudo systemctl daemon-reload` and then re-run `sudo systemctl start mongod`.

---

# Question: After installation, how do you launch the MongoDB shell on Ubuntu?

**Answer:** Use the command `mongosh`.

---

# Question: What is MongoDB Atlas?

**Answer:** A fully managed cloud database service provided by MongoDB that handles infrastructure, setup, configuration, and maintenance.

---

# Question: What are the two ways to set up a MongoDB Atlas account?

**Answer:** Using the Atlas UI or the Atlas CLI.

---

# Question: Where do you register for a MongoDB Atlas account?

**Answer:** [https://www.mongodb.com/cloud/atlas/register](https://www.mongodb.com/cloud/atlas/register)

---

# Question: What is the free cluster tier called in MongoDB Atlas?

**Answer:** M0 sandbox cluster.

---

# Question: What features should you enable when creating an Atlas cluster?

**Answer:** Automate security setup and Add sample dataset.

---

# Question: Why should you choose a region close to your location when creating a cluster?

**Answer:** To minimize latency.

---

# Question: What default IP access rule is set during Atlas setup?

**Answer:** The current IP address is added for local connectivity.

---

# Question: What is the risk of allowing access from 0.0.0.0/0 in Atlas?

**Answer:** It allows connections from anywhere, which is insecure.

---

# Question: How do you get the connection string for your Atlas cluster?

**Answer:** From the Atlas dashboard, click the green “Connect” button, select Compass, and copy the connection string shown.

---

# Question: What should you modify in the Compass connection string before use?

**Answer:** Replace `<password>` with your Atlas user password.

---

# Question: How do you connect to Atlas using Compass?

**Answer:** Paste the connection string into the URI field and click "Connect".

---

# Question: What sample dataset is preloaded in the Atlas cluster?

**Answer:** `sample_mflix` with collections: `comments`, `embedded_movies`, `movies`, `sessions`, `theatres`, and `users`.

---

# Question: How do you connect to your Atlas cluster using mongosh?

**Answer:** Paste the mongosh connection string into your terminal, enter your password when prompted, or use `--password` option.

---

# Question: What does the command `show dbs` do in mongosh?

**Answer:** Lists all available databases in the cluster.

---

# Question: How do you switch to a specific database in mongosh?

**Answer:** Use the command `use <database_name>`, e.g., `use sample_mflix`.

---

# Question: What does the response “switched to db sample\_mflix” mean?

**Answer:** It indicates that the `sample_mflix` database is now active for operations.

---

# Question: What does the command `show collections` do?

**Answer:** Lists all collections in the currently selected database.

---

# Question: Which collections should appear in `sample_mflix` after setup?

**Answer:** `comments`, `embedded_movies`, `movies`, `sessions`, `theatres`, and `users`.

---

# Question: What MongoDB method is used to retrieve documents from a collection based on criteria?

**Answer:** `find()`

---

# Question: What does the `find()` method return in MongoDB?

**Answer:** A cursor, not the actual results.

---

# Question: What is the purpose of the cursor returned by `find()`?

**Answer:** It allows performing operations such as limiting results, ordering, and skipping records.

---

# Question: How many documents are printed by default when using `find()` in the MongoDB Shell?

**Answer:** 20 documents.

---

# Question: What does the console message "Type 'it' for more" indicate in MongoDB Shell?

**Answer:** That more documents can be printed using the cursor.

---

# Question: Write a query to find all movies released in 1969 and limit the result to 5.

**Answer:**

```js
db.movies.find({"year": 1969}).limit(5)
```

---

# Question: Which MongoDB method counts how many documents match a query?

**Answer:** `countDocuments()`

---

# Question: What will the following command return: `db.movies.countDocuments({"year": 1969})`?

**Answer:** 107

---

# Question: What is a filter in MongoDB queries?

**Answer:** A JSON object with key-value pairs that define query criteria.

---

# Question: What does the `$gt` operator do in MongoDB?

**Answer:** Selects documents where the field value is greater than the specified value.

---

# Question: What does the `$lt` operator do in MongoDB?

**Answer:** Selects documents where the field value is less than the specified value.

---

# Question: What does the `$in` operator do in MongoDB?

**Answer:** Matches any of the values specified in an array.

---

# Question: Write a query to find all Comedy movies released in the USA after 1945.

**Answer:**

```js
db.movies.find({"year": {$gt: 1945}, "countries": "USA", "genres": "Comedy"})
```

---

# Question: What type of logical operation is implied by multiple fields in a `find()` query?

**Answer:** AND operation.

---

# Question: What is projection in MongoDB?

**Answer:** A way to include or exclude specific fields in the returned documents.

---

# Question: How do you exclude the `_id` field in a projection?

**Answer:** Set `_id: 0` in the projection object.

---

# Question: Write a query to show only the title, country, and year of Comedy movies from the USA after 1945, sorted by year and limited to 5.

**Answer:**

```js
db.movies.find({"year": {$gt: 1945}, "countries": "USA", "genres": "Comedy"}, {"_id":0, "title": 1, "countries": 1, "year": 1}).sort({"year": 1}).limit(5)
```

---

# Question: What method is used to insert a single document in MongoDB?

**Answer:** `insertOne()`

---

# Question: Write a query to insert a test movie titled "Once upon a time on Moon" released in 2024.

**Answer:**

```js
db.movies.insertOne({"title": "Once upon a time on Moon", "genres":["Test"], year: 2024})
```

---

# Question: What is `insertedId` in the `insertOne()` result?

**Answer:** The ObjectId automatically generated for the inserted document.

---

# Question: Which method inserts multiple documents at once?

**Answer:** `insertMany()`

---

# Question: What does MongoDB do if a document contains a new field not present in other documents?

**Answer:** It allows the insertion due to its flexible schema.

---

# Question: Write a query to insert three movies with varying years and a custom rating field.

**Answer:**

```js
db.movies.insertMany([
  {"title": "Once upon a time on Moon", "genres":["Test"], year: 2024},
  {"title": "Once upon a time on Mars", "genres":["Test"], year: 2023},
  {"title": "Tiger Force in Paradise", "genres":["Test"], year: 2019, rating: "G"}
])
```

---

# Question: Which method updates the first document that matches a filter?

**Answer:** `updateOne()`

---

# Question: What operator is used to modify field values in an update?

**Answer:** `$set`

---

# Question: Write a command to change the first movie genre from "Test" to "PlaceHolder".

**Answer:**

```js
db.movies.updateOne({genres: "Test"}, {$set: {"genres.$": "PlaceHolder"}})
```

---

# Question: Which method updates all documents matching a filter?

**Answer:** `updateMany()`

---

# Question: What does the `$inc` operator do?

**Answer:** Increments the value of a field by a specified amount.

---

# Question: Write a command to update all movies with genre "Test" to "PlaceHolder" and increment their year by 1.

**Answer:**

```js
db.movies.updateMany({ "genres": "Test" }, { $set: { "genres.$": "PlaceHolder" }, $inc: { "year": 1 } })
```

---

# Question: Are updates in MongoDB atomic?

**Answer:** Yes, updates are atomic per document.

---

# Question: What method replaces an entire document with a new one?

**Answer:** `replaceOne()`

---

# Question: Which method deletes all documents matching a filter?

**Answer:** `deleteMany()`

---

# Question: Write a command to delete all documents with genre "PlaceHolder".

**Answer:**

```js
db.movies.deleteMany({genres: "PlaceHolder"})
```

---

# Question: What result does MongoDB return after a delete operation?

**Answer:** A result object with `deletedCount`.

---

# Question: Which method deletes the first document that matches a filter?

**Answer:** `deleteOne()`

---

# Question: What command permanently deletes an entire MongoDB collection?

**Answer:** `db.collection.drop()`

---

# Question: Why is dropping a collection discouraged without caution?

**Answer:** Because it deletes all data and associated indexes.

---

# Question: What should you do if you accidentally delete all documents in the `movies` collection?

**Answer:** Re-import the data via MongoDB Atlas.

---

# Question: What is the MongoDB aggregation framework used for?

**Answer:** To perform complex calculations and data aggregations on the server side.

---

# Question: What is a pipeline in MongoDB aggregation?

**Answer:** A sequence of stages that process documents in steps.

---

# Question: Write a basic aggregation to find all Comedy movies.

**Answer:**

```js
db.movies.aggregate([{$match: {"genres": "Comedy"}}])
```

---

# Question: What does the `$match` stage do in an aggregation pipeline?

**Answer:** Filters documents based on specified criteria.

---

# Question: Write an aggregation to find average runtime of all Comedy movies of type "movie".

**Answer:**

```js
db.movies.aggregate([
  {$match: {type: "movie", genres: "Comedy"}},
  {$group: {_id: null, averageRuntime: { $avg: "$runtime" }}}
])
```

---

# Question: What does `_id: null` mean in a `$group` stage?

**Answer:** All documents are grouped into a single group.

---

# Question: What does `$avg: "$runtime"` do?

**Answer:** Calculates the average of the `runtime` field across grouped documents.

---

# Question: Where can you find more information on MongoDB aggregation methods?

**Answer:** [https://www.mongodb.com/docs/manual/reference/method/db.collection.aggregate/](https://www.mongodb.com/docs/manual/reference/method/db.collection.aggregate/)

---

