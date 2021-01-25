# TraceTogether Interview Question 2

You are free to use the language and IDE of your choice. YOu are expected to consider edge cases and come up with test cases on your own

###  Question 2

Given a 2D board containing 'X' and 'O', capture all regions surrounded by 'X'

A region is captured bu flipping all 'O's into 'X's in the surrounded region

#### Example

X X X X

X O O X

X X O X

X O X X

After running your function, the board should be

X X X X

X X X X

X X X X

X 0 X X

Surrounded regions shouldn’t be on the border, which means that any 'O' on the border of the board are not flipped to 'X'. 

Any 'O' that is not on the border and it is not connected to an 'O' on the border will be flipped to 'X'. 

Two cells are connected if they are adjacent cells connected __horizontally or vertically__.
