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

# Question: How do you list all persons who have made any orders?

**Answer:**

```sql
SELECT Persons.LastName, Persons.FirstName, Orders.OrderNo  
FROM Persons INNER JOIN Orders ON Persons.P_Id = Orders.P_Id  
ORDER BY Persons.LastName;
```

---

# Question: What type of `JOIN` is used to select only persons who have at least one matching order?

**Answer:** `INNER JOIN`

---

# Question: What is the behavior of `INNER JOIN` when some rows in the left table have no match in the right table?

**Answer:** Those rows are not included in the result set.

---

# Question: What will be excluded from the result set of an `INNER JOIN` between `Persons` and `Orders`?

**Answer:** Any person in the `Persons` table who does not have a matching `P_Id` in the `Orders` table.

---

# Question: What is the purpose of using `ORDER BY` in a `JOIN` query?

**Answer:** To sort the result set by the specified column, such as `Persons.LastName`.

---

# Question: What does the `LEFT JOIN` keyword do in SQL?

**Answer:** It returns all rows from the left table and the matched rows from the right table; unmatched rows from the right table are shown as `NULL`.

---

# Question: What is the syntax for a SQL `LEFT JOIN`?

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name1  
LEFT JOIN table_name2  
ON table_name1.column_name = table_name2.column_name;
```

---

# Question: What is another name for `LEFT JOIN` in some databases?

**Answer:** `LEFT OUTER JOIN`

---

# Question: How do you list all persons and their orders, even if some persons made no orders?

**Answer:**

```sql
SELECT Persons.LastName, Persons.FirstName, Orders.OrderNo  
FROM Persons LEFT JOIN Orders  
ON Persons.P_Id = Orders.P_Id  
ORDER BY Persons.LastName;
```

---

# Question: What value appears in the `OrderNo` column for persons with no orders when using a `LEFT JOIN`?

**Answer:** `NULL`

---

# Question: Based on the `LEFT JOIN` result, why does "Svendson Tove" appear without an `OrderNo`?

**Answer:** Because there is no matching `P_Id` for "Svendson Tove" in the `Orders` table.

---

# Question: What does the `RIGHT JOIN` keyword do in SQL?

**Answer:** It returns all rows from the right table and the matched rows from the left table; unmatched rows from the left table are shown as `NULL`.

---

# Question: What is the SQL syntax for a `RIGHT JOIN`?

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name1  
RIGHT JOIN table_name2  
ON table_name1.column_name = table_name2.column_name;
```

---

# Question: What is another name for `RIGHT JOIN` in some databases?

**Answer:** `RIGHT OUTER JOIN`

---

# Question: What does the `RIGHT JOIN` keyword do in SQL?

**Answer:** It returns all rows from the right table (e.g., `Orders`), and the matched rows from the left table (`Persons`). If there is no match, `NULL` is returned for the left table’s columns.

---

