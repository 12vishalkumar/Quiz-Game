# Quiz Game

<p align="justify">This project is a simple quiz game web application built using HTML, CSS, and JavaScript. The game allows users to start a quiz, answer multiple-choice questions, and see their results.</p>

## File Structure

- `index.html`: The main HTML file that contains the structure of the web page.
- `styles.css`: The CSS file that styles the web page.
- `script.js`: The JavaScript file that contains the logic for the quiz game.

## Description of Files

### index.html

The HTML file defines the structure of the web page. It includes:
- The `<!DOCTYPE html>` declaration and the opening `<html>` tag with a language attribute set to "en".
- The `<head>` section which contains metadata, including the character set, viewport settings, the title of the page, and a link to the external CSS file.
- The `<body>` section which contains the main content of the page:
  - A container div with the question container and control buttons.
  - The question container includes a div for displaying the question and a grid of buttons for the answers.
  - Control buttons include a "Start" button to begin the quiz and a "Next" button to proceed to the next question.
- A script tag that links to the external JavaScript file.

### script.js

The JavaScript file contains the logic for the quiz game:
- Variable declarations for DOM elements.
- Event listeners for the "Start" and "Next" buttons.
- The `startGame` function initializes the quiz, shuffles the questions, and displays the first question.
- The `setNextQuestion` function sets up the next question by resetting the state and showing the next question.
- The `showQuestion` function displays the current question and its answer options.
- The `resetState` function clears previous answers and hides the "Next" button.
- The `selectAnswer` function handles answer selection, sets the status class, and shows the "Next" button if more questions remain.
- Helper functions `setStatusClass` and `clearStatusClass` manage the visual feedback for correct and incorrect answers.
- An array of question objects with questions and answer options.

### styles.css

The CSS file styles the web page:
- General styles for body and container elements.
- Specific styles for question and answer buttons.
- Hidden class for elements not currently visible.

## Usage

To use the application:
1. Open `index.html` in a web browser.
2. Click the "Start" button to begin the quiz.
3. Answer the displayed question by clicking one of the answer buttons.
4. Click the "Next" button to proceed to the next question.
5. After answering all questions, restart the quiz by clicking the "Restart" button.

## Dependencies

No external dependencies are required for this project. It uses plain HTML, CSS, and JavaScript.

## Notes

- The questions and answers are hardcoded in the JavaScript file.
- The quiz game provides immediate feedback on the correctness of each answer.
- The quiz can be restarted by clicking the "Restart" button after completing all questions.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).