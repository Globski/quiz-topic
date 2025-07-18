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

# Question: What happens when you sort a list of integers in Redis without specifying any additional parameters?

**Answer:** The list is sorted in ascending order by default without needing any alpha parameter when sorting integers.

—--

# Question: How do you sort a list in Redis in descending order?

**Answer:** You can sort the list in descending order by specifying the appropriate descending option in the sort command.

—--

# Question: What is the behavior of the BLPOP command in Redis?

**Answer:** BLPOP blocks the execution until it can remove an element from the specified list; if the list is empty, it waits until a specified timeout before returning.

—--

# Question: What happens if BLPOP times out without finding any element to remove?

**Answer:** It returns nil, indicating no element was removed during the wait time.

—--

# Question: How is the BLPOP command used with a timeout and key in Redis? Provide an example.

**Answer:** BLPOP is called with a list key and a timeout value in seconds, for example, `BLPOP movies 15` will wait up to 15 seconds to remove an element from the `movies` list.

—--

# Question: What is the behavior of BRPOP compared to BLPOP?

**Answer:** BRPOP works similarly to BLPOP but removes elements from the end (right) of the list, also blocking execution until an element is available or the timeout occurs.

—--

# Question: What Redis commands are used to add members to a set?

**Answer:** The `SADD` command is used to add one or more members to a set.

—--

# Question: How do you list all members of a set in Redis?

**Answer:** Use the `SMEMBERS` command with the set's key to list all members.

—--

# Question: What is the main advantage of Redis sets over lists in terms of member uniqueness?

**Answer:** Sets automatically enforce uniqueness, so duplicate values cannot be added; lists can contain duplicates.

—--

# Question: What is the return value of `SADD` if you attempt to add a duplicate member to a Redis set?

**Answer:** It returns 0, indicating the member was not added because it already exists in the set.

—--

# Question: How can you get the number of members in a Redis set?

**Answer:** Use the `SCARD` command with the set's key to get the cardinality (count) of the set.

—--

# Question: Which command checks if a member exists in a Redis set?

**Answer:** The `SISMEMBER` command is used to check if a member exists in a set.

—--

# Question: What arguments does the `SISMEMBER` command require?

**Answer:** The key of the set and the member to check for membership.

—--

# Question: What does the `sismember` command return when checking if an element exists in a Redis set?

**Answer:** It returns `1` if the element is a member of the set, and `0` if it is not.

---


# Question: If the set "technology" contains `node.js`, `aws`, `redis`, and `java`, what will `sismember technology java` return?

**Answer:** It will return `1` because `java` is present in the "technology" set.

---


# Question: What will `sismember technology spring` return if `spring` is not in the "technology" set?

**Answer:** It will return `0` indicating `spring` is not a member of the set.

---


# Question: How do you create a new set in Redis and add members to it?

**Answer:** You use the `sadd` command with the set name and the members to add, e.g., `sadd front_end javascript html node react`.

---


# Question: What members are added to the "front\_end" set in the example?

**Answer:** `javascript`, `html`, `node`, and `react`.

---


# Question: What is the purpose of the `sdiff` command in Redis?

**Answer:** It returns the members that are in the first set but not in the subsequent sets.

---


# Question: What is the output of `sdiff technology front_end` given the sets "technology" and "front\_end"?

**Answer:** It returns the members `aws`, `redis`, and `java` which are in "technology" but not in "front\_end".

---


# Question: How does `sdiff` determine the difference between sets?

**Answer:** It compares the first key's set against the other sets, returning members exclusive to the first key.

---


# Question: How can you store the result of a set difference operation into a new set?

**Answer:** By using the `sdiffstore` command followed by the destination key and the sets to compare, e.g., `sdiffstore new_set technology front_end`.

---


# Question: What does the `sdiffstore` command do in the example?

**Answer:** It stores the difference between "technology" and "front\_end" (i.e., `aws`, `redis`, `java`) into the new set named "new\_set".

---


# Question: How do you verify the members of the newly stored set after using `sdiffstore`?

**Answer:** By running `smembers new_set` to list all members of the "new\_set".

