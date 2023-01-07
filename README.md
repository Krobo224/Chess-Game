# Chess-Game
Implementation of Chess Game. This is a Multiplayer game can be played with computer or human.

# Game Interface:
<img width="569" alt="image" src="https://user-images.githubusercontent.com/72267398/211152136-4467df98-d6fd-4d5e-a34a-2dcd260467da.png">

# Game Features:
i) Multiplayer Game:
* Can be played as
* Human v/s Human
* Human v/s Computer
* Computer v/s Computer
(Note:- For changing the mode change the code in line no. 52 and 53 of ChessMain.py)

ii) Play features:
* Castling
* Pawn-Promomtion
* Capturing en Passant

# Future Add-ons
* Interface to select the game mode
* Allow dragging peices
* Ordering the moves (ex. looking at checks and/or captures) should make the engine much quicker (because of the alpha-beta pruning).
* Keeping track of all the possible moves in a given position, so that after a move is made the engine doesn't have to recalculate all the moves.
* Evaluating kings placement on the board (separate in middle game and in the late game).
* Book of openings.

# Controls
* Press `z` to undo a move.
* Press `r` to reset the game.
* Run the game by running ChessMain.py
