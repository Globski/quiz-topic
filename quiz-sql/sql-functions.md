# Question: List some commonly used SQL keywords and their descriptions.

### SQL Keywords Reference

| Keyword                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| ADD                      | Adds a column in an existing table                                          |
| ADD CONSTRAINT           | Adds a constraint after a table is already created                          |
| ALL                      | Returns true if all of the subquery values meet the condition               |
| ALTER                    | Adds, deletes, or modifies columns in a table, or changes the data type     |
| ALTER COLUMN             | Changes the data type of a column in a table                                |
| ALTER TABLE              | Adds, deletes, or modifies columns in a table                               |
| AND                      | Only includes rows where both conditions is true                            |
| ANY                      | Returns true if any of the subquery values meet the condition               |
| AS                       | Renames a column or table with an alias                                     |
| ASC                      | Sorts the result set in ascending order                                     |
| BACKUP DATABASE          | Creates a back up of an existing database                                   |
| BETWEEN                  | Selects values within a given range                                         |
| CASE                     | Creates different outputs based on conditions                               |
| CHECK                    | A constraint that limits the value that can be placed in a column           |
| COLUMN                   | Changes the data type of a column or deletes a column in a table            |
| CONSTRAINT               | Adds or deletes a constraint                                                 |
| CREATE                   | Creates a database, index, view, table, or procedure                        |
| CREATE DATABASE          | Creates a new SQL database                                                  |
| CREATE INDEX             | Creates an index on a table (allows duplicate values)                       |
| CREATE OR REPLACE VIEW   | Updates a view                                                              |
| CREATE TABLE             | Creates a new table in the database                                         |
| CREATE PROCEDURE         | Creates a stored procedure                                                  |
| CREATE UNIQUE INDEX      | Creates a unique index on a table (no duplicate values)                     |
| CREATE VIEW              | Creates a view based on the result set of a SELECT statement                |
| DATABASE                 | Creates or deletes an SQL database                                          |
| DEFAULT                  | A constraint that provides a default value for a column                     |
| DELETE                   | Deletes rows from a table                                                   |
| DESC                     | Sorts the result set in descending order                                    |
| DISTINCT                 | Selects only distinct (different) values                                    |
| DROP                     | Deletes a column, constraint, database, index, table, or view               |
| DROP COLUMN              | Deletes a column in a table                                                 |
| DROP CONSTRAINT          | Deletes a UNIQUE, PRIMARY KEY, FOREIGN KEY, or CHECK constraint             |
| DROP DATABASE            | Deletes an existing SQL database                                            |
| DROP DEFAULT             | Deletes a DEFAULT constraint                                                |
| DROP INDEX               | Deletes an index in a table                                                 |
| DROP TABLE               | Deletes an existing table in the database                                   |
| DROP VIEW                | Deletes a view                                                              |
| EXEC                     | Executes a stored procedure                                                 |
| EXISTS                   | Tests for the existence of any record in a subquery                         |
| FOREIGN KEY              | A constraint that is a key used to link two tables together                 |
| FROM                     | Specifies which table to select or delete data from                         |
| FULL OUTER JOIN          | Returns all rows when there is a match in either left or right table        |
| GROUP BY                 | Groups the result set (used with aggregate functions)                       |
| HAVING                   | Used instead of WHERE with aggregate functions                              |
| IN                       | Allows you to specify multiple values in a WHERE clause                     |
| INDEX                    | Creates or deletes an index in a table                                      |
| INNER JOIN               | Returns rows that have matching values in both tables                       |
| INSERT INTO              | Inserts new rows in a table                                                 |
| INSERT INTO SELECT       | Copies data from one table into another table                               |
| IS NULL                  | Tests for empty values                                                      |
| IS NOT NULL              | Tests for non-empty values                                                  |
| JOIN                     | Joins tables                                                                |
| LEFT JOIN                | Returns all rows from the left table and matching rows from the right       |
| LIKE                     | Searches for a specified pattern in a column                                |
| LIMIT                    | Specifies the number of records to return in the result set                 |
| NOT                      | Only includes rows where a condition is not true                            |
| NOT NULL                 | A constraint that enforces a column to not accept NULL values               |
| OR                       | Includes rows where either condition is true                                |
| ORDER BY                 | Sorts the result set in ascending or descending order                       |
| OUTER JOIN               | Returns all rows when there is a match in either left or right table        |
| PRIMARY KEY              | A constraint that uniquely identifies each record in a table                |
| PROCEDURE                | A stored procedure                                                          |
| RIGHT JOIN               | Returns all rows from the right table and matching rows from the left       |
| ROWNUM                   | Specifies the number of records to return in the result set                 |
| SELECT                   | Selects data from a database                                                |
| SELECT DISTINCT          | Selects only distinct (different) values                                    |
| SELECT INTO              | Copies data from one table into a new table                                 |
| SELECT TOP               | Specifies the number of records to return in the result set                 |
| SET                      | Specifies which columns and values that should be updated in a table        |
| TABLE                    | Creates, modifies, or deletes a table or its columns/data                   |
| TOP                      | Specifies the number of records to return in the result set                 |
| TRUNCATE TABLE           | Deletes the data inside a table, but not the table itself                   |
| UNION                    | Combines result sets of two or more SELECT statements (distinct values)     |
| UNION ALL                | Combines result sets of two or more SELECT statements (allows duplicates)   |
| UNIQUE                   | A constraint that ensures all values in a column are unique                 |
| UPDATE                   | Updates existing rows in a table                                            |
| VALUES                   | Specifies the values of an INSERT INTO statement                            |
| VIEW                     | Creates, updates, or deletes a view                                         |
| WHERE                    | Filters a result set based on specified conditions                          |


