# Question: What command initializes a new `package.json` file in a Node project?

**Answer:** `npm init -y`

---

# Question: What is the purpose of using a scoped package name like `@clarkio/simple-npm-package`?

**Answer:** It helps identify the owner (user or organization) of the package and is required for scoped package publication.

---

# Question: Why should you check your `package.json` file for the `name` field before publishing?

**Answer:** To ensure it is unique and properly scoped, preventing naming conflicts and ensuring the package is correctly attributed.

---

# Question: What command is used to log in to your npm account via the terminal?

**Answer:** `npm login`

---

# Question: Why is it recommended to enable 2FA on your npm account?

**Answer:** To enhance account security and prevent unauthorized access.

---

# Question: During `npm login`, what is used to verify identity when 2FA is enabled?

**Answer:** A one-time password (OTP) from your authenticator application.

---

# Question: What command lets you preview the contents of your npm package tarball without publishing?

**Answer:** `npx pack --dry-run`

---

# Question: What does `npm publish --dry-run` do?

**Answer:** It shows what would happen during publishing without actually publishing the package.

---

# Question: What additional flag is required when publishing scoped npm packages?

**Answer:** `--access=public`

---

# Question: What is the default module format recommended for modern npm packages as of Node.js v22?

**Answer:** ECMAScript Modules (ESM)

---

# Question: Which file is used to configure TypeScript settings in a modern npm package?

**Answer:** `tsconfig.json`

---

# Question: What does the `lib` field in `tsconfig.json` specify?

**Answer:** The JavaScript features and DOM APIs to include in the compiled output.

---

# Question: What does the `module` field in `tsconfig.json` specify?

**Answer:** The module system to use, such as `NodeNext` for ESM support in Node.js.

---

# Question: What is the purpose of `outDir` in the `tsconfig.json` file?

**Answer:** It defines the directory where compiled JavaScript files will be output.

---

# Question: What command installs the TypeScript compiler and cleanup tool as dev dependencies?

**Answer:** `npm install -D typescript del-cli`

---

# Question: What script is run before npm packages the project for publishing?

**Answer:** `prepack`

---

# Question: Which directory is typically used to store test files in an npm project?

**Answer:** `tests`

---

# Question: What Node.js command is used to run tests with TypeScript stripping enabled?

**Answer:** `node --experimental-strip-types --test`

---

# Question: What is the purpose of the `test` script in `package.json`?

**Answer:** It defines how to run tests, often via Node.js test runner or other tools.

---

# Question: What version of Node.js introduced built-in test support (without external libraries)?

**Answer:** Node.js v20.x (with earlier support in v18.x and 16.17.x via experimental flags)

---

# Question: What CI tool is used in the guide to automate testing and deployment?

**Answer:** GitHub Actions

---

# Question: In the GitHub Actions YAML, which job field specifies the version of Node.js to use?

**Answer:** `matrix.node-version`

---

# Question: What is the purpose of using `npm ci` in a CI environment?

**Answer:** To install dependencies using the exact versions from `package-lock.json` for reproducibility.

---

# Question: What command generates a `.tgz` file of your npm package for local testing?

**Answer:** `npm pack`

---

# Question: What is the purpose of `npm link`?

**Answer:** To symlink your local npm package into another project for testing before publishing.

---

# Question: What are  five methods for testing a package in another project?

**Answer:** `npm pack`, relative path install, `npm link`, installing from npm registry, using Verdaccio.

---

# Question: What tool is used  for monitoring and fixing security vulnerabilities?

**Answer:** Snyk

---

# Question: Where do you store the Snyk API Token in your GitHub repository?

**Answer:** In GitHub Actions Secrets as `SNYK_TOKEN`

---

# Question: What GitHub Action workflow file is used for Snyk security checks?

**Answer:** `snyk.yml`

---

# Question: What happens when a Snyk security check fails in a pull request?

**Answer:** The GitHub Action fails and alerts the user with the detected vulnerability details.

---

# Question: What does Semantic Release use to determine the version bump (major, minor, patch)?

**Answer:** Conventional commit messages

---

# Question: What command sets up Semantic Release in your project?

**Answer:** `npx semantic-release-cli setup`

---

# Question: What scopes should be selected when creating a GitHub Personal Access Token for Semantic Release?

**Answer:** `repo`, `public_repo`, or `contents` depending on needs

---

# Question: What kind of npm token should be created for use in CI/CD environments?

**Answer:** An "Automation" type npm token

---

# Question: What key should be added to `package.json` to define the release branch?

**Answer:** `"release": { "branches": ["main"] }`

---

# Question: What does the `publishConfig` key do in `package.json`?

**Answer:** It sets publish options, such as `access: "public"` for scoped packages.

---

# Question: What command allows you to do a test run of Semantic Release locally?

**Answer:** `npx semantic-release --dry-run` (with `NPM_TOKEN` and `GH_TOKEN` set in env)

---

# Question: What two workflows must complete before the `release.yml` workflow can run?

**Answer:** `Tests` and `Snyk Security Check`

---

# Question: What built-in GitHub Action secret is used for releases instead of a PAT?

**Answer:** `GITHUB_TOKEN`

---

# Question: What does Snyk’s continuous monitoring do beyond GitHub Actions integration?

**Answer:** It monitors for new vulnerabilities and opens automated PRs to fix them.

---

# Question: Which two Snyk products are used to secure your code and dependencies?

**Answer:** Snyk Code (SAST) and Snyk Open Source (SCA)

---

# Question: Why is it important to use security tools like Snyk in npm packages?

**Answer:** To prevent introducing vulnerabilities into other projects that depend on your package.

---

