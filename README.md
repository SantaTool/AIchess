# chessAI : Chess Game with AI opponent  
This is a web-based chess game that allows you to play against an AI opponent that uses a minimax algorithm with alpha-beta pruning to make its moves. The game is implemented using the following technologies:  
- JavaScript
- jQuery
- Chess.js library for chess logic
- Chessboard.js library for rendering the chessboard  

## demo
[https://alaesahbou.github.io/chessAI](https://alaesahbou.github.io/chessAI)

## How to play
To play the game, simply open the index.html file in a web browser. The chessboard will be displayed, and you can make moves by clicking on a piece and then clicking on the square where you want to move it. The AI opponent will then make its move, and the game will continue until checkmate, stalemate, or a draw occurs.

You can adjust the search depth of the AI opponent by selecting a different value in the "Search depth" dropdown menu. A higher search depth will result in a stronger opponent, but it will also take longer to make each move.

Project structure
The project consists of the following files:

- index.html: The main HTML file that contains the chessboard and game information.
- style.css: The CSS file that styles the chessboard and game information.
- script.js: The JavaScript file that implements the game logic, including the minimax algorithm with alpha-beta pruning.
- lib/: A directory that contains the Chess.js and Chessboard.js libraries, as well as the jQuery library.  

## Credits
The chess game is based on the Chess.js and Chessboard.js libraries, which were created by Chris Oakman. The minimax algorithm with alpha-beta pruning was implemented based on the pseudocode provided on the Wikipedia page for the minimax algorithm.

## License
This project is licensed under the MIT License.
