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

Here is the **next set of quiz questions** based on the most recent material you shared. This batch covers:

* `SELECT DISTINCT`
* `WHERE` clause
* Correct use of quotes
* SQL comparison operators

---

# Question: Write an SQL query to select only distinct values from the `City` column of the `Persons` table.

**Answer:** `SELECT DISTINCT City FROM Persons`

---

# Question: What is the purpose of the `SELECT DISTINCT` statement?

**Answer:** To return only distinct (non-duplicate) values from a column

---

# Question: What values would the query `SELECT DISTINCT City FROM Persons` return from a table with cities Sandnes, Sandnes, and Stavanger?

**Answer:** Sandnes and Stavanger

---

# Question: What is the purpose of the `WHERE` clause in SQL?

**Answer:** To filter records based on a specified condition

---

# Question: Write the syntax for a basic SQL `WHERE` clause.

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name  
WHERE column_name operator value  
```

---

# Question: Provide an SQL example to select all persons who live in the city "Sandnes" from the `Persons` table.

**Answer:**

```sql
SELECT * FROM Persons  
WHERE City='Sandnes'  
```

---

# Question: What would be the result-set of the query `SELECT * FROM Persons WHERE City='Sandnes'` based on a table where two records have the city 'Sandnes'?

**Answer:**

```
P_Id  LastName  FirstName  Address     City  
1     Hansen    Ola        Timoteivn10 Sandnes  
2     Svendson  Tove       Borgvn 23   Sandnes  
```

---

# Question: What type of values should be enclosed in single quotes in SQL statements?

**Answer:** Text (string) values

---

# Question: Can SQL use double quotes for text values?

**Answer:** Yes, most database systems accept double quotes as well

---

# Question: What is the correct way to write a query to find persons with the first name "Tove"?

**Answer:** `SELECT * FROM Persons WHERE FirstName='Tove'`

---

# Question: What is wrong with the query `SELECT * FROM Persons WHERE FirstName=Tove`?

**Answer:** Text values must be enclosed in quotes

---

# Question: Should numeric values be enclosed in quotes in SQL?

**Answer:** No, numeric values should not be enclosed in quotes

---

# Question: What is the correct SQL syntax to find records where the `Year` is 1965?

**Answer:** `SELECT * FROM Persons WHERE Year=1965`

---

# Question: What is wrong with the query `SELECT * FROM Persons WHERE Year='1965'`?

**Answer:** Numeric values should not be enclosed in quotes

---

# Question: List all the comparison operators allowed in a SQL `WHERE` clause.

**Answer:**

* `=` (Equal)
* `<>` (Not equal)
* `>` (Greater than)
* `<` (Less than)
* `>=` (Greater than or equal)
* `<=` (Less than or equal)
* `BETWEEN` (Between an inclusive range)
* `LIKE` (Search for a pattern)
* `IN` (Match any of several values)

---

# Question: What alternative symbol can sometimes be used in place of `<>` in SQL?

**Answer:** `!=`

---

# Question: What is the purpose of the `AND` operator in SQL?

**Answer:** To filter records by requiring that **both** specified conditions are true

---

# Question: What is the purpose of the `OR` operator in SQL?

**Answer:** To filter records where **either** one of the specified conditions is true

---

# Question: What result will the following SQL statement return?

```sql
SELECT * FROM Persons  
WHERE FirstName='Tove' AND LastName='Svendson'  
```

**Answer:**

```
P_Id  LastName  FirstName  Address     City  
2     Svendson  Tove       Borgvn 23   Sandnes  
```

---

# Question: Write an SQL query to select records where the first name is "Tove" or "Ola".

**Answer:**

```sql
SELECT * FROM Persons  
WHERE FirstName='Tove' OR FirstName='Ola'  
```

---

# Question: What would be the result-set of the query `SELECT * FROM Persons WHERE FirstName='Tove' OR FirstName='Ola'`?

**Answer:**

```
P_Id  LastName   FirstName  Address     City  
1     Hansen     Ola        Timoteivn10 Sandnes  
2     Svendson   Tove       Borgvn 23   Sandnes  
```

---

# Question: How do you combine `AND` and `OR` conditions in SQL to avoid logical errors?

**Answer:** Use parentheses `()` to group expressions and define evaluation order

---

# Question: Write an SQL query to select all persons whose last name is "Svendson" and whose first name is either "Tove" or "Ola".

**Answer:**

```sql
SELECT * FROM Persons  
WHERE LastName='Svendson' AND (FirstName='Tove' OR FirstName='Ola')  
```

---

# Question: What will be the result of the query:

```sql
SELECT * FROM Persons  
WHERE LastName='Svendson' AND (FirstName='Tove' OR FirstName='Ola')  
```

**Answer:**

```
P_Id  LastName  FirstName  Address     City  
2     Svendson  Tove       Borgvn 23   Sandnes  
```

---

# Question: What is the purpose of the `ORDER BY` keyword in SQL?

**Answer:** To sort the records in the result-set based on one or more columns

---

# Question: What is the default sort order when using `ORDER BY` in SQL?

**Answer:** Ascending (`ASC`)

---

# Question: How do you sort records in descending order using SQL?

**Answer:** Use the `DESC` keyword after the column name in the `ORDER BY` clause

---

# Question: Write the syntax for ordering records in SQL by a specific column in ascending or descending order.

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name  
ORDER BY column_name(s) ASC|DESC  
```

