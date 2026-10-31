
# Explainable AI-Based Financial Fraud Detection System

## 1. Project Title
Explainable AI-Based Financial Fraud Detection System

## 2. Problem Statement
Credit card fraud can cause financial losses. This project uses
machine learning to identify potentially fraudulent transactions.

## 3. Objectives
- Analyse credit card transaction data.
- Preprocess data for machine learning.
- Train Logistic Regression and Random Forest models.
- Evaluate model performance using classification metrics.
- Explore feature importance to help explain model predictions.

## 4. Dataset
Credit Card Fraud Detection dataset from Kaggle.
Target column: Class (0 = normal, 1 = fraud).

## 5. Data Cleaning and EDA
Missing values, duplicates, class distribution, transaction amounts,
and feature relationships were examined in earlier project stages.

## 6. Preprocessing
The data was split into training and testing sets.
Time and Amount were scaled for Logistic Regression.
Random Forest was trained using the original feature values.

## 7. Machine Learning Models
- Logistic Regression
- Random Forest Classifier

## 8. Evaluation
Accuracy, precision, recall, F1-score, and confusion matrices
were used to evaluate the models. Refer to model_comparison.csv
for the actual measured results.

## 9. Explainability
Random Forest feature importance was visualised to show which
input features contributed most to the model's predictions.

## 10. Results
Insert and discuss the actual scores from model_comparison.csv.
Do not claim that either model is better without checking the metrics.

## 11. Limitations
The dataset is highly imbalanced. Predictions are not guarantees
of fraud and should not replace human review.

## 12. Future Improvements
- Add SHAP explanations.
- Build an interactive Streamlit dashboard.
- Test the system on additional transaction data.

## 13. Conclusion
This project demonstrates a machine learning workflow for
credit card fraud detection, from data analysis to model evaluation.
