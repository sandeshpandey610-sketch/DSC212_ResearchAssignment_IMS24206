# DSC212_ResearchAssignment_IMS24206
This project is an analysis of the spectral modularity algorithm implemented in Zachary's Karate Club network to predict communities after the split.
I did this project in my 3rd semester as a course work of DSC212 – MATHEMATICAL FOUNDATIONS TO DATA SCIENCE, Varsha 2025 of my BSMS program under the
course instructor **Saptrishi Bej**.
## **Description**
The code implements the following pipeline:

1 Graph Loading:

-Loads the classic Karate Club social network graph using NetworkX.

2Recursive Spectral Community Detection:

-Uses spectral modularity bisection (Newman's method) to recursively split the graph.
-Communities are divided based on the leading eigenvector of the modularity matrix.
-Splitting continues until no further modularity gain is possible.

3.Centrality Metric Computation (at each iteration):

-Degree Centrality
-Betweenness Centrality
-Closeness Centrality
-Clustering Coefficient

4.Visualization:

Graph layout is fixed across all iterations for consistent visual comparison.
Communities are colored after every split.
Metric evolution is visualized per node using heatmaps.

## **Background**
This project is based on:

M.E.J. Newman’s spectral methods for community detection
Zachary’s Karate Club dataset (a benchmark for social network analysis)

I have used some AI tools for help in coding (to know more about functions which are available in NetworkX)

## **Citation**
Newman (2006), “Modularity and community structure in networks,” PNAS 103(23):8577–8582.

##Author
Sandesh Pandey-IMS24206

**THANK YOU**

