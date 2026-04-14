
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

**Answer:** Distributed version control system.

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

# Question: Why should arrow functions not be used as object methods when accessing object properties like `name`?

**Answer:** Because arrow functions do not have their own `this` context, so they cannot properly access properties like `this.name` within the object.

---

# Question: What is the output of a regular function method accessing `this.name` in an object?

**Answer:** It correctly outputs the value of the `name` property, e.g., `"Hi, I'm Alice Andrew!"`.

---

# Question: What happens when an arrow function is used as an object method that references `this.name`?

**Answer:** It returns `undefined` because `this` does not refer to the object.

---

# Question: Why are arrow functions still useful despite their limitation with `this`?

**Answer:** They make code cleaner, are concise, and are especially useful for short functions and in React development.

---

# Question: What is destructuring in JavaScript?

**Answer:** Destructuring is an ES6 feature that allows extracting values from arrays or properties from objects into separate variables.

---

# Question: What problem does destructuring solve compared to pre-ES6 JavaScript?

**Answer:** It reduces repetitive code needed to extract values from arrays or objects using indexing or dot notation.

---

# Question: How were array values accessed before destructuring?

**Answer:** By assigning each element individually using indexes, e.g., `speakers[0]`, `speakers[1]`.

---

# Question: How does array destructuring simplify value extraction?

**Answer:** It allows assigning multiple variables in one line using array pattern syntax.

---

# Question: What is the result of destructuring an array into variables `[a, b, c, d]`?

**Answer:** Each variable gets the corresponding value from the array based on position.

---

# Question: What does the spread operator (`...`) do in array destructuring?

**Answer:** It collects the remaining elements of the array into a new array.

---

# Question: What does `const [, ...rest] = speakers` do?

**Answer:** It skips the first element and assigns the remaining elements to the `rest` array.

---

# Question: What is the output of logging `rest` after skipping the first array element?

**Answer:** An array containing all elements except the first (e.g., `"Walke", "Dan", "Sophie"`).

---

# Question: Can destructuring be applied to objects?

**Answer:** Yes, destructuring can extract properties from objects into variables.

---

# Question: How do you destructure properties like `name`, `jobTitle`, and `company` from an object?

**Answer:** Using syntax like `const { name, jobTitle, company } = object`.

---

# Question: Can nested object properties be destructured?

**Answer:** Yes, nested properties can be destructured by first extracting the parent object, then destructuring its properties.

---

# Question: How do you destructure nested properties like `street`, `city`, `state`, and `country`?

**Answer:** By first destructuring `address` and then extracting its properties using another destructuring statement.

---

# Question: What is one major benefit of destructuring in React applications?

**Answer:** It makes code more compact and easier to read.

---

# Question: How does destructuring improve code readability?

**Answer:** By reducing repetitive access patterns like dot notation or array indexing.

---

# Question: How can default values be set during destructuring?

**Answer:** By assigning values in the destructuring pattern, e.g., `const { name = 'Anonymous', age = 0 }`.

---

# Question: When are default values in destructuring useful?

**Answer:** When dealing with optional or undefined data.

---

# Question: How is destructuring used in React components?

**Answer:** It is commonly used to access props and state.

---

# Question: What is the purpose of modules in ES6?

**Answer:** To organize code into reusable, logical units.

---

# Question: What is a default export in ES6?

**Answer:** A single export per file that makes a component, function, or variable available to other files.

---

# Question: How do you import a default export?

**Answer:** Using syntax like `import ComponentName from './FileName';`.

---

# Question: How do you define a default export in a file?

**Answer:** Using `export default ComponentName;`.

---

# Question: How many default exports are allowed per file?

**Answer:** Only one.

---

# Question: What is a named export?

**Answer:** An export that allows multiple items to be exported from a file.

---

# Question: How do you import named exports?

**Answer:** Using curly braces, e.g., `import { A, B } from './File';`.

---

# Question: What is the advantage of named exports?

**Answer:** They allow multiple functions or components to be exported from a single file.

---

# Question: What is a React component?

**Answer:** A reusable, self-contained block of code that returns a UI.

---

# Question: What do React components return?

**Answer:** HTML elements mixed with JavaScript (JSX).

---

# Question: Why is working with the DOM in vanilla JavaScript inefficient?

**Answer:** Because frequent DOM manipulation is slow and requires more effort.

---

# Question: How does React improve DOM performance?

**Answer:** By using the virtual DOM to update only the parts that change.

---

# Question: What are the two types of React components?

**Answer:** Class components and function components.

---

# Question: Which type of component is considered the future of React?

**Answer:** Function components.