# Question: Provide the SQL syntax to use a `RIGHT JOIN`.

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name1  
RIGHT JOIN table_name2  
ON table_name1.column_name = table_name2.column_name;
```

---

# Question: Write a SQL query to list all orders with their associated persons using `RIGHT JOIN`.

**Answer:**

```sql
SELECT Persons.LastName, Persons.FirstName, Orders.OrderNo  
FROM Persons  
RIGHT JOIN Orders  
ON Persons.P_Id = Orders.P_Id  
ORDER BY Persons.LastName;
```

---

# Question: In a `RIGHT JOIN` result, what will appear in the row if there’s an `OrderNo` without a matching person?

**Answer:** The `LastName` and `FirstName` fields will be `NULL`, and only the `OrderNo` will be shown.

---

# Question: What is the output for `OrderNo 34764` when using `RIGHT JOIN` between `Persons` and `Orders`?

**Answer:** The `OrderNo 34764` is displayed with `NULL` values for `LastName` and `FirstName` because `P_Id = 15` has no match in the `Persons` table.

---

# Question: What does the `FULL JOIN` keyword do in SQL?

**Answer:** It returns all rows from both the left table and the right table. If a row has no match in the other table, it still appears in the result with `NULL` for missing values.

---

# Question: Provide the syntax for a `FULL JOIN` in SQL.

**Answer:**

```sql
SELECT column_name(s)  
FROM table_name1  
FULL JOIN table_name2  
ON table_name1.column_name = table_name2.column_name;
```

---

# Question: What is the difference between `RIGHT JOIN` and `FULL JOIN`?

**Answer:** `RIGHT JOIN` returns all rows from the right table and matched rows from the left; `FULL JOIN` returns all rows from both tables, including unmatched rows from both sides.

---

# Question: Write a SQL query using `FULL JOIN` to list all persons and all orders, matched or not.

**Answer:**

```sql
SELECT Persons.LastName, Persons.FirstName, Orders.OrderNo  
FROM Persons  
FULL JOIN Orders  
ON Persons.P_Id = Orders.P_Id  
ORDER BY Persons.LastName;
```

---

# Question: In a `FULL JOIN`, what happens to persons who have not placed any orders?

**Answer:** They appear in the result with `NULL` for the `OrderNo`.

---

# Question: In a `FULL JOIN`, what happens to orders that are not linked to any person?

**Answer:** They appear in the result with `NULL` for `LastName` and `FirstName`.

---

# Question: What is the purpose of the `UNION` operator in SQL?

**Answer:** It combines the result sets of two or more `SELECT` statements and returns only distinct values by default.

---

# Question: What are the requirements for columns used in a SQL `UNION` operation?

**Answer:** The columns must have similar data types and appear in the same order in all `SELECT` statements.

---

# Question: Provide the SQL syntax for using `UNION`.

**Answer:**

```sql
SELECT column_name(s) FROM table_name1  
UNION  
SELECT column_name(s) FROM table_name2;
```

---

# Question: How does `UNION` handle duplicate values?

**Answer:** `UNION` removes duplicates and returns only distinct values by default.

---

# Question: How can you allow duplicate values when combining results from two tables?

**Answer:** Use `UNION ALL` instead of `UNION`.

---

# Question: What is the SQL syntax for using `UNION ALL`?

**Answer:**

```sql
SELECT column_name(s) FROM table_name1  
UNION ALL  
SELECT column_name(s) FROM table_name2;
```

---

# Question: In a `UNION` query, what determines the column names in the final result-set?

**Answer:** The column names from the first `SELECT` statement are used in the final result-set.

---

# Question: Given a `UNION` operation between two tables with duplicate names, what will happen?

**Answer:** Only one of the duplicate names will appear in the result-set because `UNION` removes duplicates.

---

# Question: Given the tables `Employees_Norway` and `Employees_USA`, how can you list all **distinct** employee names from both?

**Answer:**

```sql
SELECT E_Name FROM Employees_Norway  
UNION  
SELECT E_Name FROM Employees_USA;
```

---

# Question: What would be the result of using `UNION` on two tables that both contain the name `Svendson, Stephen`?

**Answer:** Only one `Svendson, Stephen` would appear in the result-set.

---

# Question: How would you list **all** employees, including duplicates, from `Employees_Norway` and `Employees_USA`?

**Answer:**

```sql
SELECT E_Name FROM Employees_Norway  
UNION ALL  
SELECT E_Name FROM Employees_USA;
```

---

# Question: What is the difference between `UNION` and `UNION ALL`?

**Answer:** `UNION` removes duplicates and returns distinct values, while `UNION ALL` includes all values, including duplicates.

---

# Question: What is the purpose of the `SELECT INTO` statement in SQL?

**Answer:** To copy data from one table into a new table, often used to create backup copies of tables.

---

# Question: What is the general syntax for copying all columns from one table to another using `SELECT INTO`?

**Answer:**

```sql
SELECT *  
INTO new_table_name  
FROM old_tablename;
```

---

# Question: How can you copy specific columns from one table into a new table using `SELECT INTO`?

**Answer:**

```sql
SELECT column_name(s)  
INTO new_table_name  
FROM old_tablename;
```

---

# Question: In what scenario is `SELECT INTO` most often used?

**Answer:** To create backup copies of tables.

---

# Question: What optional clause can be used with `SELECT INTO` to store the new table in another database?

**Answer:** The `[IN externaldatabase]` clause.

---

# Question: What SQL statement is used to create an exact copy of the data in the "Persons" table?

**Answer:**
`SELECT * INTO Persons_Backup FROM Persons`

---

# Question: How can you copy a table into another database using SQL?

**Answer:**
By using the `IN` clause:
`SELECT * INTO Persons_Backup IN 'Backup.mdb' FROM Persons`

---

# Question: How can you copy only specific columns from a table into a new table?

**Answer:**
By specifying the columns in the SELECT statement:
`SELECT LastName, FirstName INTO Persons_Backup FROM Persons`

---

# Question: How do you use a WHERE clause with SELECT INTO to filter records?

**Answer:**
`SELECT LastName, FirstName INTO Persons_Backup FROM Persons WHERE City='Sandnes'`

---

# Question: Can SELECT INTO be used with joined tables? If yes, give an example.

**Answer:**
Yes, it can. Example:

```sql
SELECT * INTO Persons_Order_Backup  
FROM Persons  
INNER JOIN Orders ON Persons.P_Id = Orders.P_Id
```

---

# Question: What is the purpose of the CREATE DATABASE statement?

**Answer:**
To create a new database.

---

# Question: Write the SQL syntax for creating a new database.

**Answer:**
`CREATE DATABASE database_name`

---

# Question: How would you create a database named "my\_db"?

**Answer:**
`CREATE DATABASE my_db`

---

# Question: After creating a database, how can you add tables to it?

**Answer:**
By using the `CREATE TABLE` statement.

---

# Question: What is the purpose of the CREATE TABLE statement?

**Answer:**
To create a table in a database.

---

# Question: Write the general syntax of the CREATE TABLE statement.

**Answer:**

```sql
CREATE TABLE table_name (
  column_name1 data_type,
  column_name2 data_type,
  column_name3 data_type,
  ...
)
```

---

# Question: In the CREATE TABLE statement, what does the data type specify?

**Answer:**
The type of data that a column can hold.

---

# Question: Write a SQL statement to create a "Persons" table with columns: P\_Id, LastName, FirstName, Address, and City.

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int,
  LastName varchar(255),
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: What data type is used for the P\_Id column in the Persons table?

**Answer:**
`int`

---

# Question: What data type is used for the LastName, FirstName, Address, and City columns in the Persons table?

**Answer:**
`varchar(255)`

---

# Question: What SQL statement is used to insert data into an empty table?

**Answer:**
`INSERT INTO`

---

# Question: What are SQL constraints used for?

**Answer:**
To limit the type of data that can go into a table.

---

# Question: At what stages can constraints be defined in SQL?

**Answer:**
During table creation (`CREATE TABLE`) or after using `ALTER TABLE`.

---

# Question: List the six constraints focused on in the material.

**Answer:**

* NOT NULL
* UNIQUE
* PRIMARY KEY
* FOREIGN KEY
* CHECK
* DEFAULT

---

# Question: What does the NOT NULL constraint enforce?

**Answer:**
It enforces a column to not accept NULL values; the field must always contain a value.

---

# Question: Write a CREATE TABLE statement with a NOT NULL constraint on P\_Id and LastName columns.

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: What does the UNIQUE constraint do in SQL?

**Answer:**
It uniquely identifies each record in a table.

---

# Question: How is the PRIMARY KEY constraint related to the UNIQUE constraint?

**Answer:**
A PRIMARY KEY constraint automatically has a UNIQUE constraint defined on it.

---

# Question: How many UNIQUE constraints can a table have?

**Answer:**
Multiple UNIQUE constraints per table.

---

# Question: How many PRIMARY KEY constraints can a table have?

**Answer:**
Only one PRIMARY KEY constraint per table.

---

# Question: Write the MySQL syntax for adding a UNIQUE constraint on the P\_Id column during table creation.

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  UNIQUE (P_Id)
)
```

