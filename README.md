# Comparative analysis of Dijkstra using APOC and priority queue

Implementing Dijsktra algorithm to get the shortest path between two nodes.Doing a comparative analysis between Python(using priority queue) and Neo4j's APOC library and monitoring the performance on the basis of timing,resource utilization and scalability.

This study investigates the implementation and comparative performance of Dijkstra's algorithm using Pythonbased methods and Neo4j database integrated with the APOClibrary. The custom priority queue-based Python approach and Python’s NetworkX library exhibit linear runtime dependencies, with NetworkX showcasing superior efficiency. In contrast, Neo4j's APOC library consistently outperforms in computational efficiency, especially in larger graph settings. Despite its robust performance, APOC displays algorithmic runtime variability, potentially linked to caching or other database features. These results emphasize the nuanced decision-making process when choosing between Python-based solutions and database-specific tools for optimal graph processing in diverse applications. The study sheds light on the intricate trade-offs inherent in selecting appropriate tools for effective graph algorithm implementation and optimization.


