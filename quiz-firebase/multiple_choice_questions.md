# Question: What is Firebase and who developed it?

**Answer:** Firebase is a platform developed by Google for creating mobile and web applications.

---

# Question: What development tools does Firebase offer for building full stack applications?

**Answer:** Firebase provides tools for authentication, databases, file storage, security tools, and analytics.

---

# Question: What JavaScript frameworks for Firebase integration?

**Answer:** React, Next.js, Angular, and vanilla JavaScript.

---

# Question: Which authentication options are available in Firebase?

**Answer:** Email/password, email link, Google, Apple, Facebook, Twitter, GitHub, Microsoft, and Yahoo.

---

# Question: After creating a project in Firebase, what step comes next?

**Answer:** Registering a web app within the Firebase project.

---

# Question: How are email and password inputs managed in the form?

**Answer:** The email input is stored in a `email` state and the password input in a `password` state.

---

# Question: How do you install Firebase in a React project using VS Code?

**Answer:** By running the command `npm install firebase`.

---

# Question: Where should Firebase SDK data be copied in the project structure?

**Answer:** Into a new file named `firebaseConfig.js`.

---

# Question: What Firebase configuration values are included in the SDK setup?

**Answer:** API key, auth domain, project ID, and other related configuration values.

---

# Question: What should you export from `firebaseConfig.js`?

**Answer:** Export a constant named `app` which initializes Firebase using the configuration object.

---

# Question: How do you import the Firebase app configuration into your main app file?

**Answer:** Using the statement `import app from '../firebaseConfig'`.

---

# Question: Where do you navigate in Firebase Console to set up authentication?

**Answer:** Go to the "Authentication" tab and click "Get started."

---

# Question: What must be done before using email/password authentication in Firebase?

**Answer:** Enable the "Email/Password" provider and add the authorized domain in the Firebase console.

---

# Question: How do you add your domain in Firebase authentication settings?

**Answer:** Copy your project domain and paste it in the authentication settings under authorized domains.

---

# Question: What must be imported from Firebase to use authentication features in code?

**Answer:** Required functions and constants from `firebase/auth`.

---

# Question: What is the purpose of the `getAuth` function in Firebase?

**Answer:** `getAuth` is used to create an authentication instance that can be used to manage user authentication.

---

# Question: What is the purpose of the `createUserWithEmailAndPassword` function?

**Answer:** It is used to create a new user account using an email and password.

---

# Question: How is the `auth` instance created in the application?

**Answer:** By assigning the result of `getAuth()` to a constant, e.g., `const auth = getAuth()`.

---

# Question: In which function is the user creation logic placed?

**Answer:** Inside the `handleSubmit` function, which is triggered when the submit button is clicked.

---

# Question: What are the required parameters for `createUserWithEmailAndPassword`?

**Answer:** The `auth` instance, the user’s email, and the user’s password.

---

# Question: How are email and password values retrieved?

**Answer:** From the state object, using `data.email` and `data.password`.

---

# Question: How is the response from `createUserWithEmailAndPassword` handled?

**Answer:** Using `.then()` to access the response and log `response.user` to the console.

---

# Question: How are errors handled when user creation fails?

**Answer:** By using `.catch(error)` and displaying `error.message` in an alert.

---

# Question: What happens when trying to sign up with the same email twice?

**Answer:** Firebase returns an error stating that the email is already in use.

---

# Question: What is the expected error message when a duplicate email is used during sign up?

**Answer:** “auth/email-already-in-use”

---

# Question: After a successful sign-up, what user data is accessible in the response?

**Answer:** Access token, display name, original email, email verification status, and phone number.

---

# Question: What function is used to authenticate an existing user in Firebase?

**Answer:** `signInWithEmailAndPassword`

---

# Question: What should be changed to switch from sign-up to sign-in in the authentication logic?

**Answer:** Replace `createUserWithEmailAndPassword` with `signInWithEmailAndPassword`, and keep the other code the same.

---

# Question: What error message appears if a non-existent email is used to sign in?

**Answer:** “auth/user-not-found”

---

# Question: What error is shown if the correct email is used with the wrong password?

**Answer:** “auth/wrong-password”

---

# Question: What Firebase method can be used for social logins like Google Sign-In?

**Answer:** `GoogleAuthProvider`

---

# Question: What is the purpose of `GoogleAuthProvider` in Firebase Authentication?

**Answer:** It is used to authenticate users using their Google accounts.


---
