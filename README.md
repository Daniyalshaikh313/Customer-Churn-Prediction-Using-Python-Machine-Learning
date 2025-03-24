
# 📊 Customer Churn Prediction Using Python & Machine Learning
## 🎯 Objective
To build a predictive model that identifies customers likely to churn using logistic regression.

## 📚 Dataset Overview
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File Name:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Rows:** 7043
- **Columns:** 21
- **Target Variable:** `Churn` (Yes/No)

## 📦 Project Workflow
### Step 1: Data Collection & Cleaning
- Load raw data and handle missing values.
- Convert `TotalCharges` to numeric and fill missing values.
- Encode categorical variables using `pd.get_dummies()`.

### Step 2: Exploratory Data Analysis (EDA)
- Analyze churn rate distribution.
- Plot correlation heatmap.
- Visualize tenure, monthly charges, and total charges impact on churn.

### Step 3: Model Building & Evaluation
- Split data into train-test sets.
- Build Logistic Regression model.
- Evaluate model performance (81.83% accuracy).
- ![mlc](https://github.com/user-attachments/assets/d977f4f5-3d2b-48dd-a14c-177e119fcb1e)


### Step 4: Model Deployment
- Save the trained model (`customer_churn_model.pkl`).

## 🔥 Key Insights
- Higher churn is observed for customers with **short tenure**.
- **Monthly Charges** significantly influence churn probability.
![cp3](https://github.com/user-attachments/assets/124cde3d-8afa-45a2-bd12-8157932e41f6)
![cp2](https://github.com/user-attachments/assets/6ff822eb-b7e6-4cc5-9a99-eb57415736cb)
![cp](https://github.com/user-attachments/assets/cd9aa247-0b91-472a-9ca1-7cd5bd0dc22c)





