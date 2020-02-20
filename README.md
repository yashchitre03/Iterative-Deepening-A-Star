# Iterative Deepening A*

​	The python program implements the iterative deepening A* algorithm for the 15 puzzle problem. It is a search algorithm known for its completeness, optimality, and efficiency. Here we try to implement the same using two different heuristics:

1. Hamming Distance, and

2. Manhattan Distance.

   Here, we see that the Manhattan distance provides a solution by expanding less nodes than the other, to reach the goal state. The goal state of the puzzle (which the algorithm has to find) is:

|   1    |   2    |   3    |    4    |
| :----: | :----: | :----: | :-----: |
| **5**  | **6**  | **7**  |  **8**  |
| **9**  | **10** | **11** | **12**  |
| **13** | **14** | **15** | **_0_** |



## Requirement

* Python 3



## Prerequisites

* [15 Puzzle Problem](https://en.wikipedia.org/wiki/15_puzzle)

* [Iterative Deepening A-star Algorithm](https://en.wikipedia.org/wiki/Iterative_deepening_A*)

* [Admissible Heuristics](https://en.wikipedia.org/wiki/Admissible_heuristic)

  * **Hamming Distance**
  * **Manhattan Distance**

  

## Running the tests

​	It contains two different programs for different heuristic. Input should be given as a string of sequence of numbers denoting the number on the tile and the sequence of the numbers will represent the position of that tile in the puzzle. Hence, they will be placed from the top to bottom, and from left to right in the puzzle.

​	Also, the number '0' represents the empty tile in the puzzle.

For example,

**The Input**

> 1 2 3 4 5 6 0 8 9 10 7 11 13 14 15 12

**Represents**

|   1    |   2    |    3    |   4    |
| :----: | :----: | :-----: | :----: |
| **5**  | **6**  | **_0_** | **8**  |
| **9**  | **10** |  **7**  | **11** |
| **13** | **14** | **15**  | **12** |



The program will output the following :

* If goal state has been found.
* The heuristic used to find the goal state.
* Moves to reach the goal state.
* Number of nodes expanded in the tree by searching for various states using A-star.
* Time taken (in seconds).
* Memory used while running the process.







