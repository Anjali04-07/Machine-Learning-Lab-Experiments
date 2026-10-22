# Experiment 05: Support Vector Machine (SVM) for Classification

## Aim
To implement a Support Vector Machine (SVM) algorithm for classification and evaluate its performance on a dataset.

## Objectives
- To understand the concept of Support Vector Machine.
- To implement SVM for classifying data into different classes.
- To understand the role of hyperplanes and support vectors.
- To study different kernel functions used in SVM.
- To evaluate the classification model using suitable performance metrics.

## Theory

**Support Vector Machine (SVM)** is a supervised machine learning algorithm used for classification and regression. It is commonly used for classification tasks in which the goal is to assign data points to different categories.

SVM works by finding an optimal decision boundary, called a **hyperplane**, that separates data points belonging to different classes. It tries to maximize the margin, which is the distance between the hyperplane and the nearest data points from each class.

The data points closest to the decision boundary are called **support vectors**. These points play an important role in determining the position of the hyperplane.

### Important Concepts of SVM

1. **Hyperplane:** A decision boundary that separates different classes.
2. **Support Vectors:** The data points closest to the hyperplane.
3. **Margin:** The distance between the hyperplane and the nearest data points from different classes.
4. **Kernel Function:** A function used to handle data that cannot be separated easily using a straight line.

### Types of Kernel Functions

- **Linear Kernel:** Used when the classes can be separated approximately by a straight line or hyperplane.
- **Polynomial Kernel:** Used to model more complex, curved decision boundaries.
- **RBF (Radial Basis Function) Kernel:** Useful for nonlinear classification problems.
- **Sigmoid Kernel:** Uses a sigmoid-based function to determine similarity between data points.

### Advantages of SVM
- Effective for high-dimensional datasets.
- Can handle linear and nonlinear classification problems.
- Often performs well when the number of features is large.
- Uses support vectors to define the decision boundary.

### Applications of SVM
- Email spam classification.
- Image and handwriting recognition.
- Text classification.
- Disease classification using suitable data.
- Sentiment analysis.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Load the classification dataset.
3. Separate the input features and target class.
4. Preprocess the data and handle missing values, if required.
5. Divide the dataset into training and testing sets.
6. Standardize the features when appropriate.
7. Create an SVM classifier using Scikit-learn.
8. Train the model using the training data.
9. Predict the classes of the test data.
10. Evaluate the model using accuracy, confusion matrix, precision, recall, and F1-score.
11. Display and analyze the classification results.

## Results and Observations
- The SVM model classifies data points into their respective classes.
- The hyperplane separates the classes based on the learned decision boundary.
- Support vectors help determine the optimal decision boundary.
- The selected kernel affects the model's ability to classify linear and nonlinear data.
- Classification performance is evaluated using suitable metrics.

*Note: Update this section with the actual accuracy and other evaluation results obtained from your notebook.*

## Conclusion
The Support Vector Machine algorithm was implemented for classification, and its performance was evaluated using suitable classification metrics.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the predicted classes and model evaluation results.

## Installation
Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```
