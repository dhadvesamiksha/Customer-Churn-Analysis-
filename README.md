# 📉 Customer Churn Prediction

## 🧠 Overview

This project focuses on predicting customer churn using supervised machine learning techniques, based on the publicly available Telco Customer Churn dataset. Identifying churn-prone customers early empowers businesses to proactively improve retention and customer experience.

---

## 📂 Dataset

- 📄 Source: The dataset used in this project can be found here(https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
- 🧮 Records: 7,043 customer entries
- 🧾 Features: Customer demographics, account details, service subscriptions
- 🎯 Target Variable: `Churn` (Yes/No)

---

## 🎯 Objectives

- Predict customer churn using classification algorithms  
- Perform data cleaning and exploratory data analysis (EDA)  
- Evaluate models using accuracy, precision, recall, and F1-score  
- Generate business insights from churn patterns and feature importance  

---

## 🔧 Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, NumPy, matplotlib, seaborn, scikit-learn  
- **Models**: Logistic Regression, Random Forest  
- **Notebook**: Jupyter  
- **Metrics**: Accuracy, Precision, Recall, F1-Score

---

## 🛠️ Process Overview

### 1. Data Preprocessing
- Removed null and non-numeric values (`TotalCharges`)
- Encoded categorical features using LabelEncoder
- Split data into training and testing sets (80/20 split)

### 2. Exploratory Data Analysis (EDA)
- Correlation analysis and feature distribution visualizations
- Identified key churn influencers like contract type, tenure, and charges

### 3. Model Training
- Trained Logistic Regression and Random Forest classifiers
- Evaluated performance using classification metrics

### 4. Evaluation Results

| Model               | Accuracy | Precision (Churn) | Recall (Churn) |
|---------------------|----------|-------------------|----------------|
| Logistic Regression | 78.7%    | 61.8%             | 52.4%          |
| Random Forest       | 79.2%    | 64.4%             | 48.9%          |

📌 Random Forest achieved slightly better precision, while Logistic Regression offered more stable recall.

---

## 💡 Business Insights

- Customers with **month-to-month contracts** and **lower tenure** had significantly higher churn rates
- Higher churn observed in customers with **electronic check payments**
- **Tenure**, **contract type**, and **monthly charges** emerged as top predictive features

---