---

# Question: Write the SQL Server / Oracle / MS Access syntax for defining the P\_Id column as UNIQUE during table creation.

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL UNIQUE,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: How do you define a UNIQUE constraint on multiple columns during table creation?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  CONSTRAINT uc_PersonID UNIQUE (P_Id, LastName)
)
```

---

# Question: How do you add a UNIQUE constraint to a column after the table has been created?

**Answer:**

```sql
ALTER TABLE Persons  
ADD UNIQUE (P_Id)
```

---

# Question: How do you add a named UNIQUE constraint on multiple columns using ALTER TABLE?

**Answer:**

```sql
ALTER TABLE Persons  
ADD CONSTRAINT uc_PersonID UNIQUE (P_Id, LastName)
```

---

# Question: How do you drop a UNIQUE constraint in MySQL?

**Answer:**

```sql
ALTER TABLE Persons  
DROP INDEX uc_PersonID
```

---

# Question: How do you drop a UNIQUE constraint in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
ALTER TABLE Persons  
DROP CONSTRAINT uc_PersonID
```

---

# Question: What does the PRIMARY KEY constraint do in SQL?

**Answer:**
It uniquely identifies each record in a table, ensures values are unique and not NULL, and enforces table-level integrity.

---

# Question: Can a table have multiple PRIMARY KEY constraints?

**Answer:**
No, a table can have only **one** PRIMARY KEY constraint.

---

# Question: What happens if you try to insert a NULL into a PRIMARY KEY column?

**Answer:**
The insertion will fail, as PRIMARY KEY columns **cannot contain NULL values**.

---

# Question: How do you define a PRIMARY KEY on a single column during table creation in MySQL?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  PRIMARY KEY (P_Id)
)
```

---

# Question: How do you define a PRIMARY KEY on a single column during table creation in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL PRIMARY KEY,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: How do you name a PRIMARY KEY constraint on multiple columns in a CREATE TABLE statement?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  CONSTRAINT pk_PersonID PRIMARY KEY (P_Id, LastName)
)
```

---

# Question: How do you add a PRIMARY KEY constraint to an existing table on a single column?

**Answer:**

```sql
ALTER TABLE Persons  
ADD PRIMARY KEY (P_Id)
```

---

# Question: How do you add a named PRIMARY KEY constraint on multiple columns using ALTER TABLE?

**Answer:**

```sql
ALTER TABLE Persons  
ADD CONSTRAINT pk_PersonID PRIMARY KEY (P_Id, LastName)
```

---

# Question: What is required before adding a PRIMARY KEY using ALTER TABLE?

**Answer:**
The column(s) must already be defined with `NOT NULL`.

---

# Question: How do you drop a PRIMARY KEY constraint in MySQL?

**Answer:**

```sql
ALTER TABLE Persons  
DROP PRIMARY KEY
```

---

