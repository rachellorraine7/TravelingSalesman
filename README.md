# TravelingSalesman
Heuristic for the Traveling Salesman Problem
</h2>
This problem aims to find the most efficient route to visit every vertex in a graph. The input for this problem consists of N+1 lines. The first line has one number, N, which is the number of vertices. Then there are N lines following that, which each have two numbers representing a point (x,y) where there is a vertex located. The output has the length of the tour as well as the tour itself (which vetices visited in which order). I used a minimum spanning tree to make an initial greedy answer then ran simulated annealing. For each run’s change of the graph, I used a modified form of k-opt. Instead of going until fail, I used a for loop to run a number of times proportional to the number of vertices. 
