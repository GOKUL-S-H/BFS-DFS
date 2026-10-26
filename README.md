File System Representation and Search Using BFS and DFS

Project Description

This project implements a file system representation using a graph in the C programming language. Each file or directory is represented as a node, and connections between them are represented as edges using an adjacency matrix.

The project uses Breadth-First Search (BFS) and Depth-First Search (DFS) to search for a specified file from a given starting node.

Objectives

- To represent a file system using a graph.
- To implement an adjacency matrix.
- To perform BFS and DFS traversal.
- To check whether a target file is found.
- To understand graph traversal algorithms.

Technologies Used

- Programming Language: C
- Data Structure: Graph
- Graph Representation: Adjacency Matrix
- Algorithms: BFS and DFS

Features

- Accepts the number of files or directories.
- Accepts connections between nodes.
- Allows the user to select a starting node and target node.
- Displays BFS traversal order.
- Displays DFS traversal order.
- Reports whether the target node is found using both algorithms.

How to Run

1. Download or clone this repository.

2. Save the source code as "main.c".

3. Open a terminal in the project folder.

4. Compile the program:
   
   gcc main.c -o main

5. Run the program:
   
   ./main
   
   On Windows, use:
   
   main.exe

Sample Input

Enter number of files/directories: 5
Enter number of connections: 4
Enter connections (u v):
0 1
0 2
1 3
2 4
Enter starting node: 0
Enter target file node: 4

Sample Output

BFS Traversal: 0 1 2 3 4
File found using BFS.

DFS Traversal: 0 1 3 2 4
File found using DFS.

Conclusion

This project demonstrates how graphs, adjacency matrices, BFS, and DFS can be used to represent and search connected files or directories. It improves understanding of data structures and algorithms through a practical C programming application.

Author

Student Name: Gokul S. H

Department: CSE B

Activity: Challenge 17 – Data Structures and Algorithms
