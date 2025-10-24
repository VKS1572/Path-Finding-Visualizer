#Pathfinding Visualizer

Welcome to Pathfinding Visualizer! I created this tool out of fascination with pathfinding algorithms and a desire to see them in action. Enjoy exploring how these algorithms find paths in real time!
👉 Try it here (use Google Chrome): https://clementmihailescu.github.io/Pathfinding-Visualizer/

Supported Algorithms

Dijkstra’s Algorithm (weighted): Guarantees the shortest path.

A* Search (weighted): Fast and optimal; uses heuristics.

Greedy Best-First Search (weighted): Heuristic-heavy; not guaranteed shortest path.

Swarm Algorithm (weighted): Mix of Dijkstra’s and A*; not guaranteed shortest path.

Convergent Swarm (weighted): Faster, more heuristic version of Swarm.

Bidirectional Swarm (weighted): Swarm from both ends; not guaranteed shortest path.

Breadth-First Search (unweighted): Guarantees shortest path.

Depth-First Search (unweighted): Inefficient for pathfinding.

Includes Recursive Division Maze Generation for dynamic obstacle creation.

About the Swarm Algorithm

The Swarm Algorithm blends Dijkstra’s and A*, balancing exploration near the start and convergence toward the target. It uses adaptive heuristics to form a distinct triangle-like search pattern—hence the name “Swarm.”
