# 📚 Online Quiz Application (Java Mini-Project)

## Objective
A simple console-based quiz application developed in Java. The application loads a list of questions, presents them to the user one by one, accepts input, and displays the final score.

## Features
* **Multiple-Choice Questions:** Questions are presented with numbered options.
* **Score Tracking:** Tracks the user's correct answers throughout the quiz.
* **Input Validation:** Ensures the user enters a valid option number.
* **Final Results:** Displays the final score and percentage upon completion.

## Technologies Used
* **Language:** Java
* **Environment:** Console (Terminal/Command Prompt)

## Project Structure
The application is comprised of two core Java classes:
* `Question.java`: A model class representing a single question, its options, and the correct answer index.
* `QuizApp.java`: The main class containing the application logic, question list management, user input handling, and score calculation.

## How to Run the Quiz

### Prerequisites
* Java Development Kit (JDK) installed on your machine.

### Instructions

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [Your Repository URL]
    cd OnlineQuizApp
    ```

2.  **Compile the Java files:**
    Open your terminal in the project directory and use the Java compiler:
    ```bash
    javac Question.java QuizApp.java
    ```

3.  **Execute the application:**
    Run the compiled main class (`QuizApp`):
    ```bash
    java QuizApp
    ```

The quiz will start immediately, prompting you to enter the number corresponding to your answer for each question.
