# Question: What is Redis?

**Answer:**
*Redis* is an in-memory data structure store used as a database, cache, and message broker. It follows the NoSQL model like Cassandra, CouchDB, and MongoDB, allowing users to store large amounts of data without the constraints of relational databases.

---

# Question: What data structures are supported by Redis?

**Answer:**
Redis supports a variety of data structures, including *strings*, *hashes*, *sets*, *lists*, *sorted sets*, *bitmaps*, *hyperloglogs*, and *geospatial indexes*.

---

# Question: What are the two main components of Redis architecture?

**Answer:**
The two main components of Redis architecture are the *Redis Client* and the *Redis Server*. These can be on the same machine or on different machines.

---

# Question: What kind of configuration can Redis use for distributed systems?

**Answer:**
Redis can be configured in a *master-slave* setup, which supports distributed system architectures.

---

# Question: Why is Redis considered fast?

**Answer:**
Redis is extremely fast because it stores the entire dataset in *primary memory (RAM)*, enabling it to handle up to *110,000 writes per second* and *81,000 reads per second*.

---

# Question: What is pipelining in Redis?

**Answer:**
*Pipelining* in Redis allows multiple commands to be sent to the server in a single request, significantly improving communication speed between the client and server.

---

# Question: How does Redis handle persistence?

**Answer:**
Redis keeps all data in memory and saves changes to disk *asynchronously* using *flexible policies* based on elapsed time and the number of updates since the last save.

---

# Question: What does it mean that Redis operations are atomic?

**Answer:**
Atomic operations in Redis mean that if two clients access the server concurrently, each operation is executed completely without interference, ensuring data consistency.

---

# Question: What are some common use cases of Redis?

**Answer:**
Redis is used for *caching*, *messaging queues*, *short-lived data* storage like *web application sessions* and *web page hit counters*, among others.

---

# Question: How can Redis be installed using the Ubuntu package manager?

**Answer:**
To install Redis on Ubuntu:

1. Run `sudo apt update` to update the system.
2. Run `sudo apt install redis-server` to install Redis.

---

# Question: What are some other ways to install Redis?

**Answer:**
Redis can also be installed by:

* Downloading the source or binary from *redis.io*.
* Running Redis via a *Docker file*.
* Using a *ZIP file* that can be unzipped to start the server.

---

# Question: How can you start the Redis server in a background process?

**Answer:**
You can start the Redis server in a background process using the command:
`redis-server &`
This launches Redis so it continues running in the background.

---

# Question: What command is used to start the Redis CLI?

**Answer:**
The command to start the Redis CLI is:
`redis-cli`
Once entered, it connects to the Redis server and allows you to run Redis commands.

---

# Question: What is the default port number Redis CLI connects to?

**Answer:**
The default port number Redis CLI connects to is *6379*.

---

# Question: What is the basic format for storing a string in Redis?

**Answer:**
The basic format for storing a string in Redis is:
`SET <key> <value>`
For example: `SET name shabir`

---

# Question: How do you retrieve a value from Redis using its key?

**Answer:**
You can retrieve a value using the command:
`GET <key>`
Example: `GET name` would return the value associated with the key "name".

---

# Question: How can you retrieve a specific range of characters from a string value in Redis?

**Answer:**
Use the command:
`GETRANGE <key> <start> <end>`
Example: `GETRANGE email 0 4` returns the first five characters of the value stored at key "email".

---

# Question: How do you set multiple key-value pairs at once in Redis?

**Answer:**
You use the command:
`MSET key1 value1 key2 value2 ...`
Example: `MSET lang English technology Redis`

---

# Question: How do you retrieve multiple values for multiple keys in Redis?

**Answer:**
Use the command:
`MGET key1 key2 ...`
Example: `MGET lang technology` returns the values of both keys.

---

# Question: What command gives the length of the value stored at a key?

**Answer:**
The command to get the length of a string value is:
`STRLEN <key>`
Example: `STRLEN lang` would return the number of characters in the value stored at "lang".

---

# Question: What happens if you use `STRLEN` on a non-existing key?

**Answer:**
Using `STRLEN` on a key that does not exist returns *0*.

---

# Question: How can you change the value of an existing key?

**Answer:**
To change the value of an existing key, you simply use the `SET` command again:
Example: `SET name "Daily Code Buffer"` overwrites the old value with the new one.

---

