# Experiment 06: Decision Tree and K-Nearest Neighbour (KNN)

## Aim
To implement Decision Tree and K-Nearest Neighbour (KNN) algorithms for classification and evaluate their performance using suitable evaluation metrics.

## Objectives
- To understand the concepts of Decision Tree and KNN algorithms.
- To implement both algorithms using Python and Scikit-learn.
- To classify data into different categories.
- To understand how Decision Trees make decisions using rules.
- To understand how KNN classifies data based on neighbouring data points.
- To compare the performance of both classification algorithms.

## Theory

### 1. Decision Tree

A **Decision Tree** is a supervised machine learning algorithm used for classification and regression. It represents decisions in the form of a tree structure and predicts the output by following a sequence of conditions.

A Decision Tree contains the following components:

- **Root Node:** Represents the first feature or condition used to split the data.
- **Decision Node:** Represents a condition used to divide the data into smaller groups.
- **Branch:** Represents the outcome of a decision.
- **Leaf Node:** Represents the final predicted class or value.

The algorithm selects features that help separate the classes effectively. Measures such as Gini impurity and entropy can be used to select splits.

**Advantages:**
- Easy to understand and interpret.
- Requires little feature preprocessing.
- Can handle numerical and categorical features with suitable preprocessing.

**Applications:** Customer classification, risk assessment, medical data classification, and loan approval prediction.

### 2. K-Nearest Neighbour (KNN)

**K-Nearest Neighbour (KNN)** is a supervised machine learning algorithm used for classification and regression. It predicts the class of a new data point by examining the classes of its nearest training data points.

The parameter **K** specifies the number of neighbours considered for prediction. For classification, the most common class among those neighbours is generally selected.

For example, if \(K=3\) and two of the three nearest neighbours belong to Class A, the new data point is classified as Class A using majority voting.

**Steps involved in KNN:**
1. Select the value of K.
2. Calculate the distance between the new data point and training data points.
3. Identify the K nearest neighbours.
4. Count the class labels of the selected neighbours.
5. Assign the majority class to the new data point.

Euclidean distance is commonly used to measure the distance between numerical data points.

**Advantages:**
- Simple and easy to implement.
- Does not require a separate model-training process.
- Can handle classification problems with nonlinear decision boundaries.

**Limitations:**
- Prediction can be slow for large datasets.
- Performance depends on the choice of K and distance metric.
- Feature scaling is important when features have different ranges.

### Difference Between Decision Tree and KNN

| Feature | Decision Tree | KNN |
|---|---|---|
| Working principle | Uses decision rules | Uses nearest neighbours |
| Model type | Tree-based model | Instance-based model |
| Training | Learns tree structure | Stores training data |
| Feature scaling | Usually not required | Usually important |
| Prediction | Follows tree branches | Calculates distances |
| Main parameter | Tree depth and split criteria | Number of neighbours (K) |

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm

### A. Decision Tree Algorithm
1. Import the required Python libraries.
2. Load the classification dataset.
3. Separate input features and target labels.
4. Handle missing values and encode categorical features if required.
5. Split the dataset into training and testing sets.
6. Create a Decision Tree classifier.
7. Train the model using the training data.
8. Predict the classes of the test data.
9. Calculate accuracy and other classification metrics.
10. Display and analyze the results.

### B. K-Nearest Neighbour Algorithm
1. Load the classification dataset and separate features and target labels.
2. Handle missing values and encode categorical features if required.
3. Split the dataset into training and testing sets.
4. Standardize the input features.
5. Create a KNN classifier with a suitable value of K.
6. Train the classifier using the training data.
7. Predict the classes of the test data.
8. Calculate accuracy and other classification metrics.
9. Compare the KNN results with those of the Decision Tree.

## Results and Observations
- The Decision Tree classifies data using learned decision rules.
- The KNN algorithm classifies data based on the labels of its nearest neighbours.
- Feature scaling can significantly affect KNN performance