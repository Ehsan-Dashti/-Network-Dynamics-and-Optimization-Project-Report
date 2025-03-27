# Network-Dynamics-and-Optimization-Project-Report
🔗 Network Dynamics and Optimization – Project Report
This repository presents a comprehensive study of network flow optimization and traffic assignment problems, implemented using Python, NetworkX, and convex optimization tools. The project explores different strategies to improve flow efficiency in directed networks and allocation systems.

📌 Project Highlights
🧭 Flow Network Analysis
Designed a directed graph with specified capacities.

Identified minimum cuts and computed maximum flow between source and destination nodes.

Evaluated the effect of:

Adding extra capacity to existing edges.

Inserting new directed links at strategic points.

Visualized how throughput evolves with increased capacity x.

⚖️ Resource Allocation via Max-Flow
Modeled a bipartite network for assigning resources (e.g., people to preferences).

Solved for:

Optimal one-to-one assignments.

Allocation with multiple resource units and person-specific demand.

Integrated source and sink nodes to formulate the problem as a max-flow network.

🚦 Traffic Flow Optimization
Constructed a directed graph representing a transportation network using incidence matrices and travel time vectors.

Applied:

Dijkstra's algorithm for shortest path computation.

Max-flow algorithms for capacity-based routing.

Formulated and solved convex optimization problems to:

Minimize total system delay.

Compute the Wardrop Equilibrium based on integral cost functions.

🧰 Tools & Libraries
Python 3, NetworkX, Matplotlib

NumPy, CVXPY (for constrained optimization)

📁 Files
main.ipynb: Source code with detailed implementations and plots.

network_HW1_report.pdf: Technical report documenting methodology, results, and visualizations.
