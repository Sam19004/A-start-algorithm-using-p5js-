# A-start-algorithm-using-p5js-
by using this we are implimenting  A* algorithm and visulising path finding algo using p5js
 
The A* (A-star) algorithm is a popular search algorithm used for finding the shortest path between two points on a graph. It combines the strengths of two other popular search algorithms: Dijkstra's algorithm and breadth-first search.

Here is how the A* algorithm works:

Start at the initial state and add it to the open list (a list of nodes to be explored).

Repeat the following steps until the goal state is reached or the open list is empty:
a. Look at the node at the top of the open list (the node with the lowest f score).
b. If it is the goal state, stop the search.
c. Otherwise, remove the node from the open list and add it to the closed list (a list of nodes that have already been explored).
d. Generate the successors (the adjacent nodes) of the current node and add them to the open list. Make sure to only add a successor if it is not already on the open or closed lists.
e. Update the f score of each successor. The f score is a measure of how close the successor is to the goal state, based on the distance from the start and the heuristic (an estimate of the distance from the successor to the goal).

Here is some example code in p5.js that demonstrates how the A* algorithm could be implemented:
