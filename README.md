
# Machine Learning Assignment 2
## Bank Marketing Classification

-----------------------------------
Name: PRANAYJIT MAHATA 
ID: 2026CT05085
-----------------------------------

### 1. Problem Statement

The objective of this project is to implement and
compare multiple machine learning classification
algorithms to predict whether a bank customer will
subscribe to a term deposit.

Five classification algorithms are implemented and
evaluated using six performance metrics.

### 2. Dataset Description

Dataset: Bank Marketing Dataset

Source: UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/222/bank+marketing

Problem Type: Binary Classification

Target Variable: y

Target Classes:
- Yes: Customer subscribed to a term deposit.
- No: Customer did not subscribe.

The dataset contains 45,211 observations and
16 input features.

It contains both numerical and categorical
features.

### 3. GitHub Repository Link

Repository: https://github.com/2026CT05085/085_ML-Assignment2

### 4. Data Preprocessing

The following preprocessing operations were
performed:

1. Loaded the Bank Marketing dataset.
2. Identified and removed duplicate records.
3. Identified missing values.
4. Applied median imputation to numerical features.
5. Applied most-frequent imputation to categorical
   features.
6. Applied One-Hot Encoding to categorical features.
7. Applied Standard Scaling to numerical features.
8. Divided the dataset into 80% training and
   20% testing data.
9. Used stratified sampling to maintain class
   distribution.
10. Used random_state=42 for reproducibility.

All preprocessing transformations were fitted
using training data only.

### 5. Models Used

The following classification algorithms were
implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors Classifier
4. Gaussian Naive Bayes
5. Random Forest Classifier

### 6. Evaluation Metrics

The following metrics were calculated:

- Accuracy
- AUC Score
- Precision
- Recall
- F1 Score
- Matthews Correlation Coefficient (MCC)

### 7. Model Comparison

[INSERT YOUR ACTUAL MODEL COMPARISON TABLE]

### 8. Graphical Representation

The following visualizations were generated:

- Target Class Distribution
- Classification Model Performance Comparison

### 9. Model Performance Observations

[INSERT YOUR ACTUAL MODEL OBSERVATIONS]

### 10. Overall Winner

[INSERT THE BEST-PERFORMING MODEL AND
JUSTIFICATION BASED ON ACTUAL RESULTS]

### 11. Execution Instructions

Step 1: Clone the repository.

git clone https://github.com/2026CT05085/085_ML-Assignment2

Step 2: Install dependencies.

pip install -r requirements.txt

Step 3: Ensure bank-full.csv is present
in the project directory.

Step 4: Execute the Python script.

python main.py

Step 5: Check the generated comparison table,
graphs, saved models and test_data.csv.

### 12. Conclusion

This project compares five machine learning
classification algorithms on the Bank Marketing
dataset.

The models were evaluated using six performance
metrics to understand their classification
capabilities.

The comparison helps identify the most suitable
classification model for the selected dataset.
