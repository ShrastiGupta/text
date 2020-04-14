
Java program that uses Karger's randomized algorithm to compute the minimum cuts of an undirected, connected graph.

Input:
This program takes as input a  containing the adjacency list representation of a simple, undirected, connected graph. 

Output
An integer representing the minimum cut i.e the fewest number of crossing edges.

How it works
The Random Contraction Algorithm,gradually contracts all vertices until there are only 2 nodes left in the graph
first, it picks uniformly at random a remaining edge (u,v)then, it merges the two vertices into a new one, say w
removes all s loops in the graph.

