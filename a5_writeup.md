# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?
I learned how and where recursion can be used past simple functions in the solver functions. This was very interesting and complicated and I had to look up resources such as W3 schools and some ai along with help from friends in order to make sure my syntax and logic was correct.


2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?
I could use similar functions to DFS and BFS to solve other problems with a set number of possibilites. A real world scenario for DFS is something like google maps where a route needs to be found between two points. The satisfaction problems could be used in something that has a lot of variable such as a seating chart.


3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?
Stack is a LIFO data struture, similar to a stack of books. A queue is a FIFO data structure. The difference between BFS and DFS is how they explore each possibility. In DFS you go deep into a path until it doesn't work while in BFS you go level by level. DFS is better for stack because new states are added to one path and BFS is better for queue because it explores the earlier things as it follows FIFO which is how BFS works.