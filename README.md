# TIC-TAC-TOE-CODSOFT
 Pygame Setup: Initializes Pygame, creates the game window, and sets up the graphical interface.

#Description Of Tic-Tac-Toe
 
Certainly, here's a simplified point-by-point breakdown:

1. Pygame Setup: Initializes Pygame, creates the game window, and sets up the graphical interface.
   
2. Classes: 
   - Board: Represents the game board, tracks occupied squares, empty squares, and game state. Provides methods for marking squares, checking game outcome, and determining board status.
   - AI: Represents the AI opponent, with methods for making moves. Includes a random move strategy (rnd) and the minimax algorithm (minimax) for optimal decision-making.
   
3. Random Move Strategy: 
   - The rnd method selects a random empty square on the board.

4. Minimax Algorithm: 
   - The minimax method implements the minimax algorithm.
   - Recursively evaluates all possible moves, considering maximizing (AI's turn) and minimizing (opponent's turn) scenarios.
   - Utilizes an evaluation function to assign scores to board states, aiding the AI in determining the best move.
   - Positive scores indicate favorable positions for the AI, while negative scores indicate favorable positions for the opponent.