# Question: How can you store an integer value in Redis?

**Answer:**
You can store an integer value in Redis using the `SET` command:
Example: `SET count 1` stores the integer 1 under the key "count".

---

# Question: What does the `INCR` command do in Redis?

**Answer:**
The `INCR` command increments the integer value of a key by 1.
Example: `INCR count` will increase the value of "count" from 1 to 2.

---

# Question: How can you increment a key’s value by a specific amount in Redis?

**Answer:**
Use the `INCRBY` command with a key and the increment amount:
Example: `INCRBY count 10` increments the "count" value by 10.

---

# Question: What does the `DECR` command do in Redis?

**Answer:**
The `DECR` command decrements the integer value of a key by 1.
Example: `DECR count` reduces the value of "count" by 1.

---

# Question: How can you decrement a value by a specific number in Redis?

**Answer:**
Use the `DECRBY` command:
Example: `DECRBY count 5` decreases the value of "count" by 5.

---

# Question: Can Redis store float values? How?

**Answer:**
Yes, Redis can store float values using the `SET` command:
Example: `SET pi 3.14`

---

# Question: Which command is used to increment a float value in Redis?

**Answer:**
Use the `INCRBYFLOAT` command:
Example: `INCRBYFLOAT pi 0.001` increases the float value of "pi" by 0.001.

---

# Question: What does the `EXPIRE` command do in Redis?

**Answer:**
The `EXPIRE` command sets a timeout on a key, after which the key will be automatically deleted.
Example: `EXPIRE a 10` sets key "a" to expire in 10 seconds.

---

# Question: How can you check how much time is left before a key expires in Redis?

**Answer:**
Use the `TTL` (Time To Live) command:
Example: `TTL a` shows how many seconds are left before key "a" expires.

---

# Question: What does a TTL value of `-1` indicate in Redis?

**Answer:**
A TTL value of `-1` means that the key exists but has no expiration time set.

---

# Question: How can you set a key with an expiration time directly in a single command?

**Answer:**
Use the `SET` command with the `EX` option:
Example: `SET x 100 EX 10` sets the key "x" with a value of 100 and an expiration time of 10 seconds.

---

# Question: What happens when you try to `GET` a key after it has expired in Redis?

**Answer:**
You will receive a `(nil)` response or no value, indicating the key no longer exists.

---

# Question: What command can be used to retrieve all keys stored in Redis, including those added earlier?

**Answer:** The command `keys *` can be used to retrieve all keys.

---

# Question: What does the `flushall` command do in Redis?

**Answer:** The `flushall` command deletes all key-value pairs from the Redis database.

---

# Question: After executing `flushall`, what will the `keys *` command return?

**Answer:** It will return an empty set because all data has been deleted.

---

# Question: How do you add elements to a list in Redis from the left (top) side?

**Answer:** Use the `lpush` command with the key and value(s), e.g., `lpush country India`.

---

# Question: Provide an example of pushing multiple elements to a list key called "country".

**Answer:** `lpush country India` and `lpush country USA` add "India" and then "USA" to the left of the list.

---

# Question: How can you retrieve all elements from a Redis list?

**Answer:** Use the `lrange` command with the key and range start and stop, e.g., `lrange country 0 -1` to get all elements.

---

# Question: In the `lrange` command, what do the start and stop indices `0` and `-1` signify?

**Answer:** `0` is the first element, and `-1` indicates the last element of the list, so `lrange 0 -1` retrieves the entire list.

---

# Question: How do you retrieve only the first two elements of a list in Redis?

**Answer:** Use `lrange` with indices `0` and `1`, e.g., `lrange country 0 1`.

---

# Question: What is the difference between the `lpush` and `rpush` commands?

**Answer:** `lpush` adds elements to the left (top) of the list, while `rpush` adds elements to the right (bottom) of the list.

---

# Question: If a list contains \["UK", "USA", "India"], what will happen after executing `rpush country Australia`?

**Answer:** "Australia" will be added to the end (bottom) of the list, making it \["UK", "USA", "India", "Australia"].

---

# Question: How can you find the length of a Redis list?

**Answer:** Use the `llen` command with the key, e.g., `llen country`.

---

# Question: What does the `llen` command return if the specified key does not exist?

**Answer:** It returns zero.

---

# Question: How do the `lpop` and `rpop` commands modify a list?