# Question: How do you drop a named PRIMARY KEY constraint in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
ALTER TABLE Persons  
DROP CONSTRAINT pk_PersonID
```

---

# Question: What is the purpose of the FOREIGN KEY constraint?

**Answer:**
To maintain referential integrity between tables by preventing invalid data entry and disallowed deletions/updates.

---

# Question: What is the role of the P\_Id column in the "Persons" and "Orders" tables in the foreign key relationship?

**Answer:**
In `Persons`, P\_Id is the PRIMARY KEY.
In `Orders`, P\_Id is the FOREIGN KEY referencing `Persons(P_Id)`.

---

# Question: How does the FOREIGN KEY constraint prevent invalid data?

**Answer:**
It requires the foreign key value to exist in the referenced primary key column.

---

# Question: Write the SQL to create an "Orders" table with a foreign key to the "Persons" table in MySQL.

**Answer:**

```sql
CREATE TABLE Orders (
  O_Id int NOT NULL,
  OrderNo int NOT NULL,
  P_Id int,
  PRIMARY KEY (O_Id),
  FOREIGN KEY (P_Id) REFERENCES Persons(P_Id)
)
```

---

# Question: How do you define a named FOREIGN KEY constraint during table creation?

**Answer:**

```sql
CREATE TABLE Orders (
  O_Id int NOT NULL,
  OrderNo int NOT NULL,
  P_Id int,
  PRIMARY KEY (O_Id),
  CONSTRAINT fk_PerOrders FOREIGN KEY (P_Id)
  REFERENCES Persons(P_Id)
)
```

---

# Question: How do you add a FOREIGN KEY constraint to an existing table?

**Answer:**

```sql
ALTER TABLE Orders
ADD FOREIGN KEY (P_Id)
REFERENCES Persons(P_Id)
```

---

# Question: How do you add a named FOREIGN KEY constraint using ALTER TABLE?

**Answer:**

```sql
ALTER TABLE Orders
ADD CONSTRAINT fk_PerOrders
FOREIGN KEY (P_Id)
REFERENCES Persons(P_Id)
```

---

# Question: How do you drop a FOREIGN KEY constraint in MySQL?

**Answer:**

```sql
ALTER TABLE Orders
DROP FOREIGN KEY fk_PerOrders
```

---

# Question: How do you drop a FOREIGN KEY constraint in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
ALTER TABLE Orders
DROP CONSTRAINT fk_PerOrders
```

---

# Question: What does the CHECK constraint do in SQL?

**Answer:**
It restricts the values that can be inserted into a column or combination of columns based on a condition.

---

# Question: How do you create a CHECK constraint on a column using CREATE TABLE in MySQL?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  CHECK (P_Id > 0)
)
```

---

# Question: How do you create a CHECK constraint on a column using CREATE TABLE in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL CHECK (P_Id > 0),
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: How do you define a named CHECK constraint that checks multiple columns?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  CONSTRAINT chk_Person CHECK (P_Id > 0 AND City = 'Sandnes')
)
```

---

# Question: How do you add a CHECK constraint to a column after table creation?

**Answer:**

```sql
ALTER TABLE Persons
ADD CHECK (P_Id > 0)
```

---

# Question: How do you add a named CHECK constraint using ALTER TABLE?

**Answer:**

```sql
ALTER TABLE Persons
ADD CONSTRAINT chk_Person CHECK (P_Id > 0 AND City = 'Sandnes')
```

---

# Question: How do you drop a CHECK constraint in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
ALTER TABLE Persons
DROP CONSTRAINT chk_Person
```

---

# Question: What does the DEFAULT constraint do in SQL?

**Answer:**
It sets a default value for a column when no value is specified during an insert operation.

---

# Question: How do you define a DEFAULT constraint on a column when creating a table?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255) DEFAULT 'Sandnes'
)
```

---

# Question: How do you define a DEFAULT constraint using a system function like `GETDATE()`?

**Answer:**

```sql
CREATE TABLE Orders (
  O_Id int NOT NULL,
  OrderNo int NOT NULL,
  P_Id int,
  OrderDate date DEFAULT GETDATE()
)
```

---

# Question: How do you set a DEFAULT constraint on a column using ALTER TABLE in MySQL?

**Answer:**

```sql
ALTER TABLE Persons
ALTER City SET DEFAULT 'SANDNES'
```

---

# Question: How do you set a DEFAULT constraint on a column using ALTER TABLE in SQL Server, Oracle, or MS Access?

**Answer:**

```sql
ALTER TABLE Persons
ALTER COLUMN City SET DEFAULT 'SANDNES'
```

---

# Question: How do you drop a DEFAULT constraint on a column in **MySQL**?

**Answer:**

```sql
ALTER TABLE Persons
ALTER City DROP DEFAULT
```

---

# Question: How do you drop a DEFAULT constraint on a column in **SQL Server / Oracle / MS Access**?

**Answer:**

```sql
ALTER TABLE Persons
ALTER COLUMN City DROP DEFAULT
```

---

# Question: What is the purpose of the `CREATE INDEX` statement in SQL?

**Answer:**
To create an index on a column to speed up searches and queries on large datasets.

---

# Question: How do you create an index that allows duplicate values?

**Answer:**

```sql
CREATE INDEX index_name
ON table_name (column_name)
```

---

# Question: How do you create a **unique** index that disallows duplicate values?

**Answer:**

```sql
CREATE UNIQUE INDEX index_name
ON table_name (column_name)
```

---

# Question: Write an example of creating an index named `PIndex` on multiple columns.

**Answer:**

```sql
CREATE INDEX PIndex
ON Persons (LastName, FirstName)
```

---

# Question: How do you drop an index in **MS Access**?

**Answer:**

```sql
DROP INDEX index_name ON table_name
```

---

# Question: How do you drop an index in **MS SQL Server**?

**Answer:**

```sql
DROP INDEX table_name.index_name
```

---

# Question: How do you drop an index in **Oracle / DB2**?

**Answer:**

```sql
DROP INDEX index_name
```

