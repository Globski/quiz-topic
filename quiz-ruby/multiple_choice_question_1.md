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
