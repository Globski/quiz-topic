# Question: What are some of the key Jest?

**Answer:** Mocking, and asynchronous testing with Jest.

---

# Question: What does the command `npm init -y` do?

**Answer:** It initializes a new npm project and automatically answers "yes" to all prompts, creating a default `package.json` file.

---

# Question: What file is generated after running `npm init -y`?

**Answer:** `package.json`

---

# Question: What are the steps taken to open the project folder in VS Code?

**Answer:** Go to File → Open Folder → Select the `jest-course` directory.

---

# Question: What command is used to install Jest as a development dependency in the project?

**Answer:** `npm install --save-dev jest`

---

# Question: Why is Jest chosen as the testing framework?

**Answer:** Because of its simplicity and rich features, and it's considered the most popular testing framework for JavaScript.

---

# Question: What is the purpose of running `npm install --save-dev jest`?

**Answer:** To install Jest as a development dependency locally in the project.

---

# Question: Where is Jest listed after successful installation using `npm install --save-dev jest`?

**Answer:** Under the `devDependencies` section of the `package.json` file.

---

# Question: What does the `devDependencies` section in `package.json` signify?

**Answer:** It lists packages that are essential for development but not required to run the actual application in production.

---

# Question: What folder is created after successfully installing Jest?

**Answer:** `node_modules`

---

# Question: What additional file is generated during package installation besides `package.json`?

**Answer:** `package-lock.json`

---

# Question: What indicates that Jest was successfully installed after running the install command?

**Answer:** The console outputs "added 292 packages and found 0 vulnerabilities," and Jest appears under `devDependencies` in `package.json`.

---

# Question: What is the purpose of configuring an npm script after installing Jest?

**Answer:** To create a convenient shortcut command for running tests using Jest.

---

# Question: In which section of `package.json` do you configure custom npm scripts?

**Answer:** The `scripts` section.

---

# Question: What change is made to the default `test` script in `package.json` to use Jest?

**Answer:** The value of the `test` script is changed to `"jest"`.

---

# Question: What happens when you run `npm test` after updating the `test` script to use Jest?

**Answer:** It runs tests using the Jest framework.

---

# Question: What is the purpose of modifying the `test` script in `package.json` to `"jest"`?

**Answer:** To enable the command `npm test` to run Jest tests automatically.

---

# Question: What is unit testing?

**Answer:** Unit testing is the process of checking small pieces of code, such as basic functions or classes, to identify bugs early and often.

---

# Question: Why is unit testing preferred over testing the entire code at once?

**Answer:** Unit testing allows developers to identify errors early, making it easier to trace bugs within small code blocks rather than debugging the entire codebase later.

---

# Question: How does JavaScript identify a file as a test file?

**Answer:** By including `.test.js` in the filename, JavaScript (with Jest) recognizes it as a test file.

---

# Question: What  is Jest?

**Answer:** Jest is a testing framework.

---

# Question: What keyword is used to define a unit test in Jest?

**Answer:** The `test` keyword is used.

---

# Question: What are the two components passed into the `test()` function in Jest?

**Answer:** A description string and a test function (i.e., a callback that runs the actual test).

---

# Question: What does the term “exporting a function” mean in Node.js?

**Answer:** Making the function accessible to other files/modules via `module.exports`.

---

# Question: What happens if you don’t export a function in Node.js?

**Answer:** The function will not be accessible from other files, making it impossible to test or reuse.

---

# Question: At what stage should unit testing ideally occur in the development process?

**Answer:** During the development of small code blocks (early stages), not after the full code is written.

---

# Question: What advantage does unit testing provide during debugging?

**Answer:** It helps locate the source of bugs more precisely since only small code blocks are tested individually.

---

# Question: What are the two parts passed into the `test()` function in Jest?

**Answer:** A description string and a test function (callback).

---

# Question: What is the purpose of the test description in the `test()` function?

**Answer:** It provides a human-readable explanation of what the test is checking; in this case, that adding 1 and 2 should equal 3.

---

# Question: What is the syntax structure of a Jest `test()` function?

