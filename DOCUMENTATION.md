### **Features:**
 Two-player gameplay.
 Simple text-based interface.
 Detects when a player wins or if there's a draw.
 

### **Explanation:**
1. **Board Representation**: A 3x3 `char` array stores the Tic Tac Toe board. Initially, it contains numbers (1-9), representing positions players can choose.
2. **Game Flow**:
   - **displayBoard()**: Displays the current state of the board.
   - **isWinner()**: Checks if the current player has won by examining rows, columns, and diagonals.
   - **isDraw()**: Checks if all positions are filled and no winner exists, meaning the game is a draw.
   - **switchPlayer()**: Switches the current player from 'X' to 'O' and vice versa.
   - **makeMove()**: Prompts the player to choose a move and updates the board accordingly. It also checks for invalid moves.
3. **Main Loop**: Continues until there is a winner or a draw. After each move, it checks for victory or a draw.

This code provides a basic text-based Tic Tac Toe game you can play in the console!
