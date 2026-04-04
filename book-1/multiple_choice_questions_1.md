
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

# Question: What is Git and what is its primary purpose?

**Answer:** Git is an open-source version control tool used to track changes in a codebase, record who made changes, and enable collaboration among developers.

---

# Question: What types of activities does Git track in a local project?

**Answer:** Git tracks activities such as adding files, updating existing files, and creating new folders.

---

# Question: What kind of record does Git maintain for a project?

**Answer:** Git maintains a historical record of the source code.

---

# Question: What is GitHub and how does it differ from Git?

**Answer:** GitHub is a cloud-based source code hosting and project management service that uses Git to store repositories remotely and enable collaboration, while Git itself is the version control tool.

---

# Question: What is required before creating a local Git repository?

**Answer:** You must install a Git client from [https://git-scm.com/download/](https://git-scm.com/download/).

---

# Question: What command is used to create a working directory for a local repository?

**Answer:** `mkdir local_repository`

---

# Question: How do you navigate into the created working directory?

**Answer:** `cd local_repository`

---

# Question: What command is used to create an HTML file in the working directory?

**Answer:** `touch index.html`

---

# Question: What should you do if the touch command is unavailable but Node.js is installed?

**Answer:** Install touch-cli using `npm install -g touch-cli`.

---

# Question: Why do you configure a global username and email in Git?

**Answer:** To track your identity and contributions in the project source code.

---

# Question: What command sets the global Git username?

**Answer:** `git config --global user.name "Name of User"`

---

# Question: What command sets the global Git email?

**Answer:** `git config --global user.email "test@test.com"`

---

# Question: What does the `git init` command do?

**Answer:** It creates an empty local Git repository.

---

# Question: What is created internally when `git init` is executed?

**Answer:** A hidden `.git` directory that stores metadata for tracking changes.

---

# Question: What is the staging area in Git?

**Answer:** It is the state where changes are tracked and prepared to be added to the repository in the next commit.

---

# Question: What command adds a specific file to the staging area?

**Answer:** `git add index.html`

---

# Question: How do you verify the status of your working directory and staging area?

**Answer:** `git status`

---

# Question: How do you add all files in the working directory to the staging area?

**Answer:** `git add .`

---

# Question: What is the purpose of the commit stage in Git?

**Answer:** To save tracked changes into the local repository with a message.

---

# Question: What command is used to commit changes with a message?

**Answer:** `git commit -m "first commit"`

---

# Question: Why is it important to include a commit message?

**Answer:** It helps track changes and provides a reference point for reverting changes.

---

# Question: What is the first step in setting up a remote repository on GitHub?

**Answer:** Create a developer account on [https://github.com/](https://github.com/).

---

# Question: What are the steps to create a repository on GitHub?

**Answer:** Log in, click "New", provide a repository name, and choose visibility (public or private).

---

# Question: What does the `git remote add origin` command do?

**Answer:** It links the local repository to a remote GitHub repository.

---

# Question: What is the syntax for adding a remote repository?

**Answer:** `git remote add origin https://github.com/your-git-username/your-repository-name.git`

---

# Question: What does the `git branch -M main` command do?

**Answer:** It renames the current branch to "main".

---

# Question: What does the `git push -u origin main` command do?

**Answer:** It pushes the local repository to the remote GitHub repository and sets upstream tracking.

---

# Question: What are authentication and authorization in general terms?

**Answer:** Authentication verifies identity, while authorization determines access permissions.

---

# Question: What is REST API design with Flask?

**Answer:** It refers to building RESTful APIs using the Flask framework in Python.

---

# Question: What is Vite and what is it used for?

**Answer:** Vite is a frontend tool used for rapid setup of React applications.

---

# Question: What are React components?

**Answer:** Components are reusable building blocks used to create user interfaces.

---

# Question: What are props in React?

**Answer:** Props are used to pass data between components.

---

# Question: What is state in React?

**Answer:** State is used to add interactivity and manage dynamic data in components.

---

# Question: What are ES6 features in React?

**Answer:** They are modern JavaScript features such as arrow functions, destructuring, and modules used in React development.

---

# Question: What is the purpose of understanding React directory structure?

**Answer:** To effectively organize and manage application files and development workflow.

---

# Question: What are arrow functions in React?

**Answer:** They are concise functions introduced in ES6 used for defining components and handling logic.

---

# Question: What is destructuring in JavaScript?

**Answer:** It is a syntax that allows unpacking values from arrays or objects into variables.

---

# Question: What are default exports?

**Answer:** They allow exporting a single value as the main export of a module.

---

# Question: What are named exports?

**Answer:** They allow exporting multiple values from a module using specific names.

---

# Question: What are Webpack and Babel used for?

**Answer:** They are used for bundling and transpiling JavaScript code.

---

# Question: What tool is used to create a React application without build configuration?

**Answer:** Create React App.

---

# Question: What command creates a new React application?

**Answer:** `npx create-react-app frontend`

---

# Question: How do you navigate into the React project directory?

**Answer:** `cd frontend`

---

# Question: How do you open the React project in VS Code?

**Answer:** `code .`

---

# Question: What is the purpose of the node_modules folder?

**Answer:** It contains all installed dependencies and devDependencies.

---

# Question: What happens to newly installed packages in a React project?

**Answer:** They are stored in the node_modules folder.

---

# Question: What is the purpose of the public folder?

**Answer:** It contains public files like index.html and manifest.json.

---

# Question: What is the role of public/index.html?

**Answer:** It serves as the entry HTML file where React renders components into the root div.

---

# Question: What is the purpose of manifest.json?

**Answer:** It contains metadata for responsive display and application configuration.

---

# Question: Why is the src folder important?

**Answer:** It contains most of the application code and components.

---

# Question: What percentage of development typically happens in the src folder?

**Answer:** More than 80%.

---

# Question: What is the purpose of src/App.js?

**Answer:** It is used to implement React components.

---

# Question: When might you keep all components in App.js?

**Answer:** In small projects.

---

# Question: Why might you split components into multiple files?

**Answer:** To improve scalability and organization in larger applications.

---

# Question: What is the purpose of src/App.css?

**Answer:** It styles individual components.

---

# Question: What is the purpose of src/index.css?

**Answer:** It styles the overall application.

---

# Question: What is src/App.test.js used for?

**Answer:** Writing unit tests for the application.

---

# Question: What is the role of src/index.js?

**Answer:** It is the entry point of the React application.

---

# Question: What is the purpose of the .gitignore file?

**Answer:** It specifies files and folders that should not be tracked by Git.

---

# Question: Why is node_modules included in .gitignore?

**Answer:** Because it is only needed in the development environment.

---

# Question: What is the purpose of package.json?

**Answer:** It stores dependencies and project metadata.

---

# Question: How does package.json help with project setup?

**Answer:** It allows easy installation of dependencies on another system using npm.

---

# Question: What is the purpose of package-lock.json?

**Answer:** It locks dependency versions to ensure consistent installations across systems.

---

# Question: What is README.md?

**Answer:** A Markdown file used to document project information and instructions.

---

# Question: What is Markdown?

**Answer:** A lightweight markup language for formatting text.

---

# Question: What command starts the React development server?

**Answer:** `npm start`

---

# Question: What command builds a React app for production?

**Answer:** `npm run build`

---

# Question: What command starts the test runner in React?

**Answer:** `npm test`

---

# Question: What are arrow functions in JavaScript?

**Answer:** A concise syntax for writing functions introduced in ES6.

---

# Question: How do arrow functions improve code readability?

**Answer:** By providing shorter and cleaner syntax compared to traditional functions.

---

# Question: How is a traditional function defined for adding two numbers?

**Answer:**

```
function addNumbers(a, b) {
  return a + b;
}
```

---

# Question: How is the same function written using an arrow function?

**Answer:**

```
const addNumbers = (a, b) => {
  return a + b;
};
```

---

# Question: How can arrow functions be shortened further?

**Answer:** By omitting curly braces and return for single-line expressions:

```
const addNumbers = (a, b) => a + b;
```

---

# Question: What is the general syntax for arrow functions?

**Answer:**

```
const functionName = (parameters) => {
  return returnValue;
};
```

---

# Question: What syntax is used for implicit return in arrow functions?

**Answer:**

```
const functionName = (parameters) => returnValue;
```

---

# Question: Where are arrow functions commonly used in React?

**Answer:** In function components, event handlers, and array mapping.

---

# Question: What limitation do arrow functions have regarding `this`?

**Answer:** They do not have their own `this` context.

---

# Question: Why does the lack of `this` make arrow functions unsuitable in some cases?

**Answer:** Because they cannot be used as object methods where a dynamic `this` is required.

---

# Question: What is Git and what is its primary purpose?

**Answer:** Git is an open-source version control tool used to track changes in a codebase, record who made changes, and enable collaboration among developers.

---

# Question: What types of activities does Git track in a local project?

**Answer:** Git tracks activities such as adding files, updating existing files, and creating new folders.

---

# Question: What kind of record does Git maintain for a project?

**Answer:** Git maintains a historical record of the source code.

---

# Question: What is GitHub and how does it differ from Git?

**Answer:** GitHub is a cloud-based source code hosting and project management service that uses Git to store repositories remotely and enable collaboration, while Git itself is the version control tool.

---

# Question: What is required before creating a local Git repository?

**Answer:** You must install a Git client from [https://git-scm.com/download/](https://git-scm.com/download/).

---

# Question: What command is used to create a working directory for a local repository?

**Answer:** `mkdir local_repository`

---

# Question: How do you navigate into the created working directory?

**Answer:** `cd local_repository`

---

# Question: What command is used to create an HTML file in the working directory?

**Answer:** `touch index.html`

---

# Question: What should you do if the touch command is unavailable but Node.js is installed?

**Answer:** Install touch-cli using `npm install -g touch-cli`.

---

# Question: Why do you configure a global username and email in Git?

**Answer:** To track your identity and contributions in the project source code.

---

# Question: What command sets the global Git username?

**Answer:** `git config --global user.name "Name of User"`

---

# Question: What command sets the global Git email?

**Answer:** `git config --global user.email "test@test.com"`

---

# Question: What does the `git init` command do?

**Answer:** It creates an empty local Git repository.

---

# Question: What is created internally when `git init` is executed?

**Answer:** A hidden `.git` directory that stores metadata for tracking changes.

---

# Question: What is the staging area in Git?

**Answer:** It is the state where changes are tracked and prepared to be added to the repository in the next commit.

---

# Question: What command adds a specific file to the staging area?

**Answer:** `git add index.html`

---

# Question: How do you verify the status of your working directory and staging area?

**Answer:** `git status`

---

# Question: How do you add all files in the working directory to the staging area?

**Answer:** `git add .`

---

# Question: What is the purpose of the commit stage in Git?

**Answer:** To save tracked changes into the local repository with a message.

---

# Question: What command is used to commit changes with a message?

**Answer:** `git commit -m "first commit"`

---

# Question: Why is it important to include a commit message?

**Answer:** It helps track changes and provides a reference point for reverting changes.

---

# Question: What is the first step in setting up a remote repository on GitHub?

**Answer:** Create a developer account on [https://github.com/](https://github.com/).

---

# Question: What are the steps to create a repository on GitHub?

**Answer:** Log in, click "New", provide a repository name, and choose visibility (public or private).

---

# Question: What does the `git remote add origin` command do?

**Answer:** It links the local repository to a remote GitHub repository.

---

# Question: What is the syntax for adding a remote repository?

**Answer:** `git remote add origin https://github.com/your-git-username/your-repository-name.git`

---

# Question: What does the `git branch -M main` command do?

**Answer:** It renames the current branch to "main".

---

# Question: What does the `git push -u origin main` command do?

**Answer:** It pushes the local repository to the remote GitHub repository and sets upstream tracking.

---

# Question: What are authentication and authorization in general terms?

**Answer:** Authentication verifies identity, while authorization determines access permissions.

---

# Question: What is REST API design with Flask?

**Answer:** It refers to building RESTful APIs using the Flask framework in Python.

---

# Question: What is Vite and what is it used for?

**Answer:** Vite is a frontend tool used for rapid setup of React applications.

---

# Question: What are React components?

**Answer:** Components are reusable building blocks used to create user interfaces.

---

# Question: What are props in React?

**Answer:** Props are used to pass data between components.

---

# Question: What is state in React?

**Answer:** State is used to add interactivity and manage dynamic data in components.

---

# Question: What are ES6 features in React?

**Answer:** They are modern JavaScript features such as arrow functions, destructuring, and modules used in React development.

---

# Question: What is the purpose of understanding React directory structure?

**Answer:** To effectively organize and manage application files and development workflow.

---

# Question: What are arrow functions in React?

**Answer:** They are concise functions introduced in ES6 used for defining components and handling logic.

---

# Question: What is destructuring in JavaScript?

**Answer:** It is a syntax that allows unpacking values from arrays or objects into variables.

---

# Question: What are default exports?

**Answer:** They allow exporting a single value as the main export of a module.

---

# Question: What are named exports?

**Answer:** They allow exporting multiple values from a module using specific names.

---

# Question: What are Webpack and Babel used for?

**Answer:** They are used for bundling and transpiling JavaScript code.

---

# Question: What tool is used to create a React application without build configuration?

**Answer:** Create React App.

---

# Question: What command creates a new React application?

**Answer:** `npx create-react-app frontend`

---

# Question: How do you navigate into the React project directory?

**Answer:** `cd frontend`

---

# Question: How do you open the React project in VS Code?

**Answer:** `code .`

---

# Question: What is the purpose of the node_modules folder?

**Answer:** It contains all installed dependencies and devDependencies.

---

# Question: What happens to newly installed packages in a React project?

**Answer:** They are stored in the node_modules folder.

---

# Question: What is the purpose of the public folder?

**Answer:** It contains public files like index.html and manifest.json.

---

# Question: What is the role of public/index.html?

**Answer:** It serves as the entry HTML file where React renders components into the root div.

---

# Question: What is the purpose of manifest.json?

**Answer:** It contains metadata for responsive display and application configuration.

---

# Question: Why is the src folder important?

**Answer:** It contains most of the application code and components.

---

# Question: What percentage of development typically happens in the src folder?

**Answer:** More than 80%.

---

# Question: What is the purpose of src/App.js?

**Answer:** It is used to implement React components.

---

# Question: When might you keep all components in App.js?

**Answer:** In small projects.

---

# Question: Why might you split components into multiple files?

**Answer:** To improve scalability and organization in larger applications.

---

# Question: What is the purpose of src/App.css?

**Answer:** It styles individual components.

---

# Question: What is the purpose of src/index.css?

**Answer:** It styles the overall application.

---

# Question: What is src/App.test.js used for?

**Answer:** Writing unit tests for the application.

---

# Question: What is the role of src/index.js?

**Answer:** It is the entry point of the React application.

---

# Question: What is the purpose of the .gitignore file?

**Answer:** It specifies files and folders that should not be tracked by Git.

---

# Question: Why is node_modules included in .gitignore?

**Answer:** Because it is only needed in the development environment.

---

# Question: What is the purpose of package.json?

**Answer:** It stores dependencies and project metadata.

---

# Question: How does package.json help with project setup?

**Answer:** It allows easy installation of dependencies on another system using npm.

---

# Question: What is the purpose of package-lock.json?

**Answer:** It locks dependency versions to ensure consistent installations across systems.

---

# Question: What is README.md?

**Answer:** A Markdown file used to document project information and instructions.

---

# Question: What is Markdown?

**Answer:** A lightweight markup language for formatting text.

---

# Question: What command starts the React development server?

**Answer:** `npm start`

---

# Question: What command builds a React app for production?

**Answer:** `npm run build`

---

# Question: What command starts the test runner in React?

**Answer:** `npm test`

---

# Question: What are arrow functions in JavaScript?

**Answer:** A concise syntax for writing functions introduced in ES6.

---

# Question: How do arrow functions improve code readability?

**Answer:** By providing shorter and cleaner syntax compared to traditional functions.

---

# Question: How is a traditional function defined for adding two numbers?

**Answer:**

```
function addNumbers(a, b) {
  return a + b;
}
```

---

# Question: How is the same function written using an arrow function?

**Answer:**

```
const addNumbers = (a, b) => {
  return a + b;
};
```

---

# Question: How can arrow functions be shortened further?

**Answer:** By omitting curly braces and return for single-line expressions:

```
const addNumbers = (a, b) => a + b;
```

---

# Question: What is the general syntax for arrow functions?

**Answer:**

```
const functionName = (parameters) => {
  return returnValue;
};
```

---

# Question: What syntax is used for implicit return in arrow functions?

**Answer:**

```
const functionName = (parameters) => returnValue;
```

---

# Question: Where are arrow functions commonly used in React?

**Answer:** In function components, event handlers, and array mapping.

---

# Question: What limitation do arrow functions have regarding `this`?

**Answer:** They do not have their own `this` context.

---

# Question: Why does the lack of `this` make arrow functions unsuitable in some cases?

**Answer:** Because they cannot be used as object methods where a dynamic `this` is required.

---
