
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
======================================================================================================
ML Model	           ||  Accuracy ||	   AUC    ||	Precision ||	Recall    ||	F1 Score ||	MCC
======================================================================================================
Logistic Regression ||	0.901250	|| 0.905574	 ||  0.644483   ||	0.347826  ||	0.451811	|| 0.426058
------------------------------------------------------------------------------------------------------
Decision Tree	     || 0.874599	|| 0.701457  ||  0.464880	 ||   0.475425	 ||   0.470093	|| 0.399021
------------------------------------------------------------------------------------------------------
KNN	              || 0.896163	|| 0.827721	 ||  0.599002	 ||   0.340265	 ||   0.433996	|| 0.400128
------------------------------------------------------------------------------------------------------
Naive Bayes	        || 0.854805	|| 0.810095	 ||  0.405904	 ||   0.519849	 ||   0.455864	|| 0.377358
------------------------------------------------------------------------------------------------------
Random Forest	     || 0.904456	|| 0.926286	 ||  0.650621	 ||   0.396030  ||   0.492362	|| 0.459724
======================================================================================================
### 8. Graphical Representation

The following visualizations were generated:

- Target Class Distribution
- Classification Model Performance Comparison

### 9. Model Performance Observations
----------------------------------------------------------------------------------------------------------------------------------------------------------------
Logistic Regression:	Provides a baseline classification approach. It achieves an F1 score of 0.452 and an AUC of 0.906, indicating its ability to distinguish between the two classes.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
Decision Tree:	Captures nonlinear relationships between features. Its performance is reflected by an accuracy of 0.875 and an MCC of 0.399.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
KNN:	Classifies observations based on their nearest neighbours. Its performance depends on feature scaling and the selected number of neighbours.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
Naive Bayes:	Uses probability-based classification and assumes conditional independence between features. Its performance is reflected in its precision and recall scores.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
Random Forest:	Combines multiple decision trees to improve prediction stability. Its F1 score of 0.492 and AUC of 0.926 indicate its classification performance.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
### 10. Overall Winner

OVERALL WINNER BASED ON F1 SCORE

[ML Model]     [ Random Forest ]

Accuracy --->  0.904456

AUC        --->  0.926286

Precision  --->  0.650621

Recall     --->  0.39603

F1 Score   --->  0.492362

MCC        --->   0.459724

Name: 4, dtype: object

"The overall best-performing model was Random Forest, which achieved the highest F1 score of 0.492. It demonstrated a comparatively effective balance between precision and recall. The model was selected based on its performance on the test dataset. MCC and AUC were also considered to assess classification quality and class discrimination."

### 11. Execution Instructions

Step 1: Clone the repository.

git clone https://github.com/2026CT05085/085_ML-Assignment2

Step 2: Install dependencies.

pip install -r requirements.txt

Step 3: Ensure bank-full.csv is present
in the project directory.

Step 4: Execute the Python script.

2026CT05085_MLAssignment2.ipynb

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
