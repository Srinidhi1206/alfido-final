# Loan Approval Prediction

## Objective
Build a machine learning model to predict whether a loan application will be approved based on applicant demographics, financial information, and credit history.

## Dataset
Loan Approval Prediction Dataset

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing
- Loaded and explored the dataset
- Checked dataset dimensions and data types
- Verified missing values
- Encoded categorical variables
- Split data into training and testing sets
- Standardized numerical features for Logistic Regression

## Exploratory Data Analysis

### 1. Loan Approval Distribution
Analyzed the distribution of approved and rejected loan applications.

### 2. Applicant Demographics
Studied age, education, income, and employment experience.

### 3. Financial Analysis
Explored loan amount, interest rate, loan percentage, and credit score.

### 4. Credit History Analysis
Investigated the impact of credit history on loan approval.

## Machine Learning Models

### Logistic Regression
- Trained a Logistic Regression classifier
- Evaluated performance using classification metrics and ROC-AUC score

### Decision Tree Classifier
- Trained a Decision Tree model
- Compared performance with Logistic Regression

## Model Evaluation

### Logistic Regression
- Accuracy: 89%
- ROC-AUC: 0.833

### Decision Tree
- ROC-AUC: 0.852

### Classification Metrics
- Precision
- Recall
- F1-Score
- Accuracy
- ROC-AUC

## Model Comparison
Compared both models using ROC-AUC scores and performance metrics.

## Key Findings
- Credit score and credit history significantly influence loan approval.
- Applicant income plays an important role in loan decisions.
- Decision Tree achieved a slightly higher ROC-AUC score than Logistic Regression.
- Both models demonstrated strong predictive performance.

## Business Recommendations
- Prioritize applicants with strong credit history and credit scores.
- Use predictive models to support loan approval decisions.
- Continuously monitor model performance and retrain with updated data.

## Files Included
- `loan_approval_prediction.ipynb` – Complete machine learning workflow
- `loan_data_new.csv` – Dataset
- `README.md` – Project documentation

## Conclusion
This project demonstrates how machine learning can be used to automate and improve loan approval decisions. The developed models provide valuable insights and can assist financial institutions in reducing risk while improving efficiency.
