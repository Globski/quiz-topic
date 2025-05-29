# Question: What is vi?

**Answer:**
*vi* is a powerful, screen-oriented text editor originally created for Unix systems. It allows users to view and edit text files directly from the command line and is known for its efficiency and ubiquity across Unix-like systems.

---

# Question: Who is Bill Joy?

**Answer:**
Bill Joy is a computer scientist who co-founded Sun Microsystems. He is best known in this context as the original creator of the *vi* text editor, which he developed in the 1970s while working on the BSD Unix project.

---

# Question: How do you start and exit *vi*?

**Answer:**
To start *vi*, type `vi filename` in the terminal. To exit:

* Press `Esc` to ensure you're in command mode.
* Type `:q` to quit (if no changes were made),
* `:q!` to quit without saving changes,
* or `:wq` (or `:x`) to save changes and quit.

---

# Question: What are the command and insert modes in *vi*, and how do you switch from one to the other?

**Answer:**
*vi* operates in two main modes:

* **Command mode**: For issuing commands like saving, quitting, or moving the cursor.
* **Insert mode**: For typing and editing text.
  To switch from **command mode** to **insert mode**, press `i`, `I`, `a`, or `A`. To return to **command mode**, press `Esc`.

---

# Question: How do you edit text in *vi*?

**Answer:**
To edit text in *vi*, first enter **insert mode** using commands like `i` (insert before cursor) or `a` (insert after cursor). Then type your text. Press `Esc` to return to command mode when done.

---

# Question: How do you cut and paste lines in *vi*?

**Answer:**
In command mode:

* Use `dd` to cut (delete) the current line.
* Use `p` to paste the line below the current one, or `P` to paste it above.

---

# Question: How do you search forward and backward in *vi*?

**Answer:**
In command mode:

* Type `/pattern` to search forward for a pattern.
* Type `?pattern` to search backward.
  Use `n` to repeat the search in the same direction, or `N` to search in the opposite direction.

---

# Question: How do you undo an action in *vi*?

**Answer:**
In command mode, press `u` to undo the last action. Press `U` to undo all changes on the current line.

---

# Question: How do you quit *vi*?

**Answer:**
To quit:

* `:q` — quit (only if no changes were made),
* `:q!` — quit without saving changes,
* `:wq` or `:x` — save and quit.

---

# Question: How do you quit Vi?

**Answer:**
In command mode, type `:q` to quit if no changes were made, `:wq` to save and quit, or `:q!` to quit without saving changes.

---

# Question: Is Vi included with almost every Linux distribution?

**Answer:**
Yes, Vi is included with almost every Linux distribution as a standard text editor.

---

# Question: How do you enter Command Mode in Vi?

**Answer:**
Press the `Esc` key to enter command mode from any other mode.

---

# Question: How do you enter Insert Mode in Vi?

**Answer:**
From command mode, press `i` to insert text before the cursor or `a` to insert text after the cursor.

---

# Question: What is the command to insert text before the cursor?

**Answer:**
Press `i` in command mode to insert text before the cursor.

---

# Question: What is the command to delete and cut the current line?

**Answer:**
Press `dd` in command mode to delete (cut) the current line.

---

# Question: What is the command to paste the lines in the buffer into the text after the current line?

**Answer:**
Press `p` in command mode to paste the contents of the buffer after the current line.

---

# Question: What is the command to undo what you just did?

**Answer:**
Press `u` in command mode to undo the last change.

---

# Question: What is the command to quit vi even though latest changes have not been saved for this vi call?

**Answer:**
Type `:q!` in command mode to quit vi without saving changes.

---

# Question: What is the command to move the cursor to the start of the current line?

**Answer:**
Press `0` (zero) in command mode to move the cursor to the beginning of the line.

---

# Question: What is the command to move the cursor to the end of the line?

**Answer:**
Press `$` in command mode to move the cursor to the end of the line.

---
