# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent transactions in credit card data. Given the highly imbalanced nature of the dataset, the goal is to build machine learning models that effectively identify fraudulent transactions among a majority of non-fraudulent ones.

## Approach

1. **Data Preprocessing**:
   - Handled missing values and encoded categorical features.
   - Scaled features to ensure model compatibility.
   - Managed outliers in critical features.

2. **Feature Engineering**:
   - Extracted and transformed features to enhance model performance.

3. **Model Implementation**:
   - Implemented various machine learning algorithms including:
     - **Logistic Regression**
     - **Support Vector Machine (SVM)**
     - **K-Nearest Neighbors (KNN)**
     - **Ensemble Models**: Random Forest Classifier and XGBoost Classifier

4. **Hyperparameter Optimization**:
   - Used Grid Search for tuning model parameters to achieve optimal performance.

5. **Evaluation**:
   - Evaluated models based on metrics such as F1-Score, Confusion Matrix and ROC Curve.

## Conclusion

The XGBoost Classifier demonstrated superior performance making it the most effective model for detecting fraudulent transactions in this imbalanced dataset.