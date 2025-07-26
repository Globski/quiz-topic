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

# Question: What is the primary purpose of version control in software development?

**Answer:** To track and manage changes in a code base, enabling developers to monitor updates, identify contributors, and reverse undesirable changes.

---

# Question: In what way does version control improve team collaboration?

**Answer:** It allows tracking of who made changes and when, simplifies merging contributions, and enables easy reversion of undesirable edits.

---

# Question: Which tool is currently the market leader for version control?

**Answer:** Git.

---

# Question: What are the three primary file states in Git?

**Answer:** Modified, Staged, and Committed.

---

# Question: What does the "Modified" state mean in Git?

**Answer:** A file has been changed since the last commit but is not yet tracked for inclusion in the Git local database.

---

# Question: What is the meaning of the "Staged" state in Git?

**Answer:** Changes are tracked and prepared to be added to the Git local database in the next commit.

---

# Question: What does the "Committed" state indicate in Git?

**Answer:** Changes have been added to the Git local database and are now part of version history.

---

# Question: What is a local repository in Git?

**Answer:** A complete copy of the source code and Git history stored on a contributor’s local machine.

---

# Question: How does Git simplify managing multiple versions of a project?

**Answer:** By tracking all changes within one repository instead of needing multiple separate directories.

---

# Question: What is Git classified as, in terms of version control system architecture?

**Answer:** A distributed version control system.

---

# Question: What command initializes a new Git repository?

**Answer:** `git init`

---

# Question: What folder is created after running `git init`, and what does it contain?

**Answer:** A hidden `.git` folder containing metadata to track changes in the working directory.

---

# Question: What command adds a file to the staging area in Git?

**Answer:** `git add [filename]` (e.g., `git add index.html`)

---

# Question: What Git command shows the current status of files in the repository?

**Answer:** `git status`

---

# Question: What command is used to commit staged changes with a message?

**Answer:** `git commit -m "commit message"`

---

# Question: Why is it best practice to include a message in a Git commit?

**Answer:** It helps track the purpose of changes and provides a reference point for future reversions.

--

# Question: What is Git?

**Answer:** An open-source version control tool used to track changes in code and manage collaboration.

---

# Question: What is GitHub?

**Answer:** A cloud-based source code hosting and project management platform that works with Git.

---

# Question: How does GitHub complement Git?

**Answer:** It enables cloud storage of Git repositories and facilitates online collaboration among developers.

---

# Question: What role does Git play on a local machine during development?

**Answer:** It tracks all activities including adding, updating, or deleting files in the project directory.

---

# Question: What command sets the global Git username?

**Answer:** `git config --global user.name "Name of User"`

---

# Question: What command sets the global Git email?

**Answer:** `git config --global user.email "test@test.com"`

---

# Question: What command creates a new working directory for a Git project?

**Answer:** `mkdir local_repository`

---

# Question: What command changes the current directory to the working directory?

**Answer:** `cd local_repository`

---

# Question: What command creates an HTML file inside the working directory?

**Answer:** `touch index.html`

---

# Question: What should you do if `touch` is not recognized in your terminal?

**Answer:** Run `npm install -g touch-cli` (requires Node.js).

---

# Question: What command links a local Git repository to a remote GitHub repository?

**Answer:** `git remote add origin https://github.com/your-git-username/your-repository-name.git`

---

# Question: What command renames the current branch to `main`?

**Answer:** `git branch -M main`

---

# Question: What command pushes the local repository to GitHub?

**Answer:** `git push -u origin main`

---

# Question: Why are React and Flask considered good tools for full stack development?

**Answer:** Due to their simplicity, efficiency, and high performance compared to alternatives.

---

# Question: What is the purpose of the `create-react-app` tool in React development?

**Answer:**
It is used to generate a boilerplate React application without requiring manual configuration of tools like Webpack or Babel.

---

# Question: What command is used to create a new React project with Create React App?

**Answer:**
`npx create-react-app frontend`

---

# Question: After creating a React app, what command do you use to enter the project directory?

**Answer:**
`cd frontend`

---

# Question: How do you open a newly created React project in VS Code from the terminal?

**Answer:**
By typing `code .` in the terminal inside the project directory.

---

# Question: What is the purpose of the `node_modules/` folder in a React project?

**Answer:**
It contains all installed Node packages, including dependencies and devDependencies.

---

# Question: What is the purpose of the `public/index.html` file in a React project?

