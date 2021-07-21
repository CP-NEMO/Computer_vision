# K-means Clustering

This algorithems objective is to perform clustering, to minimize the sum of the squared distance between all points and the cluster center.

### The main Idea is to:

1. Choose the number of clusters K.
2. Select at random K points, the centroids(not necessarily from your dataset).
3. Assign each data point to the closest centroid → that forms K clusters.
4. Compute and place the new centroid of each cluster.
5. Reassign each data point to the new closest centroid. If any reassignment . took place, go to step 4, otherwise, the model is ready.