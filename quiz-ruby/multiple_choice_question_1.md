# Question: What class in Ruby is used to represent date and time?

**Answer:** The `Time` class.

---

# Question: How do you get the current time using the Time class?

**Answer:** `Time.new` or `Time.now`.

---

# Question: Are `Time.new` and `Time.now` functionally different?

**Answer:** No, `Time.now` is a synonym for `Time.new`.

---

# Question: Which method returns the year from a Time object?

**Answer:** `time.year`

# Question: Which method returns the month (1–12) from a Time object?

**Answer:** `time.month`

---

# Question: What method returns the day of the month (1–31)?

**Answer:** `time.day`

---

# Question: How do you retrieve the day of the week from a Time object?

**Answer:** `time.wday` (Sunday = 0)

---

# Question: What does `time.yday` return?

**Answer:** The day of the year (1–366)

---

# Question: Which method gets the hour (0–23)?

**Answer:** `time.hour`

---

# Question: How do you retrieve the minutes from a Time object?

**Answer:** `time.min`

---

# Question: Which method returns the number of seconds (0–59)?

**Answer:** `time.sec`

---

# Question: What method retrieves microseconds from a Time object?

**Answer:** `time.usec`

---

# Question: Which method returns the time zone abbreviation?

**Answer:** `time.zone`

---

# Question: How do you create a local time for July 8, 2008?

**Answer:** `Time.local(2008, 7, 8)`

---

# Question: What does `Time.local(2008, 7, 8, 9, 10)` return?

**Answer:** A Time object for July 8, 2008 at 09:10 local time.

---

# Question: How do you create a UTC time object for July 8, 2008 at 09:10?

**Answer:** `Time.utc(2008, 7, 8, 9, 10)`

---

# Question: What is the difference between `Time.gm` and `Time.utc`?

**Answer:** None; both return GMT/UTC time.

---

# Question: What does `time.to_a` return?

**Answer:** An array in the format: `[sec, min, hour, day, month, year, wday, yday, isdst, zone]`

---

# Question: How can you reconstruct a Time object from an array?

**Answer:** Use `Time.utc(*values)` or `Time.local(*values)`

---

# Question: What does `Time.now.to_i` return?

**Answer:** Number of seconds since the epoch.

---

# Question: How do you convert seconds back into a Time object?

**Answer:** `Time.at(seconds)`

---

# Question: What is returned by `Time.now.to_f`?

**Answer:** Seconds since epoch including microseconds (as a float).

---

# Question: What does `time.zone` return?

**Answer:** The timezone name (e.g., "UTC", "PST").

---

# Question: What is returned by `time.utc_offset`?

**Answer:** The offset in seconds from UTC.

---

# Question: What does `time.isdst` indicate?

**Answer:** Whether daylight savings time is in effect (`true` or `false`).

---

# Question: How do you check if a Time object is in UTC?

**Answer:** `time.utc?`

---

# Question: Which method converts a Time object to local time?

**Answer:** `time.localtime`

---

# Question: Which method converts a Time object back to UTC?

**Answer:** `time.gmtime`

---

# Question: How do you get a new Time object in the local timezone?

**Answer:** `time.getlocal`

---

# Question: How do you get a new Time object in UTC?

**Answer:** `time.getutc`

---

# Question: What does `time.to_s` return?

**Answer:** String representation of the time.

---

# Question: What is the output of `time.ctime`?

**Answer:** A human-readable string, e.g., `"Mon Jun 2 12:35:19 2008"`

---

# Question: How do you format time using `strftime`?

**Answer:** Use formatting directives like `time.strftime("%Y-%m-%d %H:%M:%S")`

---

# Question: What does `%a` represent in `strftime`?

**Answer:** Abbreviated weekday name (e.g., "Sun").

---

# Question: What does `%A` represent?

**Answer:** Full weekday name (e.g., "Sunday").

---

# Question: What does `%b` return?

**Answer:** Abbreviated month name (e.g., "Jan").

---

# Question: What does `%B` return?

**Answer:** Full month name (e.g., "January").

---

# Question: What does `%c` return?

**Answer:** Preferred local date and time representation.

---

# Question: What does `%d` stand for in date formatting?

**Answer:** Day of the month (01 to 31).

---

# Question: What does `%H` return?

**Answer:** Hour using 24-hour clock (00 to 23).

---

# Question: What does `%I` return?

**Answer:** Hour using 12-hour clock (01 to 12).

---

# Question: What does `%j` represent?

**Answer:** Day of the year (001 to 366).

---

# Question: What does `%m` return?

**Answer:** Month (01 to 12).

---

# Question: What does `%M` stand for?

**Answer:** Minute (00 to 59).

---

# Question: What is `%p` used for?

**Answer:** Meridian indicator (AM or PM).

---

# Question: What does `%S` return?

**Answer:** Seconds (00 to 60).

---

# Question: What does `%U` represent?

**Answer:** Week number of the year (first Sunday = first week).

---

# Question: What does `%W` represent?