---


# Question: What does the `sinter` command do?

**Answer:** It returns the members that are common (intersection) to all the specified sets.

---


# Question: What is the result of `sinter technology front_end` in the example?

**Answer:** It returns `node.js` as it is the only common member between the two sets.

---


# Question: Can `sinter` take multiple keys as arguments?

**Answer:** Yes, it can take two or more keys and returns the common members across all of them.

---


# Question: What happens if you run `sinter` on `technology`, `front_end`, and `new_set` sets given the example data?

**Answer:** It returns an empty list because there is no member common to all three sets.

---


# Question: How can you store the intersection of sets into a new set?

**Answer:** Using the `sinterstore` command followed by the destination key and the sets to intersect, e.g., `sinterstore new_inter technology front_end`.

---


# Question: After running `sinterstore new_inter technology front_end`, what will `smembers new_inter` return?

**Answer:** It will return `node.js` as that is the common member stored in "new\_inter".

---


# Question: How does the `sdiffstore` command differ from `sdiff`?

**Answer:** `sdiff` displays the difference without storing it, while `sdiffstore` stores the difference in a specified destination set.

---


# Question: How does the `sinterstore` command differ from `sinter`?

**Answer:** `sinter` returns the intersection members without storing them, while `sinterstore` saves the intersection in a specified destination set.

---


# Question: What will happen if you attempt to store the difference or intersection results into an existing set key?

**Answer:** The existing set will be overwritten with the new result.

---


# Question: What Redis command do you use to list all members of a set?

**Answer:** `smembers [set_key]` lists all members of the specified set.

---


# Question: When performing `sdiff technology front_end`, why is `node.js` not part of the result?

**Answer:** Because `node.js` is present in both sets, so it is excluded from the difference which shows only unique members to the first set.

---


# Question: What is the significance of order of keys in the `sdiff` command?

**Answer:** The order matters; the command returns members present in the first key but not in the subsequent keys.

---


# Question: If you want to check if a member exists in a set named `front_end`, which command do you use?

**Answer:** Use `sismember front_end [member]`.

---


# Question: What command would you use to add `react` to the `front_end` set?

**Answer:** `sadd front_end react`.

---


# Question: Can the `sinter` and `sdiff` commands be used with more than two sets?

**Answer:** Yes, they accept multiple keys and operate accordingly across all.

---


# Question: After performing `sdiffstore new_set technology front_end`, what does `smembers new_set` show?

**Answer:** It shows the members unique to "technology" set that are not in "front\_end": `java`, `aws`, and `redis`.

---


# Question: What happens if the sets passed to `sinter` have no common members?

**Answer:** The command returns an empty list.

---


# Question: Explain the sequence of commands to find and store the common members of three sets: `technology`, `front_end`, and `new_set`.

**Answer:** Use `sinterstore destination_set technology front_end new_set` to store the common members into `destination_set`. If no common members exist, the destination set will be empty.

---


# Question: What command would you use to clear all members from a set in Redis?

**Answer:** `del [set_key]` deletes the entire set, effectively clearing all members.

---

# Question: How do Redis set commands treat members that appear in multiple sets when using `sdiff`?

**Answer:** Members present in multiple sets are excluded from the difference result and only unique members to the first set are returned.

---

# Question: What Redis command is used to find the union of multiple sets?

**Answer:** The command `sunion` is used to find the union of two or more sets in Redis.

---

# Question: How do you find the union of the sets `technology` and `front end` in Redis CLI?

**Answer:** Use the command `sunion technology front end`.

---

# Question: How can you find the union of multiple sets including `technology`, `front end`, `new set`, and `new enter`?

**Answer:** Use the command `sunion technology front end new set new enter`.

---

# Question: Which command stores the union of multiple sets into a new destination set?

**Answer:** The command `sunionstore` stores the union of multiple sets into a specified destination set.

---

# Question: How would you store the union of `technology`, `front end`, `new set`, and `new enter` into a set called `new union`?

**Answer:** Use `sunionstore new_union technology front_end new_set new_enter`.

---

