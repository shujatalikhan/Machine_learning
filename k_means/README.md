## K-Means is one of the most popular "clustering" algorithms. K-means stores k centroids that it uses to define clusters. A point is considered to be in a particular cluster if it is closer to that cluster's centroid than any other centroid.

## K-Means finds the best centroids by alternating between (1) assigning data points to clusters based on the current centroids (2) chosing centroids (points which are the center of a cluster) based on the current assignment of data points to clusters.

 ![kmeans](https://user-images.githubusercontent.com/49519213/57816798-f5807f80-777c-11e9-841f-bb67c4659e05.png)
##### Figure 1: K-means algorithm. Training examples are shown as dots, and cluster centroids are shown as crosses. (a) Original dataset. (b) Random initial cluster centroids. (c-f) Illustration of running two iterations of k-means. In each iteration, we assign each training example to the closest cluster centroid (shown by "painting" the training examples the same color as the cluster centroid to which is assigned); then we move each cluster centroid to the mean of the points assigned to it. Images courtesy of Michael Jordan. 
## Elbow technique has been used on this dataset
### The Elbow method is a method of interpretation and validation of consistency within cluster analysis designed to help finding the appropriate number of clusters in a dataset.
![elbow](https://user-images.githubusercontent.com/49519213/57817229-b5ba9780-777e-11e9-85b9-a86f89ace065.png)

Files Included:
* K_means.ipynb
* Iris.csv 
