# Chess Game

This is a simple text-based chess game implemented in Python as my CS50 final project.

#### Video Demo:  https://youtu.be/w3KE9TiaXbk

## Features

* **Two-player gameplay:** Supports two players taking turns.
* **Standard chess rules:** Implements basic movement rules for all chess pieces (Pawn, Rook, Knight, Bishop, Queen, King).
* **Pawn promotion:** Allows pawns to be promoted to other pieces when they reach the opposite end of the board.
* **Color-coded board:** Uses colored text to visually represent the chessboard and pieces.
* **Turn-based display:** Shows the current turn and player.
* **Move validation:** Checks for valid moves and prevents illegal moves.
* **Game termination:** Detects a winner when a King is captured.
* **Turn count:** Displays how many turns the game lasted.

## Prerequisites

* Python 3.x

## How to Run

1.  Save the Python code to a file (e.g., `chess.py`).
2.  Open a terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Run the script using the following command:

    ```bash
    python chess.py
    ```

5.  Follow the on-screen instructions to enter player names and make moves.

## How to Play

1.  **Starting the game:**
    * When you run the script, you will be prompted to enter the names of Player 1 and Player 2.
    * The chessboard will then be displayed, with each square represented by `[ ]` and pieces represented by their acronyms.
    * The color of the piece represent the player. Green for player 1, and Red for player 2.
    * Empty spaces are represented with `.`.

2.  **Making a move:**
    * The current player's turn will be displayed.
    * To make a move, enter the starting and ending squares in the format `A1B2` or `1A2B`. For example, to move a piece from square A1 to square B2, you would enter `A1B2`.
    * The game is not case sensetive.
    * The program will validate the move and display an error message if the move is invalid.
    * If a pawn reaches the opposite end of the board, you will be prompted to choose a new piece for the pawn.

3.  **Understanding the board:**
    * The chessboard is represented by an 8x8 grid.
    * The columns are labeled A through H, and the rows are labeled 1 through 8.
    * Pieces are represented by their acronyms:
        * `P` - Pawn
        * `R` - Rook
        * `H` - Horse(Knight)
        * `B` - Bishop
        * `Q` - Queen
        * `K` - King

4.  **Game rules:**
    * The game follows standard chess rules.
    * Each piece has its own unique movement rules.
    * The goal of the game is to capture the opponent's King.
    * When a king is captured the game ends.

5.  **Ending the game:**
    * The game ends when one player captures the other player's King.
    * The winner will be announced, along with the total number of turns played.

## Notes

* This is a basic implementation and does not include advanced features like castling, en passant, or checkmate detection.
* The horse is represented by the letter H, instead of N, to avoid confusion.
* The code uses colored text for visual representation, which may not display correctly in all terminals.
* This code was made for a CS50 final project, and is not designed for advanced play.
