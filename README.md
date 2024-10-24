# Fraud Detection using Machine Learning

## Project Overview
This project aims to detect fraudulent transactions using various machine learning algorithms. The dataset consists of transaction data that includes features such as transaction type, amount, and account balances. The main goal is to build a predictive model that can identify fraudulent transactions accurately.

## Key Steps
1. **Data Preprocessing**:
   - Loading and merging multiple CSV files.
   - Handling missing values and outliers.
   - Creating new features to capture changes in account balances.
   - Balancing the dataset using downsampling and SMOTE (Synthetic Minority Over-sampling Technique).

2. **Feature Engineering**:
   - Scaling numerical features using StandardScaler.
   - Removing multicollinearity based on Variance Inflation Factor (VIF).

3. **Model Training and Evaluation**:
   - Splitting the dataset into training and testing sets.
   - Training multiple algorithms: Logistic Regression, Random Forest, Gradient Boosting, SVM, Decision Tree, and XGBoost.
   - Evaluating models based on confusion matrix, classification report, and ROC AUC score.

4. **Hyperparameter Tuning**:
   - Using RandomizedSearchCV for hyperparameter optimization of the XGBoost model.
