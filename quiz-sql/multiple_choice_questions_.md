# Question: What does SQL stand for?

**Answer:** Structured Query Language

---

# Question: What is SQL primarily used for?

**Answer:** Accessing and manipulating databases

---

# Question: Is SQL an official standard? If so, by which organization?

**Answer:** Yes, SQL is an ANSI (American National Standards Institute) standard

---

# Question: Name three popular database systems that use SQL.

**Answer:** MySQL, SQL Server, and Oracle

---

# Question: List five common actions that SQL can perform on data.

**Answer:**

1. Execute queries against a database
2. Retrieve data from a database
3. Insert records into a database
4. Update records in a database
5. Delete records from a database

---

# Question: Besides manipulating data, what else can SQL do in a database?

**Answer:**

* Create new databases
* Create new tables
* Create stored procedures
* Create views
* Set permissions on tables, procedures, and views

---

# Question: What does RDBMS stand for?

**Answer:** Relational Database Management System

---

# Question: What is the relationship between RDBMS and SQL?

**Answer:** RDBMS is the basis for SQL and all modern database systems

---

# Question: What are database objects that store data in an RDBMS called?

**Answer:** Tables

---

# Question: What is a table in a database?

**Answer:** A collection of related data entries organized in columns and rows

---

# Question: How is a table identified in a database?

**Answer:** By a name, such as "Customers" or "Orders"

---

# Question: What do rows and columns in a table represent?

**Answer:**

* Rows represent individual records
* Columns represent data fields (attributes)

---

# Question: In the "Persons" table example, how many records and columns are shown?

**Answer:** Three records and five columns

---

# Question: Write the SQL statement that selects all records from a table named "Persons".

**Answer:** `SELECT * FROM Persons`

---

# Question: Is SQL case-sensitive?

**Answer:** No, SQL is not case-sensitive

---

# Question: Is a semicolon always required at the end of an SQL statement?

**Answer:** No, it depends on the database system.

---

# Question: Why is a semicolon used in SQL?

**Answer:** It separates SQL statements, especially in systems that allow multiple statements in one call

---

# Question: Do MS Access and SQL Server 2000 require semicolons after each SQL statement?

**Answer:** No, they do not require semicolons

---

# Question: Provide an example SQL query that selects all customers not located in the USA.

**Answer:** `SELECT Company, Country FROM Customers WHERE Country <> 'USA'`

---

# Question: Based on the example query, what is the symbol `<>` used for in SQL?

**Answer:** It means "not equal to"

---

# Question: What was the result set (Company and Country) returned from the `SELECT ... WHERE Country <> 'USA'` query?

**Answer:**

* Island Trading, UK
* Galería del gastrónomo, Spain
* Laughing Bacchus Wine Cellars, Canada
* Paris spécialités, France
* Simons bistro, Denmark
* Wolski Zajazd, Poland

---

# Question: Can SQL be used to create views and stored procedures?

**Answer:** Yes

---

# Question: Can SQL set permissions in a database?

**Answer:** Yes, on tables, procedures, and views

---

# Question: Into what two major categories can SQL be divided?

**Answer:** Data Manipulation Language (DML) and Data Definition Language (DDL)

---

# Question: Which SQL commands are part of the DML?

**Answer:** SELECT, UPDATE, DELETE, INSERT INTO

---

# Question: What is the purpose of the `SELECT` command in SQL?

**Answer:** To extract data from a database

---

# Question: What does the `UPDATE` command do in SQL?

**Answer:** It updates data in a database

---

# Question: Which SQL command deletes data from a database?

**Answer:** DELETE

---

# Question: Which SQL command is used to insert new data into a database?

**Answer:** INSERT INTO

---

# Question: What is the role of the Data Definition Language (DDL) in SQL?

**Answer:** To create or delete database objects like tables and indexes, define keys, specify links between tables, and impose constraints

---

# Question: What SQL command creates a new database?

**Answer:** CREATE DATABASE

---

# Question: Which SQL command is used to modify an existing database?

**Answer:** ALTER DATABASE

---

# Question: What SQL command is used to create a new table?

**Answer:** CREATE TABLE

---

# Question: Which command allows you to modify the structure of an existing table?

**Answer:** ALTER TABLE

---

# Question: Which SQL statement deletes an entire table?

**Answer:** DROP TABLE

---

# Question: What does the SQL `CREATE INDEX` command do?

**Answer:** Creates an index (search key)

---

# Question: Which command is used to delete an index in SQL?

**Answer:** DROP INDEX

---

# Question: What is the purpose of the `SELECT` statement in SQL?

**Answer:** To select data from a database

---

# Question: Write the basic syntax of an SQL SELECT statement for specific columns.

**Answer:** `SELECT column_name(s) FROM table_name`

---

# Question: What is the SQL syntax to select all columns from a table?

**Answer:** `SELECT * FROM table_name`

---

# Question: Is SQL case-sensitive?

**Answer:** No, SQL is not case-sensitive

---

# Question: What is the equivalent of `SELECT` in lowercase?

**Answer:** `select`

---

# Question: Write an SQL query to select the columns `LastName` and `FirstName` from the `Persons` table.

**Answer:** `SELECT LastName, FirstName FROM Persons`

---

# Question: What is the result of `SELECT LastName, FirstName FROM Persons` if the table contains Hansen Ola, Svendson Tove, and Pettersen Kari?

**Answer:**

```
LastName    FirstName  
Hansen      Ola  
Svendson    Tove  
Pettersen   Kari  
```

---

# Question: Write the SQL query to select all the columns from the `Persons` table.

**Answer:** `SELECT * FROM Persons`

---

# Question: What issue can arise with duplicate values in SQL tables, and how is it handled?

**Answer:** Duplicate values may exist in columns, but the `DISTINCT` keyword can be used to return only different values

---

# Question: What is the SQL syntax to return only distinct column values?

**Answer:** `SELECT DISTINCT column_name(s) FROM table_name`

---

# Question: In what scenario would you use `SELECT DISTINCT` in a query?

**Answer:** When you want to return only the unique (non-duplicate) values from a column

---