# Question: What are the main set operations demonstrated before moving to sorted sets?

**Answer:** The main set operations demonstrated are difference (`sdiff`), intersection (`sinter`), and union (`sunion`), along with adding and removing elements.

---

# Question: What distinguishes a Redis sorted set from a regular set?

**Answer:** A sorted set is like a regular set but each member has an associated score, and the set is sorted by these scores in ascending order.

---

# Question: Which Redis command adds elements to a sorted set?

**Answer:** The command `zadd` is used to add elements to a sorted set.

---

# Question: What is the syntax to add a member with a score to a sorted set called `users`?

**Answer:** `zadd users <score> <member>`.

# Question: How can you add multiple members with their scores to a sorted set in one command?

**Answer:** Use `zadd users <score1> <member1> <score2> <member2> ...`.

---

# Question: Give an example of adding multiple members to a sorted set named `users`.

**Answer:** `zadd users 1 cover 2 x4 3 lx 4 nema 5 steve`.

---

# Question: How do you retrieve all elements in a sorted set `users` sorted by their scores?

**Answer:** Use the command `zrange users 0 -1`.

---

# Question: How can you retrieve all elements in a sorted set along with their scores?

**Answer:** Use `zrange users 0 -1 withscores`.

---

# Question: What Redis command returns the total number of elements in a sorted set?

**Answer:** The command `zcard` returns the cardinality (count) of a sorted set.

---

# Question: How do you get the count of members in the sorted set `users`?

**Answer:** Use `zcard users`.

---

# Question: Which command counts the members in a sorted set within a score range?

**Answer:** The command `zcount` counts members within a given score range.

---

# Question: How is the `zrange` command's start and stop parameters interpreted?

**Answer:** They represent the range of indexes to return from the sorted set, where `0` is the first element and `-1` is the last element.

---

# Question: What does the `withscores` option do when used with `zrange`?

**Answer:** It includes the scores of each member in the output alongside the member names.

---

# Question: If no common elements exist among multiple sets, what will `sinter` return?

**Answer:** It will return an empty list.

---

# Question: How do you store the intersection of `technology` and `front end` sets in a new set `new enter`?

**Answer:** Use `sinterstore new_enter technology front_end`.

---

# Question: How does the `sdiff` command work when comparing two sets?

**Answer:** It returns the members present in the first set but not in the second.

---

# Question: What is the difference between `sdiff` and `sdiffstore` commands?

**Answer:** `sdiff` displays the difference between sets, while `sdiffstore` stores that difference in a new set.

---

# Question: What is the key concept of sorted sets’ score in Redis?

**Answer:** Scores determine the order of elements in the sorted set from lowest to highest.

---

# Question: What happens when you add a member with a duplicate score to a sorted set?

**Answer:** The member is placed according to the score; if scores are equal, lexicographical order is used to break ties.

---

# Question: Can Redis sets store duplicate members?

**Answer:** No, sets store unique members only; duplicates are ignored.

---

# Question: Can you use the `sunionstore` command to merge multiple sets into one and overwrite existing data?

**Answer:** Yes, `sunionstore` overwrites the destination set with the union of provided sets.

---

# Question: What Redis command would you use to list all members of a set called `technology`?

**Answer:** Use `smembers technology`.

---

# Question: What is the Redis command to remove all elements from a set?

**Answer:** Use `del <set_name>` to delete the entire set, or `srem <set_name> <member>` to remove specific members.

---

# Question: When querying a sorted set, what index range would return all members?

**Answer:** The range `0` to `-1` returns all members.

---

# Question: What Redis command retrieves the score of a member in a sorted set?

**Answer:** `zscore <key> <member>` retrieves the score of the specified member.

---

# Question: If you want to see only members with scores between 2 and 4 in a sorted set, which command would you use?

**Answer:** Use `zrangebyscore <key> 2 4`.

---

# Question: What command would show the difference between two sets `technology` and `front end` without storing it?

**Answer:** `sdiff technology front_end`.

---

# Question: How do you add a member named `react` to a set named `front end`?

**Answer:** Use `sadd front_end react`.

---

