
# Question: Who is credited as the creator of the first website?

**Answer:** Sir Tim Berners-Lee

---

# Question: What was Sir Tim Berners-Lee’s vision for the web?

**Answer:** An open platform that allows internet users to share information, access opportunities, and collaborate without geographic and cultural restrictions.

---

# Question: How has the web evolved over time?

**Answer:** It has evolved from static web pages to dynamic and database-driven web applications.

---

# Question: What is the goal of starting a web application development project from scratch?

**Answer:** To transform it into a full-blown web application.

---

# Question: Which library is used for building the user-facing part of web applications?

**Answer:** React

---

# Question: What architecture is commonly used in web application development?

**Answer:** Client-server architecture

---

# Question: What is required before developing web applications?

**Answer:** Setting up development environments

---

# Question: How are development environments structured in web applications?

**Answer:** The frontend and backend have separate development environments.

---

# Question: Which technologies are used for frontend and backend in this stack?

**Answer:** React for frontend and Flask for backend

---

# Question: What is Git?

**Answer:** A source version control tool that helps developers track changes to the codebase.

---

# Question: What is GitHub?

**Answer:** An online platform for version control and collaboration among developers.

---

# Question: What is one purpose of deploying code to GitHub?

**Answer:** To share code and collaborate with other developers.

---

# Question: What is version control?

**Answer:** A system that tracks changes to a codebase and helps manage collaboration.

---

# Question: What advantages does version control provide?

**Answer:** Tracks changes, identifies who made changes and when, and allows reverting unwanted changes.

---

# Question: What type of version control system is Git?

**Answer:** Distributed version control system

---

# Question: What is a local repository in Git?

**Answer:** A complete copy of the source code stored on a contributor’s local machine.

---

# Question: What does Git track in a local repository?

**Answer:** All changes made to files within the repository.

---

# Question: What problem does Git solve regarding file versions?

**Answer:** It eliminates the need to maintain multiple versions in separate directories.

---

# Question: What are the three primary states in Git?

**Answer:** Modified, Staged, Committed

---

# Question: What does the "Modified" state mean in Git?

**Answer:** Files have been changed but not yet added to the local database.

---

# Question: What does the "Staged" state mean in Git?

**Answer:** Changes are tracked and ready to be committed.

---

# Question: What does the "Committed" state mean in Git?

**Answer:** Changes have been saved to the local Git database.

---

# Question: What is the frontend of a web application?

**Answer:** The client-side part that users see and interact with.

---

# Question: What is the backend of a web application?

**Answer:** The server-side part where code, databases, and infrastructure reside.

---

# Question: What connects the backend to the frontend?

**Answer:** A REST API layer

---

# Question: What are the tech stacks mentioned?

**Answer:** React and Flask

---

# Question: What type of tool is React?

**Answer:** A JavaScript frontend library

---

# Question: What company maintains React?

**Answer:** Formerly Facebook (Meta)

---

# Question: Name some companies that use React.

**Answer:** Facebook, Uber Eats, Skype, Netflix

---

# Question: What syntax does React use?

**Answer:** JSX (JavaScript XML)

---

# Question: What does JSX allow developers to do?

**Answer:** Write HTML elements inside JavaScript.

---

# Question: What is the Virtual DOM in React?

**Answer:** A representation of the real DOM that improves efficiency and performance.

---

# Question: What tool is used to compile JSX?

**Answer:** Babel

---

# Question: What is React Native used for?

**Answer:** Developing mobile applications for Android and iOS.

---

# Question: What is Flask?

**Answer:** A microframework used to build backend applications.

---

# Question: Name some JavaScript frameworks.

**Answer:** Angular, Ember.js, Vue

---

# Question: Name some templating languages.

**Answer:** Handlebars, EJS, Pug

---

# Question: What is Node.js?

**Answer:** A runtime environment for JavaScript

---

# Question: What tool comes bundled with Node.js?

**Answer:** Node Package Manager (NPM)

---

# Question: What are Node.js and NPM used for?

**Answer:** Building and running React applications

