
# **Scrabble Game - Web Development Project**

This project is a web-based implementation of the classic word game Scrabble, built using HTML, CSS, JavaScript, and a Node.js backend.

## Features

*   **Multiplayer:** Play against a friend on the same device.
*   **Dynamic Board:** The game board renders letter tiles and bonus squares visually.
*   **Scoring:** Implements standard Scrabble scoring rules, including letter and word multipliers.
*   **Word Validation:** Checks if played words are valid using a dictionary.
*   **Score Tracking:** Keeps track of individual word scores and total game scores.
*   **Hint System:** Provides hints for possible words using available tiles.
*   **Persistent Storage:** Uses local storage to save player names and game progress.
*   **Top Scores:** Displays top 10 word and game scores, fetched from the server.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ankitgoyal0106/Scrabble-Game.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Scrabble-Multiplayer-Game
    ```
3.  **Install server dependencies:**
    ```bash
    npm install
    ```
4.  **Start the server:**
    ```bash
    npm start 
    ```
5.  **Open the game in your browser:**
    ```bash
    http://localhost:3000
    ```

## How to Play

1.  **Enter Player Names:** Each player enters their name.
2.  **Take Turns:** Players take turns placing words on the board.
3.  **Enter Word and Position:** Type the word, x-coordinate, y-coordinate, and direction (horizontal/vertical).
4.  **Click "Play!":** The word will be played if it's valid and follows Scrabble rules.
5.  **Score:** Scores are calculated automatically.
6.  **End/reset Game:** Click "reset" to finish and start a new game.

## Project Structure

*   `src/client/`: Contains the frontend code (HTML, CSS, JavaScript).
*   `src/server/`: Contains the backend code (Node.js, Express).
*   `readme.md`: This file.

## Key Components
- **`main.js`**: This is the main entry point into the application; loaded by `index.html`.  
- **`game.js`**: Contains code that represents a Scrabble game board.  
- **`rack.js`**: Contains code that represents a rack of tiles used by a player.  
- **`scoring.js`**: Contains code that implements the scoring for the Scrabble game.  
- **`scrabbleUtils.js`**: This file contains the utility functions you wrote in the previous homework. It is not used in this homework. You are welcome to copy your implementation here.  
- **`shuffle.js`**: Used to shuffle the game tiles.  
- **`test.js`**: Contains your tests for `game.js` and `rack.js`.  
- **`dictionary.js`**: This file contains the dictionary of words that will be used in the Scrabble game.  
- **`index.html`**: This file is used to display the Scrabble board and user interface.  
- **`main.css`**: Contains the CSS for this web application.  

## Technologies Used

*   **Frontend:** HTML, CSS, JavaScript (ES6 modules)
*   **Backend:** Node.js, Express.js
*   **Additional Libraries:** chalk-animation (for server console animation), morgan (for logging) 
*   **Testing**: Jest for unit testing and frontend testing (client-side test.js)