---

# SQL Statements & Syntax Reference

| SQL Statement     | Syntax                                                                                           |
|-------------------|--------------------------------------------------------------------------------------------------|
| **AND / OR**      | SELECT column_name(s)<br>FROM table_name<br>WHERE condition AND/OR condition                     |
| **ALTER TABLE**   | ALTER TABLE table_name ADD column_name datatype<br>ALTER TABLE table_name DROP COLUMN column_name|
| **AS (alias)**    | SELECT column_name AS column_alias FROM table_name<br>SELECT column_name FROM table_name AS alias|
| **BETWEEN**       | SELECT column_name(s) FROM table_name WHERE column_name BETWEEN value1 AND value2               |
| **CREATE DATABASE** | CREATE DATABASE database_name                                                                  |
| **CREATE TABLE**  | CREATE TABLE table_name (<br>column_name1 data_type,<br>column_name2 data_type,<br>...)          |
| **CREATE INDEX**  | CREATE INDEX index_name ON table_name (column_name)<br>CREATE UNIQUE INDEX index_name ON table_name (column_name) |
| **CREATE VIEW**   | CREATE VIEW view_name AS SELECT column_name(s) FROM table_name WHERE condition                  |
| **DELETE**        | DELETE FROM table_name WHERE some_column = some_value<br>DELETE FROM table_name<br>DELETE * FROM table_name |
| **DROP DATABASE** | DROP DATABASE database_name                                                                      |
| **DROP INDEX**    | DROP INDEX table_name.index_name (SQL Server)<br>DROP INDEX index_name ON table_name (MS Access)<br>DROP INDEX index_name (DB2/Oracle)<br>ALTER TABLE table_name DROP INDEX index_name (MySQL) |
| **DROP TABLE**    | DROP TABLE table_name                                                                            |
| **EXISTS**        | IF EXISTS (SELECT * FROM table_name WHERE id = ?)<br>BEGIN ... END<br>ELSE BEGIN ... END         |
| **GROUP BY**      | SELECT column_name, aggregate_function(column_name)<br>FROM table_name<br>WHERE condition<br>GROUP BY column_name |
| **HAVING**        | SELECT column_name, aggregate_function(column_name)<br>FROM table_name<br>WHERE condition<br>GROUP BY column_name<br>HAVING aggregate_function(column_name) operator value |
| **IN**            | SELECT column_name(s) FROM table_name WHERE column_name IN (value1, value2, ...)                |
| **INSERT INTO**   | INSERT INTO table_name VALUES (value1, value2, ...)<br>INSERT INTO table_name (col1, col2, ...) VALUES (val1, val2, ...) |
| **INNER JOIN**    | SELECT column_name(s) FROM table_name1 INNER JOIN table_name2 ON table1.column = table2.column  |
| **LEFT JOIN**     | SELECT column_name(s) FROM table_name1 LEFT JOIN table_name2 ON table1.column = table2.column   |
| **RIGHT JOIN**    | SELECT column_name(s) FROM table_name1 RIGHT JOIN table_name2 ON table1.column = table2.column  |
| **FULL JOIN**     | SELECT column_name(s) FROM table_name1 FULL JOIN table_name2 ON table1.column = table2.column   |
| **LIKE**          | SELECT column_name(s) FROM table_name WHERE column_name LIKE pattern                            |
| **ORDER BY**      | SELECT column_name(s) FROM table_name ORDER BY column_name [ASC|DESC]                           |
| **SELECT**        | SELECT column_name(s) FROM table_name                                                           |
| **SELECT \***     | SELECT * FROM table_name                                                                         |
| **SELECT DISTINCT** | SELECT DISTINCT column_name(s) FROM table_name                                                 |
| **SELECT INTO**   | SELECT * INTO new_table_name [IN externaldatabase] FROM old_table_name<br>SELECT column_name(s) INTO new_table_name [IN externaldatabase] FROM old_table_name |
| **SELECT TOP**    | SELECT TOP number|percent column_name(s) FROM table_name                                        |
| **TRUNCATE TABLE**| TRUNCATE TABLE table_name                                                                        |
| **UNION**         | SELECT column_name(s) FROM table_name1 UNION SELECT column_name(s) FROM table_name2             |
| **UNION ALL**     | SELECT column_name(s) FROM table_name1 UNION ALL SELECT column_name(s) FROM table_name2         |
| **UPDATE**        | UPDATE table_name SET column1 = value1, column2 = value2, ... WHERE some_column = some_value     |
| **WHERE**         | SELECT column_name(s) FROM table_name WHERE column_name operator value                          |

