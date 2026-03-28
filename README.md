# 💳 Loan Approval Prediction using Logistic Regression

## 📊 Project Overview

This project builds a machine learning model to predict whether a loan application will be approved or not. It follows an end-to-end ML workflow including data preprocessing, feature engineering, pipeline creation, and model evaluation.

---

## 📌 Problem Statement

Financial institutions need to assess loan applications based on multiple factors such as income, credit history, and applicant details. Incorrect approvals can lead to financial risk.

This project aims to predict loan approval status using machine learning to assist in decision-making.

---

## 🎯 Objective

* Analyze applicant data and identify key factors influencing loan approval
* Handle missing values using proper preprocessing techniques
* Encode categorical features and scale numerical features
* Build a Logistic Regression model using Scikit-learn Pipeline
* Evaluate model using classification metrics
* Generate meaningful business insights

---

## 📂 Dataset Description

### 🔹 Features:

* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Gender
* Married
* Dependents
* Education
* Self_Employed
* Property_Area

### 🔹 Target:

* **Loan_Status (0 = Rejected, 1 = Approved)**

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🔄 Workflow

1. Data Loading and Cleaning
2. Handling Missing Values (SimpleImputer)
3. Feature Engineering
4. Encoding (OneHotEncoder)
5. Feature Scaling (StandardScaler)
6. Model Building using Pipeline
7. Model Evaluation

---

## 🤖 Model Used

* Logistic Regression

---

## 📊 Results

* **Accuracy:** 82.8%
* Model performs well in predicting loan approvals
* Some misclassification observed in rejected cases

---

## 📈 Model Evaluation

### 🔹 Confusion Matrix

* True Positives: 65
* True Negatives: 17
* False Positives: 17
* False Negatives: 0

### 🔹 Key Metrics

* Precision (Approved): 0.79
* Recall (Approved): 1.00
* Recall (Rejected): 0.50

---

## 🧠 Key Insights

* Credit history plays a major role in loan approval
* Model is highly accurate in predicting approved loans
* Some rejected applications are incorrectly approved (risk factor)
* Improving rejection prediction is critical for business use

---

## 🏁 Conclusion

The Logistic Regression model achieved an accuracy of 82.8% and performed well in predicting loan approvals. However, it showed limitations in identifying rejected applications, which is important in financial systems. Further improvements like class balancing and threshold tuning can enhance performance.

---

## 🚀 Future Improvements

* Handle class imbalance using class weights
* Improve recall for rejected loans
* Try advanced models (Random Forest, XGBoost)
* Deploy using Flask or Streamlit

---

## 💡 Why Pipeline?

* Prevents data leakage
* Ensures consistent preprocessing
* Makes model reusable and production-ready

---

## 🔗 Author

**Aditya Ranaware**
