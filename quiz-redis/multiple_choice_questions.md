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
