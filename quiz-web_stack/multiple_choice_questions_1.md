# Question: What is NGINX?

**Answer:** NGINX is an open-source web server software used for **reverse proxy**, **load balancing**, and **caching**.

---

# Question: Why is NGINX important for backend developers?

**Answer:** Because it plays a critical role in **serving web content**, **routing traffic**, and **optimizing performance** in web applications.

---

# Question: What browser tool use to inspect how content is served from Airbnb.com?

**Answer:** The **Developer Tools** (by right-clicking → Inspect), specifically the **Network tab**.

---

# Question: What is observed in the network tab when refreshing a page like Airbnb.com?

**Answer:** A large number of **network requests** are made from the browser to servers to **fetch various types of content** (HTML, images, etc.).

---

# Question: In the Airbnb.com, what web server was found to be serving the content?

**Answer:** **NGINX**

---

# Question: How can you identify the web server type used in a network request?

**Answer:** By inspecting the **headers** in the **Network tab** of browser developer tools, under the **server** section.

---

# Question: What is NGINX typically known as?

**Answer:** A **web server** that **serves web content** to browsers.

---

# Question: Why is calling NGINX simply a web server “not particularly accurate”?

**Answer:** Because NGINX also functions in other roles such as **reverse proxy**, **load balancer**, and **cache**, not just a basic web server.

---

# Question: What cloud provider does Airbnb likely use to host its servers?

**Answer:** **AWS (Amazon Web Services)**

---

# Question: What happens when a user goes to Airbnb.com?

**Answer:** The user’s computer sends a **request over the internet** to a server hosted by Airbnb (likely on AWS), which processes the request and returns a **response with web content**.

---

# Question: In the typical web content delivery setup, what is the first server a browser contacts?

**Answer:** The browser first contacts the Nginx server.

---

# Question: What role does the Nginx server play in the web request flow?

**Answer:** Nginx acts as an intermediary that receives the browser’s request, forwards it to the application server (e.g., Airbnb server), and then sends the server’s response back to the browser.

---

# Question: What is the technical term for a server that receives client requests and forwards them to other servers, then returns the response to the client?

**Answer:** Reverse proxy.

---

# Question: Why might it not be efficient to send requests directly to the main application server in high-traffic scenarios?

**Answer:** Because a single application server can become a bottleneck under high traffic, resulting in increased latency.

---

# Question: How can scalability be achieved for a high-traffic application like Airbnb?

**Answer:** By increasing the number of application servers behind a load balancer.

---

# Question: What is the problem introduced when multiple servers are used to handle incoming traffic?

**Answer:** There needs to be a way to distribute incoming requests evenly across multiple servers.

---

# Question: How does Nginx help distribute traffic across multiple application servers?

**Answer:** Nginx acts as a load balancer, forwarding each incoming request to an available server.

---

# Question: How does the client experience the request process when Nginx is used as a load balancer?

**Answer:** The client always sends the request to Nginx and receives a response from it, without knowing which application server handled the request.

---

# Question: What is the benefit of using Nginx as a load balancer for application scalability?

**Answer:** It enables automatic distribution of requests to multiple servers, reducing load on any single server and improving performance.

---

# Question: What is one additional important use case of Nginx besides load balancing?

**Answer:** Handling encryption for secure HTTPS communication.

---

# Question: What does HTTPS indicate about the server's communication?

**Answer:** That the server is encrypting and decrypting data to ensure secure communication.

---

# Question: What complexity arises when using HTTPS in a multi-server setup?

**Answer:** Each server must handle its own encryption and decryption, which can add overhead and complexity.

---


# Question: What is one way to simplify the process of setting up HTTPS when using multiple servers?

**Answer:** Use Nginx to handle all encryption and decryption, rather than configuring HTTPS individually on every server.

---

# Question: Why is centralizing HTTPS handling with Nginx beneficial in multi-server environments?

**Answer:** It reduces configuration complexity by allowing encryption and decryption to occur only at the Nginx level.

---

# Question: What are the two most important use cases of Nginx?

**Answer:** Acting as a load balancer and handling HTTPS encryption/decryption.

---

# Question: What command is used to install Nginx on a Mac using Homebrew?

**Answer:** `brew install nginx`

---

# Question: What prerequisite must be installed before using the `brew install nginx` command?

**Answer:** Homebrew, the package manager for macOS.

---

# Question: Where does the Nginx installation create a configuration directory on macOS?

**Answer:** `/usr/local/etc/nginx`

---

# Question: After installing Nginx, what command can be used to list the contents of the Nginx directory?

**Answer:** `ls /usr/local/etc/nginx`

---

# Question: What command is used to open the Nginx directory in Visual Studio Code?