**Answer:**
It serves as the HTML template where the React app is rendered, displaying on `localhost:3000` in development.

---

# Question: What does the `public/manifest.json` file contain?

**Answer:**
It contains application metadata and settings for responsive screen display.

---

# Question: Which folder in a React project is considered the most important for development?

**Answer:**
The `src/` folder.

---

# Question: What is the `src/App.js` file used for?

**Answer:**
To implement React components; for small projects, it can hold all the component logic.

---

# Question: What is the purpose of `src/App.css` and `src/index.css`?

**Answer:**
They are used to style components and the overall application respectively.

---

# Question: What is the function of the `src/App.test.js` file?

**Answer:**
It is used to write unit tests for the React application.

---

# Question: What is the entry point to a React application?

**Answer:**
`src/index.js`

---

# Question: What is the purpose of the `.gitignore` file?

**Answer:**
It lists files and folders that should not be tracked by Git, such as `node_modules/`.

---

# Question: What is stored in `package.json`?

**Answer:**
It contains metadata and a list of dependencies required for the project.

---

# Question: What is the purpose of `package-lock.json`?

**Answer:**
It locks the installed package versions to ensure consistent installations across environments.

---

# Question: What is the function of the `README.md` file?

**Answer:**
It provides documentation and instructions about the project for developers, typically displayed on GitHub.

---

# Question: What does the command `npm start` do?

**Answer:**
It starts the development server and runs the app on `localhost:3000`.

---

# Question: What does the command `npm run build` do?

**Answer:**
It bundles the React app into static files for production.

---

# Question: What does the command `npm test` do?

**Answer:**
It runs the test suite for the React application.

---

# Question: What are arrow functions in JavaScript?

**Answer:**
A concise syntax for writing functions using the `=>` operator introduced in ES6.

---

# Question: Write an arrow function that adds two numbers.

**Answer:**
`const addNumbers = (a, b) => a + b;`

---

# Question: What are the two syntax forms for defining arrow functions?

**Answer:**

1. With braces and return: `const fn = (x) => { return x * 2; }`
2. With implicit return: `const fn = (x) => x * 2;`

---

# Question: What is one major limitation of arrow functions?

**Answer:**
They do not have their own `this` context, which can cause issues in object methods.

---

# Question: What is destructuring in JavaScript?

**Answer:**
A syntax for extracting values from arrays or properties from objects into separate variables.

---

# Question: Can you destructure nested properties in objects?

**Answer:**
Yes, by accessing the nested object first and then destructuring its properties.

---

# Question: Provide an example of nested object destructuring for an address property.

**Answer:**

```js
const { address } = speakers;  
const { street, city, state, country } = address;
```

---

# Question: What is one benefit of destructuring in React?

**Answer:**
It reduces repetitive code and improves readability when accessing props and state.

---

# Question: How do you provide default values during destructuring?

**Answer:**
`const { name = 'Anonymous', age = 0 } = speaker;`

---

# Question: What ES6 feature allows splitting code into modules?

**Answer:**
`export` and `import` syntax.

---

# Question: What is the rule for default exports in a file?

**Answer:**
Each file can only have **one** default export.

---

# Question: Show how to export a default component.

**Answer:**
`export default App;`

---

# Question: How do you import a default export?

**Answer:**
`import App from './App';`

---

# Question: Can you have multiple named exports in a file?

**Answer:**
Yes.

---

# Question: How do you import multiple named exports?

**Answer:**
`import { FirstComponent, SecondComponent } from './ThirdComponent';`

---

# Question: What is a React component?

**Answer:** A React component is a reusable, maintainable, and self-contained block of code that returns a UI element, typically written in JavaScript with JSX syntax.

---

# Question: What are the two main types of React components?

**Answer:** Class components and function components.

---

# Question: Why are function components considered the present and future of React?

**Answer:** Function components are simpler to write, easier to maintain, and support Hooks, which enable state and lifecycle features without the complexity of classes.

---

# Question: What does JSX stand for in React?

**Answer:** JSX stands for JavaScript XML. It's a syntax extension that allows writing HTML-like elements within JavaScript code.

---

# Question: In React, what is returned by a component?

**Answer:** A React component returns HTML elements written in JSX.

---

# Question: How do you define a basic function component in React?

**Answer:**

```javascript
function App() {
  return (
    <div>
      <h1>Welcome</h1>
    </div>
  );
}
```

---

# Question: What is the difference between declaring a variable inside and outside a function component?

