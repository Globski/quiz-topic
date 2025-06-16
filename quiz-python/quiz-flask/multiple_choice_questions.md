# Question: What type of framework is Flask classified as?

**Answer:** A micro-framework.

---

# Question: What does it mean that Flask is called a micro-framework?

**Answer:** It is small enough for developers to potentially read and understand all of its source code.

---

# Question: Does Flask being small mean it lacks features compared to other frameworks?

**Answer:** No, Flask is extensible and allows developers to add only the features they need through extensions.

---

# Question: What is the core design principle of Flask regarding extensibility?

**Answer:** Flask provides a solid core with basic services, while additional features are added via extensions.

---

# Question: What are the benefits of Flask's extensible design?

**Answer:** It allows developers to build a lean stack without unnecessary features or bloat.

---

# Question: What library provides routing, debugging, and WSGI subsystems in Flask?

**Answer:** Werkzeug.

---

# Question: Which library provides template support in Flask?

**Answer:** Jinja2.

---

# Question: What is the source of command-line integration in Flask?

**Answer:** Click.

---

# Question: Who is the author of Flask and all its main dependencies?

**Answer:** Armin Ronacher.

---

# Question: Does Flask natively support database access?

**Answer:** No, Flask does not provide native support for accessing databases.

---

# Question: Does Flask include built-in tools for web form validation and user authentication?

**Answer:** No, these are handled through external extensions.

---

# Question: How are features like database access and authentication added to a Flask application?

**Answer:** Through extensions that integrate with Flask's core packages.

---

# Question: What is the most convenient way to install Flask in a new application directory?

**Answer:** By using a virtual environment.

---

# Question: What is a virtual environment in Python?

**Answer:** A virtual environment is a copy of the Python interpreter that allows you to install packages privately without affecting the system’s global Python interpreter.

---

# Question: Why are virtual environments useful in Python development?

**Answer:** They prevent package clutter and version conflicts in the system-wide Python interpreter.

---

# Question: How does using a virtual environment benefit application development?

**Answer:** It ensures that each application has access only to the packages it uses, keeping dependencies isolated per project.

---

# Question: What is one major advantage of virtual environments in terms of system permissions?

**Answer:** Virtual environments can be created and managed without administrator rights.

---

# Question: What remains unaffected when using a virtual environment to install Python packages?

**Answer:** The system’s global Python interpreter.

---

# Question: How does the use of virtual environments contribute to maintaining a clean development system?

**Answer:** They allow the global Python interpreter to remain clean and be used only as a source for creating new environments.

---

# Question: How do Python 2 and Python 3 differ in terms of creating virtual environments?

**Answer:** Python 3 supports virtual environments natively using the `venv` package, whereas Python 2 does not.

---

# Question: Which Python standard library package supports virtual environment creation in Python 3?

**Answer:** The `venv` package.

---

# Question: On Ubuntu systems, what is a possible issue with using the stock Python 3 interpreter for virtual environments?

**Answer:** The standard `venv` package may not be installed by default.

---

# Question: What happens when you create a virtual environment named `venv`?

**Answer:** A subdirectory named `venv` is created in the current directory, containing all files associated with the virtual environment.

---

# Question: What must you do before using a virtual environment in your terminal session?

**Answer:** You must activate the virtual environment.

---

# Question: What is the command to activate a virtual environment on Linux or macOS?

**Answer:** `$ source venv/bin/activate`

---

# Question: What is the command to activate a virtual environment on Microsoft Windows?

**Answer:** `$ venv\Scripts\activate`

---

# Question: What does activating a virtual environment do to the PATH environment variable?

**Answer:** It adds the virtual environment’s Python interpreter location to the PATH variable in the current command session.

---

# Question: How does the command prompt change when a virtual environment is activated?

**Answer:** It is modified to include the name of the environment, for example: `(venv) $`

---

# Question: After activation, what happens when you run the `python` command in the terminal?

**Answer:** It runs the Python interpreter from the virtual environment instead of the system-wide interpreter.

---

# Question: What must you do if you are using multiple command prompt windows and want to work within the virtual environment in each?

**Answer:** You must activate the virtual environment separately in each window.

---

# Question: What must all Flask applications create during initialization?

**Answer:** An application instance.

---

# Question: What protocol is used by web servers to pass requests to the Flask application?

**Answer:** Web Server Gateway Interface (WSGI), pronounced “wiz-ghee”.

---

# Question: How is a basic Flask application instance typically created?

**Answer:**

```python
from flask import Flask  
app = Flask(__name__)
```

---

# Question: What is the only required argument to the `Flask` class constructor?

**Answer:** The name of the main module or package of the application.

---

# Question: What is the usual value passed to the `Flask` constructor for the application name?

**Answer:** Python’s `__name__` variable.

---

# Question: Why is the `__name__` variable passed to the `Flask` constructor?

**Answer:** Because Flask uses it to determine the location of the application, allowing it to locate other application files such as images and templates.

---

# Question: Why can the `__name__` argument be confusing for new Flask developers?

**Answer:** Because its role in helping Flask locate application resources is not immediately obvious.

---

# Question: Is there only one way to initialize a Flask application?

**Answer:** No, there are more complex ways, but the basic method using `Flask(__name__)` is sufficient for simple applications.

---


