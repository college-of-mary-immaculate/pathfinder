Pathfinder App
Pathfinder is a program that uses Tree and Graph algorithms to take which calculation can search the fastest, less time, less cost taking of a path from point A to B.

FEATURES
- Draggable points A and B.
- Manual Road Block for obstacles.
- Manual Traffic Block for cost checking.
- Slider to incrementing or decrementing speed of the search progress.
- Listbox for choosing type of Tree and Graph Search Algorithms.
  Uninformed
  * Breadth First Search - Explores all nodes level by level horizontally. It uses a FIFO queue and guarantees finding the shortest path on unweighted structures.
  * Depth First Search - Delves as deep as possible along a single branch before backtracking. It uses a LIFO stack or recursion, making it highly memory efficient but prone to infinite loops in cyclical graphs
  Informed
  * Djikstra - a greedy algorithm used to find the shortest path from a starting point (node) to all other points in a weighted graph. It calculates these routes by continuously expanding to the closest unvisited neighbor and updating distances until the shortest path to every node is discovered
  * A* - Evaluates nodes by combining the actual cost from the start node (g(n)) with the estimated cost to the goal (h(n)). It is highly efficient, complete, and mathematically optimal if the heuristic is admissible
  * Greedy Best-First - Selects the next node strictly based on which one appears closest to the goal according to the heuristic (h(n)). It is fast but does not guarantee the shortest path.
- Grid of row cells of 34 and 20 cells of column.
- Button switch to run the program.
- Randomized grid with a separate button.
- Layout Grid Clearing button switch.
- Run switch button for the program's functioning.
- Legend notifications.