---

# Question: List some commonly used MySQL functions grouped by their category.

### MySQL String Functions

| Function            | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| ASCII               | Returns the ASCII value for the specific character                         |
| CHAR_LENGTH         | Returns the length of a string (in characters)                             |
| CHARACTER_LENGTH    | Returns the length of a string (in characters)                             |
| CONCAT              | Adds two or more expressions together                                      |
| CONCAT_WS           | Adds two or more expressions together with a separator                     |
| FIELD               | Returns the index position of a value in a list of values                  |
| FIND_IN_SET         | Returns the position of a string within a list of strings                  |
| FORMAT              | Formats a number to a format like "#,###,###.##", rounded as specified     |
| INSERT              | Inserts a string within a string at the specified position                 |
| INSTR               | Returns the position of the first occurrence of a string in another string |
| LCASE               | Converts a string to lower-case                                            |
| LEFT                | Extracts characters from the left side of a string                         |
| LENGTH              | Returns the length of a string (in bytes)                                  |
| LOCATE              | Returns the position of the first occurrence of a substring                |
| LOWER               | Converts a string to lower-case                                            |
| LPAD                | Left-pads a string to a certain length                                     |
| LTRIM               | Removes leading spaces from a string                                       |
| MID                 | Extracts a substring from a string                                         |
| POSITION            | Returns the position of a substring in a string                            |
| REPEAT              | Repeats a string a specified number of times                               |
| REPLACE             | Replaces all occurrences of a substring within a string                    |
| REVERSE             | Reverses a string                                                          |
| RIGHT               | Extracts characters from the right side of a string                        |
| RPAD                | Right-pads a string to a certain length                                    |
| RTRIM               | Removes trailing spaces from a string                                      |
| SPACE               | Returns a string with a specified number of spaces                         |
| STRCMP              | Compares two strings                                                       |
| SUBSTR              | Extracts a substring from a string                                         |
| SUBSTRING           | Extracts a substring from a string                                         |
| SUBSTRING_INDEX     | Returns a substring before a specified number of delimiter occurrences     |
| TRIM                | Removes leading and trailing spaces from a string                          |
| UCASE               | Converts a string to upper-case                                            |
| UPPER               | Converts a string to upper-case                                            |