---

# Question: Why are function components preferred over class components?

**Answer:** They are simpler and easier to learn.

---

# Question: Can function and class components be used together?

**Answer:** Yes, especially in legacy codebases.

---

# Question: What is a function component in React?

**Answer:** A JavaScript function that receives props and returns JSX.

---

# Question: How do you define a function component?

**Answer:** Using a function like `function App() {}`.

---

# Question: What is JSX?

**Answer:** A syntax extension that allows writing HTML-like code inside JavaScript.

---

# Question: Where can logic be written inside a function component?

**Answer:** Between the function definition and the return statement.

---

# Question: What happens to variables declared inside a function component body?

**Answer:** They are re-declared every time the component renders.

---

# Question: When should variables be defined outside a function component?

**Answer:** When they do not depend on the component’s internal logic or state.

---

# Question: What command is used to start a React application?

**Answer:** `npm start`.

---

# Question: What happens when you save changes while the React server is running?

**Answer:** The application recompiles and updates automatically in the browser.

---

# Question: What is the default local development URL for a React app?

**Answer:** `localhost:3000`.

---

# Question: What is a class component in React?

**Answer:** A JavaScript class that extends `React.Component` and includes a render method.

---

# Question: Why are class components called stateful components?

**Answer:** Because they were originally the only way to manage state in React.

---

# Question: What must every class component include?

**Answer:** A `render()` method that returns HTML (JSX).

---

# Question: What does `extends React.Component` do?

**Answer:** It allows the class to inherit functionality from React’s base component.

---

# Question: What is the purpose of importing React in a class component file?

**Answer:** To access React’s core functionality.

---

# Question: What does the `render()` method return in a class component?

**Answer:** HTML elements (JSX) that define the UI.

---

# Question: What was introduced to replace state handling in class components?

**Answer:** React Hooks.

---

# Question: What is one key benefit of destructuring for nested data?

**Answer:** It simplifies access to deeply nested properties.

---

# Question: How does destructuring reduce code length?

**Answer:** By eliminating repetitive variable assignments and access patterns.

---

# Question: What role does destructuring play in improving React code quality?

**Answer:** It enhances readability, maintainability, and reduces boilerplate code.

---


# Question: What command is used in the terminal to start the React development server?

**Answer:** `npm start`

---

# Question: What URL is used to access the running React development server locally?

**Answer:** `http://localhost:3000/`

---

# Question: What is one key advantage of function components over class components?

**Answer:** They use fewer lines of code, making them more elegant, concise, and readable.

---

# Question: Do function components require a `render()` method?

**Answer:** No, function components do not require a `render()` method.

---

# Question: How do function components produce UI output?

**Answer:** By directly returning JSX from the function.

---

# Question: How is a class component defined in React?

**Answer:** By extending `React.Component` using the `extends` keyword.

---

# Question: What is required in every class component to render UI?

**Answer:** A `render()` method.

---

# Question: What is the role of the `render()` method in a class component?

**Answer:** It returns React elements (JSX) that define what gets displayed in the UI.

---

# Question: What type of components were traditionally stateful before React Hooks?

**Answer:** Class components.

---

# Question: What type of components were traditionally stateless before React Hooks?

**Answer:** Function components.

---

# Question: How did React Hooks change function components starting from React 16.8?

**Answer:** Hooks made it possible for function components to manage state and become stateful.

---

# Question: Can function components use lifecycle methods like `componentDidMount()`?

**Answer:** No, function components cannot use traditional lifecycle methods.

---

# Question: Name three lifecycle methods available in class components.

**Answer:** `componentDidMount()`, `componentDidUpdate()`, and `componentWillUnmount()`.

---

# Question: What are the three main phases of a React component lifecycle?

**Answer:** Mounting, updating, and unmounting.

---

# Question: What happens during the mounting phase of a React component?

**Answer:** The component is created and inserted into the DOM.

---

# Question: Which lifecycle method is called before a component is mounted and is part of the mounting phase?

**Answer:** `constructor()`

---

# Question: What argument does the `constructor()` method accept?

**Answer:** `props`

---

# Question: Why is `super(props)` called inside the constructor?

**Answer:** To pass props to the parent class (`React.Component`).

---

# Question: What are the two main purposes of the constructor in a class component?

**Answer:**

1. Initialize local state using `this.state`
2. Bind event handler methods

---

# Question: Which lifecycle method is called right before rendering in the mounting phase?

**Answer:** `static getDerivedStateFromProps()`

---

# Question: What is the role of `getDerivedStateFromProps()`?

**Answer:** It is invoked immediately before rendering to update state based on props.

