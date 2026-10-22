# Experiment 10: Single-Layer Artificial Neural Network for Classification

## Aim
To build a single-layer Artificial Neural Network (ANN) for a simple classification problem and evaluate its performance using suitable metrics.

## Objectives
- To understand the basic structure of an Artificial Neural Network.
- To study the working of a single-layer neural network.
- To implement a single-layer ANN using Python.
- To classify data into different categories.
- To understand the role of weights, bias, and activation functions.
- To evaluate the classification performance of the neural network.

## Theory

An **Artificial Neural Network (ANN)** is a machine learning model inspired by the way biological neurons process information. It consists of interconnected artificial neurons that learn patterns from input data.

A single-layer neural network contains an input layer and an output layer, with no hidden layer between them. The input features are combined using weights and a bias, and an activation function is applied to generate the output.

### Components of a Single-Layer ANN

1. **Input Layer:** Receives the input features from the dataset.
2. **Weights:** Represent the importance assigned to each input feature.
3. **Bias:** Helps adjust the neuron's output.
4. **Activation Function:** Converts the weighted sum into an output or prediction.
5. **Output Layer:** Produces the predicted class or class scores.

### Working of a Single-Layer ANN

The neuron calculates a weighted sum of its input features:

\[
z=\sum_{i=1}^{n}w_i x_i+b
\]

Where:

- \(x_i\) represents an input feature.
- \(w_i\) represents its corresponding weight.
- \(b\) represents the bias.
- \(n\) is the number of input features.

The activation function is then applied to this weighted sum to produce the output.

During training, the network adjusts its weights and bias to reduce prediction errors. For a simple binary classification problem, a single-layer network can learn a linear decision boundary. For multiclass classification, an appropriate output configuration and activation function are required.

### Activation Functions

- **Step Function:** Produces a binary output based on a threshold.
- **Sigmoid Function:** Converts a value into a probability-like output between 0 and 1.
- **Softmax Function:** Converts multiple class scores into a probability distribution for multiclass classification.

### Applications
- Simple pattern recognition.
- Binary classification.
- Basic text classification.
- Classification of numerical datasets.
- Educational demonstrations of neural network learning.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
1. Import the required Python libraries.
2. Load a suitable classification dataset, such as the Iris dataset.
3. Select the input features and target class.
4. Preprocess the data and encode target labels if required.
5. Split the dataset into training and testing sets.
6. Standardize the input features when appropriate.
7. Create a single-layer neural network using a suitable classifier, such as Scikit-learn's `Perceptron` for a basic single-layer model.
8. Train the model using the training data.
9. Predict the class labels for the testing data.
10. Calculate the classification accuracy and other suitable metrics.
11. Display the results and analyze the model's performance.

## Results and Observations
- A single-layer ANN learns weights and bias from the training data.
- The trained network predicts classes based on the learned parameters.
- Feature preprocessing can improve model performance.
- A single-layer network is suitable for simple problems with approximately linearly separable classes.
- Classification accuracy and other evaluation metrics help measure the model's performance.

*Note: Update this section with the actual accuracy and observations obtained from your notebook.*

## Conclusion
A single-layer Artificial Neural Network was implemented for a classification problem, and its performance was evaluated using suitable classification metrics.

## How to Run
1. Open the experiment notebook in Jupyter Notebook or VS Code.
2. Install the required Python libraries.
3. Run all notebook cells in sequence.
4. Observe the predicted classes and evaluation results.

## Installation
Install the required libraries using the following command:

```bash id="x7f2mc"
pip install numpy pandas matplotlib scikit-learn jupyter
```