---

### MySQL Numeric Functions

| Function    | Description                                                                      |
|-------------|----------------------------------------------------------------------------------|
| ABS         | Returns the absolute value of a number                                           |
| ACOS        | Returns the arc cosine of a number                                               |
| ASIN        | Returns the arc sine of a number                                                 |
| ATAN        | Returns the arc tangent of one or two numbers                                    |
| ATAN2       | Returns the arc tangent of two numbers                                           |
| AVG         | Returns the average value of an expression                                       |
| CEIL        | Returns the smallest integer >= the number                                       |
| CEILING     | Same as CEIL                                                                     |
| COS         | Returns the cosine of a number                                                   |
| COT         | Returns the cotangent of a number                                                |
| COUNT       | Returns the number of records returned                                           |
| DEGREES     | Converts radians to degrees                                                      |
| DIV         | Performs integer division                                                        |
| EXP         | Returns e raised to the power of a number                                        |
| FLOOR       | Returns the largest integer <= the number                                        |
| GREATEST    | Returns the greatest value in a list                                             |
| LEAST       | Returns the smallest value in a list                                             |
| LN          | Returns the natural logarithm of a number                                        |
| LOG         | Returns the natural log or log to a specific base                                |
| LOG10       | Returns the log base 10 of a number                                              |
| LOG2        | Returns the log base 2 of a number                                               |
| MAX         | Returns the maximum value in a set                                               |
| MIN         | Returns the minimum value in a set                                               |
| MOD         | Returns the remainder of division                                                |
| PI          | Returns the value of π                                                           |
| POW         | Raises a number to the power of another                                          |
| POWER       | Same as POW                                                                      |
| RADIANS     | Converts degrees to radians                                                      |
| RAND        | Returns a random number                                                          |
| ROUND       | Rounds a number to a specified number of decimal places                          |
| SIGN        | Returns the sign of a number                                                     |
| SIN         | Returns the sine of a number                                                     |
| SQRT        | Returns the square root                                                          |
| SUM         | Returns the sum of values                                                        |
| TAN         | Returns the tangent of a number                                                  |
| TRUNCATE    | Truncates a number to specified decimal places                                   |

---

### MySQL Date Functions

| Function         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| ADDDATE          | Adds a time/date interval to a date                                         |
| ADDTIME          | Adds a time interval to a time/datetime                                     |
| CURDATE          | Returns the current date                                                    |
| CURRENT_DATE     | Returns the current date                                                    |
| CURRENT_TIME     | Returns the current time                                                    |
| CURRENT_TIMESTAMP| Returns the current date and time                                           |
| CURTIME          | Returns the current time                                                    |
| DATE             | Extracts the date part of a datetime expression                             |
| DATEDIFF         | Returns the days between two dates                                          |
| DATE_ADD         | Adds a time/date interval to a date                                         |
| DATE_FORMAT      | Formats a date                                                              |
| DATE_SUB         | Subtracts a time/date interval from a date                                  |
| DAY              | Returns the day of the month                                                |
| DAYNAME          | Returns the weekday name                                                    |
| DAYOFMONTH       | Returns the day of the month                                                |
| DAYOFWEEK        | Returns the weekday index                                                   |
| DAYOFYEAR        | Returns the day of the year                                                 |
| EXTRACT          | Extracts part of a date                                                     |
| FROM_DAYS        | Returns a date from a numeric date value                                    |
| HOUR             | Returns the hour part                                                       |
| LAST_DAY         | Returns the last day of the month                                           |
| LOCALTIME        | Returns the current date and time                                           |
| LOCALTIMESTAMP   | Returns the current date and time                                           |
| MAKEDATE         | Returns a date based on year and days value                                 |
| MAKETIME         | Returns a time based on hour, minute, second                                |
| MICROSECOND      | Returns microsecond part of time/datetime                                   |
| MINUTE           | Returns minute part                                                         |
| MONTH            | Returns month part                                                          |
| MONTHNAME        | Returns name of the month                                                   |
| NOW              | Returns current date and time                                               |
| PERIOD_ADD       | Adds months to a period                                                     |
| PERIOD_DIFF      | Returns difference between two periods                                      |
| QUARTER          | Returns the quarter of the year                                             |
| SECOND           | Returns seconds part                                                        |
| SEC_TO_TIME      | Converts seconds to time                                                    |
| STR_TO_DATE      | Returns a date based on string and format                                   |
| SUBDATE          | Subtracts a time/date interval from a date                                  |
| SUBTIME          | Subtracts a time interval from datetime                                     |
| SYSDATE          | Returns current date and time                                               |
| TIME             | Extracts time part from datetime                                             |
| TIME_FORMAT      | Formats a time                                                              |
| TIME_TO_SEC      | Converts time to seconds                                                    |
| TIMEDIFF         | Returns difference between two datetime values                              |
| TIMESTAMP        | Returns datetime based on date or datetime input                            |
| TO_DAYS          | Returns number of days since '0000-00-00'                                   |
| WEEK             | Returns week number of the year                                             |
| WEEKDAY          | Returns weekday number (0 = Monday)                                         |
| WEEKOFYEAR       | Returns the week number of the year                                         |
| YEAR             | Returns the year part                                                       |
| YEARWEEK         | Returns year and week number                                                |