---

# Question: How do you drop an index in **MySQL**?

**Answer:**

```sql
ALTER TABLE table_name DROP INDEX index_name
```

---

# Question: What is the purpose of the `DROP TABLE` statement?

**Answer:**
To delete a table and all of its data and structure permanently.

---

# Question: How do you delete a table in SQL?

**Answer:**

```sql
DROP TABLE table_name
```

---

# Question: What is the purpose of the `DROP DATABASE` statement?

**Answer:**
To delete a database, including all its tables and data.

---

# Question: How do you delete an entire database in SQL?

**Answer:**

```sql
DROP DATABASE database_name
```

---

# Question: How do you delete all rows from a table without deleting the table itself?

**Answer:**

```sql
TRUNCATE TABLE table_name
```

---

# Question: How do you add a new column to an existing table?

**Answer:**

```sql
ALTER TABLE table_name
ADD column_name datatype
```

---

# Question: How do you delete a column from an existing table?

**Answer:**

```sql
ALTER TABLE table_name
DROP COLUMN column_name
```

---

# Question: How do you change the data type of a column in an existing table?

**Answer:**

```sql
ALTER TABLE table_name
ALTER COLUMN column_name datatype
```

---

# Question: Write SQL to add a column named `DateOfBirth` of type `date` to the `Persons` table.

**Answer:**

```sql
ALTER TABLE Persons
ADD DateOfBirth date
```

---

# Question: Write SQL to change the data type of `DateOfBirth` to `year` in the `Persons` table.

**Answer:**

```sql
ALTER TABLE Persons
ALTER COLUMN DateOfBirth year
```

---

# Question: Write SQL to delete the column `DateOfBirth` from the `Persons` table.

**Answer:**

```sql
ALTER TABLE Persons
DROP COLUMN DateOfBirth
```

---

# Question: What keyword does MySQL use to create an auto-increment field?

**Answer:** `AUTO_INCREMENT`

---

# Question: What is the default starting value for `AUTO_INCREMENT` in MySQL?

**Answer:** 1

---

# Question: What is the default increment step for `AUTO_INCREMENT` in MySQL?

**Answer:** 1

---

