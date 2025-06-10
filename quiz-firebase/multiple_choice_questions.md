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

# Question: What is the purpose of `GoogleAuthProvider` in Firebase?

**Answer:** It is used to enable Google sign-in by initializing a Google authentication provider.

---

# Question: What function is used to initiate Google authentication via a popup window?

**Answer:** `signInWithPopup`

---

# Question: How is the Google authentication provider initialized?

**Answer:** `const googleProvider = new GoogleAuthProvider();`

---

# Question: What are the three key Firebase imports required for Google authentication?

**Answer:** `getAuth`, `GoogleAuthProvider`, and `signInWithPopup`

---

# Question: What arguments are passed to `signInWithPopup`?

**Answer:** The `auth` instance and the provider instance (e.g., `googleProvider`).

---

# Question: What must be done in Firebase console before Google Auth will work?

**Answer:** Enable Google Sign-In in the **Authentication > Sign-in Method** section and add the correct **authorized domains**.

---

# Question: What happens if the domain is not authorized in Firebase console?

**Answer:** An "unauthorized domain" error will be shown and Google Sign-In will not work.

---

# Question: What type of data is returned after successful Google sign-in?

**Answer:** User information including verified email, display name, and provider ID set to `"google.com"`.

---

# Question: Why is the email marked as verified when using Google Sign-In?

**Answer:** Because Google ensures the user’s email is verified before allowing authentication.

---

# Question: What provider must be imported to support GitHub login in Firebase?

**Answer:** `GithubAuthProvider`

---

# Question: What additional credentials must be configured for GitHub authentication?

**Answer:** A **client ID** and a **client secret** from GitHub OAuth settings.

---

# Question: Where can you set up the GitHub application needed for Firebase authentication?

**Answer:** In **GitHub > Settings > Developer Settings > OAuth Apps**.

---

# Question: What URL must be added to GitHub's OAuth app during setup?

**Answer:** The **Authorization Callback URL** provided by Firebase (usually found in the Firebase Authentication method settings for GitHub).

---

# Question: What Firebase console setting allows you to enable GitHub login?

**Answer:** Under **Authentication > Sign-in Method**, enable **GitHub** and provide the **client ID and secret**.

---

# Question: What happens if the GitHub client secret or callback URL is incorrect?

**Answer:** Authentication will fail, typically with an "unauthorized" or "invalid client" error.

---

# Question: After a successful GitHub sign-in, what is returned?

**Answer:** The same user object structure with email, provider data (`providerId: "github.com"`), and possibly the username from GitHub.

---

