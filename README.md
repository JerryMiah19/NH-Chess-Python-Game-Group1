TITLE: BELLS UNIVERSITY TWO PLAYER CHESS PYGAME

DESCRIPTION

This project is a two-player chess game built using Python and the Pygame library by we the Group 1 membersof the game development section of the New Horizons project.
It was created to replicate a traditional chess experience with visual representations of the chessboard and pieces, turn-based gameplay, and rules adherence.
The only twist is that it is modelled after the Prestiguous Bells University of Technology in terms of its vibrant colours; Cream and Brick Brown(Peru).
The game is designed to provide a user-friendly interface for local multiplayer gameplay.

FEATURES
1. INTERACTIVE GAMEPLAY: Two players take turns moving pieces on an 8x8 chessboard.
2. VALID MOVE HIGHLIGHTING: Highlights valid moves for selected pieces, In this case, WHITE(blue move path) and PERU(red move path)
3. CHECK DETECTION: Alerts players when their king is under attack.
4. GAME OVER CONDITION: Ends the game once of the kings of either players is captured.
5. CAPTURED PIECES DISPLAY: Displays captured pieces for each player on the side of the board.
6. RESTART OPTION: Players can restart the game by pressing Enter after the game ends.

REQUIREMENTS
1. Python 3.12
2. Visual Studio Code
3. Pygame library (Install via pip install pygame)

SETUP AND INSTALLATION
1. Clone or download this repository.
2. Ensure Python and Pygame are installed on your system.
3. Place the chess piece images in the assests/images directory as follows:
   
    i. peru queen.png
    ii. peru king.png
    iii. peru rook.png
    iv. peru bishop.png
    v. peru knight.png
    vi. peru pawn.png
    vii. white queen.png
    viii. white king.png
    ix. white rook.png
    x. white bishop.png
    xi. white knight.png
    xii. white pawn.png
4. Run the game using the following command:
  bash
  python main.py

HOW TO PLAY
1. START THE GAME: The game begins with White’s turn as that is the rule for every traditional chess game.
2. SELECT A PIECE: Click on a piece of your choice to view its valid moves.
3. MAKE A MOVE: Click on a highlighted square to move the selected piece you chose.
4. WINNING CONDITIONS: winning can be done in two ways for chess, they are:
i. Capturing the opponent’s king to win the game.
ii. Players can also forfeit their turn by selecting the “FORFEIT” option.
5. RESTART THE GAME: Press Enter after the game ends to restart.

GAME CONTROLS

It is not a new concept that Python Language is an Object Oriented Programming(OOP) Language, Hence, It supports the feature or concept that is known as “Event Handling”.
The Event Handling concepts employed in our codes were;
1. MOUSE CLICKING:
Left-click to select and move pieces.
2. KEYBOARD ACTION:
Press Enter to restart after the game ends.
Close the game window to exit.

CONTRIBUTION

Feel free to fork this repository and contribute by submitting pull requests, also feel free to even critique the work as we are just learners hoping to improve our coding and game development skills. Suggestions and improvements are always welcome!

LICENSE

This project is licensed under the New Horizons license.