# Question: How would you check if `java` exists in the set `technology`?

**Answer:** Use `sismember technology java`.

---

# Question: What will `sismember technology spring` return if `spring` is not a member?

**Answer:** It will return `0` indicating the member is not present.

---

# Question: Can `sunion` take more than two sets as arguments?

**Answer:** Yes, `sunion` can accept multiple sets as arguments to union all of them.

---

# Question: How would you add members `node.js`, `aws`, `redis`, and `java` to a set called `technology`?

**Answer:** Use `sadd technology node.js aws redis java`.

---

# Question: What is the effect of the command `smembers new_set` after using `sdiffstore` to create `new_set`?

**Answer:** It lists all members stored in `new_set` which are the differences between the two compared sets.

---

# Question: What Redis command is used to count the number of elements in a sorted set within a specific rank range?

**Answer:** The command `ZCOUNT` is used, passing the key (e.g., `users`), and the minimum and maximum rank range (e.g., `-inf` to `+inf` to get all elements).

---

# Question: How do you specify the full range of ranks in `ZCOUNT` to get all data?

**Answer:** Use `-inf` (negative infinity) as the minimum rank and `+inf` (positive infinity) as the maximum rank.

---

# Question: What will happen if you use `ZCOUNT users 0 4` and some elements have ranks beyond 4?

**Answer:** Elements with ranks greater than 4 will be excluded; only elements with ranks between 0 and 4 will be counted.

---

# Question: Which Redis command removes specific members from a sorted set?

**Answer:** The command `ZREM` is used, with the key and one or more member names as arguments.

---

# Question: What is the effect of executing `ZREM users alex`?

**Answer:** The member `alex` is removed from the sorted set `users`.

---

# Question: How can you retrieve all members of a sorted set in ascending order by their rank?

**Answer:** Use the command `ZRANGE users 0 -1` to get all members from rank 0 to the last rank.

---

# Question: How do you retrieve members of a sorted set in descending order by rank?

**Answer:** Use `ZREVRANGE` with the key and start and stop indices (e.g., `ZREVRANGE users 0 -1`).

---

# Question: How can you retrieve members along with their scores when using `ZRANGE` or `ZREVRANGE`?

**Answer:** Add the `WITHSCORES` option to the command.

---

# Question: What does the `ZSCORE` command do in Redis?

**Answer:** It returns the score associated with a specified member in a sorted set.

---

# Question: How do you get the score of member `shabir` in the sorted set `users`?

**Answer:** Execute `ZSCORE users shabir`.

---

# Question: What is the difference between `ZREVRANGE` and `ZREVRANGEBYSCORE`?

**Answer:** `ZREVRANGE` reverses by rank (index), while `ZREVRANGEBYSCORE` reverses the sorted set based on scores, using a score range as arguments.

---

# Question: How do you use `ZREVRANGEBYSCORE` to get all members with scores between 5 and 0 in descending order?

**Answer:** Execute `ZREVRANGEBYSCORE users 5 0 WITHSCORES`.

---

# Question: How do you increment the score of a member in a sorted set?

**Answer:** Use `ZINCRBY` followed by the key, increment value, and member name.

---

# Question: What happens when you run `ZINCRBY users 2 steve` if Steve's original score was 4?

**Answer:** Steve's score increases from 4 to 6.

---

# Question: After incrementing Steve's score to 6, how does this affect results of `ZREVRANGEBYSCORE users 5 0`?

**Answer:** Steve will no longer appear because the range is from 5 down to 0, and Steve's score is now 6 (above the max).

---

# Question: How do you remove members from a sorted set based on their score range?

**Answer:** Use the command `ZREMRANGEBYSCORE` with the key, minimum score, and maximum score.

---

# Question: If you want to remove members with scores between 0 and 3 from `users`, which command would you use?

**Answer:** `ZREMRANGEBYSCORE users 0 3`.

---

# Question: What is the behavior when removing members by score range with `ZREMRANGEBYSCORE` if the range covers multiple members?

**Answer:** All members whose scores fall within the specified range will be removed from the sorted set.

---

