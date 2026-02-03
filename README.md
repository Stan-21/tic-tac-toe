# Design
The design process for this assignment was following the comments in the TicTacToe.cpp file.  I also implemented a simple AI that could be toggled on and off, with the behaviour of the AI placing a piece on the first open square.

# OS Used
Windows

# Modified Files
TicTacToe.cpp
Application.cpp
Game.cpp (For negamax assignment)

# AI Implementation (For negamax assignment)
My updated AI uses the negamax algorithm to play moves for the AI.  It works by looping through every possible move option and recursively finding every possible outcome that could happen to calculate a score.  After looping through every possible move, the AI would play the move that leads to the highest score for the AI.  

Most of the implementation was done by following the code during lecture and then tweaked afterwards to get it fully working (since it didn't fully work in class).

# BUG (For negamax assignment)
Due to how my board is setup, it can take one input into a player and an AI move if the cursor is placed right in between two pieces.  This bug could easily be fixed by spacing out the pieces more, but I decided to leave it as is because I think the board looks better in this shape (and it shouldn't happen often).