**Answer:** Variables declared inside the function component are redefined every render, while those outside persist across renders and do not access internal component data.

--

# Question: What problem does the virtual DOM solve in React?

**Answer:** It minimizes direct DOM manipulation by updating only the changed parts of the DOM, improving performance and efficiency.

---

# Question: What must a React class component extend?

**Answer:** `React.Component`

---

# Question: What method is required in a class component to return HTML?

**Answer:** The `render()` method.

---

# Question: How do you define a minimal React class component?

**Answer:**

```javascript
import React from 'react';
class MyComponent extends React.Component {
  render() {
    return <h1>Hello</h1>;
  }
}
```

---

# Question: What is the function component equivalent of a class component with a render method?

**Answer:**

```javascript
const MyComponent = () => {
  return <h1>Hello</h1>;
}
```

---

# Question: What is the main structural difference between class and function components?

**Answer:** Class components use a `render()` method and extend `React.Component`; function components are simpler and directly return JSX.

---

# Question: Which component type supports lifecycle methods directly?

**Answer:** Class components.

---

# Question: Before React 16.8, how could you make function components stateful?

**Answer:** You had to rewrite them as class components.

---

# Question: Which React feature allows function components to be stateful?

**Answer:** Hooks, such as `useState`.

---

# Question: What are some React class lifecycle methods?

**Answer:** `constructor()`, `static getDerivedStateFromProps()`, `render()`, `componentDidMount()`, `componentDidUpdate()`, and `componentWillUnmount()`.

---

# Question: What are the three phases of a React component lifecycle?

**Answer:** Mounting, updating, and unmounting.

---

# Question: What is the purpose of the `constructor()` method in class components?

**Answer:** To initialize state and bind event handlers, and it is called before the component is mounted.

---

# Question: What does `componentDidMount()` do?

**Answer:** It runs after the component is inserted into the DOM, allowing for data fetching or event binding.

---

# Question: When is `componentDidUpdate()` called?

**Answer:** After the component updates due to a change in state or props.

---

# Question: When is `componentWillUnmount()` called?

**Answer:** Just before the component is removed from the DOM.

---

# Question: What are props in React?

**Answer:** Props are read-only objects passed from a parent component to a child component to configure or customize behavior and content.

---

# Question: Are props mutable inside child components?

**Answer:** No, props are read-only and cannot be modified directly by the receiving component.

---

# Question: How do you pass props from a parent to a child component?

**Answer:**

```jsx
<ChildComponent name="Alice" />
```

---

# Question: How do you access props in a function component?

**Answer:**

```javascript
function ChildComponent(props) {
  return <h3>{props.name}</h3>;
}
```

---

# Question: What is the direction of data flow in React using props?

**Answer:** Unidirectional — from parent to child.

--

# Question: What is `state` in React?

**Answer:** State is an internal object used by components to store dynamic data that may change over time and trigger re-renders.

---

# Question: What hook is used to manage state in function components?

**Answer:** `useState`.

---

# Question: How does `useState` work?

**Answer:** It returns an array with two values: the current state and a function to update that state.

---

# Question: What is the syntax for declaring state using `useState`?

**Answer:**

```javascript
const [state, setState] = useState(initialValue);
```

---

# Question: When does a component re-render in React?

**Answer:** When its state or props change.

---

# Question: What is the default state in a search field implemented using `useState('')`?

**Answer:** An empty string.

---

# Question: What happens when the `setSearchText` function is called?

**Answer:** The `searchText` state is updated and the component re-renders to reflect the new state.

---

# Question: Which file is typically modified to define the main app component in a React project?

**Answer:** `src/App.js`

---

# Question: How do you start a React development server from the command line?

**Answer:** Run `npm start`.

---

# Question: What is the primary purpose of state in React?

**Answer:** State in React is used to add interactivity to user interfaces by holding and managing dynamic data.

---

# Question: Before React v16.8, how was state added to components?

**Answer:** Before React v16.8, state could only be added through class components.

---

# Question: What major change did React Hooks bring to functional components?

**Answer:** React Hooks allowed functional components to use state and lifecycle features without needing to convert them into class components.

---

# Question: What are the core React Hooks introduced for stateful functional components?

**Answer:** useState, useEffect, useContext, useMemo, useReducer, useRef, useCallback.

---

# Question: What is a Hook in React?

**Answer:** A Hook is a special function that lets you use React features like state and lifecycle methods inside functional components.

