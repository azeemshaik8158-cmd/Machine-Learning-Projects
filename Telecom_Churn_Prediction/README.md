# Telecom Customer Churn Prediction

This project focuses on predicting whether a telecom customer will leave the service (churn) or continue using it. The objective is to understand the key factors influencing churn and build a reliable machine learning model to identify customers who are at risk, so companies can plan retention strategies.

---

## 🧾 Business Context
Customer churn is a major challenge in the telecom industry. Retaining existing customers is more cost-effective than acquiring new ones.  
By predicting churn in advance, telecom companies can:
- Reduce customer loss
- Improve customer satisfaction
- Support data-driven decision making

---

## 🧠 Problem Type
This is a **Binary Classification** problem where:
- 0 = Not Churned
- 1 = Churned

---

## 📂 Dataset Overview
The dataset includes customer-level details such as:
- Customer tenure
- Contract type
- Internet and phone services
- Monthly and total charges
- Payment method
- Churn label (Yes / No)

---

## 🚀 Project Workflow
### ✔ Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Split data into train and test sets

### ✔ Exploratory Data Analysis (EDA)
- Checked churn distribution
- Observed relation between features and churn
- Identified important churn drivers

### ✔ Model Development
I trained and evaluated machine learning models including:
- Random Forest Classifier

Hyperparameter tuning was applied using GridSearchCV to improve model performance.

---

## 📊 Model Performance
Final model performance:

- **Accuracy:** 79.2%
- **ROC-AUC Score:** 0.83
- Classification Report was analyzed for precision, recall and F1-score
- Confusion Matrix was used to evaluate predictions

---

## 🔍 Key Insights
- Customers with higher monthly charges show higher churn tendency
- Contract type and tenure play a major role in churn
- Feature importance helped understand key churn indicators

---

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🎯 Learning Outcome
This project helped me understand the complete end-to-end machine learning pipeline, including data preprocessing, EDA, model building, evaluation and extracting insights from real-world data.