# Question: How do you remove members from a sorted set based on their score range, for example scores between 5 and 6?

**Answer:** Use the command `ZREMRANGEBYSCORE users 5 6` to remove members with scores from 5 to 6 inclusive.

---

# Question: After removing members with scores between 5 and 6, what will be the result of `ZRANGE users 0 -1`?

**Answer:** The sorted set will no longer include members with scores 5 and 6; only remaining members with other scores will be listed.

---

# Question: How do you remove members from a sorted set based on rank range, for example ranks 0 through 2?

**Answer:** Use `ZREMRANGEBYRANK users 0 2` to remove all members with ranks from 0 to 2 inclusive.

---

# Question: What is the effect of executing `ZREMRANGEBYRANK users 0 2` if there are 5 members?

**Answer:** The first three members by rank (0, 1, 2) are removed, leaving the remaining members intact.

---

# Question: What is a HyperLogLog data structure in Redis?

**Answer:** HyperLogLog is a probabilistic data structure used to count unique elements approximately, such as unique IP addresses, search terms, or email addresses.

---

# Question: Which Redis command is used to add elements to a HyperLogLog?

**Answer:** The command `PFADD` followed by the key and one or more elements adds elements to the HyperLogLog.

---

# Question: How do you count the approximate number of unique elements stored in a HyperLogLog?

**Answer:** Use `PFCOUNT` followed by the HyperLogLog key.

---

# Question: Can you add multiple elements at once to a HyperLogLog using `PFADD`?

**Answer:** Yes, you can add multiple elements in one command, for example `PFADD hll a b c d e`.

---

# Question: How do you merge multiple HyperLogLogs into one in Redis?

**Answer:** Use the command `PFMERGE destination source1 source2 ...` to merge multiple HyperLogLogs into a single HyperLogLog stored at `destination`.

---

# Question: After merging two HyperLogLogs named `hll` and `hll2` into `merged_hll`, how do you get the total approximate count of unique elements?

**Answer:** Use `PFCOUNT merged_hll`.

---

# Question: What is a Redis hash?

**Answer:** A hash in Redis is a map between string fields and string values, ideal for storing objects.

---

# Question: How do you add a field-value pair to a Redis hash?

**Answer:** Use the command `HSET key field value`, e.g., `HSET myhash name sugar`.

---

# Question: What does the `HSET` command return upon successfully adding a new field-value pair?

**Answer:** It returns `1` if a new field was created and value set, or `0` if the field already existed and the value was updated.

---

# Question: How do you retrieve all fields and their values from a Redis hash?

**Answer:** Use the command `HGETALL key`.

---

# Question: What does the Redis command `hkeys myhash` return?

**Answer:** It returns all the keys available in the hash stored at `myhash`.

---

# Question: How can you retrieve all the values stored in a Redis hash?

**Answer:** By using the command `hvals myhash`, which returns all the values in the hash.

---

# Question: What does the Redis command `hgetall myhash` return?

**Answer:** It returns all the keys and values stored in the hash `myhash`.

---

# Question: How do you check if a specific field exists in a Redis hash?

**Answer:** Use the command `hexists myhash field`. It returns 1 if the field exists, 0 if it does not.

---

# Question: What will `hexists myhash name` return if the field `name` exists in the hash?

**Answer:** It will return 1.

---

# Question: What will `hexists myhash name1` return if the field `name1` does not exist in the hash?

**Answer:** It will return 0.

---

# Question: How do you find the number of fields stored in a Redis hash?

**Answer:** By using the command `hlen myhash`, which returns the length (number of fields) of the hash.

---

# Question: What happens if you add a new field to a Redis hash and then run `hlen` again?

**Answer:** The returned length will increase by one, reflecting the new field added.

---

# Question: Which command allows you to add multiple field-value pairs to a Redis hash in one call?

**Answer:** `hmset myhash field1 value1 field2 value2 ...`

---

# Question: Provide an example command to add `country` as `India` and `phone` as `1234567890` to a Redis hash `myhash`.

**Answer:** `hmset myhash country India phone 1234567890`

---