**Answer:** `test('description', () => { test logic });`

---

# Question: What does the `expect` function do in Jest?

**Answer:** It asserts that a value matches an expected result.

---

# Question: What is the purpose of `toBe(3)` in the test?

**Answer:** It asserts that the result of `sum(1, 2)` should strictly equal `3`.

---

# Question: What does `expect(sum(1, 2)).toBe(3);` test?

**Answer:** It checks whether the `sum` function correctly returns `3` when passed `1` and `2`.

---

# Question: Why is it important to use a semicolon after the Jest assertion?

**Answer:** To properly terminate the JavaScript statement and avoid syntax errors.

---


# Question: How do you run the test from the terminal?

**Answer:** By executing `npm test`.

---

# Question: What does the error message `"echo error no test specified"` indicate?

**Answer:** That the `test` script is not defined in the `package.json` file.

---

# Question: What must be checked if `npm test` returns an error about no test being specified?

**Answer:** Ensure that the `test` script is correctly defined in the `scripts` section of `package.json`.

---

# Question: How do you confirm you are in the correct folder before running tests in the terminal?

**Answer:** By checking the current directory and confirming it contains the `sum.js` and `sum.test.js` files.

---

# Question: What error occurs if the `test` script in `package.json` is not correctly set?

**Answer:** `"no test specified"` is shown because the key was incorrectly set to `just` instead of `test`.

---

# Question: How should the `scripts` section be correctly written in `package.json` to run tests with Jest?

**Answer:** `"scripts": { "test": "jest" }`

---

# Question: What command runs the unit tests in a Node.js project using Jest?

**Answer:** `npm test`

---

# Question: What does the output `1 passed, 1 total` from Jest mean?

**Answer:** One test was run and it passed successfully.

---

# Question: What are matchers in Jest?

**Answer:** Matchers are functions used with `expect()` to assert various conditions about test values.

---

# Question: In the example `expect(sum(1, 2)).toBe(3);`, which part is the matcher?

**Answer:** `toBe(3)` is the matcher.

---

# Question: What is the purpose of the `toBe` matcher in Jest?

**Answer:** It checks for exact equality using `===` and is used for primitive values like numbers, strings, and booleans.

---

# Question: When should you use the `toBe` matcher?

**Answer:** For asserting equality of primitive values such as numbers, strings, and booleans.

---

# Question: What are some other matchers mentioned in Jest besides `toBe`?

**Answer:** `toEqual`, `toBeTruthy`, `toBeFalsy`, `toThrow`

---

# Question: What does `expect(2 + 2).toBe(4);` test for?

**Answer:** It tests whether the result of `2 + 2` is strictly equal to `4` using the `toBe` matcher for primitive values.

---

# Question: Which types of values should be compared using the `toBe` matcher in Jest?

**Answer:** Primitive values like numbers, strings, and booleans.

---

# Question: What output confirms a passing test in Jest after running a `toBe` matcher?

**Answer:** `1 passed, 1 total`

---

# Question: When comparing objects or arrays in Jest, which matcher should be used instead of `toBe`?

**Answer:** `toEqual`

---

# Question: What does the `toEqual` matcher do?

**Answer:** It checks for deep equality between two objects or arrays.

---

# Question: Why can't `toBe` be used for object or array comparison in Jest?

**Answer:** Because `toBe` uses strict equality (`===`), which only returns true if the operands reference the same object in memory.

---

# Question: How was the deep equality of the `data` object asserted in the test?

**Answer:** `expect(data).toEqual({ one: 1, two: 2 });`

---

# Question: What does a successful test involving an object and `toEqual` indicate?

**Answer:** That the object structure and values matched exactly as expected.

---

# Question: What are `toBeTruthy` and `toBeFalsy` used for in Jest?

**Answer:** They test whether a value evaluates to `true` or `false` in a boolean context.

---

# Question: What matcher should be used to test for falsy values in Jest?

**Answer:** `toBeFalsy`

---

# Question: What is the syntax for checking if a value is falsy using Jest?

**Answer:** `expect(value).toBeFalsy();`

---

