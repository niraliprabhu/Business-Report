# Loan Approval Prediction in Banking

## 📌 Business Problem

Loan Approval Prediction is a Machine Learning application where algorithms analyze customer details like income, credit score, employment status, and past loan history to predict whether a loan should be approved or rejected.

Banks need an efficient and reliable system that:
- Accurately predicts loan approval status
- Minimizes the risk of loan default
- Reduces manual workload
- Ensures faster processing time
- Maintains fairness and transparency

---

## 📖 Introduction

In the banking sector, approving a loan is a critical financial decision. Traditional manual evaluation methods are time-consuming and may lead to errors or inconsistencies.

Using Machine Learning, banks can automate loan approval decisions by analyzing historical data. The system predicts whether a new applicant is likely to repay the loan, improving accuracy and reducing financial risk.

---

## 🎯 Objectives

1. Analyze historical loan data  
2. Identify key factors influencing loan approval  
3. Clean and preprocess the dataset  
4. Build multiple classification models  
5. Compare model performance  
6. Deploy the best-performing model  

---

## 📊 Dataset Description

The dataset includes the following features:

- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Gender
- Married
- Education
- Self_Employed
- Property_Area
- Loan_Status (Target Variable)

**Note:** Credit History is usually the most influential factor.

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost

Since this is a **binary classification problem**, these models are suitable for predicting loan approval (Yes/No).

---

## 📈 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

The model with the highest performance metrics is selected for deployment.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Flask / FastAPI
- HTML, CSS, JavaScript

---

## 🚀 Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Model Deployment  

---

## ✅ Conclusion

Loan Approval Prediction enhances efficiency, reduces default risk, and improves decision accuracy in banking. With proper preprocessing and model selection, AI-driven systems can ensure fair and reliable loan approval decisions.

---

## 📂 How to Run the Project

```bash
# Clone the repository
git clone <your-repo-link>

# Install required libraries
pip install -r requirements.txt

# Run the application
python app.py
```

---

## 👨‍💻 Author
Nirali Prabhu
Project: Loan Approval Prediction in Banking
