# Quiz Game – JavaScript

A simple command-line quiz application built with JavaScript and Node.js.

The application loads questions from a JSON file, randomly selects a specified number of questions, and allows the user to answer multiple-choice questions directly from the terminal.

## Features

- Load questions from an external JSON file.
- Randomly select questions from the available question list.
- Display multiple-choice answers.
- Validate user input.
- Calculate the number of correct answers.
- Measure the total time taken to complete the quiz.
- Display the final score as a percentage.

## Technologies

- JavaScript
- Node.js
- prompt-sync
- File System (`fs`)
- JSON

## Project Structure

```text
quiz-game/
│
├── question.json
├── index.js
├── package.json
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd quiz-game
```

3. Install dependencies:

```bash
npm install
```

4. Run the application:

```bash
node index.js
```

## How It Works

1. The application loads questions from `question.json`.
2. The user chooses how many questions to answer.
3. Questions are randomly selected from the available list.
4. The user answers each question by entering the corresponding number.
5. At the end, the application displays:
   - Number of correct answers.
   - Total time taken.
   - Final score percentage.

## Example Output

```text
Enter the number of questions you want to answer: 3

What is JavaScript?
1. A programming language
2. A database
3. An operating system

Enter the number of your choice: 1

Correct: 2
Time: 15s
Score: 67%
```

## Learning Objectives

This project was created to practice fundamental JavaScript and Node.js concepts:

- Functions and parameters.
- Arrays and array methods (`sort`, `slice`).
- Objects and property access.
- Loops and conditional statements.
- JSON parsing.
- File System operations.
- User input with `prompt-sync`.
- Random number generation.
- Date and time calculations using `Date.now()`.

