# Tic-Tac-Toe-React
This project is a simple implementation of the classic Tic-Tac-Toe game built using React. It provides an interactive user interface where two players can play the game, track their moves, and restart the game as needed. The design is enhanced with CSS animations and custom styles.
### Features
- Two-player game with alternating turns.
- Dynamic game board with clickable squares.
- Displays the active player and highlights their name.
- Announces the winner or if the game is a draw.
- Allows players to change their names.
- Keeps a log of all moves made during the game.
- Option to restart the game.
### Installation
1. Clone the repository:
   - git clone https://github.com/MieteX1/ReactOne.git
2. Navigate to the project directory
3. Install the dependencies:
   - npm install
4. Start the development server:
   - npm run-script dev
5. Open your browser and navigate to http://localhost:5173.
### Usage
- Click on any empty square to place your symbol (X or O).
- The game will automatically switch turns between Player 1 (X) and Player 2 (O).
- Once a player wins or the game is a draw, a message will be displayed.
- Click the "Rematch!" button to restart the game.
- Players can edit their names by clicking the "Edit" button next to their names.
### Key Files
- **index.html**: The main HTML file that sets up the basic structure of the application.
- **index.jsx**: The entry point of the React application, where the root component is rendered.
- **App.jsx**: The main component that holds the state and logic of the game.
- **components/**
  - **Player.jsx**: Component for displaying and editing player names.
  - **GameBoard.jsx**: Component for rendering the game board and handling moves.
  - **Log.jsx**: Component for logging the moves made during the game.
  - **GameOver.jsx**: Component for displaying the game over message and rematch button.
- **index.css**: Contains all the styles for the application.
- **winning-combinations.js**: Defines the winning combinations for the game.
### Technologies Used
- **React**: A JavaScript library for building user interfaces.
- **JavaScript (ES6+)**: The programming language used for the logic.
- **HTML5**: The standard markup language for creating web pages.
- **CSS3**: Styling the application with custom animations and styles.


This project is a fun and interactive way to play Tic-Tac-Toe and also serves as a good starting point for learning React. Enjoy the game!
