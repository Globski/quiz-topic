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

# Question: What is the drawback of embedding HTML response strings directly in Python source files?

**Answer:** It makes the code difficult to maintain.

---

# Question: How does Flask support variable sections in URLs?

**Answer:** By using a special syntax with angle brackets in the `@app.route` decorator.

---

# Question: In the Flask route `@app.route('/user/<name>')`, what does `<name>` represent?

**Answer:** It is a dynamic component of the URL that will be passed as an argument to the view function.

---

# Question: What happens when a URL matches the static portion of a Flask route that has a dynamic component?

**Answer:** Flask maps the URL to the route, and the dynamic component is passed to the view function as an argument.

---

# Question: What happens when the Flask server starts?

**Answer:** It enters a loop that accepts and services requests until the application is stopped.

---

# Question: How can the Flask server be stopped during development?

**Answer:** By pressing `Ctrl+C`.

---

# Question: What URL should you enter in a browser to access a running Flask application on the local machine?

**Answer:** `http://localhost:5000/`

---

# Question: What HTTP error code is returned if the URL path does not match any defined route in a Flask application?

**Answer:** 404

---

# Question: What does a 404 error indicate in a Flask application?

**Answer:** That the requested URL path does not exist in the application.

---

# Question: What is the intended use of the Flask development server?

**Answer:** It is intended only for development and testing purposes.

---

# Question: How can the Flask development server be started programmatically?

**Answer:** By invoking the `app.run()` method.

---

# Question: What was required in older versions of Flask to start the development server?

**Answer:** The application's main script had to include the `if __name__ == '__main__': app.run()` block.

---

# Question: Why is the `if __name__ == '__main__': app.run()` block no longer necessary in modern Flask?

**Answer:** Because the `flask run` command now starts the development server without needing that code.

---

# Question: What is the purpose of Flask's debug mode?

**Answer:** To enable the reloader and debugger modules, which improve the development experience.

---

# Question: What does the Flask reloader do?

**Answer:** It monitors all source code files and automatically restarts the server when any file is modified.

---

# Question: Why is the reloader useful during development?

**Answer:** It ensures that any saved changes are picked up immediately by restarting the server automatically.

---

# Question: What does the Flask debugger do?

**Answer:** It provides an interactive, browser-based stack trace when an unhandled exception occurs.

---

# Question: What can developers do using the Flask debugger?

**Answer:** Inspect source code and evaluate expressions anywhere in the call stack.

---

# Question: When does the Flask debugger appear?

**Answer:** When the application raises an unhandled exception during development.

---

# Question: What happens if you start the Flask server using `app.run()` instead of the `flask` command?

**Answer:** The `FLASK_APP` and `FLASK_DEBUG` environment variables are not used.

---

# Question: How can you enable debug mode programmatically when using `app.run()`?

**Answer:** By passing `debug=True` as an argument: `app.run(debug=True)`.

---

# Question: Why should debug mode **never** be enabled on a production server?

**Answer:** Because the debugger allows remote code execution, making the server vulnerable to attacks.

---

# Question: What protection does Flask provide to limit access to the debugger?

**Answer:** The debugger requires activation with a PIN, which is printed to the console by the `flask run` command.

---

# Question: What does the command `flask --help` do?

**Answer:** It displays available options and commands supported by the `flask` CLI tool.

---

# Question: What environment variable must be set to specify the Flask application to run?

**Answer:** `FLASK_APP`

---

# Question: What environment variable can be set to enable debug mode when using the `flask run` command?

**Answer:** `FLASK_DEBUG`

---

# Question: What is the purpose of the `flask` shell command?

**Answer:** It runs an interactive shell in the Flask application context.

---

# Question: What are the two most useful commands provided by the `flask` CLI?

**Answer:** `run` and `shell`

---

# Question: What does the command `flask run` do?

**Answer:** It runs the Flask development server.

---

# Question: What will be displayed if you run `flask` without any arguments?

**Answer:** A help message listing usage, options, and available commands.

---

# Question: How does the `flask` command identify which application to load?

**Answer:** It uses the `FLASK_APP` environment variable.

---

# Question: What is the purpose of the `--host` argument in the `flask run` command?

**Answer:** It tells the Flask development server which network interface to listen on for incoming connections.

---

# Question: What is the default network interface used by Flask’s development server?

**Answer:** `localhost`, which only accepts connections originating from the same machine.

---

# Question: How can you make the Flask development server accept connections from other computers on the same network?

**Answer:** By running `flask run --host 0.0.0.0`.

---

# Question: What does `0.0.0.0` mean when used with the `--host` option?

**Answer:** It means the server will listen on all available network interfaces.

---

# Question: If your Flask server is started with `--host 0.0.0.0`, how can it be accessed from other devices in the network?

**Answer:** By using the URL `http://a.b.c.d:5000`, where `a.b.c.d` is the IP address of the host machine.

---

# Question: What are the purposes of the `--reload`, `--no-reload`, `--debugger`, and `--no-debugger` options in the `flask run` command?

**Answer:** They provide finer control over the reloader and debugger, allowing them to be enabled or disabled independently of the debug mode setting.

---

# Question: What does the `--no-debugger` option do if debug mode is already enabled?

**Answer:** It disables the debugger while keeping debug mode and the reloader active.

---

# Question: What is the conventional name used for a Python virtual environment directory?

**Answer:** `venv`

---

