 Graph Representation using Adjacency List in C

This project implements **Graph Representation using an Adjacency List** in the C programming language.

The program creates an undirected graph and displays its adjacency list representation.

--- Concept Overview

 Graph (Data Structure)

A Graph is a non-linear data structure consisting of:

- **Vertices (Nodes)**
- **Edges (Connections between vertices)**

Graphs are widely used in:
- Networking
- Social media connections
- Routing algorithms
- Pathfinding problems

---

 Representation Used

 Adjacency List Representation

In this method:

- Each vertex maintains a linked list.
- The linked list stores all adjacent vertices.
- Memory efficient compared to adjacency matrix (especially for sparse graphs).

---

 Program Features

- Uses `struct` to define graph nodes
- Dynamic memory allocation using `malloc()`
- Supports undirected graph
- Displays adjacency list clearly
- No user input required (edges added manually)

---

 Graph Used in Program

Vertices: 0, 1, 2, 3  
Edges:
- 0 — 1
- 0 — 2
- 1 — 2
- 2 — 3
