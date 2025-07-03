# Question: What does SQL stand for?

**Answer:** Structured Query Language.

---

# Question: What is SQL used for?

**Answer:** Fetching data from almost every database in the world.

---

# Question: Why is learning SQL important for data science professionals?

**Answer:** Because it is a core skill required for daily tasks involving data manipulation and analysis.

---

# Question: What practical setup for working with databases?

**Answer:** Setting up a local database using the MySQL server.

---

# Question: What operations on databases?

**Answer:** Creating, modifying, and deleting databases and database tables.

---

# Question: What does the acronym CRUD stand for?

**Answer:** Create, Read, Update, Delete.

---

# Question: Why is CRUD important in relational databases?

**Answer:** Because they represent the four basic operations used to manage data stored in tables.

---

# Question: What functionality related to data handling?

**Answer:** Exporting and importing data from relational databases.

---

# Question: What environment is used for working with SQL?

**Answer:** A traditional setting using commonly used software like a MySQL server.

---

# Question: What types of information must the centralized database record?

**Answer:** Office locations, employee details, customer data, sales representatives, orders, and payments.

---

# Question: What operational tasks should the database support?

**Answer:** Adding new customers, placing orders, recording payments, hiring employees, querying data, and performing analytics.

---

# Question: Why are text files not ideal for storing business data?

**Answer:** Because looking up and querying data is very difficult in plain text files.

---

# Question: What are some alternative formats to relational databases for storing data?

**Answer:** JSON files, CSV files, and spreadsheets like Excel.

---

# Question: What is a limitation of using spreadsheets for business operations?

**Answer:** They become limited in functionality with large datasets and advanced querying needs.

---

# Question: What are the difficulties in using spreadsheets for integrating with business systems?

**Answer:** Connecting forms to spreadsheets and writing custom business logic is tricky and limited.

---

# Question: What is a relational database?

**Answer:** A data storage system that stores data in structured tables, with each table representing a type of entity.

---

# Question: What is the basic unit of storage in a relational database?

**Answer:** Tables, where each table corresponds to a specific kind of entity (e.g., customers, products, employees).

---

# Question: How is customer data typically stored in a relational database?

**Answer:** As rows in a table, with each customer having attributes like customer ID, first name, last name, and date created.

---

# Question: What does the "customer ID" column typically represent?

**Answer:** A unique numerical identifier for each customer.

---

# Question: What kind of data does the "date created" column store?

**Answer:** The date and exact time when the customer was added to the database.

---

# Question: What does each column in a relational database table represent?

**Answer:** A specific type of data or attribute, such as names, dates, or identifiers.

---

# Question: What is another name for a row in a relational database table?

**Answer:** A record.

---

# Question: What does CRUD stand for in the context of relational databases?

**Answer:** Create, Read, Update, Delete.

---

# Question: What does the "Create" operation in CRUD refer to?

**Answer:** Adding a new row (record) into a table.

---

# Question: What does the "Read" operation in CRUD refer to?

**Answer:** Querying or retrieving data from the database.

---

# Question: What does the "Update" operation in CRUD refer to?

**Answer:** Modifying existing data in a row, such as changing an address or phone number.

---

# Question: What does the "Delete" operation in CRUD refer to?

**Answer:** Removing a row (record) from a table.

---

# Question: What is the significance of relationships between tables in a relational database?

**Answer:** They allow tables to be connected through relationship constraints, enabling linked data across entities.

---

# Question: What is an example of a relationship between two tables in a relational database?

**Answer:** An employee record being linked to an office record to show where the employee works.

---

# Question: What types of relationships can exist between tables in a relational database?

**Answer:** One-to-one, one-to-many, and many-to-one relationships.

---

# Question: What language is used to retrieve data from a relational database?

**Answer:** SQL (Structured Query Language).

---

# Question: Where can relational databases be hosted?

**Answer:** Locally on a computer or on the cloud for distributed access.

---

# Question: What are the advantages of hosting a database in the cloud for a company?

**Answer:** Centralized access for all employees across different offices, with permission-based usage through browser applications.

---

# Question: Where is the relational database for a platform like Jovian typically hosted?

**Answer:** On the cloud.

---

# Question: What happens when you view your profile on a site like Jovian?

**Answer:** Data is retrieved from a relational database and displayed on your profile page.

---

# Question: What is an Entity Relationship Diagram (ERD)?

**Answer:** A diagram that describes all the tables in a database and the relationships between them.

---

# Question: When is an ERD typically created?

**Answer:** When setting up a relational database, especially during initial design.

---

# Question: What does an ERD represent?

**Answer:** The structure of the database including tables (entities), fields (columns), and their relationships.

---

# Question: What does each box in an ERD represent?

**Answer:** A table in the database.

---

# Question: What is shown inside each box in an ERD?

**Answer:** The list of columns (fields) in that table.

---

# Question: Does an ERD contain actual data?

**Answer:** No, it only contains the structure (blueprint) of the database.

---

# Question: What does the key icon next to a column in an ERD represent?

**Answer:** That the column is a **primary key**—a unique identifier for records in the table.

---

# Question: What is an example of a primary key in the "offices" table?

**Answer:** `officeCode`.

---

# Question: What types of details are included in the "offices" table in the ERD?

**Answer:** City, phone number, address lines, state, country, postal code, territory, and possibly geo-location.

---

# Question: What does a blue square in the ERD typically indicate?

**Answer:** That the field is **required** (non-nullable)

---

# Question: Where is the relational database for a platform like Jovian typically hosted?

**Answer:** On the cloud.

---

# Question: What happens when you view your profile on a site like Jovian?

**Answer:** Data is retrieved from a relational database and displayed on your profile page.

---

# Question: What is an Entity Relationship Diagram (ERD)?

**Answer:** A diagram that describes all the tables in a database and the relationships between them.

---

# Question: When is an ERD typically created?

**Answer:** When setting up a relational database, especially during initial design.

---

# Question: What does an ERD represent?

**Answer:** The structure of the database including tables (entities), fields (columns), and their relationships.

---

# Question: What does each box in an ERD represent?

**Answer:** A table in the database.

---

# Question: What is shown inside each box in an ERD?

**Answer:** The list of columns (fields) in that table.

---

# Question: Does an ERD contain actual data?

**Answer:** No, it only contains the structure (blueprint) of the database.

---

# Question: What does the key icon next to a column in an ERD represent?

**Answer:** That the column is a **primary key**—a unique identifier for records in the table.

---

# Question: What does a blue square in the ERD typically indicate?

**Answer:** That the field is **required** (non-nullable).

---

# Question: What does an empty field in an ERD indicate?

**Answer:** It indicates that the field is optional and may not be filled in for all records.

---

# Question: Does the ERD specify data types for each field?

**Answer:** No, the ERD does not specify data types, but they can be inferred.

---

# Question: What are the likely data types for the fields `officeCode`, `city`, and `phone`?

**Answer:** `officeCode` might be a string or number; `city` and `phone` are likely strings.

---

# Question: What is the first step toward understanding a database structure?

**Answer:** Understanding the Entity Relationship Diagram (ERD).

---