---

# Question: What is the result of the query `SELECT * FROM Persons ORDER BY LastName`?

**Answer:** It returns all records sorted by `LastName` in ascending (A–Z) order

---

# Question: What clause would you add to an SQL `SELECT` statement to sort results from Z to A by `LastName`?

**Answer:** `ORDER BY LastName DESC`

---

# Question: What is the purpose of `ORDER BY ... DESC` in an SQL `SELECT` statement?

**Answer:** It sorts the result set in descending order based on the specified column(s).

---

# Question: What are the two forms of the `INSERT INTO` statement?

**Answer:**

1. Without column names: `INSERT INTO table_name VALUES (value1, value2, …)`
2. With specified column names: `INSERT INTO table_name (col1, col2, …) VALUES (val1, val2, …)`

---

# Question: When using the first form of `INSERT INTO`, what is required?

**Answer:** You must provide values for **all columns** in the exact order defined by the table schema.

---

# Question: What is the syntax to insert a complete row into a table called Persons without specifying column names?

**Answer:** `INSERT INTO Persons VALUES (value1, value2, value3, value4, value5)`

---

# Question: SQL statement used to insert the row (4, 'Nilsen', 'Johan', 'Bakken 2', 'Stavanger') into the Persons table.

**Answer:**

```
INSERT INTO Persons 
VALUES (4,'Nilsen','Johan','Bakken 2','Stavanger')
```

---

# Question: Why might you choose to specify column names in an `INSERT INTO` statement?

**Answer:** To insert values into only specific columns, leaving others at default or NULL.

---

# Question: Write the SQL statement that inserts only the P\_Id, LastName, and FirstName columns with values (5, 'Tjessem', 'Jakob').

**Answer:**

```
INSERT INTO Persons (P_Id, LastName, FirstName) 
VALUES (5, 'Tjessem', 'Jakob')
```

---

# Question: After inserting only specific columns, what are the values of Address and City for that row?

**Answer:** They are left blank (NULL or default), as they were not provided.

---

# Question: True or False: You can omit columns and leave them out of an `INSERT` if you specify other columns by name.

**Answer:** True.

---

# Question: In the example where only some columns are inserted, what is the P\_Id of the row that does not have Address or City values?

**Answer:** 5 (LastName 'Tjessem', FirstName 'Jakob').

---

# Question: What will happen to the unspecified columns (Address, City) for the new row in the partially-specified `INSERT INTO`?

**Answer:** They will either contain NULL or their default values defined in the table schema.

---

# Question: Does `ORDER BY DESC` modify the table data?

**Answer:** No, it only affects the order of rows in the result set, not the table itself.

---

# Question: What would happen if you try `INSERT INTO Persons VALUES (...)` but provide too few values?

**Answer:** The database will throw an error, because it expects a value for every column in the table in order.

---

# Question: If you specify column names in `INSERT INTO`, do you have to provide values for those columns in the same order?