# Question: Write the MySQL syntax to make a column `P_Id` an auto-incrementing primary key.

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int NOT NULL AUTO_INCREMENT,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255),
  PRIMARY KEY (P_Id)
)
```

---

# Question: How can you set the auto-increment value to start from 100 in MySQL?

**Answer:**

```sql
ALTER TABLE Persons AUTO_INCREMENT = 100;
```

---

# Question: In MySQL, do you need to specify a value for the `AUTO_INCREMENT` field when inserting a record?

**Answer:** No, a unique value is added automatically.

---

# Question: Write a valid `INSERT` SQL statement in MySQL that auto-generates the primary key.

**Answer:**

```sql
INSERT INTO Persons (FirstName, LastName)
VALUES ('Lars', 'Monsen');
```

---

# Question: What keyword does SQL Server use for auto-increment?

**Answer:** `IDENTITY`

---

# Question: What is the default starting value and increment step for `IDENTITY` in SQL Server?

**Answer:** Starting value is 1 and it increments by 1.

---

# Question: How do you define a column `P_Id` in SQL Server to start at 10 and increment by 5?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id int PRIMARY KEY IDENTITY(10,5),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: Can you omit the `P_Id` column when inserting into a SQL Server table with `IDENTITY`?

**Answer:** Yes, the value is generated automatically.

---

# Question: Write the SQL Server `INSERT` statement that auto-generates `P_Id`.

**Answer:**

```sql
INSERT INTO Persons (FirstName, LastName)
VALUES ('Lars', 'Monsen');
```

---

# Question: What keyword does MS Access use for auto-increment?

**Answer:** `AUTOINCREMENT`

---

# Question: What is the syntax to define an auto-incrementing primary key field in MS Access?

**Answer:**

```sql
CREATE TABLE Persons (
  P_Id PRIMARY KEY AUTOINCREMENT,
  LastName varchar(255) NOT NULL,
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255)
)
```

---

# Question: How do you set `P_Id` to start at 10 and increment by 5 in MS Access?

**Answer:** Use `AUTOINCREMENT(10,5)`

---

# Question: What keyword does Oracle use for auto-increment?

**Answer:** Oracle does not use a keyword; it uses a sequence object.

---

# Question: Write the Oracle SQL syntax to create an auto-increment sequence called `seq_person`.

**Answer:**

```sql
CREATE SEQUENCE seq_person
MINVALUE 1
START WITH 1
INCREMENT BY 1
CACHE 10;
```

---

# Question: In Oracle, how do you retrieve the next value from a sequence?

**Answer:** Use the `sequence_name.nextval` function.

---

# Question: Write the Oracle SQL `INSERT` statement to add a record using an auto-incremented primary key.

**Answer:**

```sql
INSERT INTO Persons (P_Id, FirstName, LastName)
VALUES (seq_person.nextval, 'Lars', 'Monsen');
```

---

# Question: What is the purpose of `CACHE 10` in an Oracle sequence?

**Answer:** It stores 10 sequence values in memory for faster access.

---

# Question: What is a view in SQL?

**Answer:** A view is a virtual table based on the result-set of an SQL statement.

---

# Question: Can a SQL view contain rows and columns from multiple tables?

**Answer:** Yes

---

# Question: Does a SQL view always return up-to-date data?

**Answer:** Yes, because the database engine executes the view’s SQL statement every time it’s queried.

---

# Question: What is the syntax for creating a view?

**Answer:**

```sql
CREATE VIEW view_name AS
SELECT column_name(s)
FROM table_name
WHERE condition;
```

---

# Question: What SQL functions or clauses can be used in a view definition?

**Answer:** SQL functions, `WHERE`, and `JOIN` statements.

---

# Question: Write the SQL to create a view showing active products from the `Products` table.

**Answer:**

```sql
CREATE VIEW [Current Product List] AS
SELECT ProductID, ProductName
FROM Products
WHERE Discontinued = No;
```

---

# Question: How do you query data from the `[Current Product List]` view?

**Answer:**

```sql
SELECT * FROM [Current Product List];
```

---

# Question: Write a SQL view that shows products with a unit price above average.

**Answer:**

```sql
CREATE VIEW [Products Above Average Price] AS
SELECT ProductName, UnitPrice
FROM Products
WHERE UnitPrice > (SELECT AVG(UnitPrice) FROM Products);
```

---

# Question: How do you retrieve all records from `[Products Above Average Price]`?

**Answer:**

```sql
SELECT * FROM [Products Above Average Price];
```

---

# Question: Write the SQL to create a view called `[Category Sales For 1997]` that calculates total sales by category.

**Answer:**

```sql
CREATE VIEW [Category Sales For 1997] AS
SELECT DISTINCT CategoryName, SUM(ProductSales) AS CategorySales
FROM [Product Sales for 1997]
GROUP BY CategoryName;
```

---

# Question: How do you query `[Category Sales For 1997]`?

**Answer:**

```sql
SELECT * FROM [Category Sales For 1997];
```

---

# Question: Can you add a `WHERE` condition when querying a view?

**Answer:** Yes

---

# Question: How would you query `[Category Sales For 1997]` to get sales only for the "Beverages" category?

**Answer:**

```sql
SELECT * FROM [Category Sales For 1997]
WHERE CategoryName = 'Beverages';
```

---

# Question: How do you retrieve all sales records from the view "Category Sales For 1997" where the category is "Beverages"?

**Answer:**
`SELECT * FROM [Category Sales For 1997] WHERE CategoryName='Beverages'`

---

# Question: What SQL syntax is used to update a view?

**Answer:**
`CREATE OR REPLACE VIEW view_name AS SELECT column_name(s) FROM table_name WHERE condition`

---

# Question: How would you update the "Current Product List" view to include the "Category" column?

**Answer:**

```sql
CREATE VIEW [Current Product List] AS  
SELECT ProductID, ProductName, Category  
FROM Products  
WHERE Discontinued=No
```

---

# Question: What SQL command is used to delete a view?

**Answer:**
`DROP VIEW view_name`

---

# Question: What is the most difficult part of working with dates in SQL?

**Answer:**
Ensuring the date format you insert matches the format expected by the date column in the database.

---

# Question: Why is it problematic to include time components when comparing dates?

**Answer:**
Because queries that filter by date alone (`WHERE OrderDate='YYYY-MM-DD'`) will fail if the date column includes time, resulting in no matches.

---

# Question: What is a tip to simplify queries involving date comparisons?

**Answer:**
Avoid including time components in date values.

---

# Question: What does `NOW()` return in MySQL?

**Answer:**
The current date and time.

---

# Question: What is returned by `CURDATE()` in MySQL?

**Answer:**
The current date.

---

# Question: What does the `CURTIME()` function return?

**Answer:**
The current time.

---

# Question: What is the purpose of the `DATE()` function in MySQL?

**Answer:**
It extracts the date part from a date or date/time expression.

---

# Question: Which MySQL function returns a single part of a date/time value?

**Answer:**
`EXTRACT()`

---

# Question: How does `DATE_ADD()` work in MySQL?

**Answer:**
It adds a specified time interval to a date.

---

# Question: What is the use of `DATE_SUB()` in MySQL?

**Answer:**
It subtracts a specified time interval from a date.

---

# Question: Which function returns the number of days between two dates in MySQL?

**Answer:**
`DATEDIFF()`

---

# Question: What is the purpose of `DATE_FORMAT()`?

**Answer:**
It displays date/time data in different formats.

---

# Question: What does `GETDATE()` return in SQL Server?

**Answer:**
The current date and time.

---

# Question: Which SQL Server function returns a single part of a date/time?

**Answer:**
`DATEPART()`

---

# Question: How does `DATEADD()` work in SQL Server?

**Answer:**
It adds or subtracts a specified time interval from a date.

---

# Question: What does `DATEDIFF()` return in SQL Server?

**Answer:**
The time (in specified units) between two dates.

---

# Question: How do you format date/time data in SQL Server?

**Answer:**
Using the `CONVERT()` function.

---

# Question: What are the MySQL date data types and their formats?

**Answer:**

* `DATE` - `YYYY-MM-DD`
* `DATETIME` - `YYYY-MM-DD HH:MM:SS`
* `TIMESTAMP` - `YYYY-MM-DD HH:MM:SS`
* `YEAR` - `YYYY` or `YY`

---

# Question: What are the SQL Server date data types and their formats?

**Answer:**

* `DATE` - `YYYY-MM-DD`
* `DATETIME` - `YYYY-MM-DD HH:MM:SS`
* `SMALLDATETIME` - `YYYY-MM-DD HH:MM:SS`
* `TIMESTAMP` - a unique number (not a date)

---

# Question: What query selects orders placed on "2008-11-11" from an `Orders` table with only dates (no time)?

**Answer:**
`SELECT * FROM Orders WHERE OrderDate='2008-11-11'`

---

# Question: What will happen if you run `SELECT * FROM Orders WHERE OrderDate='2008-11-11'` on a column that includes time?

**Answer:**
You will get no result, because the time component causes the values to differ from `'2008-11-11'`.

---

# Question: How can default date values be assigned using `NOW()` in a table definition?

**Answer:**

```sql
CREATE TABLE Orders (
  OrderId int NOT NULL,
  ProductName varchar(50) NOT NULL,
  OrderDate datetime NOT NULL DEFAULT NOW(),
  PRIMARY KEY (OrderId)
)
```

---

# Question: What happens when a row is inserted into a table where `OrderDate` has a default of `NOW()`?

**Answer:**
The current date and time are automatically inserted into the `OrderDate` column.

---

# Question: How do you insert a record with default `NOW()` value for `OrderDate`?

**Answer:**
`INSERT INTO Orders (ProductName) VALUES ('Jarlsberg Cheese')`

---

# Question: How is the result of `NOW()`, `CURDATE()`, and `CURTIME()` typically displayed in MySQL?

**Answer:**
NOW() → full datetime, CURDATE() → date only, CURTIME() → time only.
Example: `2008-11-11 12:45:34`, `2008-11-11`, `12:45:34`

---

# Question: How do you set `CURDATE()` as the default value for a `datetime` column?

**Answer:**

```sql
CREATE TABLE Orders (
  OrderId int NOT NULL,
  ProductName varchar(50) NOT NULL,
  OrderDate datetime NOT NULL DEFAULT CURDATE(),
  PRIMARY KEY (OrderId)
)
```

---

# Question: What is the result of inserting a record into a table where `OrderDate` defaults to `CURDATE()`?

**Answer:**
The current date (with time set to 00:00:00) is inserted automatically.

---

# Question: What does the `CURTIME()` function return in MySQL?

**Answer:**
It returns the current time.

---

# Question: What is the syntax for the `CURTIME()` function?

**Answer:**
`CURTIME()`

---

# Question: What is the output of `SELECT NOW(), CURDATE(), CURTIME()`?

**Answer:**
It returns the current date and time, current date, and current time respectively.
Example:
`2008-11-11 12:45:34`, `2008-11-11`, `12:45:34`

---

# Question: What does the `DATE()` function do in MySQL?

**Answer:**
It extracts the date part from a date or date/time expression.

---

# Question: What is the syntax of the `DATE()` function?

**Answer:**
`DATE(date)`, where `date` is a valid date expression.

---

# Question: What is the result of the query:

```sql
SELECT ProductName, DATE(OrderDate) AS OrderDate FROM Orders WHERE OrderId=1
```

given `OrderDate = '2008-11-11 13:23:44.657'`?
**Answer:**
It returns `Jarlsberg Cheese`, `2008-11-11`

---

# Question: What is the use of the `EXTRACT()` function in MySQL?

**Answer:**
It returns a specific part (e.g., year, month, day) from a date/time value.

---

# Question: What is the syntax for the `EXTRACT()` function?

**Answer:**
`EXTRACT(unit FROM date)`, where `unit` is the part to extract.

---

# Question: Which units can be used with the `EXTRACT()` function?

**Answer:**

* MICROSECOND
* SECOND
* MINUTE
* HOUR
* DAY
* WEEK
* MONTH
* QUARTER
* YEAR
* SECOND\_MICROSECOND
* MINUTE\_MICROSECOND
* MINUTE\_SECOND
* HOUR\_MICROSECOND
* HOUR\_SECOND
* DAY\_MICROSECOND
* DAY\_SECOND
* DAY\_MINUTE
* DAY\_HOUR
* YEAR\_MONTH

---

# Question: What does the following query return?

```sql
SELECT EXTRACT(YEAR FROM OrderDate) AS OrderYear,  
       EXTRACT(MONTH FROM OrderDate) AS OrderMonth,  
       EXTRACT(DAY FROM OrderDate) AS OrderDay  