**Answer:** `code .`

---

# Question: What is the primary file used for configuring Nginx as a reverse proxy?

**Answer:** `nginx.conf`

---

# Question: What does the `nginx.conf` file control?

**Answer:** It configures how Nginx functions as a reverse proxy and defines how it serves web content.

---

# Question: What command is used to start the Nginx server after installation?

**Answer:** `nginx`

---

# Question: After starting Nginx, what URL should be visited to verify it's working locally?

**Answer:** `http://localhost:880`

---

# Question: What happens when visiting `http://localhost:880` after starting Nginx?

**Answer:** The browser sends a request to the Nginx server, which then serves static content back to the browser.

---

# Question: How can you confirm that Nginx is serving content by inspecting your browser?

**Answer:** Use the Network tab in developer tools to see the request and verify that the server is listed as Nginx.

---

# Question: What is the next step after confirming Nginx is serving content successfully?

**Answer:** Begin returning other files, folders, and images needed for the application.

---

# Question: What are the two primary elements found in the `nginx.conf` file?

**Answer:** Directives (key-value pairs) and contexts (blocks enclosed in curly braces).

---

# Question: What is a directive in an `nginx.conf` file?

**Answer:** A directive is a key-value pair that configures specific behaviors in Nginx, such as `worker_processes 1;`.

---

# Question: Provide an example of a directive found in the Nginx configuration file.

**Answer:** `worker_processes 1;` is a directive where `worker_processes` is the key and `1` is the value.

---

# Question: What is the `include` directive used for in Nginx?

**Answer:** It includes external configuration files, such as `mime.types`.

---

# Question: What is a context in the `nginx.conf` file?

**Answer:** A context is a block enclosed in curly braces `{}` that groups related directives under a specific scope, like `events` or `http`.

---

# Question: Can directives be nested inside contexts in Nginx configuration?

**Answer:** Yes, directives can be defined within contexts and are specific to that context.

---

# Question: What is the purpose of the `http` context in Nginx?

**Answer:** It defines the HTTP server and contains directives relevant to serving HTTP content.

---

# Question: What are examples of contexts in a basic Nginx configuration file?

**Answer:** `events` and `http`.

---

# Question: What must be defined even if unused to ensure proper Nginx configuration?

**Answer:** The `events` context must be defined even if it is not used.

---

# Question: What kind of content is referred to as "static content" in the context of a web server?

**Answer:** Files like HTML, CSS, and images that do not change dynamically.

---

# Question: What command was used to create a directory named `my_site` from the terminal?

**Answer:** `mkdir my_site`.

---

# Question: What command was used to open the created folder in Visual Studio Code?

**Answer:** `code .` (run from inside the `my_site` directory).

---

# Question: What was the purpose of creating the `index.html` file in the `my_site` directory?

**Answer:** To serve it as static content through the Nginx server.

---

# Question: What content was added to the `index.html` file to display in the browser?

**Answer:** An HTML structure with a `<body>` containing `<h1>Hello, my friends, I am served from nginx</h1>`.

---

# Question: Which port is configured for the Nginx server to listen?

**Answer:** Port 8080.

---

# Question: Which directive is used to specify the port Nginx should listen on?

**Answer:** `listen`.

---

# Question: Which directive specifies the root directory from which Nginx will serve files?

**Answer:** `root`.

---

# Question: In the configuration, what directory path is assigned to the `root` directive?

**Answer:** The full path to the `my_site` directory (copied from the file system).

---

# Question: Under which context is the `server` context defined?

**Answer:** Inside the `http` context.

---

# Question: What is the purpose of the `server` context in Nginx configuration?

**Answer:** It defines the configuration for a specific server, including directives like `listen` and `root`.

---

# Question: What does Nginx do by default when accessing a route with a configured `root` directive?

**Answer:** It looks for an `index.html` file in the specified root directory and serves it.

---

# Question: What should you do after modifying the Nginx configuration to apply changes?

**Answer:** Run the command `nginx -s reload` in the terminal.

---

# Question: Why might you still see the default Nginx page after configuring the `root` and `listen` directives?

**Answer:** Because the Nginx server needs to be reloaded with the new configuration using `nginx -s reload`.

---

# Question: What command is used to reload the Nginx configuration?

**Answer:** `nginx -s reload`

---

# Question: What is the purpose of creating a `styles.css` file in this example?

**Answer:** To apply custom styles to the `h1` element of the `index.html` using CSS.

---

# Question: What styles were applied to the `h1` element in the `styles.css` file?

**Answer:** `background-color: pink;` and `color: aqua;`.

---

# Question: What HTML tags were added to properly structure the document for styling?

