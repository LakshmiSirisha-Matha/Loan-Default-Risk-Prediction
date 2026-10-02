# Loan Default Risk Prediction

## Project Overview

This project focuses on predicting whether a customer is likely to default on a loan using Machine Learning classification algorithms.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, data preprocessing, model building, model evaluation, cross-validation, and model comparison.

## Objective

The main objective is to build and compare different machine learning classification models for predicting loan default risk.

## Dataset

This project uses a **synthetic loan dataset** created for machine learning practice and analysis.

The dataset contains customer and loan-related features used to predict the loan default outcome.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Project Workflow

### 1. Data Understanding

* Dataset shape
* Data types
* Missing values
* Duplicate records
* Unique values

### 2. Exploratory Data Analysis

* Target variable distribution
* Numerical feature distributions
* Categorical feature analysis
* Histograms
* Boxplots
* Correlation heatmap
* Pairplot
* Outlier detection

### 3. Data Cleaning

* Missing-value treatment
* Category typo correction
* Unnecessary column removal
* Outlier treatment

### 4. Feature Engineering

* Date-based features
* Income-related features
* Loan-to-income features

### 5. Data Preprocessing

* Missing-value imputation
* One-hot encoding
* Feature scaling

### 6. Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

### 7. Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 8. Model Improvement

* Cross-validation
* GridSearchCV
* Random Forest hyperparameter tuning

## Model Performance

| Model               |   Accuracy |  Precision |     Recall |   F1 Score |
| ------------------- | ---------: | ---------: | ---------: | ---------: |
| Logistic Regression |     93.65% |     96.10% |     91.33% |     93.65% |
| Decision Tree       |     92.10% |     92.05% |     92.59% |     92.32% |
| SVM                 |     93.80% |     96.02% |     91.72% |     93.82% |
| Random Forest       |     93.95% |     95.39% |     92.69% |     94.02% |
| **XGBoost**         | **95.90%** | **96.55%** | **95.42%** | **95.98%** |
| Tuned Random Forest |     94.00% |     95.39% |     92.79% |     94.07% |

## Final Result

Among the evaluated models, **XGBoost achieved the highest overall performance**.

* **Accuracy:** 95.90%
* **Precision:** 96.55%
* **Recall:** 95.42%
* **F1 Score:** 95.98%

Based on these evaluation results, XGBoost was selected as the final model among the evaluated models.

## Key Learnings

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory data analysis
* Feature engineering
* Classification algorithms
* Model evaluation
* Cross-validation
* Hyperparameter tuning
* Model comparison
* Feature importance analysis

## Project Files

```text
Loan-Default-Risk-Prediction/
│
├── Loan_Default_Risk_Prediction.ipynb
├── synthetic_loan_dataset.csv
└── README.md
```

## Author

**Lakshmi Sirisha Matha**

B.Tech – Computer Science and Engineering (Data Science)
