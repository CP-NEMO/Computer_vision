# K-means Clustering

This algorithems objective is to perform clustering, to minimize the sum of the squared distance between all points and the cluster center.

### The main Idea is to:

1. Choose the number of clusters K.
2. Select at random K points, the centroids(not necessarily from your dataset).
3. Assign each data point to the closest centroid → that forms K clusters.
4. Compute and place the new centroid of each cluster.
5. Reassign each data point to the new closest centroid. If any reassignment . took place, go to step 4, otherwise, the model is ready.


#### Input Image:
![image](https://user-images.githubusercontent.com/30102047/126491396-7c807a34-13c0-40f9-91cc-94d8a91bcd6a.jpg)


#### Clustered Image:
![Figure_1](https://user-images.githubusercontent.com/30102047/126491458-64f66e9e-06d9-45c9-8676-bb20de4b5958.png)


#### Disable only the cluster number 2 (turn the pixel into black):
![Figure_2](https://user-images.githubusercontent.com/30102047/126491539-dbd6cccd-ddca-48ae-bbe2-8f2fadfdb1e5.png)





# Refrence Read:
* https://www.google.com/urlsa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiUp4HKofTxAhU7_3MBHVDADkQQFjACegQIBxAD&url=https%3A%2F%2Fcyberleninka.org%2Farticle%2Fn%2F501681.pdf&usg=AOvVaw2tF_tcQiDXKoxa5JtesY1T
* https://www.sciencedirect.com/science/article/pii/S089571771200369X