**Answer:** Week number of the year (first Monday = first week).

---

# Question: What does `%w` return?

**Answer:** Day of the week (0 = Sunday to 6 = Saturday).

---

# Question: What is `%x` used for?

**Answer:** Date only (preferred format).

---

# Question: What is `%X` used for?

**Answer:** Time only (preferred format).

---

# Question: What does `%y` return?

**Answer:** Year without century (00–99).

---

# Question: What does `%Y` return?

**Answer:** Full year with century.

---

# Question: What does `%Z` return?

**Answer:** Timezone name.

---

# Question: What does `%%` represent in `strftime`?

**Answer:** A literal percent character.

---

# Question: What happens when you subtract a number from a Time object?

**Answer:** Returns a new Time object that many seconds earlier.

---

# Question: What happens when you add a number to a Time object?

**Answer:** Returns a new Time object that many seconds later.

---

# Question: What is returned when you subtract one Time object from another?

**Answer:** A float representing the number of seconds between the two times.

---

# Question: What are some common real-world examples of ranges?

**Answer:** January to December, 0 to 9, and lines 50 through 67.

---

# Question: What are the three main ways Ruby uses ranges?

**Answer:** Ranges as sequences, ranges as conditions, and ranges as intervals.

---

# Question: What operators does Ruby use to create ranges?

**Answer:** Ruby uses `..` for inclusive ranges and `...` for exclusive ranges.

---

# Question: What is the output of the range `(1..5)`?

**Answer:** 1, 2, 3, 4, 5

---

# Question: What is the output of the range `(1...5)`?

**Answer:** 1, 2, 3, 4

---

# Question: What is the output of the range `('a'..'d')`?

**Answer:** 'a', 'b', 'c', 'd'

---


# Question: What class does Ruby use to represent a range like `1..100`?

**Answer:** Range object.

---

# Question: How can you convert a range into an array in Ruby?

**Answer:** Use the `to_a` method.

---

# Question: What does the following code return: `(1..10).to_a`?

**Answer:** `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`

---

# Question: What does the following code return: `('bar'..'bat').to_a`?

**Answer:** `["bar", "bas", "bat"]`

---

# Question: What does the method `include?` do on a range?

**Answer:** It checks if a value exists within the range.

---

# Question: What is the result of `digits.include?(5)` when `digits = 0..9`?

**Answer:** `true`

---

# Question: What method retrieves the smallest value in a range?

**Answer:** `min`

---

# Question: What method retrieves the largest value in a range?

**Answer:** `max`

---

# Question: What does the method `reject` do on a range?

**Answer:** It filters out elements that meet the specified condition.

---

# Question: What is the output of `digits.reject { |i| i < 5 }` when `digits = 0..9`?

**Answer:** `[5, 6, 7, 8, 9]`

---

# Question: How can you iterate over all elements in a range?

**Answer:** Use the `.each` method.

---

# Question: What output does the code `digits.each do |digit| puts "In Loop #{digit}" end` produce for `digits = 0..9`?

**Answer:**

```
In Loop 0
In Loop 1
In Loop 2
In Loop 3
In Loop 4
In Loop 5
In Loop 6
In Loop 7
In Loop 8
In Loop 9
```

---

# Question: How can ranges be used in conditional expressions?

**Answer:** Using range operators (`..`) to determine if a condition holds between two values.

---

# Question: What does the expression `print if /start/../end/` do inside a `while gets` loop?

**Answer:** It prints all lines from the input starting with a line matching "start" until a line matching "end".

---

# Question: How are ranges used in a `case` statement?

**Answer:** To match values against specific intervals.

---

# Question: What will be printed when `score = 70` is matched against:

```ruby
case score
when 0..40 then "Fail"
when 41..60 then "Pass"
when 61..70 then "Pass with Merit"
when 71..100 then "Pass with Distinction"
else "Invalid Score"
end
```

**Answer:** `Pass with Merit`

---

# Question: What operator is used in Ruby to test if a value falls within a range?

**Answer:** `===` (case equality operator)

---

# Question: What is the result of `((1..10) === 5)`?

**Answer:** `true`

---

# Question: What is the result of `(('a'..'j') === 'c')`?

**Answer:** `true`

---

# Question: What is the result of `(('a'..'j') === 'z')`?

**Answer:** `false`

---

# Question: What are iterators in Ruby?

**Answer:** Iterators are methods supported by collections, used to return all elements of a collection one after the other.

---

# Question: What types of objects in Ruby are typically considered collections?

**Answer:** Arrays and hashes.

---

# Question: What does the `each` iterator do in Ruby?

**Answer:** It executes a block of code for each element in a collection, returning each element one by one.

---

# Question: What is the syntax for using the `each` iterator with a block?

**Answer:**

```ruby
collection.each do |variable|
   code
end
```

---

# Question: In the `each` iterator, what role does the variable play inside the block?

**Answer:** It holds the value of each element during the iteration.

---

# Question: What will the following code output?

```ruby
ary = [1,2,3,4,5]
ary.each do |i|
   puts i
end
```

