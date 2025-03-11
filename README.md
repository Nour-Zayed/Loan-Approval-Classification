## Loan Approval Classification 
This project implements a machine learning-based loan approval system that predicts whether a loan application should be approved or rejected based on applicant details. The classification model is trained on historical loan data and evaluates various features such as income, credit history, loan amount, employment status, and debt-to-income ratio.

The system helps banks and financial institutions automate loan approval decisions, reducing manual effort, processing time, and potential errors while improving accuracy.

## 🔹 Features

### 1️⃣ Data Preprocessing & Cleaning

Handles missing values using statistical imputation techniques.

Encodes categorical variables (e.g., gender, loan status, education level) using One-Hot Encoding & Label Encoding.

Scales numerical features (e.g., income, loan amount) for better model performance.

### 2️⃣ Exploratory Data Analysis (EDA)

Analyzes feature distributions, correlations, and trends using Matplotlib & Seaborn.

Detects outliers and applies transformations for better model stability.

Visualizes loan approval rates across different applicant categories.

### 3️⃣ Machine Learning Model Training

Implements various classification models:

✔️ Logistic Regression

✔️ Decision Trees

✔️ Random Forest

✔️ Support Vector Machine (SVM)

✔️ Gradient Boosting (XGBoost, LightGBM, CatBoost)

Uses GridSearchCV & RandomizedSearchCV for hyperparameter tuning.

Compares model accuracy, precision, recall, and F1-score.
