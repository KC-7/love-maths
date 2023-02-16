

# Love Maths Project
This is a simple Math game web app where users can practice basic Math skills such as addition, subtraction, multiplication and division.

## Live Link
[Click here :)](https://kc-7.github.io/love-maths/)

## How To Play
The Love Maths app has a user-friendly interface. To start a new game, simply click on one of the four game mode buttons - addition, subtraction, multiplication, or division.

A new question will appear with two random numbers between 1 and 25. The user should enter their answer in the answer box and either click on the submit button or press enter. If the user's answer is correct, a message congratulating them will appear, and their score will increase by one. If the answer is incorrect, a message with the correct answer will appear, and their incorrect answer count will increase by one.

The user can choose to play a new game by clicking on one of the four game mode buttons, and the app will generate new random numbers to start a new game. The game will continue until the user decides to stop.

## Javascript

The Love Maths game is created using Javascript. The script listens for the 'DOMContentLoaded' event and then assigns event listeners to the buttons on the page.

The script generates two random numbers between 1 and 25, and displays a question based on the game type selected by the user. The game types are 'addition', 'multiply', 'subtract', and 'division'.

The 'runGame' function is the main game loop that gets called when the script is first loaded and after the user's answer has been processed. It sets the answer box value to an empty string and focuses the cursor on it.

The 'checkAnswer' function checks the user's answer against the correct answer and increments the score or incorrect answer count accordingly. It then calls the 'runGame' function with the next game type.

The 'calculateCorrectAnswer' function gets the operands (the numbers) and the operator (+, -, *, /) directly from the DOM and returns the correct answer.

The 'incrementScore' and 'incrementWrongAnswer' functions get the current score and incorrect answer counts from the DOM and increment them by 1.

There are four functions for displaying the questions based on the game type: 'displayAdditionQuestion', 'displaySubtractQuestion', 'displayMultiplyQuestion', and 'displayDivisionQuestion'.

## Credits

- This project was created by following a walkthrough Code Institute Project as part of their Full Stack Developer Course. 

- The readme was created using ChatGPT.
