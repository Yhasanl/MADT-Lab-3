# MADT Lab #3 - Android App Testing

This repository contains the solution for the MADT Lab #3 assignment. As part of the project, both Unit and UI tests have been written and successfully executed for the application.

## 🤖 AI Session Summary and User Requests

In accordance with the assignment requirements, the creation of tests and GitHub operations were performed in completely separate AI sessions (chats):

### Session 1: Unit Test Generation
* **User Request:** "I want to generate Unit tests for my Android application that will ensure 100% code coverage at the class and function level."
* **Result:** Unit tests for the core logic were written by the AI using JUnit, and all tests passed successfully.

### Session 2: UI (Integration) Test Generation
* **User Request:** "Write UI tests for my application using at least 4 different scenarios to verify the user interface. There is a keyboard issue in the emulator during tests (typeText error), find a solution for this."
* **Result:** 4 different test scenarios were created by the AI using the Espresso framework. The keyboard error was resolved by replacing the `typeText()` method with `replaceText()`. As a result, all 4 tests passed successfully (4/4 passed).

### Session 3: GitHub Deployment and MD File Creation
* **User Request:** "I have finished all the tests. Now, how can I push my project to a new GitHub repository via the terminal? Also, prepare a final MD (Markdown) file for me summarizing the previous conversations."
* **Result:** The AI provided step-by-step instructions for the `git init`, `commit`, `branch`, and `push` commands. Minor issues in the terminal like "remote origin already exists" and browser authentication were resolved with AI assistance, and the codebase was successfully pushed to GitHub.

---

## 🚀 Setup and Execution
1. Clone the repository: `git clone https://github.com/Yhasanl/MADT-Lab-3.git`
2. Open the project in Android Studio.
3. Use the IDE's built-in test tools (the "Play" button next to the test classes/methods) to run the tests.
