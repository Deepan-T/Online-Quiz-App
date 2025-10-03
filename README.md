# Java Quiz Application

A simple command-line Java application designed to test basic knowledge of Java programming concepts.

## 🚀 Features

* **Multiple-Choice Questions:** Presents a series of multiple-choice questions on fundamental Java topics.
* **Real-time Scoring:** Calculates and displays the user's score immediately after the quiz.
* **Detailed Results:** Provides a breakdown of each question, showing the user's selected answer, the correct answer, and whether the user's selection was right or wrong.

## ✨ Concepts Covered

The quiz questions primarily focus on the following Java fundamentals:

* Control Flow (Loops, `if-else` vs. `switch`)
* Collections Framework (`List`, `Map`, `ArrayList`)
* Utility Classes (`Scanner`, `Collections`)

## 🛠️ Requirements

* **Java Development Kit (JDK):** Version 8 or higher.

## 💻 How to Run

### 1. Save the Code

Save the entire code snippet provided into a single file named **`QuizApp.java`**.

### 2. Compile

Open your terminal or command prompt, navigate to the directory where you saved `QuizApp.java`, and compile the file:

```bash
javac QuizApp.java
3. Execute
Run the compiled class file:

Bash

java QuizApp
The application will start, and you will be prompted to answer the questions one by one.

📝 Code Structure
The application consists of two main classes:

Question
. This class is responsible for managing a single quiz question.

. Constructor: Initializes the question text, a list of options, and the index of the correct option.

. displayQuestion(): Prints the question and its numbered options to the console.

. checkAnswer(int answer): Compares the user's input with the correct option.

. getCorrectAnswer(): Returns the string value of the correct option.

QuizApp
. This class contains the main method and drives the entire quiz flow.

. Initialization: Creates a List of Question objects, populating the quiz with all the questions.

. Quiz Logic: Iterates through the questions, prompts the user for input using Scanner, checks the answer, and keeps track of the score and userAnswers.

Results: Prints the total score and then a detailed breakdown of the quiz session.

🤝 Contribution
. Feel free to fork this repository, add more questions, improve the user interface, or add new features like randomization or question difficulty levels!

. Fork the repository.

. Create a new branch (git checkout -b feature/new-quiz-type).

. Make your changes.

. Commit your changes (git commit -m 'feat: added 5 new collections questions').

Push to the branch (git push origin feature/new-quiz-type).

Open a Pull Request.
