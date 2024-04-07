# Assignment No. 4 Readme

## Overview
This repository contains the code and documentation for Assignment No. 4, focusing on implementing K-means clustering algorithm for a given collection of points. The program answers specific questions related to clustering, such as assigning points to clusters, determining cluster population, and updating centroid values.

## Contents
- `k_means_clustering.py`: Python script containing the implementation of K-means clustering algorithm and code to answer the given questions.
- `README.md`: This file providing an overview of the assignment, methodology, and instructions for running the code.

## Methodology
1. **Initialization**: Define initial centroids, m1=P1 and m2=P8.
2. **Assign Points to Clusters**: Calculate Euclidean distance between each point and centroids. Assign each point to the cluster corresponding to the nearest centroid.
3. **Update Centroids**: Calculate mean of points in each cluster. Update centroids to new mean values.
4. **Answering Questions**:
   - Determine cluster of P6 by calculating its distance from centroids.
   - Find population of cluster around m2 by counting points in C2.
   - Update values of m1 and m2 by calculating mean of points in each cluster.

## Advantages and Disadvantages
- **Advantages**:
  - Simple and Intuitive: K-means clustering is easy to understand and implement.
  - Efficient: Works well for large datasets and high-dimensional data.
  - Scalability: Scales well with increasing dataset sizes.
  - Interpretability: Results are straightforward and easy to interpret.
- **Disadvantages & Limitations**:
  - Sensitivity to Initial Centroids: Results can vary based on initial centroid selection.
  - Assumption of Spherical Clusters: Assumes clusters are spherical, which may not always be the case.
  - Impact of Outliers: Outliers can significantly affect cluster centroids.
  - Determining Number of Clusters: Number of clusters needs to be specified beforehand.

## Conclusion
In conclusion, K-means clustering is a simple yet effective method for grouping data points into clusters. While it's straightforward to implement and scales well with large datasets, it requires careful consideration of initial centroids and assumes spherical clusters. Despite its limitations, K-means remains a popular choice for clustering tasks due to its efficiency and interpretability. The provided Python script demonstrates the implementation of K-means and answers specific questions related to clustering.