# Question: How can you retrieve multiple values from a Redis hash at once?

**Answer:** Using the command `hmget myhash field1 field2 ...`

---

# Question: What is the result of running `hmget myhash name email phone` if those fields exist in the hash?

**Answer:** It returns the values for `name`, `email`, and `phone` fields in the order requested.

---

# Question: If you want to increment a numeric field in a Redis hash by an integer, which command should you use?

**Answer:** Use the command `hincrby myhash field increment`.

---

# Question: How would you increment the `age` field in `myhash` by 2?

**Answer:** `hincrby myhash age 2`

---

# Question: Which Redis command increments a hash field by a floating point number?

**Answer:** `hincrbyfloat myhash field increment_float`

---

# Question: How would you increase the `age` field in `myhash` by 1.5 using Redis commands?

**Answer:** `hincrbyfloat myhash age 1.5`

---

# Question: How do you remove a field from a Redis hash?

**Answer:** Use the command `hdel myhash field`.

---

# Question: What does the return value of `hdel myhash field` indicate?

**Answer:** It returns the number of fields removed (1 if the field was removed, 0 if the field did not exist).

---

# Question: After deleting a field from a hash using `hdel`, how can you verify that the field no longer exists?

**Answer:** Use `hexists myhash field` which will return 0 if the field was successfully removed.

---

# Question: Is it possible to use pipelining with Redis hash commands, and if so, which commands support adding and retrieving multiple fields?

**Answer:** Yes, pipelining can be used; `hmset` supports adding multiple fields, and `hmget` supports retrieving multiple fields.

---

# Question: What happens if you mistakenly enter a field name in lowercase when it should be uppercase in commands like `hmset` or `hmget`?

**Answer:** Redis treats field names as case-sensitive, so the incorrect case will lead to either creating a new field or returning null values for that field.

---

# Question: What does the Redis command `hstrlen myhash name` do?

**Answer:** It returns the length of the string value stored at the `name` field in the hash `myhash`.

---

# Question: If the field `name` in `myhash` has the value `shabiri`, what will `hstrlen myhash name` return?

**Answer:** It will return `7`, since "shabiri" has 7 characters.

---

# Question: What is the purpose of the Redis command `hsetnx`?

**Answer:** `hsetnx` sets the value of a field in a hash only if the field does not already exist; it prevents overwriting existing fields.

---

# Question: What will the command `hsetnx myhash name newvalue` return if `name` already exists in `myhash`?

**Answer:** It will return `0`, and the value will not be updated.

---

# Question: What will the command `hsetnx myhash lastname Khan` return if `lastname` does not exist in `myhash`?

**Answer:** It will return `1`, and the `lastname` field will be added with value `Khan`.

---

# Question: What is the purpose of the Redis `MULTI` command?

**Answer:** `MULTI` starts a Redis transaction, queuing subsequent commands without executing them until `EXEC` is called.

---

# Question: What happens to Redis commands issued after `MULTI` but before `EXEC`?

**Answer:** They are queued and not executed immediately.

---

# Question: Which Redis command ends a transaction and executes all previously queued commands?

**Answer:** `EXEC`

---

# Question: What does the Redis `DISCARD` command do?

**Answer:** It cancels a transaction, discarding all queued commands without executing them.

---

# Question: What is the role of the `WATCH` command in Redis transactions?

**Answer:** `WATCH` monitors one or more keys, and if any of them are modified before the transaction executes, the transaction is aborted to prevent race conditions.

---

# Question: In a Redis transaction, if you queue `SET name shabir` and then `GET name`, what will happen when you run `EXEC`?

**Answer:** Both commands will be executed in order as part of the transaction.

---

# Question: If an error occurs in one of the commands queued in a Redis transaction, what is the expected behavior?

**Answer:** If `EXEC` is issued, all commands are executed atomically; if the error is caught before `EXEC`, Redis may refuse to execute the transaction.

---

# Question: When does a Redis transaction enter execution mode?

**Answer:** When the `EXEC` command is issued after queuing commands with `MULTI`.

---

# Question: What happens if you issue a `GET` command after `MULTI` and before `EXEC`?

