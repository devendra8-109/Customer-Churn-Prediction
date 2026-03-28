 🔮 Customer Churn Prediction | Decision Tree Classifier

## 📌 Project Overview
Predicting whether a telecom customer will churn (leave the service) using a Decision Tree Classification model built in Python. This project covers the complete machine learning workflow — from raw data cleaning to model evaluation and actionable business insights.

## 🗂️ Dataset
- Source: Telco Customer Churn — Kaggle
- Size: 7,043 customer records
- Features: 21 columns
- Target: Churn (Yes / No)

## 🛠️ Tools & Technologies
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
- Model: Decision Tree Classifier
- IDE: VS Code / Jupyter Notebook

## 🔄 Project Workflow
1. Loaded and explored real Telco customer dataset
2. Data cleaning — handled missing values, converted TotalCharges to numeric
3. Label encoding of all categorical variables
4. 80-20 Train-Test Split
5. Built Decision Tree Classifier (max_depth=5)
6. Evaluated using Accuracy Score, Confusion Matrix and Classification Report
7. Visualized Feature Importance, Churn Distribution and Confusion Matrix
8. Predicted churn probability for a new customer profile

## 📊 Results
- Model: Decision Tree Classifier
- Accuracy: 67.60%
- Top Churn Factor: Contract Type
- Training Samples: 5,634
- Testing Samples: 1,409

## 🔑 Key Business Insights
- Contract Type is the strongest predictor — month-to-month customers churn the most
- Customers with no Online Security are at significantly higher churn risk
- New customers with low tenure have the highest probability of churning
- High monthly charges combined with short tenure is a strong churn signal
