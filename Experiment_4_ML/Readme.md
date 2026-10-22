# Experiment 04: Principal Component Analysis (PCA)

## Aim
To apply Principal Component Analysis (PCA) on a multivariate dataset to reduce its dimensionality, visualize the data in lower dimensions, and evaluate the amount of variance retained after transformation.

## Objectives
- To understand the concept of Principal Component Analysis.
- To reduce the number of features in a multivariate dataset.
- To transform high-dimensional data into two or three dimensions.
- To visualize the transformed data using graphs.
- To calculate explained variance and determine the information retained after dimensionality reduction.

## Theory

**Principal Component Analysis (PCA)** is an unsupervised dimensionality reduction technique used to reduce the number of features in a dataset while preserving as much information as possible.

A multivariate dataset may contain many features, some of which provide overlapping or correlated information. PCA transforms the original features into a new set of variables called **principal components**.

The first principal component captures the maximum possible variance in the data. The second principal component captures the maximum remaining variance and is perpendicular to the first component. The following components capture progressively smaller amounts of variance.

### Steps involved in PCA

1. **Standardization:** Scale numerical features so that they have a comparable scale.
2. **Covariance analysis:** Identify relationships between features.
3. **Principal component calculation:** Determine the directions that capture the greatest variance.
4. **Dimensionality reduction:** Select the required number of principal components.
5. **Visualization:** Plot the transformed data using two or three principal components.
6. **Variance evaluation:** Calculate the explained variance ratio to measure how much information is retained.

### Explained Variance

The explained variance ratio indicates the proportion of the total variance captured by each principal component.

The cumulative explained variance is calculated by adding the explained variance ratios of the selected components.

For example, if the first two principal components retain 95% of the total variance, the data can be represented in two dimensions while preserving approximately 95% of its original variance.

PCA is useful for data visualization, noise reduction, feature extraction, and simplifying complex datasets.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Load a multivariate dataset.
3. Separate the numerical features from other columns, if necessary.
4. Check the dataset for missing values and handle them appropriately.
5. Standardize the features using `StandardScaler`.
6. Apply PCA using the `PCA` class from Scikit-learn.
7. Transform the standardized data into a lower-dimensional representation.
8. Calculate the explained variance ratio for each principal component.
9. Calculate the cumulative explained variance.
10. Visualize the transformed data using a two-dimensional scatter plot.
11. Display the variance retained after dimensionality reduction.
12. Analyze the results and conclude whether PCA has reduced the dimensionality effectively.

## Results and Observations
- PCA transforms the original features into a smaller number of principal components.
- The transformed data can be visualized using a two-dimensional scatter plot.
- The explained variance ratio indicates the amount of variance captured by each component.
- The cumulative explained variance shows the total variance retained by the selected components.
- The actual percentage of variance retained depends on the dataset and the number of principal components selected.

*Note: Update this section with the actual explained variance and observations obtained when running the notebook.*

## Conclusion
Principal Component Analysis was studied and applied to a multivariate dataset to reduce dimensionality, visualize data in lower dimensions, and evaluate the variance retained after transformation.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the transformed data visualization and explained variance results.

## Installation
Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```
