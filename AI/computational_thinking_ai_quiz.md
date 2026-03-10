# Question: Why is the current time described as an incredibly exciting time in programming?
**Answer:** Because AI can now help solve problems, find bugs in code, and even add new features to software, making development faster and more powerful.

---

# Question: In what ways can AI assist programmers?
**Answer:** AI can help solve problems, detect bugs or mistakes in code, and generate or suggest additional features to add to software.

---

# Question: Why is AI's ability to add features to software considered a huge development?
**Answer:** Because it reduces the limitations caused by human developers, who previously had limited time and resources to implement features and fix bugs.

---

# Question: What has historically been the bottleneck in software development?
**Answer:** Humans have been the bottleneck because there are only so many hours in a day and only so many people available to write and maintain code.

---

# Question: Why do developers face limits when trying to solve bugs or implement features?
**Answer:** Because teams have limited time and limited numbers of developers, while the number of bugs and desired features can be much larger.

---

# Question: Despite AI assistance, what do programmers still need to understand?
**Answer:** Programmers still need to understand the fundamentals of programming and computing.

---

# Question: What type of thinking?
**Answer:** To think logically about problems, specifically how to take input and produce correct output.

---

# Question: What core skill related to computing?
**Answer:** The ability to take input, process it correctly, and produce the correct output.

---

# Question: Which programming languages?
**Answer:** C, Python, SQL, HTML, CSS, and JavaScript.

---

# Question: What long-term skill beyond learning specific programming languages?
**Answer:** Learn how to teach yourself new technologies and programming concepts.

---

# Question: What ability develop regarding computers?
**Answer:** you will be able to instruct computers more effectively about what tasks they should perform.

---

# Question: Even with AI tools, who remains in control of the programming process?
**Answer:** The human programmer remains in control.

---

# Question: What metaphors are used to describe the programmer's role when working with computers and AI?
**Answer:** The programmer is described as being in the driver's seat, the pilot, or the conductor.

---

# Question: Why is learning foundational or introductory material still empowering?
**Answer:** Because it gives learners the knowledge needed to understand what they are doing and effectively control the tools they use.

---

# Question: What advantage does understanding foundational concepts give programmers when using AI tools?
**Answer:** It allows them to understand what they are asking AI to do and ensures they remain in control of the development process.

---

# Question: why might it still be useful to understand concepts even when AI tools can help solve problems?

**Answer:** Because mastering the underlying ideas allows a person to understand the problem and then use AI tools or co-pilot assistants to help implement or solve it more efficiently.

---

# Question: How does AI relate to learning programming concepts?

**Answer:** Programmers may increasingly focus on mastering the core ideas while relying on AI assistants to help implement or solve coding problems.

---

# Question: What software tool? What is another common name used for Visual Studio Code?

**Answer:** Visual Studio Code, commonly known as VS Code. Visual Studio Code is commonly abbreviated as VS Code.

---

# Question: What type of software is Visual Studio Code?

**Answer:** Visual Studio Code is a popular, largely open-source or free software text editor used by developers to write code.

---

# Question: Who commonly uses Visual Studio?

**Answer:** It is used by real-world professionals and developers in the software industry.

---

# Question: What type of application is Visual Studio Code compared to?

**Answer:** It is compared to a text editor similar to Notepad or TextEdit.

---

# Question: What interface element appears at the bottom of the VS Code screen?

**Answer:** A terminal window appears at the bottom of the screen.

---

# Question: What is the purpose of the terminal window in VS Code?

**Answer:** The terminal window allows users to type commands that tell the computer what actions to perform.

---

# Question: What example project building for demonstration purposes?

**Answer:** Creating a personal chatbot.

---

# Question: Which existing chatbot systems examples of well-known AI chatbots?

**Answer:** ChatGPT, Gemini, and Claude are examples of well-known chatbots.

---

# Question: What does the `.py` extension in `chat.py` indicate?

**Answer:** The `.py` extension indicates that the program is written in the Python programming language.

---

# Question: Where is the code executed within the programming environment?

**Answer:** The code is executed **at the bottom of the window in the terminal in Vs Code**.

---

# Question: What command is used to include the OpenAI library in the Python program?

**Answer:** `import openai`

---

# Question: What is the purpose of importing the OpenAI library in the Python program?

**Answer:** Importing the OpenAI library allows the programmer to **use OpenAI's API features and functionality within their code**.

---

# Question: What does API stand for?