---

# Question: What are the three cyclic phases in a React component's lifecycle?

**Answer:** Mounting, updating, and unmounting.

---

# Question: Name four lifecycle methods used in class components.

**Answer:** componentWillMount(), componentDidMount(), componentWillUpdate(), componentDidUpdate().

---

# Question: How do Hooks differ from class lifecycle methods?

**Answer:** Hooks replace class lifecycle methods by allowing similar functionality within functional components using simpler, more modular syntax.

---

# Question: What does `this.updateNameState.bind(this)` do in a class component?

**Answer:** It binds the updateNameState function to the current instance of the component to preserve the correct `this` context.

---

# Question: What are the two rules of using React Hooks?

**Answer:**

1. Hooks must be called at the top level of a functional component.
2. Hooks must only be called from functional components or custom Hooks, not regular JavaScript functions or class components.

---

# Question: Why were React Hooks introduced?

**Answer:** Hooks were introduced to simplify stateful logic in React components, improve reusability, and eliminate the complexity of class components.

---

# Question: Why are class components considered difficult for beginners?

**Answer:** Because they require understanding OOP concepts, managing `this`, and using methods like `.bind()`.

---

# Question: How do Hooks promote code reusability?

**Answer:** Hooks separate stateful logic from UI logic, enabling the creation of custom Hooks that can be reused across components.

---

# Question: What does the useState Hook do?

**Answer:** It allows functional components to hold and update state variables.

---

# Question: What is the syntax for useState?

**Answer:** `const [state, stateUpdater] = useState(initialState);`

---

# Question: What does the resetCountHandler() function do?

**Answer:** It resets the count state variable to 0.

---

# Question: What are the values returned by useState?

**Answer:** The current state value and a state updater function.

---

# Question: Can useState handle objects or only primitives?

**Answer:** useState can handle any data type, including primitives, arrays, and objects.

---

# Question: How does destructuring help when using useState?

**Answer:** It allows concise assignment of the current state value and its updater function in one line.

---

# Question: What is required before using the useState Hook in a component?

**Answer:** You must import it from React using `import { useState } from 'react';`.

---

# Question: How do you pass state from a parent to a child component?

**Answer:** By passing it as a prop to the child component.

---

# Question: What is conditional rendering in React?

**Answer:** It's the technique of displaying or hiding UI elements based on the current state.

---

# Question: Can Hooks be invoked inside loops or nested functions?

**Answer:** No, Hooks must be called at the top level of functional components.

---

# Question: Can Hooks be used inside class components?

**Answer:** No, Hooks can only be used in functional components and custom Hooks.

---

# Question: What advantage do custom Hooks offer?

**Answer:** They allow developers to extract and reuse stateful logic across multiple components and projects.

---

# Question: What future direction does the React team recommend?

**Answer:** Embracing functional component architecture and using Hooks over class components.

---

# Question: What is the primary purpose of the `useEffect` Hook in React?

**Answer:** To handle side effects like fetching data, updating the DOM, or managing subscriptions in functional components.

---

# Question: What arguments does `useEffect` accept?

**Answer:** A callback function and an optional dependency array.

---

# Question: Which class lifecycle methods does `useEffect` replace in functional components?

