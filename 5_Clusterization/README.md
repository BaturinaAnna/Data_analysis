# Clusterization

Dataset - "quake.csv": Presented observations of a couple of thousand earthquakes. Each observation has 4 parameters - depth (in kilometers), latitude, longitude (2 coordinates of the earthquake) and strength on the Richter scale 

1. Data clustering. Algorithms: Hierarchical Clustering, K-Means, EM, Density Algorithm (DBSCAN, HDBSCAN or OPTICS). For hierarchical try different distances between objects and inter-cluster distances.
2. For all algorithms select optimal parameters. The most important parameter is the number of clusters. For DBSCAN - radius e and the number of core key points, respectively (for HDBSCAN, only core). To justify your choice, use clustering quality indices, rock scree, personal observation of the dataset, and visualization of the clustering result (by drawing points on a plane and seeing that the resulting clustering works quite well). 
3. Compare algorithms (by speed / quality of the resulting clusters) as well as the clustering themselves (Fowlkes-Mallows index). 
4. Give a description of the performed manipulations and the obtained result:
5. The chosen best clustering / clustering pair (from different algorithms) should be visualized on the Earth map using latitude and longitude as coordinates. 
6. Clustering interpretation - why exactly such clusters turned out, what means division into these groups, what each group of objects means.