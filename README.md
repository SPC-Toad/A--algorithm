# A* Pathfinding Algorithm in Java

This project implements the A* (A-star) pathfinding algorithm in Java. The A* algorithm is widely used for graph traversal and pathfinding problems, finding the shortest path between nodes in a weighted graph.

## Features

- Efficient pathfinding using the A* algorithm.
- Supports custom grid sizes and obstacles.
- Easy to integrate into other Java projects.

## Prerequisites

- Java Development Kit (JDK) 8 or higher

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/AStarJava.git
   cd AStarJava
   ```

2. **Compile the Java file:**

   ```sh
   javac AStar.java
   ```

3. **Run the application:**

   ```sh
   java AStar
   ```

## Usage

1. **Grid Configuration:**
   - You can configure the grid, start, and goal positions, as well as obstacles in the `AStar.java` file.

2. **Example:**

   ```java
   int[][] grid = {
       {0, 0, 0, 0},
       {1, 1, 0, 1},
       {0, 0, 0, 0},
       {0, 1, 1, 0},
       {0, 0, 0, 0}
   };

   AStar aStar = new AStar(grid, new Node(0, 0), new Node(4, 3));
   List<Node> path = aStar.findPath();
   ```

3. **Output:**
   - The path will be printed to the console, showing the coordinates of each step from the start to the goal.

## Learning Resource

For a detailed explanation of the A* algorithm and its implementation, refer to this helpful video tutorial:

[Introduction to A* Pathfinding Algorithm](https://www.youtube.com/watch?v=ySN5Wnu88nE)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

