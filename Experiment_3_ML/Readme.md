# Experiment 03: Linear Regression and Logistic Regression Algorithms

## Aim

To implement Linear Regression and Logistic Regression algorithms using Python for regression and classification tasks.

## Objectives

- To understand the concepts of Linear Regression and Logistic Regression.
- To implement Linear Regression for predicting continuous values.
- To implement Logistic Regression for classification problems.
- To evaluate model performance using suitable evaluation metrics.
- To understand the difference between regression and classification algorithms.

## Theory

Linear Regression and Logistic Regression are supervised Machine Learning algorithms. They learn from labeled data and use the learned patterns to make predictions.

### 1. Linear Regression

Linear Regression is used to predict continuous numerical values by finding a linear relationship between input features and the target variable.

**Equation:**

\[
y = b_0 + b_1x
\]

Where:
- \(y\) = Predicted value
- \(x\) = Input feature
- \(b_0\) = Intercept
- \(b_1\) = Regression coefficient

**Example:** Predicting house prices based on their area.

### 2. Logistic Regression

Logistic Regression is a supervised classification algorithm used to predict the probability that an observation belongs to a particular class. For binary classification, it uses the sigmoid function to map predictions to probabilities between 0 and 1.

**Sigmoid Function:**

\[
P(Y=1\mid x)=\frac{1}{1+e^{-(b_0+b_1x)}}
\]

The predicted probability is compared with a threshold, commonly 0.5, to assign a class.

**Example:** Predicting whether an email is spam or not spam.

### 3. Difference Between Linear and Logistic Regression

| Linear Regression | Logistic Regression |
|---|---|
| Predicts continuous values. | Predicts class probabilities and classes. |
| Used for regression tasks. | Used for classification tasks. |
| Fits a linear relationship to the target. | Uses a logistic function for classification probabilities. |
| Evaluated using metrics such as MAE, MSE, and R². | Evaluated using metrics such as accuracy, precision, recall, and F1-score. |

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm

### A. Linear Regression

1. Import the required Python libraries.
2. Load the dataset.
3. Select the input features and target variable.
4. Divide the data into training and testing sets.
5. Create a Linear Regression model.
6. Train the model using the training data.
7. Predict continuous values for the test data.
8. Evaluate the model using suitable regression metrics.
9. Visualize actual and predicted values where appropriate.

### B. Logistic Regression

1. Import the required Python libraries.
2. Load the dataset.
3. Select the input features and target class.
4. Preprocess the data and encode categorical variables if required.
5. Divide the data into training and testing sets.
6. Create a Logistic Regression model.
7. Train the model using the training data.
8. Predict class labels for the test data.
9. Evaluate the model using suitable classification metrics.
10. Display the results using a confusion matrix or other suitable visualization.

## Results and Observations

- Linear Regression was used to predict continuous numerical values.
- Logistic Regression was used to classify observations into classes.
- Model performance was evaluated using appropriate metrics.
- The results demonstrated the difference between regression and classification tasks.

Actual observations should be updated according to the results obtained from the experiments.

## Conclusion

Linear Regression and Logistic Regression were implemented using Python to understand continuous-value prediction and classification in supervised Machine Learning.

## How to Run

1. Clone or download the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook in Jupyter Notebook or VS Code.
4. Ensure the required input data is available at the correct path.
5. Run all notebook cells in sequence.

## Installation

Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```