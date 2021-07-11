# Lab:11 - Numpy

## Challenge description

Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)

    should have add_red method that accepts a row and column as input which colors corresponding cell.

    should have add_blue method that accepts a row and column as input which colors corresponding cell.

    should have render method that displays the chess board on screen with red and blue shown in correct locations

    should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## Link to code

[Chess Board](/home/wonde/codefellows/code-401/chess-board/chess_board.ipynb)

## Unit Tests Required

queens on same row should be “under attack”

queens on same column should be “under attack”

queens on same diagonal should be “under attack”

queens with any other coordinates should NOT be “under attack”

## Pull request


## Resources and Collaboration

This is done in collaboration with my class mates Daniel Dills, Davve Sok, and Micheal Ryan

We use codes from of the following web links to solve some logical problems

[GeeksforGeeks](https://www.geeksforgeeks.org/python-program-print-checkerboard-pattern-nxn-using-numpy/)
[GeeksforGeeks](https://www.geeksforgeeks.org/check-if-a-queen-can-attack-a-given-cell-on-chessboard/)