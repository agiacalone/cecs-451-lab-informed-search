
# CECS 451 Lab #1: Informed Search  

## Assignment Description

The goal of this assignment is to practice the methods discussed in lecture about **informed search**, specifically using **hill-climbing** to search for solutions. Use the readings in Chapter 4 of *Artificial Intelligence: A Modern Approach (AIMA3e)* as a reference for this assignment.

You will create a **Sudoku solver** program that uses the **hill-climbing algorithm** to produce solutions for any given 9x9 Sudoku puzzle.

You may use any programming language that you feel comfortable with,
as long as you are able to implement the hill-climbing algorithm completely. Your program should accept a matrix as an input (like the examples that I have included below) and return a formatted output that resembles a Sudoku layout. Text output is fine, or you may output to a file (or both). Your program should also display the intermediate steps to solving the puzzle (the program’s “thinking”, in a manner of speaking) in order to receive full credit.

[Information about Sudoku and how the game is played can be found here](https://en.wikipedia.org/wiki/Sudoku).

We will only be implementing the standard 9x9 Sudoku puzzle, so feel free to ignore any of the variants (meaning, don’t make this problem any harder than it has to be).

Additionally, include a one-page paper discussing how you went about designing the algorithm, any diﬃculties in designing/creating the program, and how eﬃciently or accurately the program runs along with
any additional information that you think I might like to read.

## Requirements

- You may use **any programming language** you are comfortable with, as long as you implement hill-climbing completely.
- Your program should:
  - Accept a **matrix input** (example provided below).
  - Return a **formatted output** that resembles a Sudoku layout.
  - Display **intermediate steps** ("thinking") to receive full credit.
- Output can be to **console** or **a file** (or both).

## Sample Code

Use the following three Sudoku puzzles as testers to evaluate the accuracy of your algorithm. Include, with your code submittal, screenshots of your program execution solving these puzzles.

#### Easy Difficulty:
```
[[8,_,_,9,_,3,_,_,1],
 [_,_,5,_,8,_,9,_,_],
 [_,3,_,_,_,_,_,6,_],
 [4,_,_,1,_,6,_,_,2],
 [_,6,_,_,_,_,_,4,_],
 [1,_,_,7,_,2,_,_,5],
 [_,7,_,_,_,_,_,9,_],
 [_,_,2,_,5,_,8,_,_],
 [9,_,_,4,_,1,_,_,3]]
```

#### Moderate Difficulty:

```
[[3,_,7,_,9,_,_,6,_],
 [9,5,_,_,_,8,_,_,2],
 [6,_,_,7,_,_,_,_,_],
 [_,3,_,_,6,_,_,5,_],
 [_,_,9,_,_,_,6,_,_],
 [_,8,_,_,4,_,_,2,_],
 [_,_,_,_,_,5,_,_,6],
 [4,_,_,9,_,_,_,1,3],
 [_,9,_,_,1,_,2,_,7]]
```
#### Fiendish Difficulty:
```
[[_,6,_,_,5,_,_,2,_],
[_,_,_,3,_,_,_,9,_],
[7,_,_,6,_,_,_,1,_],
[_,_,6,_,3,_,4,_,_],
[_,_,4,_,7,_,1,_,_],
[_,_,5,_,9,_,8,_,_],
[_,4,_,_,_,1,_,_,6],
[_,3,_,_,_,8,_,_,_],
[_,2,_,_,4,_,_,5,_]]
```

## Deliverables

Demonstrate your program for the instructor and submit a copy of your source code file(s), screenshots of a trial run with the sample test puzzles, and your one-page writeup on Beachboard Dropbox. Acceptable file submission formats for your writeup are: `.txt`, `.rtf`, `.doc`, `.docx`, or `.pdf`. Do not compress your files when submitting them. Please be sure to document and comment your assignment appropriately, or **it will not receive a grade**.