---

# Question: How do you check if Node.js is installed?

**Answer:** `node -v`

---

# Question: How do you check the NPM version?

**Answer:** `npm -v`

---

# Question: What is VS Code?

**Answer:** A free code editor for building and debugging applications.

---

# Question: What features does VS Code provide?

**Answer:** IntelliSense, code refactoring, and extensions.

---

# Question: What is a Git Client?

**Answer:** A command-line interface used to interact with Git repositories.

---

# Question: Why is a Git Client needed?

**Answer:** To track changes in project files.

---

# Question: How do you verify Git installation?

**Answer:** `git --version`

---

# Question: What language is Flask based on?

**Answer:** Python

---

# Question: What kind of applications can Flask build?

**Answer:** Enterprise-grade, scalable, reliable, and maintainable applications.

---

# Question: What is a microservice?

**Answer:** A small, independent, loosely coupled software component.

---

# Question: What flexibility does Flask provide?

**Answer:** Freedom to choose database, template engine, deployment, and manage sessions, users, and security.

---

# Question: What advantage does Flask have for APIs?

**Answer:** Easier API development and database integration.

---

# Question: How does Django differ from Flask?

**Answer:** Django enforces a structured framework with built-in components.

---

# Question: How do you check if Python is installed?

**Answer:** `python --version` or `python -c "import sys; print(sys.version)"`

---

# Question: What command is used on macOS for Python version check?

**Answer:** `python3 --version`

---

# Question: What is pip?

**Answer:** A package manager for Python

---

# Question: How do you upgrade pip?

**Answer:** `python -m pip install --upgrade pip`

---

# Question: What is a virtual environment?

**Answer:** A tool to isolate dependencies for Python projects.

---

# Question: Why use a virtual environment?

**Answer:** To avoid conflicts between project dependencies and system libraries.

---

# Question: How do you create a virtual environment?

**Answer:** `python -m venv venv`

---

# Question: What command is used on Windows to create a virtual environment?

**Answer:** `py -m venv venv`

---

# Question: What tool is used for Python 2 virtual environments?

**Answer:** virtualenv

---

# Question: What are Python frameworks mentioned?

**Answer:** Flask and Django

---

# Question: What is the first step in setting up a React project?

**Answer:** Install Node.js

---

# Question: Where do you download Node.js?

**Answer:** [https://nodejs.org/en/](https://nodejs.org/en/)

---

# Question: What editor should be installed for development?

**Answer:** VS Code

---

# Question: Where do you download Git?

**Answer:** [https://git-scm.com/downloads](https://git-scm.com/downloads)

---

# Question: What must be installed for Flask development?

**Answer:** Python and required packages

---

# Question: How do you install Flask?

**Answer:** `pip install flask`

---

# Question: What file is created to test Flask?

**Answer:** app.py
```python
from flask import Flask
app = Flask(__name__)
@app.route('/')
def index():
return 'Welcome to Gloriana Platform!'

if __name__ == '__main__':
app.run()
```
---

# Question: What does the sample Flask route return?

**Answer:** "Welcome to Gloriana Platform!"

---

# Question: What command runs the Flask app?

**Answer:** `flask run`

---

# Question: What file stores environment variables in Windows?

**Answer:** `.env`

---

# Question: What file stores environment variables in macOS/Linux?

**Answer:** `.flaskenv`

---

# Question: What variables are defined in `.flaskenv`?

**Answer:** FLASK_APP, FLASK_ENV, FLASK_DEBUG

---

# Question: What does python-dotenv do?

**Answer:** Loads environment variables into the application

---

# Question: How do you install python-dotenv?

**Answer:** `pip install python-dotenv`

---

# Question: How do you activate a virtual environment on Windows?

**Answer:** `venv\Scripts\activate` or `venv\Scripts\activate.bat`

---

# Question: How do you activate a virtual environment on macOS/Linux?

**Answer:** `source venv/bin/activate`

---

# Question: How do you deactivate a virtual environment?

**Answer:** `deactivate`

---
