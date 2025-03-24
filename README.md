
# CECS 451 – Lab #1: Informed Search  

## Assignment Description

The goal of this assignment is to practice the methods discussed in lecture about **informed search**, specifically using **hill-climbing** to search for solutions. Use the readings in Chapter 4 of *Artificial Intelligence: A Modern Approach (AIMA3e)* as a reference for this assignment.

You will create a **Sudoku solver** program that uses the **hill-climbing algorithm** to produce solutions for any given 9x9 Sudoku puzzle.

## Requirements

- You may use **any programming language** you are comfortable with, as long as you implement hill-climbing completely.
- Your program should:
  - Accept a **matrix input** (example provided below).
  - Return a **formatted output** that resembles a Sudoku layout.
  - Display **intermediate steps** ("thinking") to receive full credit.
- Output can be to **console** or **a file** (or both).

## Sample Input Format

```plaintext
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

- `0` indicates an empty cell.

## What to Submit

1. **Your source code** for the hill-climbing Sudoku solver.
2. A **brief write-up** (1–2 pages) explaining your design and approach.
3. Include:
   - Any known limitations.
   - How you handled plateaus or local maxima.
   - Output from sample runs.

## Hints

- Try experimenting with different **heuristics** (e.g., number of conflicts).
- Hill-climbing may get stuck! Consider how to **escape local optima**.
- Visualize your program’s decision-making—make it easy to debug and grade.

---

**Instructor Note:**  
This lab focuses on both algorithm implementation and *strategic reasoning*. You are expected to *analyze the process*, not just return a solved puzzle.

