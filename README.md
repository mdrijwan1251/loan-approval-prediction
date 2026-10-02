# Loan Approval Prediction

A machine learning project that predicts whether a loan application is likely to be approved based on applicant financial and demographic information.

## Project Objective

The objective of this project is to build and compare machine learning classification models for predicting loan approval.

## Dataset

The dataset contains **1,500 records** with applicant information and a loan approval target.

### Features

* Applicant Income
* Education Level
* DTI Ratio
* Credit Score
* Applicant ID
* Age

### Target

* `Loan_Approved`

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Machine Learning Workflow

1. Data loading
2. Data inspection
3. Data cleaning
4. Exploratory Data Analysis (EDA)
5. Train-test split
6. Feature engineering
7. Feature scaling
8. Outlier handling
9. Model training
10. Model evaluation
11. Model comparison

## Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

## Feature Engineering

Additional features were created from the original variables, including:

* DTI Ratio Squared
* Credit Score Squared

Data preprocessing also included feature scaling and outlier handling.

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Results

| Model                | Accuracy | F1-Score |
| -------------------- | -------: | -------: |
| Logistic Regression  |   ~72.3% |   ~0.745 |
| KNN                  |   ~62.0% |   ~0.650 |
| Gaussian Naive Bayes |   ~67.3% |   ~0.701 |

*Results may vary slightly depending on preprocessing, random state, and the final version of the notebook.*

## Key Learning Outcomes

* Learned how to preprocess a real-world classification dataset.
* Practiced exploratory data analysis and feature engineering.
* Compared multiple classification algorithms.
* Learned how scaling and outlier handling affect model performance.
* Evaluated models using multiple classification metrics rather than accuracy alone.

## Project Structure

```text
loan-approval-prediction/
│
├── loan_approval_prediction.ipynb
├── README.md
├── dataset/
│   └── loan_approval.csv
└── .gitignore
```

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* More extensive feature engineering
* Model explainability
* Deployment as a web application/API

## Author

**Mohd Rijwan**

[GitHub Profile](YOUR_GITHUB_LINK)
