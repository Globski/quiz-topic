# Question: What is React and what is it commonly used for?

**Answer:**
React is a JavaScript library for building user interfaces. It is commonly used to build single-page applications and allows developers to create reusable UI components.

---
# Question: What must be installed before setting up React.js on your system?

**Answer:**  
You must have **Node.js** and **npm** installed before setting up React.js. These tools are essential for managing packages and running React-based projects.

---

# Question: Where can you download Node.js and npm?

**Answer:**  
Node.js and npm can be downloaded from the official website:  
[https://nodejs.org/en/](https://nodejs.org/en/)

---

# Question: What does the Node.js home page provide automatically?

**Answer:**  
The Node.js homepage automatically detects your platform and provides the most recent installation options suitable for your system.

---

# Question: Where can you find more installation options for Node.js?

**Answer:**  
You can click on **Other Downloads**, which is the first of three links visible beneath each default download option on the homepage. This link takes you to a page with all installation choices for various platforms.

---

# Question: What does the 'Other Downloads' link provide access to?

**Answer:**  
The 'Other Downloads' link provides access to a page listing **all installation options** for **all main platforms**, including source code versions and different builds of Node.js.

# Question: What is available at the bottom of the Node.js download page?

**Answer:**  
A bullet list of available resources is provided, including guidance on installing Node.js via source code and the node package manager (npm), for systems that require specialized instructions.

---

# Question: What file do you need to locate after downloading Node.js, and what should you do with it?

**Answer:**  
You need to find the `.pkg` file in your Downloads folder. Double-click it to open the "Install Node.js" pop-up window and follow the given instructions to complete the installation.

---

# Question: What is the easiest and recommended way to create a React.js project?

**Answer:**  
The easiest and recommended way to create a React.js project is by using the `create-react-app` command.

---

# Question: What other methods exist for creating React.js projects besides create-react-app?

**Answer:**  
React.js projects can also be created using custom-built setups that incorporate tools like webpack and Babel, though they are more complex.

---

# Question: Where can you find further guidance on React.js installation and setup?

**Answer:**  
Further guidance is available at the official React documentation:  
[https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)

---

# Question: What are the steps to install React.js using create-react-app?

**Answer:**  
1. **Open your terminal** (PowerShell/Command Prompt for Windows; Bash for Linux).  
2. **Create a new project folder** with a name of your choice using:  
   ```bash
   mkdir react-projects
   ```  
3. **Navigate to the new directory** using:  
   ```bash
   cd react-projects
   ```  
4. **Create a new React project** using:  
   ```bash
   npx create-react-app my-app
   ```  
5. **Grant permission** to install required files and folders when prompted.  
6. **Navigate to your new React project directory** using:  
   ```bash
   cd my-app
   ```

---

# Question: What should you expect during the React installation process?

**Answer:**  
You will be prompted to grant permission to install the necessary files and folders. The process may take several minutes to complete.

---

# Question: What command do you use to launch the Node.js development server and preview your React app locally?

**Answer:**  
You use the command:  
```bash
npm start
```  
This launches the Node.js development server and opens your React app in a browser for live preview.

---

# Question: What happens when you run `npm start` in your React project directory?

**Answer:**  
Running `npm start` starts a local development server and attempts to open a new browser window displaying your app at `http://localhost:3000`.

---

# Question: What should you do if the browser doesn't open automatically after running `npm start`?

**Answer:**  
Manually open your browser and type `http://localhost:3000` into the address bar to access the React application.

---

# Question: How do you stop the development server once you're done?

**Answer:**  
You stop the server by pressing `Ctrl + C` in the terminal window where it is running.

---

# Question: How do you restart the development server after stopping it?

**Answer:**  
You can restart the server by running the command `npm start` again in your terminal.

---

# Question: Why should the process started by `npm start` remain running during development?

**Answer:**  
Keeping the `npm start` process running is essential because it automatically updates the website on `localhost:3000` with any changes you make to your code.
