# Titanic Survival Prediction 🚢

This project predicts whether a passenger survived the Titanic disaster using Machine Learning. It demonstrates a full workflow: data preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and prediction for Kaggle submission.

---

## **Project Overview**
The Titanic dataset provides information about passengers such as class, age, sex, fare, and family relations aboard. The objective is to predict survival (`0 = No`, `1 = Yes`) based on these features.

Key steps:
- Data Cleaning & Handling Missing Values
- Feature Engineering (encoding categorical features, scaling if needed)
- Model Training & Comparison
- Hyperparameter Tuning with **GridSearchCV**
- Evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix
- Making predictions on the test set for Kaggle submission

---

## **Models Used**
1. **Random Forest Classifier** 🌲 — Best performing model after Grid Search  
2. **Logistic Regression** 📈  
3. **Support Vector Classifier (SVC)** ⚡  

We compare all three models using metrics on the validation set and select the best model for final prediction.