**Answer:** `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.

---

# Question: What does an empty dependency array (`[]`) in `useEffect` signify?

**Answer:** The effect runs only once, when the component is first mounted.

---

# Question: What is the result of passing a state variable to the `useEffect` dependency array?

**Answer:** The effect re-runs whenever the specified state changes.

---

# Question: How does `useEffect(() => {...}, [data])` behave?

**Answer:** The effect runs whenever the `data` state is updated.

---

# Question: What role does a cleanup function in `useEffect` play?

**Answer:** It runs when the component unmounts or when dependencies change, preventing memory leaks.

---

# Question: Why is an `isMounted` flag useful in a `useEffect` data fetch?

**Answer:** It prevents calling `setData` on an unmounted component, avoiding memory leaks or errors.

---

# Question: What is the function of the `fetchSpeakers()`?

**Answer:** It asynchronously fetches data from an API and updates the state with `setData`.

---

# Question: What does the `map()` method do in the render logic?

**Answer:** It iterates over the `data` array and displays each speaker's first and last name.

---

# Question: What problem does `useContext` solve in React?

**Answer:** It eliminates the need for props drilling by enabling state sharing across deeply nested components.

---

# Question: What is the syntax for using `useContext`?

**Answer:** `const value = useContext(Context)`

---

# Question: What is props drilling?

**Answer:** Passing data through multiple intermediary components to reach a deeply nested component.

---

# Question: How is context created in React?

**Answer:** With `createContext(initialValue)`

---

# Question: How is a context value provided to child components?

**Answer:** By wrapping them with `<Context.Provider value={...}>...</Context.Provider>`

---

# Question: How do components consume context values?

**Answer:** By calling `useContext(Context)` within the component.

---

# Question: What are the two main uses of the `useRef` Hook?

**Answer:** Accessing DOM elements directly and persisting state values across renders without re-rendering.

---

# Question: Why is `useRef` preferable to `useState` for storing mutable values without triggering re-renders?

**Answer:** Because `useRef` updates the `.current` property without causing a component re-render.

---

# Question: How can you use `useRef` to autofocus an input?

**Answer:** Attach `ref={inputRef}` to the input element and call `inputRef.current.focus()` in a function.

---

# Question: What is the effect of calling `useRef(null)`?

**Answer:** It creates a mutable ref object with an initial `current` value of `null`.

---

# Question: What does the `useReducer` Hook return?

**Answer:** An array with the current state and a `dispatch` function: `[state, dispatch]`

---

# Question: What are the two arguments passed to `useReducer`?

**Answer:** A `reducer` function and an `initialState` object.

---

# Question: What is a reducer function in React?

**Answer:** A function that determines how the state is updated based on the received action type and payload.

---

# Question: What is `dispatch` used for in `useReducer`?

**Answer:** To send actions to the reducer function to modify the state.

---

# Question: What is the purpose of the `initialState` in `useReducer`?

**Answer:** To define the initial values for the component's state.

---

# Question: What are the typical properties of an action in `useReducer`?

**Answer:** `type` (required) and `payload` (optional data).

---

# Question: What action is dispatched when fetching event schedules begins?

**Answer:** `{ type: "getEventSchedule" }`

---

# Question: What happens in the `"getEventSchedule"` case in the reducer?

**Answer:** The `isLoading` property is set to `true` and `error` to `null`.

---

# Question: What action type is dispatched on successful data fetch?

**Answer:** `{ type: "getEventScheduleSuccess", payload: response.data }`

---

# Question: What state update occurs on `getEventScheduleSuccess`?

**Answer:** `isLoading` is set to `false`, and `data` is set to the fetched payload.

---

# Question: What happens when the data fetch fails?

**Answer:** The `getEventScheduleFailure` action is dispatched, setting the `error` state.

---

# Question: How is `useEffect` used in the `useReducer` example?

**Answer:** It dispatches `getEventSchedule` and fetches data using Axios, then dispatches success or failure based on the result.

---

# Question: What endpoint is used to fetch schedule data?

**Answer:** `http://localhost:8000/schedules/`

---

# Question: How is JSON Server installed?

**Answer:** With the command `npm i -g json-server`

---

# Question: How is the JSON Server started on port 8000?

**Answer:** With `json-server --watch db.json --port=8000`

---

# Question: What condition displays the message "No schedules available."?

**Answer:** When `state.data` exists and its length is `0`.

--

# Question: What is the main purpose of the `useMemo` Hook in React?

**Answer:** To optimize performance by memoizing the result of resource-intensive computations and returning cached output when inputs do not change.

---

# Question: What software development technique does `useMemo` implement?

**Answer:** Memoization.

---

# Question: What are the two major performance benefits of `useMemo` in React applications?

**Answer:** Preventing unnecessary component re-renders and memoizing the return value of expensive computations.

---

# Question: Write the correct syntax for applying `useMemo` to filter speakers by `searchTerm`.

**Answer:**

```js
const filteredSpeakers = useMemo(() =>
  speakers.filter((speaker) =>
    speaker.name.toLowerCase().includes(searchTerm.toLowerCase())
  ),
[searchTerm]);
```

---

# Question: Why does the filtered function not re-run when `text` changes in the `useMemo` example?

**Answer:** Because `text` is not included in the `useMemo` dependency array.

---

# Question: What console output helps confirm that re-rendering is happening unnecessarily?

**Answer:** `"Filtering speakers..."` is printed to the console during each render, even when not needed.

---

# Question: What is the main difference between `useMemo` and `useCallback`?

**Answer:** `useMemo` returns a memoized value, while `useCallback` returns a memoized function.

---

