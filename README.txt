Welcome to the "Guess My Number" game! This is a simple number guessing game where you need to guess a random number between 1 and 20. You will be provided with feedback on each guess, and the game will keep track of your score and highscore.

How to Play
Open the index.html file in your web browser.
The game interface will display a header with the title "Guess My Number!" and a random number represented by a question mark ("?").
Below the header, you will see an input field where you can enter your guess and a "Check!" button to submit your guess.
The game will provide feedback based on your guess:
If your guess is correct, it will display "🎉 Correct Number!" and change the background color to green.
If your guess is higher or lower than the secret number, it will display "📈 Too high!" or "📉 Too low!" respectively.
If you submit without entering a number, it will display "⛔️ No number!".
You have a total of 20 points (score), and each incorrect guess will deduct one point from your score.
The highest score you achieve during the game will be recorded as your highscore.
You can play multiple times by clicking the "Again!" button, which resets the game with a new random number and your score set to 20.
Good luck and have fun guessing the number!

Technologies Used
This game is created using HTML, CSS, and JavaScript.

How to Customize
If you want to customize the game, you can do the following:

Adjust the range of the random number by changing the multiplier in the JavaScript code: Math.trunc(Math.random() * 20) + 1. For example, changing 20 to 50 will generate a random number between 1 and 50.
Modify the styles in the style.css file to change the appearance of the game interface.
Have fun playing and happy coding!