**Answer:** Yes, the values must match the column names in the order listed.

---

# Question: Can you use `ORDER BY` without specifying `ASC` or `DESC`? If so, what is the default order?

**Answer:** Yes; the default is ascending (`ASC`).

---

# Question: Provide one example of when specifying column names in `INSERT` is necessary.

**Answer:** When inserting into a table with columns that have default values or allow NULL, and you only want to set certain columns (e.g., inserting only id and name into a table with many optional fields).

---

# Question: Edge Case — What happens if the table has a NOT NULL column that you omit in a partial `INSERT`?

**Answer:** The database will throw an error for violating NOT NULL constraint, unless a default value is defined.

---

# Question: Variation — How would you insert multiple rows at once using the full-values `INSERT` syntax?

**Answer:**

```
INSERT INTO table_name VALUES 
(val1, val2, …),
(valA, valB, …),
…
```

---

# Question: What is the purpose of the SQL `UPDATE` statement?

**Answer:** To modify or update existing records in a table.

---

# Question: What is the syntax of the `UPDATE` statement in SQL?

**Answer:**

```sql
UPDATE table_name  
SET column1 = value1, column2 = value2, ...  
WHERE some_column = some_value;
```

---

# Question: Why is the `WHERE` clause important in an `UPDATE` statement?

**Answer:** It specifies which records to update. If omitted, all rows in the table will be updated.

---

# Question: What is the result of omitting the `WHERE` clause in an `UPDATE` statement?

**Answer:** All records in the table will be updated with the new values.

---

# Question: Provide the SQL statement used to update "Tjessem, Jakob" with a new address and city.

**Answer:**

```sql
UPDATE Persons  
SET Address='Nissestien 67', City='Sandnes'  
WHERE LastName='Tjessem' AND FirstName='Jakob';
```

---

# Question: What happens to the "Persons" table after executing the `UPDATE` on "Tjessem, Jakob"?

**Answer:** His Address becomes "Nissestien 67" and City becomes "Sandnes".

---

# Question: What is the result of the following SQL command without a `WHERE` clause?

```sql
UPDATE Persons  
SET Address='Nissestien 67', City='Sandnes';
```

**Answer:** All records in the Persons table will have their Address and City changed to "Nissestien 67" and "Sandnes".

---

# Question: Which record(s) would be affected by the following SQL?

```sql
UPDATE Persons  
SET City = 'Oslo'  
WHERE P_Id = 3;
```

**Answer:** Only the record with `P_Id = 3`.

---

# Question: What is the purpose of the SQL `DELETE` statement?

**Answer:** To remove records (rows) from a table.

---

# Question: What is the syntax of the `DELETE` statement in SQL?

**Answer:**

```sql
DELETE FROM table_name  
WHERE some_column = some_value;
```

---

# Question: Why must you be careful when using the `DELETE` statement without a `WHERE` clause?

**Answer:** Because it will delete **all records** in the table.

---

# Question: What happens if you omit the `WHERE` clause in a `DELETE` statement?

**Answer:** All rows in the table will be deleted.

---

# Question: Which SQL statement would delete "Tjessem, Jakob" from the "Persons" table?

**Answer:**

```sql
DELETE FROM Persons  
WHERE LastName='Tjessem' AND FirstName='Jakob';
```

---

# Question: After deleting "Tjessem, Jakob", how many records remain in the "Persons" table?

**Answer:** Four records (assuming no other deletions occurred).

---

# Question: What is the result of executing the following SQL command?

```sql
DELETE FROM Persons;
```

**Answer:** All records in the Persons table will be deleted.

---

# Question: True or False: The `UPDATE` and `DELETE` statements can modify or remove multiple records at once if the `WHERE` condition matches multiple rows.

**Answer:** True.

---

# Question: What is a real risk when forgetting the `WHERE` clause in an `UPDATE` or `DELETE` statement?

**Answer:** Unintended data loss or bulk updates across all records in the table.

---

# Question: What SQL statement deletes a specific row from a table where both `LastName` and `FirstName` match certain values?

**Answer:**

```sql
DELETE FROM Persons WHERE LastName='Tjessem' AND FirstName='Jakob'
```

---