**Answer:** **API** stands for **Application Programming Interface**.

---

# Question: What is the purpose of an API in software development?

**Answer:** An API allows developers to **write code that interacts with software or services provided by another company or system**.

---

# Question: Which company provides the API used in the example program?

**Answer:** The API is provided by **OpenAI**.

---

# Question: What is meant by creating a “client” in the context of using an API?

**Answer:** A **client** is a program that **uses and interacts with the functionality provided by an API**.

---

# Question: What method is used in the program to generate a response from the OpenAI API?

**Answer:** `client.responses.create`

---

# Question: What is the purpose of calling `client.responses.create()` in the program?

**Answer:** It sends a **request to the OpenAI API to generate a response based on the provided input and model**.

---

# Question: What parameter is used to send a prompt or question to the API?

**Answer:** The **`input`** parameter.

---

# Question: What example prompt is provided as input to the API?

**Answer:** `"in one sentence what is Computer Programming?"`

---

# Question: What are AI models in the context of tools like ChatGPT?

**Answer:** AI models are **statistical models that determine how artificial intelligence systems generate responses and perform tasks**.

---

# Question: What parameter specifies which AI model the program should use?

**Answer:** The **`model`** parameter.

---

# Question: Which AI model is specified in the example program?

**Answer:** `"gpt5"`

---

# Question: How is the AI model specified in the API request?

**Answer:** By setting `model="gpt5"` inside the `client.responses.create()` function.

---

# Question: What command is used in the terminal to run the Python script?

**Answer:** `python chat.py`

---

# Question: What condition must be met for the program to run successfully?

**Answer:** The program must **contain no typographical errors**.

---

# Question: What is the purpose of using the `print` statement in the program?

**Answer:** The `print` statement displays the **response generated by the OpenAI API**.

---

# Question: What property of the response object is printed to show the generated answer?

**Answer:** `response.output_text`

---

# Question: What is the overall goal of the Python program?

**Answer:** The program demonstrates how to **build a simple chatbot by sending a prompt to OpenAI’s API and printing the generated response using Python code**.

---

# Question: What was the initial limitation of the user's chatbot implementation?
**Answer:** The chatbot was hard-coded to permanently answer only one specific question.

---

# Question: Approximately how many lines of code were used in the initial chatbot implementation mentioned?
**Answer:** Not even 10 lines of code, since a few of them were blank.

---

# Question: What example question did the hard-coded chatbot answer?
**Answer:** "What is Computer Programming?"

---

# Question: How did the chatbot describe Computer Programming when asked the question?
**Answer:** Computer programming is the process of writing instructions that tell a computer what to do. These instructions are written in special languages called programming languages.

---

# Question: What improvement was proposed to make the chatbot program more dynamic?
**Answer:** Modifying the program to ask the human user for their question instead of using a fixed hard-coded question.

---

# Question: What Python function was introduced to collect a question from the user?
**Answer:** The `input()` function.

---

# Question: What variable name was used to store the user's question?
**Answer:** The variable `prompt`.

---

# Question: What line of Python code was used to request input from the user?
**Answer:** `prompt = input()`

---

# Question: What does the `=` operator represent in the statement `prompt = input()`?
**Answer:** It assigns the value returned by `input()` to the variable `prompt`.

---

# Question: What concept in programming is compared to variables like `x`, `y`, or `z` in mathematics?
**Answer:** A variable, which stores data such as the user's input.

---

# Question: What type of data is stored in the variable `prompt`?
**Answer:** The keystrokes or text typed by the human user as their question.

---

# Question: How is the stored `prompt` used in the chatbot program?
**Answer:** It is passed as the input to OpenAI so the AI can generate a response based on the user's question.

---

# Question: What new capability does the chatbot gain after using `input()`?
**Answer:** The chatbot can accept and respond to dynamically entered questions from the user.

---

# Question: What example dynamic question was entered into the program?
**Answer:** "In one sentence, what is Computer programming?"

---

# Question: What happened after the user entered the question dynamically?
**Answer:** The chatbot returned an answer similar to the earlier one but slightly different.

---

# Question: Why might the chatbot's answer vary even when asking the same question again?
**Answer:** Because the AI may generate a slightly different variant of the response each time.

---

# Question: What action was suggested to further test the chatbot after receiving a response?
**Answer:** Running the program again using the command `python chat.py`.

---


# Question: What computer science topics?

**Answer:** Problem solving, algorithms, data structures, and programming languages such as C and Python.

---

