#Tic-Tac-Toe Game

#Project Description
This is a simple Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns playing as "X" and "O" on a 3x3 grid. The game determines the winner based on predefined winning combinations or declares a draw if all boxes are filled without a winner.

Features
Two-player turn-based gameplay (Player X and Player O).
Winning detection based on standard Tic-Tac-Toe rules.
Draw detection if all boxes are filled without a winner.
Reset functionality to start a new game.
Modern and responsive design with color-coded "X" (Red) and "O" (Blue).
Simple hover effects and interactivity for better user experience.

Technologies Used
HTML: For the structure and layout of the game board.
CSS: For styling the game board, buttons, and hover effects, creating a professional and minimalist design.
JavaScript: For game logic, turn handling, winner and draw detection, and interactivity.

Game Rules
The game is played between two players. Player "X" and Player "O" take turns to mark empty cells in a 3x3 grid.
The goal is to place three marks (either X or O) in a horizontal, vertical, or diagonal row.
The first player to do so wins the game, and the game will display a "Congratulations, Winner is X/O" message.
If all boxes are filled and no player has three in a row, the game will declare a Draw.

Project Structure
|-- index.html      # Main HTML file containing the game structure
|-- style.css       # CSS file for styling the game and UI elements
|-- app.js          # JavaScript file containing game logic and interactivity
|-- README.md       # Project documentation

Files Overview:
index.html: Contains the game layout and elements (buttons, boxes, etc.).
style.css: Handles the styling of the game, including the black/white/red/blue color scheme.
app.js: Implements the game logic, winner detection, draw condition, and reset functionality.

How to Play
Open the game in your browser.
Click on any empty box in the 3x3 grid to place your mark ("X" or "O").
The game alternates turns between Player X and Player O.
The first player to align three marks in a row (horizontal, vertical, or diagonal) wins.
If all boxes are filled and there is no winner, the game will end in a draw.
Click the "New Game" button to start a new round, or "Reset Game" to clear the board and reset the turn to Player O.