**Answer:**

```
1
2
3
4
5
```

---

# Question: What iterator in Ruby can be used to apply a transformation to every element and return a new collection?

**Answer:** The `collect` iterator.

---

# Question: Is the `collect` iterator required to use a block?

**Answer:** No, `collect` does not need to be associated with a block.

---

# Question: What will the following code output?

```ruby
a = [1,2,3,4,5]
b = a.collect
puts b
```

**Answer:**

```
1
2
3
4
5
```

---

# Question: What method should be used to copy an array in Ruby instead of `collect`?

**Answer:** The `clone` method.

---

# Question: When is `collect` typically used?

**Answer:** When you want to transform or manipulate each value in a collection to produce a new array.

---

# Question: What will the following code output?

```ruby
a = [1,2,3,4,5]
b = a.collect { |x| 10 * x }
puts b
```

**Answer:**

```
10
20
30
40
50
```

---

# Question: What does DBI stand for in Ruby and what is its main purpose?

**Answer:** DBI stands for Database Independent Interface. It provides an abstraction layer between Ruby code and the underlying database, allowing easy switching of database implementations.

---

# Question: What are the two main layers of Ruby DBI architecture?

**Answer:** The DBI layer (database-independent interface) and the DBD layer (database-dependent driver).

---

# Question: What is the role of the DBI layer in Ruby DBI architecture?

**Answer:** The DBI layer provides common access methods that are used the same way across different database systems.

---

# Question: What is the function of the DBD layer in Ruby DBI?

**Answer:** The DBD layer interprets DBI requests and maps them to specific commands for the underlying database engine.

---

# Question: List any five database systems supported by Ruby DBI.

**Answer:** MySQL, PostgreSQL, Oracle, SQLite, ODBC.

---

# Question: What must be installed to access MySQL databases using Ruby?

**Answer:** The Ruby MySQL module, which acts as a DBD.

---

# Question: What is the command to install the Ruby DBI module using RubyGems?

**Answer:** `gem install dbi`

---

# Question: What command is used to extract the DBI tarball?

**Answer:** `tar zxf dbi-0.2.0.tar.gz`

---

# Question: What is the command to configure the DBI distribution with all drivers?

**Answer:** `ruby setup.rb config`

---

# Question: How do you configure the DBI setup for only the DBI module and MySQL driver?

**Answer:** `ruby setup.rb config --with = dbi,dbd_mysql`

---

# Question: What are the commands to build and install DBI after configuration?

**Answer:**

```bash
ruby setup.rb setup  
ruby setup.rb install  
```

---

# Question: What is the Ruby code to connect to a MySQL database named TESTDB using DBI?

**Answer:** `DBI.connect("DBI:Mysql:TESTDB:localhost", "testuser", "test123")`

---

# Question: What does `select_one("SELECT VERSION()")` return in Ruby DBI?

**Answer:** It returns the first row from the result set of the query, such as the server version string.

---

# Question: What is returned if the connection to the database fails?

**Answer:** `dbh` is set to `nil`, and error details can be retrieved using `e.err` and `e.errstr`.

---

# Question: What is the purpose of `dbh.disconnect` in a DBI script?

**Answer:** It closes the connection to the database and releases associated resources.

---

# Question: What does the `do` method in Ruby DBI do?

**Answer:** It executes a SQL statement that does not return rows and returns the count of affected rows.

---

# Question: Which SQL commands can be executed using the `do` method?

**Answer:** Commands like `DROP`, `CREATE`, `INSERT`, `UPDATE`, and `DELETE`.

---

# Question: What method must be called after an `INSERT` to save the changes?

**Answer:** `dbh.commit`

---

# Question: What is the difference between `do` and `prepare/execute` in Ruby DBI?

**Answer:** `do` is used for one-time SQL commands, while `prepare/execute` is used for repeated or parameterized SQL operations.

---

# Question: What is the syntax to prepare and execute an INSERT with bind values?

**Answer:**

```ruby
sth = dbh.prepare("INSERT INTO EMPLOYEE(...) VALUES (?, ?, ?, ?, ?)")
sth.execute('John', 'Poul', 25, 'M', 2300)
```

---

# Question: What method is used to release the statement handle after execution?

**Answer:** `sth.finish`

---

# Question: When should `rollback` be called in Ruby DBI?

**Answer:** When an error occurs and you want to revert the changes made during the transaction.

---

# Question: What is the purpose of using bind values in DBI?

**Answer:** To insert or use dynamic values securely and efficiently in SQL statements using placeholders (`?`).

---

# Question: What method is used to fetch query results one by one?

**Answer:** `sth.fetch do |row| ... end`

---

# Question: How is a SELECT query executed with a condition in DBI?

**Answer:**

```ruby
sth = dbh.prepare("SELECT * FROM EMPLOYEE WHERE INCOME > ?")
sth.execute(1000)
```

---

# Question: What is the output of the example SELECT query if there are two qualifying records?

**Answer:** It prints the details of both employees whose income is greater than 1000.

---

