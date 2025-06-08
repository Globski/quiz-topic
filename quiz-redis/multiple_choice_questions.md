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