# Question: What technique was repeatedly used in the code to guide how the AI should answer?

**Answer:** Providing a prompt from the human.

---

# Question: What example instructions were included in the human prompts to control the AI’s response format?

**Answer:** “In one sentence” and “in one word.”

---

# Question: Why keep providing formatting instructions like “in one sentence” in the prompt?

**Answer:** To control how the AI formats its responses.

---

# Question: What improvement was suggested so the human does not need to repeatedly include formatting instructions in every prompt?

**Answer:** Using a system prompt with standardized instructions.

---

# Question: What was the original variable name used for the prompt before renaming it?

**Answer:** Prompt.

---

# Question: What new variable name was introduced to clarify that the prompt comes from the user?

**Answer:** `user_prompt`.

---

# Question: What additional type of prompt was introduced besides the user prompt?

**Answer:** A system prompt.

---

# Question: What is a **system prompt** in the context of the example?

**Answer:** Standardized instructions given to the AI that control how it should behave.

---

# Question: What example instruction was included in the system prompt?

**Answer:** “Limit your answer to one sentence.”

---

# Question: Why is the system prompt useful in this program?

**Answer:** It ensures the AI consistently follows instructions without the user needing to repeat them in every prompt.

---

# Question: What variable was used to store the standardized AI instructions?

**Answer:** `system_prompt`.

---

# Question: What service was used to process both the user prompt and system prompt?

**Answer:** OpenAI.

---

# Question: What two pieces of information were sent to the AI service as input?

**Answer:** The user prompt and the system prompt.

---

# Question: What command was used in the terminal to run the chatbot program?

**Answer:** `python chat.py`

---

# Question: After adding the system prompt, what question was asked in the terminal to test the program?

**Answer:** “What is Computer programming?”

---

# Question: What kind of answer did the AI return after the system prompt was implemented?

**Answer:** A correct and concise description of Computer programming.

---

# Question: What does the example demonstrate about programming with AI?

**Answer:** It demonstrates that **small amounts of code or instructions (even around 10 lines of text) can influence AI behavior in powerful ways.**

---

# Question: What is **rubber duck debugging**?

**Answer:** Rubber duck debugging is a technique where a programmer **explains their code or problem aloud to a rubber duck (or another object)** to clarify their thinking and discover mistakes.

---

# Question: Why is rubber duck debugging effective for solving programming problems?

**Answer:** Because **verbalizing the problem forces the programmer to organize their thoughts**, often revealing logical errors or misunderstandings.

---

# Question: What kind of object is traditionally used in rubber duck debugging?

**Answer:** A **rubber duck** or any **inanimate cute object placed on the programmer’s desk**.

---

# Question: In rubber duck debugging, when is the technique typically used?

**Answer:** It is used **when a programmer is struggling with a bug or mistake and does not have immediate help from someone more knowledgeable.**

---

# Question: What realization often occurs during rubber duck debugging?

**Answer:** The programmer often suddenly realizes the mistake themselves — the **“light bulb moment.”**

---

# Question: What is the purpose of the **CS50 virtual duck**?

**Answer:** The virtual duck helps students **talk through their programming problems and receive AI assistance while debugging.**

---

# Question: What website provides access to the CS50 AI tools?

**Answer:** The website is **cs50.ai**.

---

# Question: What development environment URL also integrates the CS50 AI tools?

**Answer:** The development environment URL is **cs50.dev**.

---

# Question: What role do **cs50.ai** and **cs50.dev** play?

**Answer:** They provide **AI tools students can use to help with programming and problem-solving.**

---

# Question: Which AI-based software is for solving problems?

**Answer:** AI-based software such as **Claw, Gemini, ChatGPT**

---

# Question: What is the purpose of CS50’s AI-based “virtual duck”?

**Answer:** The virtual duck is designed to **act like a good human tutor**, helping students reason through problems without directly giving away the answer.

---

# Question: What behavior is the CS50 virtual duck designed to emulate?

**Answer:** It emulates the behavior of **a helpful human tutor who guides students toward a solution instead of simply providing the answer outright**.

---

# Question: What fundamental question is introduced before beginning the study of programming and AI?

**Answer:** The question **“What is computer science?”**

---

# Question: How is **computer science** defined?

**Answer:** Computer science is **the study of information, including how information is represented and how it is processed**.

---

# Question: What is **computational thinking**?

**Answer:** Computational thinking is **the application of ideas from computer science to solve real-world problems**.

---

