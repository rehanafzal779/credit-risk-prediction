# 💳 Credit Risk Prediction – Internship Task 2

## 📌 Objective

Build a machine learning model to predict whether a loan applicant is likely to default or get loan approval, based on financial and demographic information.

---

## 📊 Dataset Overview

- **Dataset**: Loan Prediction Dataset (from Kaggle)
- **Target Variable**: `Loan_Status`
- **Features**: ApplicantIncome, LoanAmount, Credit_History, Gender, Education, etc.

---

## 🛠️ Methodology

1. **Data Cleaning**: Handled missing values with median/mode
2. **EDA**:
   - Histograms and box plots to examine income, loan amount
   - Countplots to analyze education and approval rates
3. **Modeling**:
   - Logistic Regression and Decision Tree Classifier
   - Split data 80/20 using `train_test_split`
4. **Evaluation**:
   - Accuracy score
   - Confusion matrix

---

## 📈 Results

- **Logistic Regression Accuracy**: ~84%
- Logistic Regression gave more stable predictions with fewer false positives

---

## 🧠 Insights

- Credit history is the strongest predictor of loan approval
- Higher applicant income alone doesn't guarantee approval

---

## 📁 Files

- `credit_risk_model.ipynb`: Full notebook
- `loan_data.csv`: Cleaned dataset (optional)
- `README.md`: This file

---

## 📬 Author

Ahmad Afzal  