---

### MySQL Advanced Functions

| Function         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| BIN              | Returns binary representation of a number                                  |
| BINARY           | Converts a value to a binary string                                         |
| CASE             | Returns value based on condition logic                                      |
| CAST             | Converts a value to a specified data type                                   |
| COALESCE         | Returns first non-null value in a list                                      |
| CONNECTION_ID    | Returns the current connection ID                                           |
| CONV             | Converts a number from one base to another                                  |
| CONVERT          | Converts a value to a specified data type or character set                  |
| CURRENT_USER     | Returns the MySQL account name and host for the current client              |
| DATABASE         | Returns name of the current database                                        |
| IF               | Returns one value if condition is TRUE, another if FALSE                   |
| IFNULL           | Returns alternate value if expression is NULL                              |
| ISNULL           | Returns 1 if expression is NULL, 0 otherwise                                |
| LAST_INSERT_ID   | Returns the last AUTO_INCREMENT value                                       |
| NULLIF           | Returns NULL if two expressions are equal                                   |
| SESSION_USER     | Returns the current MySQL user name and host name                           |
| SYSTEM_USER      | Returns the current MySQL user name and host name                           |
| USER             | Returns the current MySQL user name and host name                           |
| VERSION          | Returns the current MySQL server version                                    |


---

# Question: List some commonly used SQL Server functions grouped by their category.

### SQL Server String Functions

| Function        | Description                                                                                         |
|-----------------|-----------------------------------------------------------------------------------------------------|
| ASCII           | Returns the ASCII value for the specific character                                                  |
| CHAR            | Returns the character based on the ASCII code                                                       |
| CHARINDEX       | Returns the position of a substring in a string                                                     |
| CONCAT          | Adds two or more strings together                                                                   |
| Concat with +   | Adds two or more strings together                                                                   |
| CONCAT_WS       | Adds two or more strings together with a separator                                                  |
| DATALENGTH      | Returns the number of bytes used to represent an expression                                         |
| DIFFERENCE      | Compares two SOUNDEX values and returns an integer                                                  |
| FORMAT          | Formats a value with the specified format                                                           |
| LEFT            | Extracts a number of characters from a string (starting from left)                                  |
| LEN             | Returns the length of a string                                                                      |
| LOWER           | Converts a string to lower-case                                                                     |
| LTRIM           | Removes leading spaces from a string                                                                |
| NCHAR           | Returns the Unicode character based on the number code                                              |
| PATINDEX        | Returns the position of a pattern in a string                                                       |
| QUOTENAME       | Returns a Unicode string with delimiters for a valid SQL Server identifier                          |
| REPLACE         | Replaces all occurrences of a substring with a new substring                                       |
| REPLICATE       | Repeats a string a specified number of times                                                       |
| REVERSE         | Reverses a string and returns the result                                                            |
| RIGHT           | Extracts a number of characters from a string (starting from right)                                |
| RTRIM           | Removes trailing spaces from a string                                                               |
| SOUNDEX         | Returns a 4-character code to evaluate string similarity                                            |
| SPACE           | Returns a string with the specified number of space characters                                      |
| STR             | Returns a number as string                                                                          |
| STUFF           | Deletes part of a string and inserts another at a specified position                                |
| SUBSTRING       | Extracts some characters from a string                                                              |
| TRANSLATE       | Replaces characters in a string using a mapping                                                     |
| TRIM            | Removes leading and trailing (or specified) characters from a string                               |
| UNICODE         | Returns the Unicode value of the first character in a string                                        |
| UPPER           | Converts a string to upper-case                                                                     |

