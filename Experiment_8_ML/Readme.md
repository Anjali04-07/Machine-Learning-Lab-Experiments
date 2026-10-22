# Experiment 08: Comparison of Different Classification Algorithms

## Aim
To compare different classification algorithms using suitable datasets and problem statements, and evaluate their performance using accuracy, precision, and recall.

## Objectives
- To understand different classification algorithms in machine learning.
- To implement multiple classification models using Python.
- To select suitable datasets for different classification problems.
- To evaluate model performance using accuracy, precision, and recall.
- To compare the performance of different classification algorithms.
- To identify a suitable classification algorithm based on the problem and evaluation results.

## Theory

**Classification** is a supervised machine learning technique used to predict the category or class of a given data point based on its input features.

For example, classification can be used to identify spam emails, predict whether a customer will leave a service, classify flowers into species, and detect fraudulent transactions.

Different classification algorithms use different approaches to learn patterns from data. Comparing their performance helps determine which algorithm is most suitable for a particular problem.

### 1. Logistic Regression
Logistic Regression is a supervised learning algorithm used mainly for classification. It estimates the probability that an input belongs to a particular class and assigns a class based on a decision threshold.

**Example:** Classifying emails as spam or not spam.

### 2. Decision Tree Classifier
A Decision Tree classifies data using a tree-like structure of conditions. Each internal node represents a decision, each branch represents an outcome, and each leaf node represents a predicted class.

**Example:** Predicting whether a customer will purchase a product.

### 3. K-Nearest Neighbour (KNN)
KNN classifies a new data point by examining the classes of its nearest training data points. The most common class among the selected neighbours is generally assigned to the new point.

**Example:** Classifying flowers based on their measurements.

### 4. Support Vector Machine (SVM)
SVM identifies a decision boundary that separates classes while attempting to maximize the margin between them. Kernel functions can be used to handle nonlinear classification problems.

**Example:** Classifying images or text into different categories.

### 5. Random Forest Classifier
Random Forest combines predictions from multiple decision trees. For classification, the trees' predictions are generally combined using majority voting.

**Example:** Classifying customers into different risk categories.

### Classification Evaluation Metrics

A classification model can be evaluated using the following metrics:

**1. Accuracy**

Accuracy measures the proportion of all predictions that are correct.

\[
Accuracy=\frac{TP+TN}{TP+TN+FP+FN}
\]

**2. Precision**

Precision measures the proportion of predicted positive cases that are actually positive.

\[
Precision=\frac{TP}{TP+FP}
\]

**3. Recall**

Recall measures the proportion of actual positive cases correctly identified by the model.

\[
Recall=\frac{TP}{TP+FN}
\]

Where:

- **TP (True Positive):** Positive cases correctly predicted as positive.
- **TN (True Negative):** Negative cases correctly predicted as negative.
- **FP (False Positive):** Negative cases incorrectly predicted as positive.
- **FN (False Negative):** Positive cases incorrectly predicted as negative.

For multiclass classification, precision and recall can be calculated using macro, micro, or weighted averaging, depending on the evaluation objective.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Select suitable datasets and define classification problem statements.
3. Load the datasets and inspect their structure.
4. Handle missing values and encode categorical features or target labels when required.
5. Separate the input features and target class.
6. Divide each dataset into training and testing sets using an appropriate split.
7. Apply feature scaling where necessary, especially for KNN and SVM.
8. Create Logistic Regression, Decision Tree, KNN, SVM, and Random Forest classifiers as appropriate.
9. Train each classifier using the training data.
10. Predict the class labels for the test data.
11. Calculate accuracy, precision, and recall for each model.
12. Use an appropriate averaging method for multiclass datasets.
13. Store the evaluation results in a comparison table.
14. Compare the models and identify the most suitable algorithm for each problem statement.

## Results and Observations
- Different classification algorithms may produce different evaluation results on the same dataset.
- Accuracy indicates the overall proportion of correct predictions.
- Precision indicates how reliable positive predictions are.
- Recall indicates how effectively the model identifies actual positive cases.
- Accuracy alone may be misleading for imbalanced datasets; precision and recall provide additional information.
- The most suitable algorithm depends on the dataset, class distribution, problem requirements, and evaluation results.

*Note: Update this section with the actual accuracy, precision, recall, and comparison table obtained from your notebook.*

## Conclusion
Different classification algorithms were implemented and compared using accuracy, precision, and recall to identify suitable models for different classification problems.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the evaluation metrics and comparison table.

## Installation
Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```
