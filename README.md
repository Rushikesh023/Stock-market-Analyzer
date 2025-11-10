------------------------------------------------------------

📘 Overview
The Disaster Response Routing System is a C-based project that applies
graph traversal algorithms (BFS and DFS) to identify safe and efficient
evacuation routes during natural disasters such as floods, earthquakes,
and landslides. The system models locations as graph nodes and routes
as edges, enabling quick path discovery and reachability analysis.

------------------------------------------------------------

🎯 Objectives
- Represent disaster-prone areas as graph nodes and roads as edges.
- Implement BFS and DFS algorithms to find safe routes.
- Compare traversal methods for speed and safety.
- Demonstrate real-world use of graph algorithms in disaster management.

------------------------------------------------------------

⚙️ System Requirements
Hardware:
- Processor: Intel i3 or higher
- RAM: 2 GB minimum
- Storage: 100 MB free

Software:
- OS: Windows
- Compiler: GCC / VS Code

------------------------------------------------------------

🧩 How It Works
1. Input number of locations and routes.
2. Build the adjacency matrix for the graph.
3. Enter the starting location.
4. Use BFS for shortest route discovery.
5. Use DFS to explore all reachable paths.
6. View safe routes and traversal order.

------------------------------------------------------------

💻 Sample Input / Output

Input:
Enter number of locations: 4
Enter adjacency matrix:
0 1 1 0
1 0 0 1
1 0 0 1
0 1 1 0
Enter starting location: 0

Output:
Using BFS: 0 1 2 3
Using DFS: 0 1 3 2

------------------------------------------------------------

✅ Testing and Results
Test Case 1: 4 nodes, connected → BFS: 0 1 2 3 → Pass
Test Case 2: Sparse connectivity → Correct reachability → Pass
Test Case 3: Isolated node → Shown as unreachable → Pass

------------------------------------------------------------

📈 Conclusion
The system successfully applies BFS and DFS to real-world disaster
management, offering a practical example of data structure applications.

Future Enhancements:
- Implement Dijkstra’s or A* algorithms for weighted graphs.
- Integrate with GPS and real-time disaster data for smart city use.

------------------------------------------------------------

📚 References
1. Tanaka, H. et al. “Graph-Based Route Optimization for Disaster
   Evacuation Systems.” IEEE Transactions, 2024.
2. Fei, J. & Li, M. “Efficient Pathfinding in Emergency Scenarios
   using BFS/DFS.” arXiv, 2025.
3. National Institute of Disaster Management, India.
   “Computational Tools for Evacuation Planning,” 2023.