# Question: What command is used to create a virtual environment in Python 3?

**Answer:** `python3 -m venv venv`

---

# Question: Where should your current directory be set before running the virtual environment creation command?

**Answer:** The `flasky` directory

---

# Question: What does the command `python3 -m venv venv` do?

**Answer:** It creates a new subdirectory named `venv` inside `flasky` with a project-specific Python interpreter.

---

# Question: Does Python 2 support the `venv` module?

**Answer:** No, Python 2 does not have a `venv` module.

---

# Question: What utility must be used in Python 2 to create a virtual environment?

**Answer:** The third-party utility `virtualenv`

---

# Question: What is the command to install `virtualenv` on Linux or macOS?

**Answer:** `sudo pip install virtualenv`

---

# Question: What is the command to install `virtualenv` on Windows?

**Answer:** `pip install virtualenv` (run from a Command Prompt opened as Administrator)

---

# Question: What argument does the `virtualenv` command require?

**Answer:** The name of the virtual environment directory to create

---

# Question: What command should you run to exit a virtual environment?

**Answer:** `deactivate`

---

# Question: What does the `deactivate` command do?

**Answer:** It restores the `PATH` environment variable and the terminal prompt to their original states.

---

# Question: What tool is used to install Python packages inside a virtual environment?

**Answer:** `pip`

---

# Question: How can you ensure that `pip` refers to the version inside the virtual environment?

**Answer:** By activating the virtual environment before using `pip`.

---

# Question: What command installs Flask in an activated virtual environment?

**Answer:** `pip install flask`

---

# Question: What happens when you run `pip install flask` in a virtual environment?

**Answer:** Flask and all its dependencies are installed.

---

# Question: What command lists all installed packages in the current virtual environment?

**Answer:** `pip freeze`

---

# Question: What additional information does `pip freeze` provide about each installed package?

**Answer:** The exact version number of each package.

---

# Question: What is the role of the web server in the Flask request-response cycle?

**Answer:** It receives requests from clients and forwards them to the Flask application instance.

---

# Question: What does the Flask application use to determine which code to run for a given URL?

**Answer:** A mapping of URLs to Python functions.

---

# Question: What is the term for the association between a URL and the function that handles it in Flask?

**Answer:** A **route**.

---

# Question: What is the most convenient way to define a route in Flask?

**Answer:** Using the `@app.route` decorator.

---

# Question: What does the following code do?

```python
@app.route('/')
def index():
    return '<h1>Hello World!</h1>'
```

**Answer:** It registers the `index()` function as the handler for the root URL `/`.

---

# Question: What standard Python feature is used in `@app.route`?

**Answer:** A **decorator**.

---

# Question: What is a common use of decorators in Python?

**Answer:** To register functions as handlers for certain events.

---

# Question: Besides using `@app.route`, what other method does Flask provide to define routes?

**Answer:** `app.add_url_rule()`

---

# Question: What are the three basic arguments for `app.add_url_rule()`?

**Answer:** The URL, the endpoint name, and the view function.

---

# Question: What is the content of the `hello.py` example in Flask?

**Answer:**

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def index():
    return '<h1>Hello World!</h1>'
```

---

# Question: What command is used to start the Flask development web server?

**Answer:** `flask run`

---

# Question: What environment variable must be set before running `flask run`?

**Answer:** `FLASK_APP`

---

# Question: How do Linux and macOS users set the `FLASK_APP` environment variable?

**Answer:** `export FLASK_APP=hello.py`

---

# Question: How do Microsoft Windows users set the `FLASK_APP` environment variable?

**Answer:** `set FLASK_APP=hello.py`

---

# Question: What message confirms that the Flask development server is running?

**Answer:** `* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)`

---

# Question: What must be ensured before starting the Flask app using `flask run`?

**Answer:** The virtual environment must be activated and Flask must be installed.

---

# Question: What happens once the Flask development server starts up?

**Answer:** It enters a loop that continuously accepts and handles requests until the application is stopped using Ctrl+C.

---

# Question: What URL should you enter in the browser to access the running Flask application?

**Answer:** `http://localhost:5000/`

---

# Question: What response does Flask return if you enter a URL the application does not handle?

**Answer:** It returns a 404 error code indicating the requested page was not found.

---

# Question: Is Flask's built-in web server suitable for production use?

**Answer:** No, it is intended only for development and testing.

---

# Question: What method can be used to start the Flask server programmatically?

**Answer:** `app.run()`

---

# Question: What Python code snippet is required to start a Flask app programmatically in older versions?

**Answer:**

```python
if __name__ == '__main__':
    app.run()
```

---

# Question: Why is the `app.run()` method still included in some Flask applications despite `flask run` being available?

**Answer:** It supports legacy versions of Flask that did not have the `flask` command-line tool.

---

# Question: In what situation might the `app.run()` method still be useful, despite `flask run` being available?

**Answer:** During unit testing, as covered in Chapter 15.

---

# Question: How is a dynamic route defined in Flask?

**Answer:** By using angle brackets in the route decorator, e.g., `@app.route('/user/<name>')`.

---

# Question: What is the output of visiting `http://localhost:5000/user/Dave` in the browser with the dynamic route defined?

**Answer:** `<h1>Hello, Dave!</h1>`

---

# Question: In the dynamic route example, what does the `name` argument in the `user(name)` function represent?

**Answer:** The value captured from the `<name>` segment of the URL.

---










