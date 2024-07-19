/*
Spiderverse
The Spiderverse Dimension Graph is a Java program designed to model and process dimensions within the Spiderverse. 
It implements Dijkstra's algorithm to find the shortest paths between dimensions and manages the graph's vertices and edges.

Features

Graph Management:
Add dimensions as vertices to the graph.
Retrieve vertices from the graph.
Represent the graph as a set of dimensions.

Dijkstra's Algorithm:
Calculate the shortest paths between dimensions using Dijkstra's algorithm.
Update distances and paths for each dimension based on their connections.

Key Topics Covered
Graph Theory
Dijkstra's Algorithm
Hash Sets
Hash Maps
Object-Oriented Programming (OOP)

Methods
addVertex(Dimension v): Adds a dimension as a vertex to the graph.
calc_dijkstra(Spiderverse graph, Dimension root): Calculates the shortest paths from the root dimension to all other dimensions using Dijkstra's algorithm.
findVertex(int r_dimension): Finds and returns a dimension vertex by its number.
getVertices(): Returns the set of all dimension vertices in the graph.

*/
