**Rock Paper Scissors Game**

This is a simple implementation of the Rock Paper Scissors game in JavaScript. The game allows you to play against the computer for a total of 5 rounds and determines the winner based on the scores.

**How to Play**
Clone or download the repository to your local machine.
Open the index.html file in your web browser.
Open the browser's developer console (usually accessed with F12 or Ctrl+Shift+J).
You will be prompted to enter your choice: Rock, Paper, or Scissors. Type your choice into the prompt and press Enter.
The game will simulate the computer's choice and display the result of the round in the console.
Repeat steps 4 and 5 for the remaining rounds.
After 5 rounds, the final scores will be displayed, and the winner (or a tie) will be announced.
Code Explanation
The game consists of the following functions:

**getComputerChoice()**
This function randomly selects a choice (Rock, Paper, or Scissors) for the computer using JavaScript's Math.random() function.

**playRound(playerSelection, computerSelection)**
This function takes two parameters, playerSelection and computerSelection, representing the choices of the player and computer, respectively. It compares the choices and determines the outcome of the round (tie, win, or lose) based on the rules of Rock Paper Scissors.

**game()**
This function manages the overall game flow. It initializes the player and computer scores, runs the game for 5 rounds, and keeps track of the scores. At the end of the game, it determines the winner or a tie based on the scores and displays the result.

**Have Fun!**
Feel free to modify the code, add more features, or customize the game according to your preferences. Enjoy playing Rock Paper Scissors!