**Answer:** The `GET` command will be queued and its result will only be available after executing `EXEC`.

---

# Question: Can you cancel a Redis transaction after starting it with `MULTI` but before executing it?

**Answer:** Yes, by using the `DISCARD` command.

---

# Question: How do you start a FastAPI server using the `uvicorn` command?

**Answer:** By typing `uvicorn filename:app`, where `filename` is the Python file (without `.py`) and `app` is the FastAPI instance.

---

# Question: What message indicates the FastAPI server started successfully?

**Answer:** A line showing the server is running at `http://127.0.0.1:8000`.

---

# Question: What does the IP address `127.0.0.1` represent?

**Answer:** It refers to the local machine, also known as localhost.

---

# Question: On what port does the FastAPI development server run by default?

**Answer:** Port `8000`.

---

# Question: What output is displayed when visiting `http://127.0.0.1:8000` in the browser after starting the server?

**Answer:** `{"message": "Hello World"}`

---

# Question: What is the term used in FastAPI documentation for a route or endpoint?

**Answer:** Path operation

---

# Question: What two components make up a FastAPI path operation?

**Answer:** The function and the decorator.

---

# Question: What is the purpose of the decorator in a FastAPI path operation?

**Answer:** It maps the function to a specific route and HTTP method, defining how FastAPI should respond to a request.

---

# Question: Is the `async` keyword required when defining a FastAPI route handler?

**Answer:** No, it is optional unless performing asynchronous tasks like API calls or database access.

---

# Question: What happens if the `async` keyword is removed from a FastAPI route handler that doesn’t use asynchronous operations?

**Answer:** The code behaves exactly the same, as `async` is not required in this case.

---

# Question: Does the name of a FastAPI route handler function affect its behavior?

**Answer:** No, the function name is arbitrary and does not impact functionality.

---

# Question: Why is it recommended to use descriptive names for FastAPI path operation functions?

**Answer:** To make the code more readable and reflect the operation's purpose (e.g., `get_user`, `login_user`).

---

# Question: Does the name of a FastAPI route function affect the behavior of the API?

**Answer:** No, the function name is arbitrary and does not impact API behavior.

---

# Question: What is recommended when naming FastAPI route functions?

**Answer:** Use descriptive names that reflect the purpose of the function (e.g., `login_user`, `get_user`).

---

# Question: Where should the logic for operations like user authentication be placed in FastAPI?

**Answer:** Inside the function defined for the path operation.

---

# Question: What does a FastAPI path operation typically return?

**Answer:** Any return value, commonly a Python dictionary, which FastAPI automatically converts to JSON.

---

# Question: What is JSON and why is it important in APIs?

**Answer:** JSON (JavaScript Object Notation) is a universal data format used to send and receive data between APIs and clients.

---

# Question: What happens if the decorator is removed from a FastAPI route function?

**Answer:** The function no longer behaves as an API endpoint; it becomes a plain Python function.

---

# Question: What does the decorator do in a FastAPI route?

**Answer:** It registers the function as an API endpoint (a path operation) that can respond to HTTP requests.

---

# Question: What symbol is used in Python to define a decorator?

**Answer:** The `@` symbol.

---

# Question: In FastAPI, what does the decorator typically reference?

**Answer:** The FastAPI app instance followed by the HTTP method and route path (e.g., `@app.get("/")`).

---

# Question: What is the purpose of the HTTP method in a FastAPI decorator?

**Answer:** It specifies which type of HTTP request (e.g., GET, POST) the endpoint should handle.

---

# Question: What are the four main HTTP methods supported in FastAPI?

**Answer:** `GET`, `POST`, `PUT`, and `DELETE`.

---

# Question: Where can a user learn more about HTTP methods?

**Answer:** The Mozilla Developer Network (MDN) HTTP methods documentation page.

---

# Question: In FastAPI, what is the path argument in a decorator?

**Answer:** It defines the URL path after the domain name that maps to the route (e.g., `"/"` for the root path).

---

# Question: What does the root path (`"/"`) represent in a FastAPI route?

