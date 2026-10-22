# Experiment 01: Data Pre-processing on a Raw Dataset

## Aim

To perform data preprocessing on a raw dataset by handling missing values, normalization, and standardization using Python.

## Objectives

- To identify and handle missing values in a dataset.
- To apply normalization to numerical features.
- To apply standardization to numerical features.
- To prepare clean data for Machine Learning algorithms.

## Theory

Data preprocessing is an important step in Machine Learning. Raw datasets may contain missing values and numerical features with different scales. Preprocessing improves data quality and prepares the data for further analysis and model building.

### 1. Handling Missing Values

Missing values occur when some data entries are unavailable. They can be handled by removing incomplete rows or replacing missing values with suitable values such as the mean, median, or mode.

### 2. Normalization

Normalization scales numerical values to a fixed range, commonly between 0 and 1. It is useful when features have different value ranges.

**Formula:**

X' = (X − Xmin) / (Xmax − Xmin)

Where:
- X = Original value
- Xmin = Minimum value of the feature
- Xmax = Maximum value of the feature
- X' = Normalized value

### 3. Standardization

Standardization transforms numerical features so that they have a mean of approximately 0 and a standard deviation of approximately 1.

**Formula:**

Z = (X − μ) / σ

Where:
- X = Original value
- μ = Mean of the feature
- σ = Standard deviation of the feature
- Z = Standardized value

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (optional)

## Algorithm

1. Import the required Python libraries.
2. Load the raw dataset.
3. Display the dataset and inspect its structure.
4. Identify missing values in each column.
5. Handle missing values using an appropriate method.
6. Select the numerical features.
7. Apply Min-Max normalization.
8. Apply standardization using `StandardScaler`.
9. Compare the original and transformed data.
10. Display the preprocessed dataset.

## Results and Observations

- Missing values were identified and handled using a suitable method.
- Normalization was applied to scale numerical features to the selected range.
- Standardization was applied to transform numerical features based on their mean and standard deviation.
- The processed data was prepared for further Machine Learning tasks.

Actual observations should be updated according to the results obtained from the experiment.

## Conclusion

Data preprocessing was performed by handling missing values, normalization, and standardization to prepare the dataset for Machine Learning tasks.

## How to Run

1. Clone or download the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook in Jupyter Notebook or VS Code.
4. Ensure the input dataset is available at the correct path.
5. Run all notebook cells in sequence.

## Installation

Install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```