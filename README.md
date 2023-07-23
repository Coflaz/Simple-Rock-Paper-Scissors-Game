# Updated Rock Paper Scissors Game

This is an updated version of the Rock Paper Scissors game implemented as a web application using HTML, CSS, and JavaScript. The game allows you to play against the computer and keeps track of your score (wins, losses, and ties) throughout the game.

## How to Play

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your web browser.

## Rules of The Game

- Rock beats Scissors
- Scissors beat Paper
- Paper beats Rock

## Game Interface

The game interface displays three buttons for you to make your choice:

1. **Rock**: Click this button to choose "Rock" as your play.
2. **Paper**: Click this button to choose "Paper" as your play.
3. **Scissors**: Click this button to choose "Scissors" as your play.

After making your choice, the computer will randomly select its play (Rock, Paper, or Scissors). The result of the game will be displayed on the screen, indicating whether you won, lost, or tied with the computer.

## Score Keeping

The game keeps track of your score. It is divided into three categories:

- **Wins**
- **Losses**
- **Ties**

The scores are updated and displayed on the screen as the game progresses.

## Additional Features

The game also provides the following additional functionalities:

1. **Reset Scores**: Click this button to reset your scores back to zero.
2. **Save Scores**: Click this button to save your current scores in the browser's local storage. The scores can be retrieved later using the "Continue" button.
3. **Continue**: Click this button to retrieve the saved scores from the local storage and continue the game from where you left off.

## JavaScript Functions

The game logic is implemented in JavaScript using the following key functions:

- `computerPlay()`: Randomly selects Rock, Paper, or Scissors for the computer's play.
- `winLoseTie(playerChoice, computerChoice)`: Evaluates the result of the game based on your and the computer's choices.
- `gameResultChange(result)`: Updates the result of the game on the screen.
- `gameSituationChange(playerChoice, computerChoice, result)`: Updates the game situation on the screen.
- `scoreTableChange()`: Updates the score table on the screen.
- `resetScores()`: Resets your scores to zero.
- `saveScores()`: Saves your current scores in the browser's local storage.
- `continueGame()`: Retrieves the saved scores from the local storage and continues the game.

Have fun playing Rock Paper Scissors!