**Answer:** `<!DOCTYPE html>`, `<head>`, `<meta charset="UTF-8">`, `<title>`, and `<link>` to the CSS file.

---

# Question: What was the issue when the CSS file was served but the styles were not applied?

**Answer:** The `Content-Type` of the CSS file was incorrectly set to `text/plain` instead of `text/css`.

---

# Question: How was it determined that the CSS file was being served but not interpreted properly?

**Answer:** By inspecting the browser’s network tab and checking the MIME type (`Content-Type`) of the file.

---

# Question: What MIME type did the CSS file incorrectly have when first served by Nginx?

**Answer:** `text/plain`

---

# Question: What should the correct MIME type be for a CSS file?

**Answer:** `text/css`

---

# Question: Where in the Nginx configuration can you define MIME types?

**Answer:** Inside the `http` context.

---

# Question: Why is it important to configure the correct MIME type for static files in Nginx?

**Answer:** Because browsers use the MIME type to determine how to process the file; incorrect types may prevent proper rendering or styling.

---






# Question: What is the main purpose of encryption in modern technology?

**Answer:**
Encryption scrambles data so that only authorized users can access it. It is used in everyday applications like locking phones and password-protecting files.

---

# Question: How are passwords used in securing data?

**Answer:**
Passwords act as keys to lock our data and identify us to systems. They are crucial in encryption and must be protected to prevent unauthorized access.

---

# Question: What type of encryption is used to secure data during web transactions?

**Answer:**
Public-key encryption is used for securing data during web transmissions, such as online shopping or accessing online accounts.

---

# Question: How has software changed the process of movie animation?

**Answer:**
Software has replaced traditional cel animation, enabling the creation of entire movie sets through CGI, which uses mathematical descriptions to render scenes.

---

# Question: Why are game graphics considered impressive beyond just visual appeal?

**Answer:**
Game graphics are impressive because they are generated in real-time using efficient and clever techniques, often under strict time constraints, unlike movie CGI.

---

# Question: What is the benefit of data compression?

**Answer:**
Data compression reduces file size, allowing us to store more information and use less bandwidth. It is essential for applications like Blu-ray discs and video streaming.

---

# Question: What is the role of search algorithms in computing?

**Answer:**
Search algorithms help locate data instantly, whether on a personal computer or the entire web, by organizing and retrieving information efficiently.

---

# Question: What does concurrency enable in modern computing?

**Answer:**
Concurrency allows multiple programs or users to access shared data simultaneously without interference, enabling functions like multiplayer gaming and online banking.

---

# Question: How do mapping systems determine the best route?

**Answer:**
Mapping systems use software to interpret maps and apply specialized search techniques to find the most efficient routes between locations.

---

# Question: Why do most people trust the “lock” icon in their browser when entering sensitive information?

**Answer:**
The lock icon indicates that the website is using secure encryption protocols (like HTTPS), which protect data—such as credit card numbers—by making it unreadable to unauthorized parties during transmission.

---

# Question: How does creating a password protect the data on your phone?

**Answer:**
A password protects your phone’s data by triggering encryption mechanisms that scramble the contents, making them inaccessible to anyone without the correct password.

---

# Question: What does computer security aim to protect?

**Answer:**
Computer security focuses on protecting digital data from unauthorized access, theft, or tampering, often by using technologies like encryption and secure authentication.

---

# Question: Why was data more secure before the digital age?

**Answer:**
Before the digital age, most data was stored physically (e.g., in filing cabinets or shoeboxes), making it harder to access or steal remotely. Today, digital data can be accessed or stolen from anywhere, often without the victim's immediate knowledge.

---

# Question: What is the role of encryption in computer security?

**Answer:**
Encryption is the foundation of computer security. It transforms readable data (plaintext) into unreadable data (ciphertext), which can only be decrypted by someone with the correct key.

---

# Question: What is plaintext and ciphertext in the context of encryption?

**Answer:**
Plaintext is the original, readable form of data, while ciphertext is the encrypted, unreadable form. Encryption turns plaintext into ciphertext, and decryption reverses the process.

---

# Question: Who is considered an attacker in the context of computer security?

**Answer:**
An attacker is anyone who tries to decrypt or access encrypted data without proper authorization.

---

# Question: What is the goal of encryption from a security standpoint?

**Answer:**
The goal of encryption is to ensure that authorized users can easily decrypt and access data, while making it virtually impossible for unauthorized users (attackers) to do so.

---

# Question: Why is no encryption system considered completely unbreakable?

**Answer:**
Because with enough time and computing power, any encryption system can theoretically be broken. The goal is to make decryption so difficult that it becomes impractical for attackers.

---

# Question: What is the primary goal of computer security in terms of encryption?

