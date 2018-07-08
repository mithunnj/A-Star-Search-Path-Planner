# A-Star-Search-Path-Planner

A-Star search provides an efficient method of travelling from a starting position, and finishing at a specific goal. This algorithm provides us with a path that minimizes the cost of travelling along the chosen path, which can include minimizing distance, time or other factors like fuel cost.

Compared to A-Star and Best First search, Uniform cost search is considered to be an "uninformed" search technique due to the fact that it does not use a heuristic function. While the Uniform cost search searches every possible path from each node, it doesn't take into account a weighted factor representing how close we are getting to the goal. Using the heuristic function enables us to explore a fewer number of nodes because the algorithm pursues paths that get us closer to our goal. While A* and Best First Search share the similarities of using heuristics to optimize the path planning process, Best First Search doesn't take into account the cost of travelling to a specific node. Instead it priotizes it's decisions based on the move that has the lowest heuristics. However, A* not only chooses a path with the lowest heuristics but also the path that costs the least to arrive to a specific node. 

By leveraging my understanding of the algorithms above, I was able to program an efficient path planner in Python. 