---

### SQL Server Math/Numeric Functions

| Function    | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| ABS         | Returns the absolute value of a number                                     |
| ACOS        | Returns the arc cosine of a number                                         |
| ASIN        | Returns the arc sine of a number                                           |
| ATAN        | Returns the arc tangent of a number                                        |
| ATN2        | Returns the arc tangent of two numbers                                     |
| AVG         | Returns the average value of an expression                                 |
| CEILING     | Returns the smallest integer value that is >= a number                     |
| COUNT       | Returns the number of records returned by a query                          |
| COS         | Returns the cosine of a number                                             |
| COT         | Returns the cotangent of a number                                          |
| DEGREES     | Converts radians to degrees                                                |
| EXP         | Returns e raised to the power of a number                                  |
| FLOOR       | Returns the largest integer <= to a number                                 |
| LOG         | Returns the natural logarithm or logarithm to specified base               |
| LOG10       | Returns the base-10 logarithm of a number                                  |
| MAX         | Returns the maximum value in a set                                         |
| MIN         | Returns the minimum value in a set                                         |
| PI          | Returns the value of π                                                     |
| POWER       | Raises a number to the power of another                                    |
| RADIANS     | Converts degrees to radians                                                |
| RAND        | Returns a random number                                                    |
| ROUND       | Rounds a number to a specified number of decimal places                    |
| SIGN        | Returns the sign of a number                                               |
| SIN         | Returns the sine of a number                                               |
| SQRT        | Returns the square root of a number                                        |
| SQUARE      | Returns the square of a number                                             |
| SUM         | Calculates the sum of values                                               |
| TAN         | Returns the tangent of a number                                            |

---

### SQL Server Date Functions

| Function         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| CURRENT_TIMESTAMP| Returns the current date and time                                           |
| DATEADD          | Adds a date/time interval to a date                                         |
| DATEDIFF         | Returns the difference between two dates                                    |
| DATEFROMPARTS    | Returns a date from year, month, and day parts                              |
| DATENAME         | Returns a specified part of a date (as string)                              |
| DATEPART         | Returns a specified part of a date (as integer)                             |
| DAY              | Returns the day of the month for a given date                               |
| GETDATE          | Returns the current system date and time                                    |
| GETUTCDATE       | Returns the current system UTC date and time                                |
| ISDATE           | Checks if an expression is a valid date                                     |
| MONTH            | Returns the month part for a given date                                     |
| SYSDATETIME      | Returns the current system date and time with precision                     |
| YEAR             | Returns the year part for a given date                                      |

---

### SQL Server Advanced Functions

| Function         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| CAST             | Converts a value to a specified datatype                                    |
| COALESCE         | Returns the first non-null value in a list                                  |
| CONVERT          | Converts a value to a specified datatype                                    |
| CURRENT_USER     | Returns the name of the current user in the database                        |
| IIF              | Returns a value if a condition is TRUE, otherwise another value             |
| ISNULL           | Returns a specified value if the expression is NULL                         |
| ISNUMERIC        | Returns 1 if expression is numeric, 0 otherwise                             |
| NULLIF           | Returns NULL if two expressions are equal                                   |
| SESSION_USER     | Returns the name of the current user in the database                        |
| SESSIONPROPERTY  | Returns session settings for a specified option                             |
| SYSTEM_USER      | Returns the login name of the current user                                  |
| USER_NAME        | Returns the database user name based on a given ID                          |

---

# 🧵 MS Access String Functions