**Answer:** `lpop` removes and returns the first element (from the left/top), while `rpop` removes and returns the last element (from the right/bottom).

---

# Question: Given a list \["UK", "USA", "India", "Australia"], what will be the list after executing `lpop country`?

**Answer:** "UK" will be removed, resulting in \["USA", "India", "Australia"].

---

# Question: After performing `rpop country` on the list \["USA", "India", "Australia"], what is the resulting list?

**Answer:** "Australia" is removed, resulting in \["USA", "India"].

---

# Question: How would you add "France" to the left of the "country" list?

**Answer:** Use `lpush country France`.

---

# Question: How can you verify the current contents of the "country" list after modifications?

**Answer:** Use `lrange country 0 -1` to get all elements.

---

# Question: What command would you use to change an existing element in a Redis list, for example, changing "France" to another country?

**Answer:** The `lset` command can be used to set the value at a specific index, e.g., `lset country [index] new_value`.

---

# Question: What does the `lset` command do in the context of a list in Redis?

**Answer:** The `lset` command updates the value at a specified index of a list key. Indexing starts from zero.

---

# Question: If a list key "country" contains \["france", "usa", "india"], what will be the result of running `lset country 0 germany`?

**Answer:** The value at index 0 ("france") will be changed to "germany", so the list becomes \["germany", "usa", "india"].

---

# Question: How do you insert an element before or after a specified element in a Redis list?

**Answer:** Use the `linsert` command with the key, the position ("before" or "after"), the pivot element, and the new value to insert.

---

# Question: Provide the syntax and an example to insert "new zealand" before "germany" in a list with key "country".

**Answer:** `linsert country before germany new zealand` inserts "new zealand" before "germany" in the list.

---

# Question: How can you insert an element after "usa" in the list "country"?

**Answer:** Use `linsert country after usa <value>`, replacing `<value>` with the element to insert.

---

# Question: What command allows you to get the value at a particular index in a Redis list?

**Answer:** The `lindex` command, used as `lindex <key> <index>`, returns the value at the specified index.

---

# Question: Using `lindex country 3`, what value is returned if the list at key "country" has "uae" at index 3?

**Answer:** It returns "uae".

---

# Question: What is the difference between `lpush` and `lpushx` commands in Redis?

**Answer:** `lpush` creates a new list if it does not exist and pushes the value; `lpushx` only pushes the value if the list already exists, otherwise does nothing.

---

# Question: What does the `lpushx movies "some_value"` command return if the key "movies" does not exist?

**Answer:** It returns 0, indicating no element was added because the list does not exist.

---

# Question: When `lpushx` is used on an existing list, what does it return?

**Answer:** It returns the new length of the list after the value is added.

---

# Question: How can you check the contents of a list "movies" from start to end in Redis?

**Answer:** Use `lrange movies 0 -1` to get all elements of the list.

---

# Question: What does `lrange movies 0 -1` return if the list "movies" does not exist?

**Answer:** It returns an empty list, indicating no elements exist.

---

# Question: What commands can be used to insert data into an existing list, but only if the list already exists?

**Answer:** `lpushx` and `rpushx`.

---

# Question: How do you retrieve only a subset of elements from a Redis list?

**Answer:** Use the `lrange` command with start and stop indices, e.g., `lrange country 0 1` retrieves elements at indices 0 and 1.

---

# Question: What is the purpose of the Redis `sort` command when used with lists?

**Answer:** The `sort` command sorts the elements in a list by certain criteria like lexicographically or numerically.

---

# Question: How do you specify that the list elements are strings when using the `sort` command?

**Answer:** By including the `ALPHA` option in the sort command.

---

# Question: What parameters can be provided to the `sort` command to control its behavior?

**Answer:** Parameters include the key, pattern, limit (offset and count), order (asc or desc), and options like `ALPHA` for sorting strings.

---

# Question: What does the command `lrange country 0 1` return if the list contains \["germany", "usa", "india"]?

**Answer:** It returns \["germany", "usa"], the elements at indices 0 and 1.

---

# Question: How does Redis indexing work for list commands like `lset` and `lindex`?

**Answer:** Indexing starts at 0 for the first element.

---

# Question: What happens if you try to use `lset` with an index that does not exist in the list?

**Answer:** It returns an error because the index is out of range.

---

# Question: How does the `linsert` command behave if the pivot element is not found in the list?

**Answer:** The command returns -1 and does not insert anything.

---