# Question: After executing `DELETE FROM Persons WHERE LastName='Tjessem' AND FirstName='Jakob'`, what remains unchanged in the table?

**Answer:** The table structure, attributes, and other rows remain unchanged.

---

# Question: How can you delete **all rows** in a table without deleting the table itself in SQL?

**Answer:**

```sql
DELETE FROM table_name
```

---

# Question: What is the purpose of the SQL `TOP` clause?

**Answer:** It is used to specify the number or percentage of records to return, which is useful for large tables to improve performance.

---

# Question: Does every SQL database system support the `TOP` clause?

**Answer:** No, not all database systems support the `TOP` clause.

---

# Question: What is the correct SQL Server syntax for selecting the top 5 rows from a table?

**Answer:**

```sql
SELECT TOP 5 column_name(s) FROM table_name
```

---

# Question: What is the MySQL equivalent of SQL Server’s `SELECT TOP` clause?

**Answer:**

```sql
SELECT column_name(s) FROM table_name LIMIT number
```

---

# Question: How do you select the first 5 records in MySQL?

**Answer:**

```sql
SELECT * FROM Persons LIMIT 5
```

---

# Question: What is the Oracle equivalent of SQL Server’s `SELECT TOP` clause?

**Answer:**

```sql
SELECT column_name(s) FROM table_name WHERE ROWNUM <= number
```

---

# Question: How do you retrieve the first 5 records in Oracle SQL?

**Answer:**

```sql
SELECT * FROM Persons WHERE ROWNUM <= 5
```

---

# Question: Given the `Persons` table, how do you select only the first two records using SQL Server syntax?

**Answer:**

```sql
SELECT TOP 2 * FROM Persons
```

---

# Question: Why might using the `TOP` clause be beneficial in large tables?

**Answer:** Because retrieving a large number of records can degrade performance, the `TOP` clause allows limiting the result set for efficiency.

---

# Question: What does the `TOP PERCENT` clause do in SQL Server?

**Answer:** It selects a percentage of rows from the top of the result set based on the specified percentage.

---

# Question: What SQL Server query selects 50% of the records from the `Persons` table?

**Answer:**

```sql
SELECT TOP 50 PERCENT * FROM Persons
```

---

# Question: If the `Persons` table has 4 rows, how many rows will be returned by `SELECT TOP 50 PERCENT * FROM Persons`?

**Answer:** 2 rows.

---

# Question: What are SQL wildcards used for?

**Answer:** SQL wildcards are used to substitute characters in a `LIKE` clause to search for data in a database based on patterns.

---

# Question: What does the `%` wildcard represent in SQL?

**Answer:** A substitute for **zero or more characters**.

---

# Question: What does the `_` wildcard represent in SQL?

**Answer:** A substitute for **exactly one character**.

---

# Question: What does `[charlist]` do in a SQL `LIKE` clause?

**Answer:** It matches **any single character** in the specified `charlist`.

---

# Question: What does `[^charlist]` or `[!charlist]` do in SQL wildcards?

**Answer:** It matches **any single character not in** the specified `charlist`.

---

# Question: Which SQL query selects persons who live in cities starting with "sa"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City LIKE 'sa%'
```

---

# Question: What is the result of the query `SELECT * FROM Persons WHERE City LIKE 'sa%'` on the provided table?

**Answer:** It returns persons from **Sandnes**, because the city name starts with "sa".

---

# Question: Which SQL statement selects persons who live in cities containing the pattern "nes"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City LIKE '%nes%'
```

---

# Question: What does the `_` wildcard do in a SQL `LIKE` clause?

**Answer:** It substitutes for exactly **one character**.

---

# Question: Which SQL query selects persons with a `FirstName` where the second and third letters are "la"?

**Answer:**

```sql
SELECT * FROM Persons WHERE FirstName LIKE '_la'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE FirstName LIKE '_la'` on the given `Persons` table?

**Answer:**
It returns the person with `FirstName` "Ola".

---

# Question: What SQL pattern matches a `LastName` starting with "S", followed by any character, then "end", another character, and ending with "on"?

**Answer:**

```sql
SELECT * FROM Persons WHERE LastName LIKE 'S_end_on'
```

---