# Question: What is computer science ultimately about?

**Answer:** Computer science is ultimately about **problem solving**.

---

# Question: What role do computers and programming play in computer science?

**Answer:** Computers and programming are **tools and methodologies used to help solve problems**.

---

# Question: In problem-solving, what does the **input** represent?

**Answer:** The input represents **the problem or the information that needs to be processed**.

---

# Question: In problem-solving, what does the **output** represent?

**Answer:** The output represents **the desired result or solution to the problem**.

---

# Question: What does the **“process”** in problem-solving represent?

**Answer:** The proceed represents **the process or method that transforms the input into the output**.

---

# Question: How does the input output model illustrate problem solving in computer science?

**Answer:** It shows that **a problem (input) is processed by some method or algorithm (process) to produce a solution (output)**.

---

# Question: Why must people agree on a standard way to represent information when using computers and digital devices?

**Answer:** Because computers and devices must **represent inputs and outputs in a standardized format** so that information can be processed consistently.

---

# Question: What question is raised about how information might be represented for computers?

**Answer:** Whether information should be represented using **English or some other system**.

---

# Question: What two symbols make up the entire alphabet used by computers?

**Answer:** **0 and 1**.

---

# Question: What is the significance of the digits 0 and 1 in computing systems?

**Answer:** They form the **binary system**, which computers use to represent and process all information.

---

# Question: What is **unary notation**?

**Answer:** Unary notation is a number system that uses **a single digit repeatedly to represent numbers**, also known as **base-1**.

---

# Question: What alternative number system is introduced after unary to improve counting efficiency?

**Answer:** **Binary**.

---

# Question: When using binary representation, what is the highest number you can count to?

**Answer:** **31**.

---

# Question: What key principle about computer systems is illustrated by assigning fixed meanings to each finger?

**Answer:** Computers rely on **agreed-upon standardized representations** to interpret patterns of bits (0s and 1s) as numbers or information.

---









# Question: In binary finger-counting , what number can be represented using three fingers with different combinations?

**Answer:** Up to **7**, because three binary positions allow **2³ = 8 combinations**, representing numbers **0 through 7**.

---

# Question: What is the maximum number that can be represented using five fingers in the binary finger system?

**Answer:** **31**.

---

# Question: Why is 31 the maximum number that can be counted with five fingers in binary?

**Answer:** Because five binary positions produce **2⁵ = 32 possible combinations**, representing numbers **0 through 31**.

---

# Question: Why are there 32 possible combinations with five binary positions but the highest number is 31?

**Answer:** Because **one combination represents 0**, leaving **31 as the highest value**.

---

# Question: What number system is being demonstrated when each finger position is assigned a specific value?

**Answer:** **Base-2 (binary)**.

---

# Question: What does it mean by assigning different “weights” to finger positions?

**Answer:** Each finger position represents **a different value (typically powers of two)** in binary representation.

---

# Question: What number system do computers fundamentally use to represent information?

**Answer:** **Binary (base-2)**.

---

# Question: What is the formal name for a single binary digit?

**Answer:** **Binary digit**.

---

# Question: What is the common shorthand term for a binary digit?

**Answer:** **Bit**.

---

# Question: What are the two possible values a bit can represent?

**Answer:** **0 or 1**.

---

# Question: What larger data measurement terms are derived from bits?

**Answer:** **Bytes, kilobytes, megabytes, gigabytes, terabytes, and more**.

---

# Question: In the physical analogy, how can a **0** be represented?

**Answer:** By **a light bulb being off**.

---

# Question: In the physical analogy, how can a **1** be represented?

**Answer:** By **a light bulb being on**.

---

# Question: Why is electricity a convenient way to represent binary values in computers?

**Answer:** Because electricity can **either be flowing or not flowing**, which naturally maps to **1 or 0**.

---

# Question: What real-world device behavior is used to explain binary states?

**Answer:** **Turning a light switch on or off**.

---

# Question: How does binary simplify electrical representation in computing systems?

**Answer:** It avoids the need to measure **exact amounts of electricity**, requiring only two states: **presence or absence of electrical flow**.

---

# Question: What voltage is given to illustrate the presence or absence of electricity?

**Answer:** **0 volts representing no electricity** and **around 5 volts representing electricity present**.

---

# Question: Why is binary considered robust for representing information in hardware?

**Answer:** Because it relies on **two easily distinguishable physical states**, such as **on/off or voltage/no voltage**, making it reliable for electronic circuits.