# Question: What problem does `useCallback` solve in React applications?

**Answer:** It prevents unnecessary re-rendering of components due to referential inequality of functions.

---

# Question: When is the function inside `useCallback` re-created?

**Answer:** Only when one of its dependencies changes.

---

# Question: Write an example of a `useCallback` function that removes a speaker from a list.

**Answer:**

```js
const handleRemoveSpeaker = useCallback(
  (id) => setSpeakers(speakers.filter((user) => user.id !== id)),
  [speakers]
);
```

---

# Question: Why does using `useCallback` help when rendering `App`, `List`, and `ListItem` components?

**Answer:** It ensures that the same function instance is used across renders unless dependencies change, avoiding unnecessary re-renders.

---

# Question: What is the role of referential equality in React component re-rendering?

**Answer:** React compares function references to determine changes; different references cause unnecessary re-renders even if the function body is unchanged.

---

# Question: What is a custom Hook in React?

**Answer:** A regular JavaScript function that starts with `use` and internally calls one or more React built-in Hooks.

---

# Question: Why must a custom Hook name begin with `use`?

**Answer:** It signals to React that the function follows Hook rules and can be validated by the linter and React engine.

---

# Question: What are three benefits of using custom Hooks in React?

**Answer:** Reusability of logic across components, separation of concerns between logic and UI, and easier debugging.

---

# Question: Write an example of importing and using a custom Hook named `useFetchSpeakers`.

**Answer:**

```js
import useFetchSpeakers from "./useFetchSpeakers";
const [data] = useFetchSpeakers(API_URL);
```

---

# Question: What argument does the `useFetchSpeakers` custom Hook receive?

**Answer:** A URL string representing the endpoint to fetch data from.

---

# Question: What React Hooks are used inside `useFetchSpeakers`?

**Answer:** `useState` and `useEffect`.

---

# Question: Describe the key steps taken in the `useFetchSpeakers` custom Hook.

**Answer:** Accepts a `url`, fetches data in `useEffect`, converts it to JSON, stores it with `setData`, and returns the `data` state.

---

# Question: What causes the custom Hook `useFetchSpeakers` to re-run?

**Answer:** A change in the `url` dependency passed to `useEffect`.

---

# Question: What structure does `useFetchSpeakers` return?

**Answer:** An array containing the fetched `data`.

---

# Question: How does using a custom Hook promote separation of concerns?

**Answer:** It isolates logic like data fetching from the UI rendering code in the component.

---

# Question: What does the following code do?

```js
useEffect(() => {
  const fetchSpeakers = async () => {
    const response = await fetch(url);
    const data = await response.json();
    setData(data.users);
  };
  fetchSpeakers();
}, [url]);
```

**Answer:** It defines an asynchronous function to fetch data from a given URL and stores the result in state, re-running only when the URL changes.

---

# Question: What version of React introduced Hooks?

**Answer:** React 16.8.

---

# Question: Before Hooks, what type of component was needed to use state in React?

**Answer:** Class components.

---

# Question: How do Hooks improve the development experience in React?

**Answer:** By enabling elegant, concise, and stateful function components.

---

# Question: Why is there an increasing demand for database-driven web applications?

**Answer:** Because of the abundance of available data and the widespread use of web applications by businesses to interact with stakeholders.

---

# Question: What is the role of a frontend developer in full-stack development related to data?

**Answer:** To consume data from either internal or third-party APIs and display it in the UI.

---

# Question: What is an API in the context of web development?

**Answer:** An API allows communication among systems using a set of rules, often based on HTTP protocols.

---

# Question: What are the two major formats for data exchange over the internet?

**Answer:** XML and JSON.

---

# Question: Why is JSON preferred over XML in web development?

**Answer:** JSON is specifically designed for data interchange, handles arrays seamlessly, and is widely adopted by developers.

---

# Question: What is the purpose of React’s exposed interfaces for data fetching?

**Answer:** To help developers fetch data efficiently and build intuitive user interfaces.

---

# Question: What is the Fetch API?

**Answer:** An inbuilt web API in browsers that provides a JavaScript interface for HTTP communication.

---

# Question: Why is understanding JavaScript essential for React developers?

**Answer:** Because the React ecosystem relies on JavaScript, including its APIs like `fetch()` for networking.

---

# Question: What does the `fetch()` function return?

**Answer:** A Promise that resolves to a Response object representing the response to the request.

---