# Question: What result is returned by the query `SELECT * FROM Persons WHERE LastName LIKE 'S_end_on'`?

**Answer:**
It returns the person with `LastName` "Svendson".

---

# Question: What does `[charlist]` represent in SQL wildcard usage?

**Answer:** It matches any single character **within the list**.

---

# Question: Which SQL query selects all persons whose `LastName` starts with **b**, **s**, or **p**?

**Answer:**

```sql
SELECT * FROM Persons WHERE LastName LIKE '[bsp]%'
```

---

# Question: What result is returned from `SELECT * FROM Persons WHERE LastName LIKE '[bsp]%'` on the given table?

**Answer:**
It returns persons with `LastName` **Svendson** and **Pettersen**.

---

# Question: What does `[!charlist]` (or `[^charlist]`) do in SQL wildcard usage?

**Answer:** It matches any single character **not** in the list.

---

# Question: Which query returns persons whose `LastName` does **not** start with **b**, **s**, or **p**?

**Answer:**

```sql
SELECT * FROM Persons WHERE LastName LIKE '[!bsp]%'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE LastName LIKE '[!bsp]%'` on the provided data?

**Answer:**
It returns the person with `LastName` **Hansen**.

---

# Question: What is the purpose of the `LIKE` operator in SQL?

**Answer:** It is used in a `WHERE` clause to search for a specified **pattern** in a column.

---

# Question: What is the correct syntax for using the `LIKE` operator?

**Answer:**

```sql
SELECT column_name(s)
FROM table_name
WHERE column_name LIKE pattern
```

---

# Question: Which SQL query selects persons living in cities that start with "s"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City LIKE 's%'
```

---

# Question: What does the `%` wildcard mean when used **after** a character in a SQL `LIKE` clause?

**Answer:** It matches any sequence of characters **after** the specified pattern.

---

# Question: What is the result of `SELECT * FROM Persons WHERE City LIKE 's%'` on the provided `Persons` table?

**Answer:**
All three persons are returned: Sandnes and Stavanger both start with "s".

---

# Question: What SQL query selects persons living in a city that **ends** with the letter "s"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City LIKE '%s'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE City LIKE '%s'` on the provided table?

**Answer:**
Only one person is returned: the one living in **Sandnes**.

---

# Question: What does the `%` wildcard mean when placed **before and after** a pattern in a `LIKE` clause?

**Answer:** It matches any sequence of characters **before and after** the specified pattern.

---

# Question: What SQL query selects persons living in a city that **contains** the pattern "tav"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City LIKE '%tav%'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE City LIKE '%tav%'` on the table?

**Answer:**
It returns the person living in **Stavanger**.

---

# Question: Which SQL query returns persons **not** living in a city that contains "tav"?

**Answer:**

```sql
SELECT * FROM Persons WHERE City NOT LIKE '%tav%'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE City NOT LIKE '%tav%'`?

**Answer:**
It returns the persons living in **Sandnes** (2 people).

---

# Question: What is the purpose of the `IN` operator in SQL?

**Answer:**
It allows you to specify **multiple values** in a `WHERE` clause.

---

# Question: What is the purpose of the `IN` operator in SQL?

**Answer:** It allows you to specify **multiple values** in a `WHERE` clause for comparison.

---

# Question: What is the correct syntax for using the `IN` operator?

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name  
WHERE column_name IN (value1, value2, ...)
```

---

# Question: Which SQL query selects persons whose last name is either "Hansen" or "Pettersen"?

**Answer:**

```sql
SELECT * FROM Persons  
WHERE LastName IN ('Hansen', 'Pettersen')
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE LastName IN ('Hansen', 'Pettersen')` on the provided table?

**Answer:**
It returns the persons with `LastName` "Hansen" and "Pettersen".

---

# Question: What does the `BETWEEN` operator do in SQL?

**Answer:** It selects values within a **range**, inclusive of the **start and end** values.

---

# Question: What data types can be used with the `BETWEEN` operator in SQL?

**Answer:** Numbers, text (strings), or dates.

---

# Question: What is the correct SQL syntax for using the `BETWEEN` operator?

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name  
WHERE column_name BETWEEN value1 AND value2
```

---

