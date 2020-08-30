# chess-board

**Feature Tasks and Requirements**

Render out chess boards with red and blue queens on them.

We’re keeping it really basic here so the only pieces are queens and each queen is represented by a blue or red square.

Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

**Implementation Notes**

Define a ChessBoard class
should have ```add_red``` method that accepts a row and column as input
should have ```add_blue``` method that accepts a row and column as input
should have render method that displays the chess board on screen with red and blue shown in correct locations
should have ```is_under_attack``` method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally