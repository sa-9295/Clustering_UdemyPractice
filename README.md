# Clustering

Clustering is a Machine Learning technique that involves the grouping of data points. Given a set of data points, we can use a clustering algorithm to classify each data point into a specific group. It is an unsupervised learning approach.
Two most popular clustering algorithms are as below:

1. KMeans Clustering: K means is an iterative clustering algorithm that aims to find local maxima in each iteration. This algorithm works in these 5 steps :
  a. Randomly specify the number of clusters k.
  b. Each data point is classified by computing the distance between that point and the cluster center. Classify the point to be in the       group whose center is closest to it.
  c. Compute the clusters centroid.
  d. Re-assign group points to the closest cluster with newly calculated centroids.
  e. Repeat these sets of iterations until no improvements are possible.
  
  2. Hierarchial Clustering: It builds a hierarchy of clusters. This hierarchy of clusters is represented as a tree (or dendrogram). This algorithm works in these steps:
    a. Begin by treating each sample data point.
    b. Calculate the distance between the clusters and two closets clusters are then merged till we have a single cluster at the top.

The decision of the no. of clusters that can best depict different groups can be chosen by observing the dendrogram. The best choice of the no. of clusters is the no. of vertical lines in the dendrogram cut by a horizontal line that can transverse the maximum distance vertically without intersecting a cluster.
  
Hierarchical clustering can’t handle big data well but K Means clustering can. This is because the time complexity of K Means is linear i.e. O(n) while that of hierarchical clustering is quadratic i.e. O(n2).

As a part of the course of Machine Learning from Udemy, this section contains implemetation of both algorithms using Python and R. The data is for different customers and based on different paramters(for e.g., Spending Score) we specify the group to which the customers belong.
