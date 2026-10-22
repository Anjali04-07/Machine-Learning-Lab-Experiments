# Experiment 09: K-Means Clustering Algorithm

## Aim
To implement the K-Means clustering algorithm to group data into multiple clusters based on the similarity of their features.

## Objectives
- To understand the concept of unsupervised machine learning.
- To implement the K-Means clustering algorithm using Python.
- To group similar data points into different clusters.
- To understand the role of centroids and distance calculations.
- To visualize the clusters using suitable graphs.
- To evaluate the quality of clustering using an appropriate metric.

## Theory

**K-Means clustering** is an unsupervised machine learning algorithm used to divide a dataset into a specified number of clusters based on feature similarity.

Unlike supervised learning, K-Means does not require predefined class labels. Instead, it identifies groups of data points with similar feature values.

Each cluster is represented by a **centroid**, which is the mean position of the data points assigned to that cluster. The algorithm assigns each data point to the nearest centroid and repeatedly updates the centroids until the clusters stabilize or a stopping condition is reached.

### Steps involved in K-Means

1. **Choose K:** Select the number of clusters to create.
2. **Initialize centroids:** Choose initial cluster centers.
3. **Assign data points:** Assign each point to its nearest centroid, usually using Euclidean distance.
4. **Update centroids:** Calculate the mean of the points assigned to each cluster.
5. **Repeat:** Continue assigning points and updating centroids until the assignments stabilize or the maximum number of iterations is reached.

### Objective of K-Means

K-Means aims to minimize the sum of squared distances between each data point and its assigned cluster centroid.

\[
J=\sum_{i=1}^{K}\sum_{x\in C_i}
\|x-\mu_i\|^2
\]

Where:

- \(K\) is the number of clusters.
- \(C_i\) represents the data points in cluster \(i\).
- \(\mu_i\) is the centroid of cluster \(i\).
- \(x\) represents an individual data point.

### Selecting the Number of Clusters

The **Elbow Method** can help select a suitable value of K. It plots the within-cluster sum of squares against different values of K. The point where the reduction in this value begins to slow down is considered a possible choice for the number of clusters.

### Advantages
- Simple and easy to implement.
- Efficient for many numerical datasets.
- Helps discover patterns in unlabeled data.
- Produces understandable cluster assignments.

### Limitations
- The number of clusters must be selected in advance.
- Results can depend on the initial centroids.
- Feature scaling is important when features have different ranges.
- It may perform poorly with irregularly shaped clusters or clusters with very different densities.

### Applications
- Customer segmentation.
- Grouping similar products.
- Document clustering.
- Image segmentation.
- Identifying patterns in business and scientific data.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Load a numerical dataset.
3. Inspect the data and handle missing values, if required.
4. Select the features to be used for clustering.
5. Standardize the features when their scales differ.
6. Select a suitable number of clusters, K.
7. Create a K-Means model using Scikit-learn.
8. Fit the model to the prepared data.
9. Obtain the cluster labels for the data points.
10. Calculate the cluster centroids.
11. Visualize the clusters using a scatter plot when two suitable features or a two-dimensional projection are available.
12. Optionally use the Elbow Method or silhouette score to assess clustering quality.
13. Analyze the resulting clusters and draw a conclusion.

## Results and Observations
- K-Means groups data points into K clusters based on feature similarity.
- Each data point is assigned to the nearest cluster centroid.
- Centroids represent the mean feature values of their assigned data points.
- Feature scaling can affect the resulting cluster assignments.
- The Elbow Method and silhouette score can help assess a suitable clustering configuration.

*Note: Update this section with the actual number of clusters, graph, and evaluation results obtained from your notebook.*

## Conclusion
The K-Means clustering algorithm was implemented to group data points based on feature similarity, and the resulting clusters were analyzed using visualization and suitable evaluation methods.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the cluster assignments, centroids, and visualization.

## Installation
Install the required libraries using the following command:

```bash id="k9z3vd"
pip install numpy pandas matplotlib scikit-learn jupyter
```