**Answer:**
To make attacks so resource-intensive and time-consuming that they are practically impossible to succeed, even if technically feasible.

---

# Question: Why are old, pre-software encryption techniques still relevant today?

**Answer:**
Because they form the foundational concepts upon which modern digital encryption schemes are built. Techniques like transposition still influence current encryption methods.

---

# Question: What does the term "transposition" mean in the context of encryption?

**Answer:**
Transposition refers to a method of encryption that involves rearranging the positions of characters in the plaintext to create ciphertext without altering the actual characters.

---

# Question: How does a simple transposition cipher work?

**Answer:**
A simple transposition cipher works by selecting letters from the plaintext in a specific pattern (e.g., every third letter), and rearranging them in multiple passes to obscure the original message.

---

# Question: Why were transposition ciphers useful among children passing notes?

**Answer:**
Because they could quickly scramble a message in a way that made it unreadable to others, while still being easy to reverse for the intended recipient.

---

# Question: Why is the basic transposition method considered weak encryption?

**Answer:**
Because it relies on secrecy of the method itself, which can be easily compromised if someone reveals the technique. Once the method is known, the messages become easy to decode.

---

# Question: What is the primary weakness of using secret encryption methods without keys?

**Answer:**
They are vulnerable to leaks—if the method becomes known, anyone can decrypt the messages, making the encryption ineffective.

---

# Question: What is Kerckhoffs’s Principle?

**Answer:**
Kerckhoffs’s Principle states that the security of a cryptographic system should depend only on the secrecy of the key, not on the secrecy of the encryption method itself.

---

# Question: How do modern encryption systems ensure security if the method is publicly known?

**Answer:**
They use secret cipher keys. Even if the encryption method is public, the data remains secure because only the correct key can successfully decrypt the message.

---

# Question: What is a cipher key in encryption?

**Answer:**
A cipher key is a secret value (such as a number or string) shared between the sender and receiver that determines how data is encrypted or decrypted within a known encryption method.

---

# Question: Why is it difficult to decrypt a transposition message without the key?

**Answer:**
Without the key, the sequence of rearranged letters is unknown, making it nearly impossible to reverse the process accurately without trying an enormous number of possibilities.

---

# Question: What is one strategy for maintaining encryption security against leaks?

**Answer:**
Regularly changing the cipher key helps prevent leaks from compromising the encryption, even if someone learns the method being used.

---

# Question: What is a brute-force attack in the context of encryption?

**Answer:**
A brute-force attack tries every possible permutation or key until the correct plaintext is found. It’s a trial-and-error method that becomes impractical when the number of combinations is very large.

---

# Question: How many possible permutations are there for the message "CATHY LIKES KEITH" using transposition?

**Answer:**
There are approximately **40 billion** possible permutations, making brute-force decryption very difficult without additional clues.

---

# Question: Why are brute-force attacks often inefficient?

**Answer:**
Because they test all possible combinations, many of which are nonsensical. This makes the process extremely slow unless additional information can help narrow down the possibilities.

---

# Question: How can an attacker improve their chances without using brute force?

**Answer:**
By using language patterns or context—like recognizing that most English words don’t start with “HT,” or guessing likely names or words in the message—an attacker can eliminate many permutations.

---

# Question: What is the purpose of varying the substitution pattern in encryption?

**Answer:**
Varying the substitution pattern strengthens encryption against frequency analysis by ensuring that the same plaintext letter can be replaced by different ciphertext letters throughout the message.

---

# Question: What is the name of the technique that uses varying substitution patterns during encryption?

**Answer:**
The technique is known as polyalphabetic substitution.

---

# Question: What is a tabula recta?

**Answer:**
A tabula recta is a grid of alphabets where each row and column is labeled with a letter of the alphabet, used to vary encryption in polyalphabetic substitution.

---

# Question: How are the rows and columns labeled in a tabula recta?

**Answer:**
Each row and column in a tabula recta is labeled with the letter of the alphabet that starts that row or column.

---

# Question: In a tabula recta, what does the intersection of row D and column H contain?

**Answer:**
The intersection of row D and column H contains the letter K.

---

# Question: What type of key is used in a tabula recta to vary encryption?

**Answer:**
A textual key, where letters are used to select columns, is used to vary encryption in a tabula recta.

---

# Question: In the tabula recta example, how is the first letter of the ciphertext derived from the plaintext letter S and key letter T?

**Answer:**
The first letter of the ciphertext is found at the intersection of row S and column T in the tabula recta, which is the letter L.

---

# Question: What happens when the plaintext is longer than the key in a tabula recta encryption?

**Answer:**
When the plaintext is longer than the key, the letters of the key are reused starting from the beginning.

---
