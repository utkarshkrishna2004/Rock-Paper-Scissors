## Rock Paper Scissors

This project is a simple implementation of the classic game "Rock Paper Scissors" using JavaScript. The game allows the player to choose between rock, paper, and scissors, and then plays against the computer, determining the winner based on the chosen moves.

### Usage
To play the game, open the `index.html` file in a web browser of your choice. The page will display the game interface with three buttons representing the player's moves: Rock, Paper, and Scissors. Click on any of the buttons to make your move and see the result of the game displayed in an alert box.

### Features
- Player Moves: The game allows the player to select their move by clicking on the corresponding buttons for Rock, Paper, or Scissors.
- Computer Opponent: The computer randomly selects its move to compete against the player.
- Result Display: After making a move, an alert box displays the player's choice, the computer's choice, and the result of the game (win, lose, or tie).

### Technologies Used
- HTML
- JavaScript

### How It Works
1. The `playGame` function is triggered when the player clicks on one of the move buttons. It takes the player's move as an argument.
2. The `pickComputerMove` function generates a random number between 0 and 1 and assigns a corresponding move to the computer based on the ranges defined.
3. The `playGame` function compares the player's move with the computer's move using a series of conditional statements.
4. The result of the game is determined based on the rules of Rock Paper Scissors, and the outcome is stored in the `result` variable.
5. An alert box is displayed, showing the player's move, the computer's move, and the result of the game.

### Future Enhancements
- User Interface: Improve the visual presentation of the game by styling the buttons and adding a scoreboard or visual indicators for the game results.
- Multiplayer Mode: Implement a two-player mode where two human players can compete against each other.
- Game Rounds: Add the ability to play multiple rounds and keep track of the overall score.

### Hosted Project
The Rock Paper Scissors game is hosted on GitHub Pages. You can access it [here](https://utkarshkrishna2004.github.io/Rock-Paper-Scissors/).

Feel free to explore the code and make modifications according to your requirements or to further enhance the project.

Thank you!
