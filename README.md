# 📊 Loan Approval Prediction Using SAS

## 📌 Business Objective
Analyze loan application data to identify key factors influencing loan approval, borrower creditworthiness, and interest rates. Build predictive models to support better lending decisions and reduce default risk.

---

## 📂 Dataset
- Source: Kaggle – [Loan Prediction Dataset](https://www.kaggle.com/datasets)
- Includes 45,000+ loan applications with demographic, financial, and loan-related variables.
- File used: `loan_data.csv`

---

## 🛠️ Tools & Technologies
- **SAS Studio**: Data cleaning, EDA, logistic & linear regression modeling
- **Excel**: Basic tabular analysis and stats
- **Techniques**: Logistic Regression, Linear Regression, Feature Engineering, EDA

---

## 🧠 Project Overview
- Built a **logistic regression model** to predict loan approval (`loan_status`)  
  → Achieved **89% accuracy** with strong precision & recall  
- Built a **linear regression model** to estimate interest rate (`loan_int_rate`)  
  → R² = 0.0227 (low explanatory power, suggesting need for more variables)  
- Applied data preprocessing: outlier treatment, missing value imputation, log transformation, and feature scaling  
- Created derived variables like debt-to-income ratio and addressed multicollinearity

---

## 📊 Key Insights
- **Higher income and credit score** → greater likelihood of loan approval  
- **Mortgage holders** requested higher loan amounts than renters or owners  
- Weak correlation between credit score and loan amount  
- Class imbalance in target variable addressed using SMOTE

---

## 🔍 Techniques Used
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Logistic Regression (binary classification)  
- Linear Regression (numerical prediction)  
- Feature Engineering (log transforms, ratios)  
- Model Evaluation (confusion matrix, accuracy, AUC, R²)

---

## 📝 Project Files
- `Loan data ( FINAL PROJECT MEMO ).docx`: Full analysis report with methodology, results, and visualizations  
- `loan_data.csv`: Cleaned dataset used for modeling  
- `README.md`: This project summary

---

## 👨‍💻 Author
**Krishna Teja Reddy Kotla**  
Master’s in Management Information Systems  
Auburn University at Montgomery  
📧 krishnatejareddy.kotla@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/krishnatejakotla)


