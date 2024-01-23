# Tic-tak-game


It looks like you've shared JavaScript code for a simple tic-tac-toe game. The code uses HTML elements, such as buttons and message containers, to create a user interface. Here's a brief description of the main components and functionality:

HTML Structure:

The game likely has an HTML structure that includes a grid of boxes for the tic-tac-toe board, reset and new game buttons, and a message container to display game messages.
JavaScript Variables:

boxes: Represents all the boxes in the tic-tac-toe grid.
resetBtn: Represents the button to reset the game.
newGameBtn: Represents the button to start a new game.
msgContainer: Represents the container for displaying messages.
msg: Represents the message element inside the container.
turnO: Represents the current player (O or X).
count: Keeps track of the number of moves made to determine a draw.
winPatterns: Defines the winning combinations on the tic-tac-toe board.
Functions:

resetGame: Resets the game to its initial state, enabling the boxes for input.
gameDraw: Displays a message when the game ends in a draw.
disableBoxes: Disables input for all boxes.
enableBoxes: Enables input for all boxes and clears their content.
showWinner: Displays a message declaring the winner.
checkWinner: Checks if there is a winner based on the current board state.
Event Listeners:

Each box has a click event listener that alternates between placing "O" and "X" based on the current player's turn. It also checks for a winner or a draw after each move.
The "New Game" and "Reset" buttons have event listeners that call the resetGame function.
Game Logic:

The game uses a simple algorithm to check for winning combinations after each move. If a winner is found, the game declares the winner. If no winner is found after nine moves, the game is declared a draw.
Overall, this code implements a basic tic-tac-toe game with a simple user interface and game logic using HTML, CSS, and JavaScript.