| Function   | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| Asc        | Returns the ASCII value for the specific character                         |
| Chr        | Returns the character for the specified ASCII number code                  |
| Concat with & | Adds two or more strings together                                       |
| CurDir     | Returns the full path for a specified drive                                |
| Format     | Formats a value with the specified format                                  |
| InStr      | Gets the position of the first occurrence of a string in another           |
| InstrRev   | Gets the position of the first occurrence of a string in another, from end |
| LCase      | Converts a string to lower-case                                            |
| Left       | Extracts a number of characters from a string (from left)                  |
| Len        | Returns the length of a string                                             |
| LTrim      | Removes leading spaces from a string                                       |
| Mid        | Extracts characters from a string (starting at any position)               |
| Replace    | Replaces a substring within a string                                       |
| Right      | Extracts characters from a string (from right)                             |
| RTrim      | Removes trailing spaces from a string                                      |
| Space      | Returns a string of the specified number of space characters               |
| Split      | Splits a string into an array of substrings                                |
| Str        | Returns a number as a string                                               |
| StrComp    | Compares two strings                                                       |
| StrConv    | Returns a converted string                                                 |
| StrReverse | Reverses a string and returns the result                                   |
| Trim       | Removes both leading and trailing spaces                                   |
| UCase      | Converts a string to upper-case                                            |


---

### MS Access Numeric Functions

| Function    | Description                                                             |
|-------------|-------------------------------------------------------------------------|
| Abs         | Returns the absolute value of a number                                  |
| Atn         | Returns the arc tangent of a number                                     |
| Avg         | Returns the average value of an expression                              |
| Cos         | Returns the cosine of an angle                                          |
| Count       | Returns the number of records returned by a select query               |
| Exp         | Returns e raised to the power of a specified number                     |
| Fix         | Returns the integer part of a number                                    |
| Format      | Formats a numeric value with the specified format                       |
| Int         | Returns the integer part of a number                                    |
| Max         | Returns the maximum value in a set of values                            |
| Min         | Returns the minimum value in a set of values                            |
| Randomize   | Initializes the random number generator                                 |
| Rnd         | Returns a random number                                                 |
| Round       | Rounds a number to a specified number of decimal places                 |
| Sgn         | Returns the sign of a number                                            |
| Sqr         | Returns the square root of a number                                     |
| Sum         | Calculates the sum of a set of values                                   |
| Val         | Reads a string and returns the numbers found in the string              |

---

### 📅 MS Access Date Functions

| Function     | Description                                                              |
|--------------|--------------------------------------------------------------------------|
| Date         | Returns the current system date                                          |
| DateAdd      | Adds a time/date interval to a date and then returns the date            |
| DateDiff     | Returns the difference between two dates                                 |
| DatePart     | Returns a specified part of a date (as an integer)                       |
| DateSerial   | Returns a date from the specified parts (year, month, and day)           |
| DateValue    | Returns a date based on a string                                         |
| Day          | Returns the day of the month for a given date                            |
| Format       | Formats a date value with the specified format                           |
| Hour         | Returns the hour part of a time/datetime                                 |
| Minute       | Returns the minute part of a time/datetime                               |
| Month        | Returns the month part of a given date                                   |
| MonthName    | Returns the name of the month based on a number                          |
| Now          | Returns the current date and time                                        |
| Second       | Returns the seconds part of a time/datetime                              |
| Time         | Returns the current system time                                          |
| TimeSerial   | Returns a time from the specified parts (hour, minute, second)           |
| TimeValue    | Returns a time based on a string                                         |
| Weekday      | Returns the weekday number for a given date                              |
| WeekdayName  | Returns the weekday name based on a number                               |
| Year         | Returns the year part of a given date                                    |

---

### 🧩 MS Access Other Functions

| Function      | Description                                                          |
|---------------|----------------------------------------------------------------------|
| CurrentUser   | Returns the name of the current database user                        |
| Environ       | Returns the value of an OS environment variable                      |
| IsDate        | Checks whether an expression can be converted to a date              |
| IsNull        | Checks whether an expression contains Null (no data)                 |
| IsNumeric     | Checks whether an expression is a valid number                       |

---