# Question: Which SQL query selects persons whose last name is alphabetically between "Hansen" and "Pettersen"?

**Answer:**

```sql
SELECT * FROM Persons  
WHERE LastName BETWEEN 'Hansen' AND 'Pettersen'
```

---

# Question: What is the result of `SELECT * FROM Persons WHERE LastName BETWEEN 'Hansen' AND 'Pettersen'`?

**Answer:**
It returns the person with `LastName` **"Hansen"** only, because "Pettersen" is not alphabetically between "Hansen" and "Pettersen" (it's equal to the upper bound, which may be included depending on DBMS collation rules).

> ⚠️ If this result seems inconsistent, flag for `[Missing context]` as SQL collation and inclusivity may vary.

---

# Question: How does the `BETWEEN` operator behave differently across various databases?

**Answer:** Some databases include both boundary values, others exclude both, and some include the first value and exclude the second.

---

# Question: Why is it important to check how your specific database treats the `BETWEEN` operator?

**Answer:** Because the inclusion or exclusion of boundary values may affect which records are selected or omitted, potentially leading to incorrect query results.

---

# Question: How would you select all records with `LastName` not between 'Hansen' and 'Pettersen'?

**Answer:**

```sql
SELECT * FROM Persons  
WHERE LastName NOT BETWEEN 'Hansen' AND 'Pettersen';
```

---

# Question: What is the purpose of using aliases in SQL?

**Answer:** Aliases are used to give a table or column a temporary name, often to simplify complex queries or improve readability.

---

# Question: What is the syntax for giving an alias to a **table** in SQL?

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name AS alias_name;
```

---

# Question: What is the syntax for giving an alias to a **column** in SQL?

**Answer:**

```sql
SELECT column_name AS alias_name  
FROM table_name;
```

---

# Question: Provide an example of a SQL query using table aliases.

**Answer:**

```sql
SELECT po.OrderID, p.LastName, p.FirstName  
FROM Persons AS p, Product_Orders AS po  
WHERE p.LastName='Hansen' AND p.FirstName='Ola';
```

---

# Question: Rewrite the previous query **without aliases**.

**Answer:**

```sql
SELECT Product_Orders.OrderID, Persons.LastName, Persons.FirstName  
FROM Persons, Product_Orders  
WHERE Persons.LastName='Hansen' AND Persons.FirstName='Ola';
```

---

# Question: What are the benefits of using aliases in SQL queries?

**Answer:** They make queries easier to write and read, especially when dealing with long or complex table or column names.

---

# Question: What is the purpose of SQL `JOIN` operations?

**Answer:** To retrieve data from two or more tables based on relationships between columns in those tables.

---

# Question: What is a **primary key** in a database table?

**Answer:** A column or a combination of columns with unique values for each row, used to uniquely identify records and create relationships across tables.

---

# Question: In the "Persons" table, which column is the primary key?

**Answer:** `P_Id`

---

# Question: In the "Orders" table, which column refers to a person in the "Persons" table?

**Answer:** `P_Id`

---

# Question: How does the `P_Id` column in "Orders" relate to the "Persons" table?

**Answer:** It acts as a foreign key referencing the `P_Id` primary key in the "Persons" table.

---

# Question: What does the `JOIN` type return in SQL?

**Answer:** Rows with at least one match in both tables.

---

# Question: What does a `LEFT JOIN` return?

**Answer:** All rows from the left table and matched rows from the right table; unmatched right table fields will be `NULL`.

---

# Question: What does a `RIGHT JOIN` return?

**Answer:** All rows from the right table and matched rows from the left table; unmatched left table fields will be `NULL`.

---

# Question: What does a `FULL JOIN` return?

**Answer:** All rows with a match in **either** left or right table, combining results from `LEFT JOIN` and `RIGHT JOIN`.

---

# Question: What does the `INNER JOIN` keyword do?

**Answer:** Returns rows with at least one match in both tables.

---

# Question: Is there a difference between `JOIN` and `INNER JOIN`?

**Answer:** No, they are functionally equivalent.

---

# Question: Provide the syntax for an `INNER JOIN` in SQL.

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name1  
INNER JOIN table_name2  
ON table_name1.column_name = table_name2.column_name;
```

---