FROM Orders WHERE OrderId=1
```

Given `OrderDate = '2008-11-11 13:23:44.657'`
**Answer:**
`OrderYear: 2008`, `OrderMonth: 11`, `OrderDay: 11`

---

# Question: What is the purpose of the `DATE_ADD()` function in MySQL?

**Answer:**
It adds a specified time interval to a date.

---

# Question: What is the syntax of the `DATE_ADD()` function?

**Answer:**
`DATE_ADD(date, INTERVAL expr type)`

---

# Question: What are valid types for `INTERVAL` in `DATE_ADD()`?

**Answer:**

* MICROSECOND
* SECOND
* MINUTE
* HOUR
* DAY
* WEEK
* MONTH
* QUARTER
* YEAR
* SECOND\_MICROSECOND
* MINUTE\_MICROSECOND
* MINUTE\_SECOND
* HOUR\_MICROSECOND
* HOUR\_SECOND
* HOUR\_MINUTE
* DAY\_MICROSECOND
* DAY\_SECOND
* DAY\_MINUTE
* DAY\_HOUR
* YEAR\_MONTH

---

# Question: Given an order date of `'2008-11-11 13:23:44.657'`, what is the result of:

```sql
SELECT OrderId, DATE_ADD(OrderDate, INTERVAL 45 DAY) AS OrderPayDate FROM Orders
```

**Answer:**
`OrderId: 1`, `OrderPayDate: 2008-12-26 13:23:44.657`

---

# Question: What does the `DATE_SUB()` function do in MySQL?

**Answer:**
It subtracts a specified time interval from a date.

---

# Question: What is the syntax of the `DATE_SUB()` function?

**Answer:**
`DATE_SUB(date, INTERVAL expr type)`

---

# Question: What interval types can be used with `DATE_SUB()`?

**Answer:**
Same as `DATE_ADD()`:
MICROSECOND, SECOND, MINUTE, HOUR, DAY, WEEK, MONTH, QUARTER, YEAR, and composite types like DAY\_HOUR, YEAR\_MONTH, etc.

---

# Question: What is the result of the following SQL query?

```sql
SELECT OrderId, DATE_SUB(OrderDate, INTERVAL 5 DAY) AS SubtractDate FROM Orders
```

Given `OrderDate = '2008-11-11 13:23:44.657'`
**Answer:**
`OrderId: 1`, `SubtractDate: 2008-11-06 13:23:44.657`

---

# Question: What does the `DATEDIFF()` function do in MySQL?

**Answer:**
It returns the number of days between two dates.

---

# Question: What is the syntax of the `DATEDIFF()` function?

**Answer:**
`DATEDIFF(date1, date2)`

---

# Question: Does `DATEDIFF()` consider the time portion of the date?

**Answer:**
No, it only considers the **date** parts.

---

# Question: What is the result of:

```sql
SELECT DATEDIFF('2008-11-30','2008-11-29') AS DiffDate
```

**Answer:**
`DiffDate: 1`

---

# Question: What is the result of:

```sql
SELECT DATEDIFF('2008-11-29','2008-11-30') AS DiffDate
```

**Answer:**
`DiffDate: -1`

---

# Question: What does the `DATE_FORMAT()` function do in MySQL?

**Answer:**
It formats a date value according to a specified format string.

---

# Question: What is the syntax for the `DATE_FORMAT()` function?

**Answer:**
`DATE_FORMAT(date, format)`

---

### 🔸 **`DATE_FORMAT` Placeholders**

| Format       | Description                                           |
| ------------ | ----------------------------------------------------- |
| `%a`         | Abbreviated weekday name                              |
| `%b`         | Abbreviated month name                                |
| `%c`         | Month, numeric                                        |
| `%D`         | Day of the month with English suffix (e.g., 1st, 2nd) |
| `%d`         | Day of month, 2-digit (00–31)                         |
| `%e`         | Day of month, numeric (0–31)                          |
| `%f`         | Microseconds                                          |
| `%H`         | Hour (00–23)                                          |
| `%h` or `%I` | Hour (01–12)                                          |
| `%i`         | Minutes (00–59)                                       |
| `%j`         | Day of year (001–366)                                 |
| `%k`         | Hour (0–23)                                           |
| `%l`         | Hour (1–12)                                           |
| `%M`         | Month name                                            |
| `%m`         | Month, numeric (00–12)                                |
| `%p`         | AM or PM                                              |
| `%r`         | 12-hour time (hh\:mm\:ss AM or PM)                    |
| `%S` or `%s` | Seconds (00–59)                                       |
| `%T`         | 24-hour time (hh\:mm\:ss)                             |
| `%U`         | Week (00–53), Sunday first                            |
| `%u`         | Week (00–53), Monday first                            |
| `%V`         | Week (01–53), used with `%X`                          |
| `%v`         | Week (01–53), used with `%x`                          |
| `%W`         | Weekday name                                          |
| `%w`         | Day of week (0=Sunday, 6=Saturday)                    |
| `%X`         | Year for week (Sunday start), 4-digit                 |
| `%x`         | Year for week (Monday start), 4-digit                 |
| `%Y`         | Year, four digits                                     |
| `%y`         | Year, two digits                                      |

---

# Question: What is the output of the following expression:

```sql
DATE_FORMAT(NOW(), '%b %d %Y %h:%i %p')
```

**Answer:**
Example output: `Nov 04 2008 11:45 PM`

---

# Question: What does this return?

```sql
DATE_FORMAT(NOW(), '%m-%d-%Y')
```

**Answer:**
`11-04-2008`

---

# Question: What does this return?

```sql
DATE_FORMAT(NOW(), '%d %b %y')
```

**Answer:**
`04 Nov 08`

---

# Question: What does this return?

```sql
DATE_FORMAT(NOW(), '%d %b %Y %T:%f')
```

**Answer:**
`04 Nov 2008 11:45:34:243000` (with microseconds)

---

















