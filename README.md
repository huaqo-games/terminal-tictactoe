# terminal-tictactoe

## Overview
This Tic Tac Toe game is implemented in C++ and allows two players to take turns marking spaces on a 3x3 grid. The game determines a winner if a player successfully aligns three of their symbols horizontally, vertically, or diagonally.

## Prerequisites
To compile and run the game, ensure you have the following installed on your system:

- **g++ (GNU Compiler Collection)**: A C++ compiler to build the project.

## Compilation and Execution
Follow these steps to compile and run the program:

1. Open a terminal and navigate to the directory containing `tictactoe.cpp`.
2. Compile the code with the following command:
   ```bash
   g++ -std=c++11 tictactoe.cpp -o tictactoe
   ```
   This will create an executable file named `tictactoe`.

3. Run the program using:
   ```bash
   ./tictactoe
   ```

## Gameplay Instructions
1. At the start, the game displays an empty 3x3 board and a guide for the input keys.
2. Players take turns entering their moves. Input keys correspond to the grid positions:
   - `L1`, `M1`, `R1` for the top row.
   - `L2`, `M2`, `R2` for the middle row.
   - `L3`, `M3`, `R3` for the bottom row.

3. Example of valid input:
   - `M2` will place the current player's marker in the middle cell of the board.

4. The game checks for a win or draw after each move. If a player wins, the game announces the winner and exits.

5. If a player attempts to mark an already occupied cell, they will be prompted to choose another position.

6. Invalid input (e.g., `X1`, `middle`) will prompt the player to enter a valid move.

## Troubleshooting
- If you encounter issues running the game, ensure `g++` is installed and the file paths are correct.
- If the program fails to compile, ensure you are using at least C++11 by specifying `-std=c++11` during compilation.

## License
This project is distributed under the MIT License.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Credits
- **Developer:** Joaquin Gottlebe
- **Built With:** C++