---

# Question: Which lifecycle method is responsible for rendering HTML elements to the DOM?

**Answer:** `render()`

---

# Question: What determines what is displayed in the UI of a React component?

**Answer:** The JSX returned by the `render()` method.

---

# Question: When is `componentDidMount()` called in the lifecycle?

**Answer:** After the component is rendered into the DOM (after the first `render()` call).

---

# Question: What is a common use of `componentDidMount()`?

**Answer:** To perform side effects or user actions after the component is mounted.

---

# Question: What is meant by the term "component lifecycle" in React?

**Answer:** The sequence of phases a component goes through from creation to removal (mounting, updating, unmounting).

---

# Question: How is the lifecycle of a React component compared to real life?

**Answer:** It is compared to being born (mounting), growing (updating), and dying (unmounting).

---

# Question: What does it mean that function components accept props as arguments?

**Answer:** Props are passed directly into the function as parameters.

---

# Question: What makes function components simpler than class components?

**Answer:** They eliminate the need for class syntax, `this`, and lifecycle method definitions like `render()`.

---

# Question: What is required to make a function component stateful before React Hooks?

**Answer:** It had to be rewritten as a class component.

---

# Question: What is JSX in the context of React components?

**Answer:** A syntax extension that allows writing HTML-like code within JavaScript to describe UI structure.

---

# Question: What types of operations can the `componentDidMount()` method perform in a React component lifecycle?

**Answer:** It can run statements that require loading data from external sources and trigger user or system events after the component has been rendered.

---

# Question: When is the `componentDidMount()` method invoked in the React lifecycle?

**Answer:** It is invoked after the component has been rendered and mounted into the DOM.

---

# Question: What is the updating phase in the React component lifecycle?

**Answer:** The updating phase is the stage immediately after mounting where the component reacts to changes in state or props and re-renders accordingly.

---

# Question: Which method is commonly used during the updating phase of a React component lifecycle?

**Answer:** `componentDidUpdate()`.

---

# Question: What triggers a React component to update?

**Answer:** A component updates when there is a change in its state or props.

---

# Question: How does React handle updates to state or props?

**Answer:** React re-renders the component using the `render()` method and returns the updated state to the UI.

---

# Question: What is the unmounting phase in React?

**Answer:** It is the phase where a component is removed from the DOM tree, marking the end (death) of its lifecycle.

---

# Question: Which lifecycle method is invoked during the unmounting phase?

**Answer:** `componentWillUnmount()`.

---

# Question: When exactly is `componentWillUnmount()` executed?

**Answer:** Immediately before the component is unmounted from the DOM tree.

---

# Question: How does user interaction relate to the React component lifecycle?

**Answer:** User interactions cause components to be inserted into the DOM, updated through state changes, or removed when no longer needed.

---

# Question: What happens to a component when a user navigates away from it (e.g., from a contact page to another UI element)?

**Answer:** The component’s lifecycle ends, and it is unmounted from the DOM.

---

# Question: What are props in React?

**Answer:** Props are arguments passed to React components that allow them to communicate and share data.

---

# Question: What is the purpose of props in React applications?

**Answer:** They enable data transfer between components, making applications reusable and configurable.

---

# Question: How are props passed in React?

**Answer:** Props are passed as attributes from a parent component to a child component.

---

# Question: What type of data structure are props?

**Answer:** Props are objects that store attribute values.

---

# Question: How is the concept of props similar to HTML?

**Answer:** Like HTML attributes, props pass values to components via attributes.

---

# Question: What is the direction of data flow for props in React?

**Answer:** Unidirectional—from parent to child components.

---

# Question: Can child components modify props?

**Answer:** No, props are read-only and cannot be modified by child components.

---

# Question: What is React state?

**Answer:** State is a built-in object used to store and manage data that can change over time within a component.

---

# Question: What is the primary role of state in React?

**Answer:** It controls component interactivity and determines how components behave and render.

---

# Question: What happens when a component’s state changes?

**Answer:** React re-renders the component to reflect the updated state.

---

# Question: What factors can cause a state change?

**Answer:** User actions or system-generated events.

---

# Question: How do props and state differ in React?

**Answer:** Props pass data between components, while state manages internal data within a component.

---

# Question: What is an example of state change in a user interface?

**Answer:** Typing into a search input field, where the typed text becomes the new state.

---

# Question: Why is state needed in input fields?

**Answer:** To capture user input, update the UI, and trigger re-rendering with new data.

---

# Question: How does `useState` indicate that state will change over time?

**Answer:** By initializing with a value (e.g., an empty string), signaling React that the state is dynamic.

