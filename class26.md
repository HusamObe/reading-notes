# Graphs: An Overview

## Table of Contents
- [Introduction](#introduction)
- [Types of Graphs](#types-of-graphs)
- [Graph Components](#graph-components)
- [Graph Terminology](#graph-terminology)
- [Graph Representation](#graph-representation)
- [Common Graph Algorithms](#common-graph-algorithms)
- [Applications of Graphs](#applications-of-graphs)

## Introduction
A **graph** is a mathematical and data structure concept used to represent a set of objects (vertices or nodes) and the connections between them (edges). Graphs are versatile and can model various real-world relationships, making them a fundamental tool in computer science and beyond.

## Types of Graphs
There are several types of graphs, including:
- **Directed Graph (Digraph):** Graph with directed edges, indicating a one-way relationship between vertices.
- **Undirected Graph:** Graph with undirected edges, representing a symmetric relationship.
- **Weighted Graph:** Graph with numerical values assigned to edges, often representing distances, costs, etc.
- **Unweighted Graph:** Graph with no values associated with edges.
- **Cyclic Graph:** Graph containing cycles (loops) of vertices.
- **Acyclic Graph:** Graph without any cycles.

## Graph Components
A graph consists of two main components:
1. **Vertices (Nodes):** Represent entities in the graph.
2. **Edges:** Connect vertices and represent relationships between them.

## Graph Terminology
- **Degree of a Vertex:** The number of edges incident to a vertex.
- **Path:** A sequence of vertices where each adjacent pair is connected by an edge.
- **Cycle:** A path that starts and ends at the same vertex.
- **Connected Graph:** A graph where there is a path between any two vertices.
- **Disconnected Graph:** A graph composed of multiple disconnected components.
- **Subgraph:** A graph formed from a subset of the vertices and edges of a larger graph.

## Graph Representation
Graphs can be represented using various data structures:
- **Adjacency Matrix:** A 2D matrix representing connections between vertices.
- **Adjacency List:** A list where each vertex has a list of its adjacent vertices.
- **Edge List:** A list of edges, each containing the pair of connected vertices.

## Common Graph Algorithms
- **Depth-First Search (DFS):** Traverses as far as possible along each branch before backtracking.
- **Breadth-First Search (BFS):** Explores all vertices at the same level before moving to the next level.
- **Dijkstra's Algorithm:** Finds the shortest path between two vertices in a weighted graph.
- **Topological Sorting:** Orders vertices in a directed acyclic graph (DAG) based on dependencies.

## Applications of Graphs
Graphs have wide-ranging applications:
- **Social Networks:** Representing connections between users.
- **Routing and Navigation:** Finding optimal paths in maps.
- **Recommendation Systems:** Suggesting items based on user interactions.
- **Circuit Design:** Modeling electrical circuits.
- **Web Page Ranking:** Ranking websites using link analysis algorithms.
