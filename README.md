# Rock Paper Scissors Game
This is a simple web-based Rock Paper Scissors game implemented in HTML, CSS, and JavaScript. The game allows a player to make choices among Rock, Paper, and Scissors and compete against the computer. It also keeps track of the player's score (wins, losses, and ties) throughout the game.

## How to Play
1. Clone or download the repository to your local machine.
2. Open the Rock-Paper-Scissors.html file in your web browser.

## Rules of The Game
- Rock beats Scissors
- Scissors beat Paper
- Paper beats Rock

## Game Interface
The game interface displays three buttons for the player to choose from:

1. **Rock**: Select this button to choose "Rock" as your play.
2. **Paper**: Select this button to choose "Paper" as your play.
3. **Scissors**: Select this button to choose "Scissors" as your play.

After making a choice, the computer will randomly select its play (Rock, Paper, or Scissors). The result of the game will be displayed as an alert, indicating whether the player won, lost, or tied with the computer.

## Score Keeping
The game keeps track of the player's score. The score is divided into three categories:

- **Wins**
- **Losses**
- **Ties**

The scores are updated and displayed accordingly as the game progresses.

## Additional Features
The game also provides the following additional functionalities:

1. **Show Scores**: Displays the current scores (Wins, Losses, and Ties) in an alert box.
2. **Reset Scores**: Resets the scores back to zero and displays the updated scores in an alert box.
3. **Save Scores**: Saves the current scores in the browser's local storage. The scores can be retrieved later using the "Continue" button.
4. **Continue**: Retrieves the saved scores from the local storage and displays them in an alert box. The game can continue from where it was left off.

## JavaScript Functions
The game logic is implemented in JavaScript. Here are the key functions used in the script:

- `computerPlay()`: Randomly selects Rock, Paper, or Scissors for the computer's play.
- `evaluateScore(pChoice, cChoice)`: Evaluates the result of the game based on the player's and computer's choices.
- `playerScoreUpdate(result)`: Updates the player's score based on the game result.
- `alertResult(pChoice, cChoice, result)`: Displays an alert with the result of the game.
- `showScores()`: Displays the current scores in an alert box.
- `resetScores()`: Resets the scores to zero and displays the updated scores in an alert box.
- `saveScores()`: Saves the current scores in the browser's local storage.
- `continueGame()`: Retrieves the saved scores from local storage and continues the game from where it was left off.

Have fun playing Rock Paper Scissors!
