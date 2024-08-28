# Simple Quiz App

This is a simple quiz application built using HTML, CSS, and JavaScript. The quiz allows users to answer multiple-choice questions and see their score at the end.

[TRY IT NOW 😊](https://vivek4nag.github.io/Quiz-App/)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- Multiple-choice questions
- Displays correct and incorrect answers
- Shows the final score at the end of the quiz
- Option to retake the quiz

## Technologies Used

- **HTML**: Structure of the web page
- **CSS**: Styling the quiz application
- **JavaScript**: Logic for quiz functionality


## Usage

1. When you open the quiz app, the first question will be displayed.
2. Click on an answer to select it.
3. Click the "Next" button to proceed to the next question.
4. After answering all questions, your score will be displayed.
5. Click "Play Again" to retake the quiz.

## Code Structure

- **`index.html`**: The main HTML file that contains the structure of the quiz application.
- **`styles.css`**: The CSS file that styles the quiz application.
- **`script.js`**: The JavaScript file that contains the logic for displaying questions, handling user input, and calculating scores.

## Customization

You can customize the quiz by modifying the `questions` array in the `script.js` file. Each question object in the array has a `question` property for the question text and an `answers` property which is an array of answer objects. Each answer object should have:
- `text`: The text of the answer
- `correct`: A boolean indicating whether the answer is correct

Example:

```javascript
const questions = [
    {
        question: "Your new question?",
        answers: [
            { text: "Answer 1", correct: false },
            { text: "Answer 2", correct: true },
            { text: "Answer 3", correct: false },
            { text: "Answer 4", correct: false }
        ]
    },
    // Add more questions here
];
