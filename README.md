# Tic-Tac-Toe-in-C++
A basic game of Tic Tac Toe in C++ programming language.
The program works as follows:
1. The grid is made using a 2D array. All the nine spaces in the grid are initialized to a big enough negative integer but all the integers should be different for the check function to work.
2. The initialization is achieved by initializing the first space as -100 then running the loop to initialize the grid elements as -99,-98,-97 and so on.
3. Once the board is initialized each player is provided with turns using different functions for different players, different players have different numbers to insert int the 2D array.
4. The turns are counted so that the program can display that its a tie match when the grid is filled.
5. After each, layers turn the function check() checks for the winner by checking for same elements in each row, column and diagonals.
6. If a player has won midway through the game then the check function returns 0 and the loop is exited using the break statement, and the winner is displayed.
