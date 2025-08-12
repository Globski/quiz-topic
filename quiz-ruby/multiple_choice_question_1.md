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
