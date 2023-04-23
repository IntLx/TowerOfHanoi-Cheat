# TowerOfHanoi-Cheat
This is a Python program that solves the Tower of Hanoi puzzle. The Tower of Hanoi is a classic problem in computer science and mathematics, where the objective is to move a stack of disks from the leftmost peg to the rightmost peg, using only three pegs and obeying the following rules:

Only one disk can be moved at a time.
Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty peg.
No disk may be placed on top of a smaller disk.
The program uses recursion to solve the puzzle, following the algorithm:

Move n-1 disks from the source peg to the auxiliary peg.
Move the nth disk from the source peg to the destination peg.
Move the n-1 disks from the auxiliary peg to the destination peg.
The program takes user input for the number of disks and displays the steps to solve the puzzle.

How it works:

The program starts by taking user input for the number of disks. It then initializes the three pegs as lists and populates the first peg with the given number of disks, in decreasing size order. The program then calls the solve_tower_of_hanoi function, passing the number of disks, the source peg, the auxiliary peg, and the destination peg as arguments.

The solve_tower_of_hanoi function is a recursive function that follows the algorithm described above. The base case is when there is only one disk, which is simply moved from the source peg to the destination peg. For n disks, the function first recursively moves n-1 disks from the source peg to the auxiliary peg, then moves the nth disk from the source peg to the destination peg, and finally recursively moves the n-1 disks from the auxiliary peg to the destination peg.

At each step, the program displays the current state of the three pegs and the disk that is being moved. Once the puzzle is solved, the program displays the total number of moves that were made.

The Tower of Hanoi puzzle is a classic example of recursion and is often used to illustrate the power and elegance of recursive algorithms. This Python program provides a simple and clear implementation of the solution to this problem.


made ai write this lengty thing
