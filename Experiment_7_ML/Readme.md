# Experiment 07: Comparison of Different Regression Algorithms

## Aim
To compare different regression algorithms using suitable datasets and problem statements, and evaluate their performance using appropriate evaluation metrics.

## Objectives
- To understand different regression algorithms used in machine learning.
- To implement multiple regression models using Python.
- To select suitable datasets and regression problem statements.
- To evaluate model performance using standard regression metrics.
- To compare the strengths and limitations of different regression algorithms.
- To identify a suitable regression model based on the problem and evaluation results.

## Theory

**Regression** is a supervised machine learning technique used to predict a continuous numerical value based on one or more input features.

For example, regression can be used to predict house prices, student marks, product sales, and temperature.

Different regression algorithms learn different relationships between input features and the target variable. Comparing multiple algorithms helps determine which model is most suitable for a particular problem.

### 1. Linear Regression
Linear Regression models the relationship between input features and a continuous output using a linear equation.

For a single input feature:

\[
\hat{y}=b_0+b_1x
\]

It is suitable when the relationship between the input and output is approximately linear.

**Example:** Predicting house prices based on house area.

### 2. Polynomial Regression
Polynomial Regression models nonlinear relationships by including polynomial powers of the input features.

For example:

\[
\hat{y}=b_0+b_1x+b_2x^2
\]

It is useful when the relationship between input and output follows a curved pattern.

**Example:** Predicting crop yield based on temperature when the relationship is nonlinear.

### 3. Decision Tree Regression
Decision Tree Regression divides the dataset into smaller regions using decision rules and predicts a numerical value for each region.

It can model nonlinear relationships and interactions between features.

**Example:** Predicting house prices using area, location-related features, and number of rooms.

### 4. Random Forest Regression
Random Forest Regression combines predictions from multiple decision trees. The final prediction is generally the average of the individual tree predictions.

It can model complex relationships and often provides more stable predictions than a single decision tree.

**Example:** Predicting product sales using price, advertising expenditure, and seasonal information.

### 5. Support Vector Regression (SVR)
Support Vector Regression applies Support Vector Machine principles to predict continuous values. It attempts to fit predictions within a specified error tolerance and can use kernels to model nonlinear relationships.

Feature scaling is generally important when using SVR.

**Example:** Predicting energy consumption from weather and usage measurements.

### Regression Evaluation Metrics

The following metrics can be used to compare regression algorithms:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted values. Lower is better.
- **Mean Squared Error (MSE):** Measures the average squared prediction error. Lower is better.
- **Root Mean Squared Error (RMSE):** The square root of MSE, expressed in the target variable's units. Lower is better.
- **R-squared (\(R^2\)):** Measures how well the model explains variation in the target. A higher value is generally better, although it should be considered alongside error metrics and test performance.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Select suitable datasets and define regression problem statements.
3. Load the datasets and inspect their structure.
4. Handle missing values and preprocess the features.
5. Separate the input features and continuous target variable.
6. Divide each dataset into training and testing sets.
7. Create Linear Regression, Polynomial Regression, Decision Tree Regression, Random Forest Regression, and Support Vector Regression models as appropriate.
8. Train each model using the training data.
9. Predict the target values for the test data.
10. Calculate MAE, MSE, RMSE, and \(R^2\) for each model.
11. Store the evaluation results in a comparison table.
12. Visualize actual and predicted values where appropriate.
13. Compare the models and identify the most suitable model for each problem statement.

## Results and Observations
- Different regression algorithms may produce different prediction errors on the same dataset.
- Linear Regression is useful for approximately linear relationships.
- Polynomial Regression can capture curved relationships when an appropriate degree is selected.
- Decision Tree and Random Forest Regression can capture nonlinear patterns.
- Support Vector Regression can model complex relationships using suitable kernels and parameters.
- The best-performing model should be selected using test-set evaluation metrics and, where appropriate, cross-validation.

*Note: Add the actual comparison table, metric values, and graphs from your notebook after running the experiments. The best algorithm depends on the dataset and problem statement.*

## Conclusion
Different regression algorithms were compared using suitable datasets and evaluation metrics to understand their performance and identify appropriate models for different prediction problems.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the evaluation metrics, comparison table, and prediction graphs.

## Installation
Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```
