# Gomoku - 4-Piece Chess Version

## Description
This is a two-player strategy game inspired by Gomoku, adapted to a 4-piece win condition. Players take turns placing their pieces on a 10x10 grid, aiming to be the first to align four of their pieces horizontally, vertically, or diagonally.

## How to Play
- The game is played on a 10x10 board.
- Players take turns entering coordinates in the format: `row column` (e.g., `0 1`).
- Player 1 uses piece `1`, Player 2 uses piece `2`.
- The first player to align four pieces wins.
- If the board fills up without a winner, the game ends in a draw.

## Rules
- Input must be within the range `0–9` for both row and column.
- Invalid or occupied positions will prompt a retry.
- The game alternates turns between Player 1 and Player 2.

## Running the Game
- If running online, you may need to rename the main file to `Main`.
- Launch the program and follow the on-screen prompts to play.

## Sample Game Table

0 | 0 1 0 0 0 0 0 0 0 0  
1 | 0 0 0 0 0 0 0 0 0 0  
2 | 0 0 0 0 0 0 0 0 0 0  
3 | 0 0 0 0 0 0 0 0 0 0  
4 | 0 0 0 0 0 0 0 0 0 0  
5 | 0 0 0 0 0 0 0 0 0 0  
6 | 0 0 0 0 0 0 0 0 0 0  
7 | 0 0 0 0 0 0 0 0 0 0  
8 | 0 0 0 0 0 0 0 0 0 0  
9 | 0 0 0 0 0 0 0 0 0 0  
  +-------------------- 
    
  0 1 2 3 4 5 6 7 8 9  
  
## Error Handling
- Input `-1 0` → **Out of range! Input again.**
- Input `0 10` → **Out of range! Input again.**
- Input `0 1` on an occupied cell → **Invalid move. Try again.**

## Win Condition
Player 1 wins with a sequence like:

Player 2's turn. 

Enter row and column (e.g., 0 1): 0 1 

Invalid move. Try again. 

Player 2's turn. 

Users can type the row and column e.g., 0 0 to play this game. 


## Draw Condition
If all cells are filled without a winner, the game ends in a draw. A full list of moves leading to a draw is included in the source code.
0 0
0 1
0 2
0 3
0 4
0 5
0 6
0 7
0 8
0 9
1 0
1 1
1 2
1 3
1 4
1 5
1 6
1 7
1 8
1 9
2 0
2 1
2 2
2 3
2 4
2 5
2 6
2 7
2 8
2 9
3 1
3 0
3 3
3 2
3 5
3 4
3 7
3 6
3 9
3 8
4 0
4 1
4 2
4 3
4 4
4 5
4 6
4 7
4 8
4 9
5 0
5 1
5 2
5 3
5 4
5 5
5 6
5 7
5 8
5 9
6 0
6 1
6 2
6 3
6 4
6 5
6 6
6 7
6 8
6 9
7 1
7 0
7 3
7 2
7 5
7 4
7 7
7 6
7 9
7 8
8 0
8 1
8 2
8 3
8 4
8 5
8 6
8 7
8 8
8 9
9 0
9 1
9 2
9 3
9 4
9 5
9 6
9 7
9 8
9 9

Enjoy this game!