**Answer:** It corresponds to the base URL of the API, meaning no additional path after the domain is required.

---

# Question: Does adding or omitting a trailing slash in the root path change the behavior?

**Answer:** No, using or omitting the trailing slash (`/`) in the root path does not affect the behavior.

---

# Question: What happens when a `WATCH` is set on a key and a transaction is created in Redis?

**Answer:** If the watched key remains unchanged by other clients, the transaction executes successfully; if the key is changed by another client before the transaction executes, the transaction is aborted.

---

# Question: Will a transaction be aborted if the watched key is modified by the same client that initiated the transaction?

**Answer:** No, the transaction is only aborted if the watched key is changed by a **different client**.

---

# Question: In Redis, what does the `MULTI` command do?

**Answer:** It marks the start of a transaction block.

---

# Question: What is the role of the `EXEC` command in Redis transactions?

**Answer:** It executes all queued commands in the transaction if the watched keys were not modified by other clients.

---

# Question: What command is used to clear all data from the Redis database?

**Answer:** `FLUSHALL`

---

# Question: What does Redis Pub/Sub stand for, and what is its purpose?

**Answer:** Pub/Sub stands for Publisher/Subscriber model, used for broadcasting messages to multiple subscribers via channels.

---

# Question: Can you subscribe to a Redis channel before it is created?

**Answer:** Yes, Redis allows subscribing to a channel even if it hasn’t been created yet.

---

# Question: What command is used to subscribe to a Redis channel?

**Answer:** `SUBSCRIBE <channel_name>`

---

# Question: What command is used to publish a message to a Redis channel?

**Answer:** `PUBLISH <channel_name> <message>`

---

# Question: What is the output of the `PUBLISH` command?

**Answer:** It returns the number of subscribers that received the message.

---

# Question: How do you exit from a Redis client that is in `SUBSCRIBE` mode?

**Answer:** By pressing `Ctrl + C` or quitting the client.

---

# Question: If two clients are subscribed to the `news` channel and a message is published, what output does `PUBLISH` return?

**Answer:** It returns `2`, indicating the message was sent to two subscribers.

---

# Question: Can a Redis client subscribe to multiple channels at once?

**Answer:** Yes, a client can subscribe to multiple channels simultaneously.

---

# Question: What command is used in Redis for subscribing to multiple channels with pattern matching?

**Answer:** `PSUBSCRIBE <pattern>`

---

# Question: In pattern-based subscriptions, what does the `*` wildcard character do?

**Answer:** It matches zero or more characters, allowing subscription to multiple channels with similar names (e.g., `news*` matches `news1`, `news2`, etc.).

---

# Question: What does the `?` wildcard character do in `PSUBSCRIBE`?

**Answer:** It matches exactly one character at that position in the channel name (e.g., `h?llo` matches `hello`, `hxllo`).

---

# Question: How can you subscribe to specific named channels like `ball` and `bill` using pattern matching?

**Answer:** Use a pattern like `b[ai]ll` which matches both `ball` and `bill`.

---

# Question: What happens when a message is published to a channel that no client is subscribed to?

**Answer:** `PUBLISH` returns `0`, indicating no clients received the message.

---

# Question: If a client subscribes with the pattern `news*`, will it receive messages from `news`, `news1`, and `newsUpdate`?

**Answer:** Yes, it will receive messages from all channels matching that pattern.

---

# Question: Will the `PSUBSCRIBE` pattern `h?llo` match the channel `hxllo`?

**Answer:** Yes, because `?` matches any single character.

---

# Question: What command is used to re-open the Redis CLI after quitting a client session?

**Answer:** `redis-cli`

---

# Question: Can you mix standard and pattern-based subscriptions across different clients in Redis?

**Answer:** Yes, clients can use `SUBSCRIBE` and `PSUBSCRIBE` independently to consume messages in different formats.

---

# Question: What is the effect of `PUBLISH broadcast "new broadcast"` when a client is subscribed to the `broadcast` channel?

**Answer:** The message `"new broadcast"` will be delivered to all subscribers of the `broadcast` channel.

---





