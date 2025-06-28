# 🏦 Loan Approval Prediction using SVM (Support Vector Machine)

## 📌 Project Overview

This machine learning project focuses on predicting whether a loan will be approved or not, based on customer data. The classification algorithm used is **Support Vector Machine (SVC)**, known for handling complex decision boundaries and high-dimensional data effectively.

---

## 🎯 Objective

To automate the loan approval process by training a model that can predict `Loan_Status` based on customer attributes such as income, credit history, education, property area, and more.

---

## 📁 Files in the Repository

- `Loan_Prediction_SVM.ipynb` – Jupyter Notebook with all steps: data cleaning, EDA, SVM modeling, and evaluation
- `README.md` – Project documentation

---

## 📊 Dataset Description

- **Source**: [Loan Prediction Dataset – Analytics Vidhya / Kaggle](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/)
- **Features**:
  - Gender, Married, Dependents, Education, Self_Employed
  - ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term
  - Credit_History, Property_Area
- **Target**: `Loan_Status`
  - `Y`: Loan Approved  
  - `N`: Loan Rejected

---

## 🧠 Tech Stack

- **Python**
- **Jupyter Notebook**
- **Libraries Used**:
  - `Pandas` & `NumPy` – Data manipulation
  - `Matplotlib` & `Seaborn` – Data visualization
  - `Scikit-learn` – Machine learning and evaluation

---

## 🔍 Workflow Summary

1. **Data Loading & Cleaning**
   - Loaded CSV dataset using Pandas
   - Handled missing values and converted categorical variables using Label Encoding

2. **Exploratory Data Analysis (EDA)**
   - Visualized correlations and feature importance
   - Explored categorical distributions affecting loan status

3. **Preprocessing**
   - Applied Label Encoding and standardization using `StandardScaler`
   - Split data into training and test sets

4. **Model Building**
   - Used `SVC()` from scikit-learn
   - Trained the model and predicted on test data

5. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results & Insights

- **Model Used**: Support Vector Classifier (SVC)
- **Accuracy Achieved**: *e.g., 81.3%* (replace with actual from your output)
- **Key Insights**:
  - Credit History and Income play a significant role in loan approval
  - Preprocessing steps like handling missing values and encoding improved model performance

---

## 🚀 How to Run

### Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
