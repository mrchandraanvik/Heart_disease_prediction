Heart Disease Prediction using Machine Learning

An end-to-end machine learning project focused on predicting the likelihood of heart disease using clinical and physiological attributes. The project follows a complete data science workflow including exploratory data analysis (EDA), feature analysis, preprocessing, baseline modeling, advanced ensemble learning, hyperparameter tuning, cross-validation, and Kaggle submission generation.

Project Overview

The objective of this project is to build a robust binary classification model capable of accurately predicting the presence of heart disease. Multiple machine learning techniques were explored and evaluated to identify the most effective predictive model.

Workflow
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Correlation Analysis
Outlier and Distribution Analysis
Feature Importance Evaluation
Logistic Regression Baseline Model
XGBoost Ensemble Model
Hyperparameter Tuning
Stratified K-Fold Cross Validation
Final Prediction and Kaggle Submission
Key Techniques Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Model Performance
Logistic Regression
Accuracy: ~88.47%
ROC-AUC Score: ~0.9515
Tuned XGBoost
Accuracy: ~88.97%
ROC-AUC Score: ~0.9559
Cross Validation
Stratified 5-Fold Cross Validation
Mean ROC-AUC: ~0.9551
Key Insights
Features such as Thallium, Chest Pain Type, Max Heart Rate, and ST Depression were identified as highly influential predictors.
XGBoost outperformed Logistic Regression by effectively capturing nonlinear feature relationships.
Cross-validation results demonstrated strong model stability and minimal overfitting.
