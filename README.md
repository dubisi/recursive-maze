# Recursive Backtracking Maze

* GUI based (turtle interface).
* This algorithm creates a new maze from a grid of cells. A random starting cell is chosen, and marked as visited. Then repeat the following steps:
  * If there are unvisited neighbors, choose a random one and remove the wall between them. Mark this new cell as visited.
  * If all neighbors have been visited, back up until finding a cell that has unvisited neighbors.
  
# To run

* `python3 maze.py`
