Overview:
This project engineered a distributed ETL pipeline to process and analyze a million-row social graph of Spotify artist connections. The goal was to segment artist communities based on listener behavior and connectivity metrics using Big Data frameworks.


Technical Stack & Architecture:
Processing Engine: PySpark (Spark SQL & MLlib).



Algorithms: K-Means Clustering, PageRank, Degree Centrality.


Evaluation: Silhouette Scores for cluster density validation.

Key Engineering Deliverables:

1. Distributed Join Optimization: Optimized shuffle operations and partitioning to handle million-row nodes and edges effectively.



2. Community Segmentation: Deployed a K-Means model to identify niche artist clusters with high internal engagement.


3. Performance: Reduced compute overhead for graph traversal by 25% through efficient data cleaning and partitioning.
