# Question: What is Flask and why is it considered minimalistic?

**Answer:**
Flask is a minimalistic Python web framework that provides starting components for building modern web applications without enforcing a strict project structure or including boilerplate code.

---

# Question: How does Flask differ from Django in terms of architecture and design philosophy?

**Answer:**
Flask offers flexibility by not enforcing project structure or component usage, while Django is more opinionated, offering a full-stack, out-of-the-box solution with rigid architectural guidelines.

---

# Question: Why is Flask considered lightweight?

**Answer:**
Flask only includes core components necessary to get started, without requiring predefined structures or extra tools, making it a microframework.

---

# Question: What level of control does Flask provide to developers compared to Django?

**Answer:**
Flask allows developers to choose their own database, template engine, deployment process, and session/security management methods, whereas Django enforces specific tools and practices.

---

# Question: What makes Flask suitable for microservices architecture?

**Answer:**
Flask’s lightweight, flexible, and modular nature makes it ideal for building independent, loosely coupled microservices that focus on specific functions.

---

# Question: What is a microservice in the context of web development?

**Answer:**
A microservice is a small, independent, and loosely coupled software component that performs a specific function within a larger application.

---

# Question: Why did Pinterest choose Flask over Django?

**Answer:**
Pinterest switched to Flask for its API and microservices due to Flask's simplicity, flexibility, and better scalability for high-traffic, large-scale applications.

---

# Question: What makes Flask easier for Python developers to contribute to?

**Answer:**
Flask's simplicity, flexibility, and alignment with core Python syntax make it easy for Python developers to understand and contribute without needing to learn rigid conventions.

---

# Question: How does Flask's flexibility benefit time to market and performance?

**Answer:**
Flask’s lightweight nature avoids the overhead of complex frameworks, reducing development time and potentially improving performance.

---

# Question: What is meant by Flask being "less opinionated"?

**Answer:**
It means Flask imposes fewer conventions and standards, giving developers more freedom to structure their applications as they see fit.

---

# Question: Why is scaling considered a challenge with Django?

**Answer:**
Django’s monolithic structure and built-in components can complicate scaling and impact performance in large, distributed systems.

---

# Question: What benefits can be achieved by combining React with Flask?

**Answer:**
Combining React with Flask improves scalability, reusability, maintainability, and the development of secure web and mobile applications.

---

# Question: What role does cloud computing play in Flask-based applications?

**Answer:**
Cloud computing enhances Flask applications by providing scalable infrastructure ideal for microservices and distributed architectures.

---

# Question: What is the first step in setting up a Flask development environment?

**Answer:**
Install Python.

---

# Question: How can you check if Python is already installed on your system (Windows or macOS/Linux)?

**Answer:**
Run `$ python --version` or `$ python -c "import sys; print(sys.version)"` in the terminal.

---

# Question: What command works specifically on macOS/Linux to check Python 3 installation?

**Answer:**
`$ python3 --version`

---

# Question: Where can you download Python if it is not installed?

**Answer:**
From the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

---

# Question: What is pip and why is it important?

**Answer:**
pip is a package manager for Python used to install and update Python packages necessary for development.

---

# Question: How do you upgrade pip?

**Answer:**
Run `$ python -m pip install --upgrade pip`

---

# Question: What is a virtual environment in Python?

**Answer:**
A virtual environment is a self-contained directory that allows you to manage dependencies separately for each project without affecting system-wide Python installations.

---

# Question: How do you create a virtual environment in Python?

**Answer:**
Run `$ python -m venv venv` or `$ py -m venv venv` (on Windows).

---

# Question: How do you activate a virtual environment on Windows?

**Answer:**
Run `$ venv\Scripts\activate`

---

# Question: If `$ venv\Scripts\activate` doesn't work on Windows, what alternative should be used?

**Answer:**
Use `$ venv\Scripts\activate.bat`

---

# Question: How do you activate a virtual environment on macOS/Linux?

**Answer:**
Run `$ source venv/bin/activate`

---

# Question: What command is used to install Flask after activating the virtual environment?

**Answer:**
`$ pip install flask`

---

# Question: What is the purpose of the `app.py` file in a Flask project?

**Answer:**
It contains the Flask application code used to define routes and run the server.

---

# Question: What is the minimal content of a `app.py` file to test a Flask app?

**Answer:**

```python
from flask import Flask  
app = Flask(__name__)  
@app.route('/')  
def index():  
    return 'Welcome to Latto Platform!'  
if __name__ == '__main__':  
    app.run()
```

---

# Question: What environment variable file can be created to manage Flask settings?

**Answer:**
Either `.env` or `.flaskenv`

---

# Question: What three variables should be included in the `.flaskenv` file?

**Answer:**

```
FLASK_APP=app.py  
FLASK_ENV=development  
FLASK_DEBUG=true
```

---

# Question: What package should be installed to load environment variables from `.env` or `.flaskenv`?

**Answer:**
`python-dotenv`

---

# Question: What command installs `python-dotenv`?

**Answer:**
`$ pip install python-dotenv`

---

# Question: How do you run a Flask application from the terminal?

**Answer:**
`$ flask run`

---

# Question: What command is used to exit a virtual environment?

**Answer:**
`$ deactivate`

---
