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

# Question: What is the *vi* editor and why is it considered the de facto standard Unix editor?

**Answer:**
*vi* is a screen-oriented text editor for Unix systems that lets users edit text files efficiently. It’s considered the de facto standard because it is available on nearly all Unix flavors, uses few resources, and its implementations are consistent across systems.

---

# Question: What are the two main operation modes in *vi* and what is their purpose?

**Answer:**
The two main modes are:

* **Command mode:** Used for administrative tasks like saving, moving the cursor, cutting, pasting, and executing commands.
* **Insert mode:** Used for inserting text into the file.

---

# Question: How do you switch from Command mode to Insert mode and vice versa in *vi*?

**Answer:**
From Command mode, press `i` to enter Insert mode. From Insert mode, press `Esc` to return to Command mode.

---

# Question: How do you start editing a new file called `testfile` using *vi*?

**Answer:**
Type `vi testfile` in the terminal. If the file doesn’t exist, *vi* creates a new file with that name.

---

# Question: What symbol represents unused lines in *vi*?

**Answer:**
The tilde (`~`) symbol appears on unused lines in *vi*.

---

# Question: How can you ensure you are in Command mode in *vi*?

**Answer:**
Press the `Esc` key twice; this guarantees you are in Command mode.

---

# Question: How do you move the cursor down two lines in *vi*?

**Answer:**
Type `2j` in Command mode to move down two lines.

---

# Question: How do you delete two characters under the cursor in *vi*?

**Answer:**
Type `2x` in Command mode to delete two characters under the cursor.

---

# Question: How do you delete two lines starting from the cursor line in *vi*?

**Answer:**
Type `2dd` in Command mode to delete two lines starting from the current line.

---

# Question: How do the search commands `/` and `?` differ in *vi*?

**Answer:**
`/pattern` searches forward (downwards) in the file, while `?pattern` searches backward (upwards).

---

# Question: What commands repeat the last search in the same or opposite direction in *vi*?

**Answer:**
Press `n` to repeat the search in the same direction, and `N` to repeat it in the opposite direction.

---

# Question: How do you search for a character forward on the current line in *vi*?

**Answer:**
Press `f` followed by the character in Command mode.

---

# Question: What is the syntax for replacing all occurrences of a word on the current line in *vi*?

**Answer:**
Use the substitution command: `:s/search/replace/g` where `g` means global replacement on the current line.

---

# Question: How can you run an external shell command, like `ls`, from within *vi*?

**Answer:**
Type `:!ls` in Command mode to run the `ls` command without leaving *vi*.

---

# Question: What is *vi* and what are its two main modes of operation?

**Answer:**
*vi* is the default full-screen text editor for UNIX systems. It operates in two modes:

* **Command mode**, where typed characters are interpreted as commands that manipulate the file.
* **Insert mode**, where typed characters are inserted as text into the file.

---

# Question: How do you start editing a file named `filename` using *vi*?

**Answer:**
Type `vi filename` in the terminal. If the file exists, its contents are shown; if not, a new empty file is created.

---

# Question: How do you exit *vi* and save changes?

**Answer:**
Use `:x` or `:wq` followed by Enter to save changes and quit. Use `:q` to quit if no changes were made, and `:q!` to quit without saving changes.

---

# Question: How do you move the cursor down one line in *vi*?

**Answer:**
Press `j` or the Return key. Arrow keys may work on some systems but are not guaranteed.

---

# Question: What key moves the cursor to the start of the current line?

**Answer:**
Press `0` (zero) in Command mode.

---

# Question: How do you undo the last action in *vi*?

**Answer:**
Press `u`. This toggles undo and redo for the most recent change.

---

# Question: Which command inserts text before the cursor in *vi*?

**Answer:**
Press `i` to enter Insert mode and insert text before the cursor.

---

# Question: How do you delete the entire current line in *vi*?

**Answer:**
Press `dd` in Command mode.

---

# Question: How do you copy (yank) the current line and paste it below the cursor in *vi*?

**Answer:**
Press `yy` to copy the current line, then `p` to paste it after the current line.

---

# Question: How do you search forward for a string "example" in *vi*?

**Answer:**
Type `/example` followed by Enter.

---

# Question: How do you move to the next occurrence of the last search in *vi*?

**Answer:**
Press `n` to move forward, or `N` to move backward to the previous occurrence.

---

# Question: How do you save the current file under a new name "newfile" in *vi*?

**Answer:**
Type `:w newfile` followed by Enter.

---

# Question: What command do you use to read and insert contents of a file "insertfile" after the current line in *vi*?

**Answer:**
Type `:r insertfile` followed by Enter.

---