---

# Question: What is the significance of state in building user interfaces?

**Answer:** It enables dynamic, interactive UIs that respond to user input and system events.

---

# Question: How do developers benefit from using state in React?

**Answer:** They can manage changing data and create responsive user experiences.

---

# Question: What is the relationship between state updates and UI rendering?

**Answer:** State updates trigger re-rendering, ensuring the UI reflects the latest data.

---

# Question: What overall role do props and state play together in React?

**Answer:** Props handle data flow between components, while state manages dynamic data within components to create interactive applications.

---

# Question: What is the role of state in React applications?

**Answer:** State is the medium through which interactivity is added to the user interface, enabling dynamic behavior in components.

---

# Question: Before React v16.8, how could developers add state to components?

**Answer:** By using class components, as functional components were stateless.

---

# Question: What limitation did functional components have before React v16.8?

**Answer:** They were stateless and could only render JSX as presentational components.

---

# Question: What feature introduced state management to functional components?

**Answer:** The Hooks API.

---

# Question: What are the fundamental building blocks of a React application?

**Answer:** Components.

---

# Question: Why is making components stateful important?

**Answer:** It enhances the user experience by enabling dynamic and interactive behavior.

---

# Question: Name at least five React Hooks used for stateful logic.

**Answer:** useState, useEffect, useContext, useMemo, useReducer.

---

# Question: Which Hook is used to create stateful components?

**Answer:** useState.

---

# Question: Which Hook is used to handle side effects in React components?

**Answer:** useEffect.

---

# Question: Which Hook is used for managing global state in React applications?

**Answer:** useContext.

---

# Question: Which Hook allows direct access to DOM elements and persistence of values?

**Answer:** useRef.

---

# Question: Which Hook is used for complex state management similar to Redux patterns?

**Answer:** useReducer.

---

# Question: Which Hook is used to improve performance by memoizing values?

**Answer:** useMemo.

---

# Question: Which Hook helps prevent unnecessary re-rendering of functions?

**Answer:** useCallback.

---

# Question: What is the purpose of custom Hooks?

**Answer:** To enable code reusability by encapsulating reusable logic.

---

# Question: What is a Hook in React?

**Answer:** A Hook is a special function that allows function components to use React core features like state and lifecycle methods.

---

# Question: What two major features do Hooks enable in function components?

**Answer:** State management and lifecycle handling.

---

# Question: What does the lifecycle of a React component represent?

**Answer:** The phases a component goes through from initialization to removal from the UI.

---

# Question: What are the three main lifecycle phases in React?

**Answer:** Mounting, updating, and unmounting.

---

# Question: What happens during the mounting phase?

**Answer:** The component is initialized and inserted into the DOM.

---

# Question: What happens during the updating phase?

**Answer:** The component re-renders due to changes in state or props.

---

# Question: What happens during the unmounting phase?

**Answer:** The component is removed from the DOM when no longer needed.

---

# Question: Name two lifecycle methods used in class components during mounting.

**Answer:** componentWillMount() and componentDidMount().

---

# Question: Name two lifecycle methods used during updating in class components.

**Answer:** componentWillUpdate() and componentDidUpdate().

---

# Question: Why are Hooks preferred over lifecycle methods in modern React?

**Answer:** They allow function components to be stateful without requiring class components.

---

# Question: Before React 16.8, what was the only way to make components stateful?

**Answer:** By using class components.

--

# Question: What does `import React from 'react';` do?

**Answer:** It imports the React library and its core features into the file.

---

# Question: What does `class App extends React.Component` signify?

**Answer:** It defines a class component named App that inherits from React.Component.

---

# Question: What modern React feature replaces the need for this class-based approach?

**Answer:** React Hooks.

---

# Question: What key advantage do Hooks provide over class components?

**Answer:** They simplify state management and lifecycle handling in functional components without needing classes.

---

# Question: What does "state transition" refer to in React?

**Answer:** The process of updating state values in response to user actions or events.

---

# Question: What kind of component would only render JSX without Hooks?

**Answer:** A stateless functional (presentational) component.

---

# Question: What does it mean for a Hook to be “special”?

**Answer:** It is a React-provided function that enables use of internal React features in function components.

---

# Question: What happens to a component when a user navigates away from the UI?

**Answer:** It enters the unmounting phase and is removed from the DOM.

---

# Question: What concept tracks a component from creation to removal?

**Answer:** The component lifecycle.

---

# Question: What is the primary goal of using Hooks in modern React development?

**Answer:** To build stateful, reusable, and efficient functional components.

---