# Question: What React Hook is commonly used to handle side effects like data fetching?

**Answer:** `useEffect`.

---

# Question: What does `response.json()` do in a Fetch API call?

**Answer:** It parses the response body as JSON and returns a promise with the result.

---

# Question: What does `map()` do in the context of displaying fetched data?

**Answer:** It iterates through the data array and renders UI elements for each item.

---

# Question: What is a best practice when fetching data in real-world React apps?

**Answer:** Managing network errors and implementing a loading state for better UX.

---

# Question: What are the three main ways to handle asynchronous code in JavaScript?

**Answer:** Callbacks, Promises, and async/await.

---

# Question: How does async/await improve on Promises?

**Answer:** It provides cleaner syntax and better code organization for asynchronous operations.

---

# Question: What is the structure of an async function that fetches data in React?

**Answer:** Define an async function, use `await fetch()`, `await .json()`, and call `setData()` inside a `try/catch`.

---

# Question: What does the `catch` block do in async/await data fetching?

**Answer:** It handles any errors that occur during the fetch operation.

---

# Question: Why is the dependency array `[data]` used in the `useEffect` Hook in async/await

**Answer:** So the effect re-runs when `data` changes, triggering a re-fetch and re-render.

---

# Question: What does `setData(data.users)` mean in async/await 

**Answer:** It updates the `data` state with the array of users from the response JSON.

---

# Question: How does async/await improve performance in data fetching?

**Answer:** It allows code to run in non-blocking mode, improving responsiveness.

---

# Question: What is Axios?

**Answer:** A lightweight JavaScript HTTP client used to make Promise-based API requests in browsers and Node.js.

---

# Question: What command is used to install Axios?

**Answer:** `npm install axios`

---

# Question: What function is used in Axios to make GET requests?

**Answer:** `axios.get(URL)`

---

# Question: In Axios, how is the fetched data accessed from the response?

**Answer:** Through `response.data`.

---

# Question: How does Axios simplify data fetching compared to Fetch API?

**Answer:** It abstracts response parsing and has built-in features like automatic JSON transformation.

---

# Question: Does Axios return a Promise?

**Answer:** Yes, it returns a Promise that resolves to a response object.

---

# Question: How is the `useEffect` Hook used with Axios?

**Answer:** To call the data-fetching function once the component mounts.

---

# Question: What is React Query?

**Answer:** A data-fetching library for React that includes features like caching, retries, and pre-fetching out of the box.

---

# Question: What command installs React Query?

**Answer:** `npm install react-query`

---

# Question: What Hook does React Query provide for fetching data?

**Answer:** `useQuery()`

---

# Question: What arguments does `useQuery` accept?

**Answer:** A query key (e.g., `"speakers"`) and a callback function that returns a Promise.

---

# Question: What properties are returned by `useQuery()`?

**Answer:** `data`, `isLoading`, and `error`.

---

# Question: What does `isLoading` indicate in `useQuery()`?

**Answer:** Whether the query is currently fetching data.

---

# Question: How does React Query handle caching?

**Answer:** It automatically caches query results using the query key.

---

# Question: What does `QueryClient` do in React Query?

**Answer:** It manages default settings and configurations for all queries.

---

# Question: What does `QueryClientProvider` do?

**Answer:** It provides the `QueryClient` instance to the application’s React tree.

---

# Question: How does React Query improve over manual `useState` and `useEffect`?

**Answer:** It abstracts away boilerplate logic for fetching, caching, and managing states like loading and error.

---

# Question: What is the advantage of using React Query’s declarative API?

**Answer:** It simplifies the logic and reduces the amount of code required to fetch and manage data.

---

# Question: What is the role of `data.data.map(...)` in React Query

**Answer:** It iterates over the fetched users array nested inside the `data` object returned by Axios.

---

# Question: What should be displayed when an error occurs in React Query?

**Answer:** An error message such as `<h4>Error: {error.message}, retry again</h4>`.

---

# Question: What should be displayed when data is loading in React Query?

**Answer:** A loading indicator such as `<h4>...Loading data</h4>`.

---

# Question: What four tools for data fetching in React?

**Answer:** Fetch API, async/await, Axios, and React Query.

---

# Question: What does React Query radically change in data fetching?

**Answer:** It introduces powerful features like transparent caching, retries, and simplified state management.

---

# Question: Why is effective data handling critical in React applications?

**Answer:** Because most modern applications are data-driven and depend on external or internal APIs to function.

---
