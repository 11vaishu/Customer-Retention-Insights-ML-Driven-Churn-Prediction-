# 📌 Customer Retention Insights – ML-Driven Churn Prediction

## 📖 Overview
This project predicts customer churn for a telecom service provider and provides actionable insights to improve retention strategies. It combines **machine learning models** with **business intelligence dashboards** to identify high-risk customers and the factors driving churn.

## 🎯 Objectives
- Predict which customers are likely to churn.
- Identify key factors contributing to churn.
- Present insights in an interactive Tableau dashboard.

## 📊 Dataset
- **Source:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Records:** 7,043  
- **Features:** Demographics, service subscriptions, billing details, churn status.

## 🛠 Technologies Used
- **Programming & Libraries:** Python, Pandas, NumPy, Scikit-learn
- **Modeling:** Logistic Regression (Balanced Class Weights), Random Forest
- **Visualization:** Seaborn, Matplotlib, Tableau
- **Techniques:** EDA, Feature Encoding, Class Imbalance Handling, Model Evaluation (Accuracy, Recall, Precision, F1-Score)

## 🔄 Project Workflow
1. **Data Cleaning & Preprocessing**
   - Removed invalid values in `TotalCharges`
   - One-hot encoded categorical variables
   - Dropped irrelevant columns like `customerID`

2. **Exploratory Data Analysis (EDA)**
   - Churn distribution analysis
   - Churn by contract type, internet service, tenure, monthly charges
   - Visualizations using Seaborn & Matplotlib

3. **Model Training & Evaluation**
   - Trained **Logistic Regression** and **Random Forest** models
   - Applied `class_weight='balanced'` to handle class imbalance
   - Achieved **80% recall** for churners using Logistic Regression (balanced)

4. **Dashboard Creation**
   - Designed an interactive Tableau dashboard
   - Filters for gender, contract, payment method
   - KPIs and churn trend charts

---

## 📈 Results
- **Logistic Regression (Balanced):** 80% recall for churners (best for retention-focused use case)
- **Random Forest (Balanced):** Higher precision, slightly lower recall
- Tableau dashboard delivers clear churn segmentation for decision-makers

---

## 📂 Repository Structure
