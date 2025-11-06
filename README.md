🏦 Loan Payback Prediction

Predicting whether a borrower will repay their loan using machine learning and financial risk analysis.
Achieved 90% accuracy and 0.91 AUC using Logistic Regression with feature encoding and scaling.

🎯 Project Objective

Financial institutions face the challenge of identifying high-risk borrowers to reduce defaults.
This project aims to predict the probability of loan repayment and uncover the factors driving default behavior.

🧰 Tools & Libraries

🐍 Python, Pandas, NumPy

📊 Matplotlib, Seaborn for EDA

⚙️ Scikit-Learn for ML modeling

🧮 Logistic Regression, ColumnTransformer, OneHotEncoder, StandardScaler

🧠 Dataset

📂 Source: Kaggle – Predicting Loan Payback

Features include:

annual_income, debt_to_income_ratio, credit_score, loan_amount, interest_rate

gender, marital_status, education_level, employment_status, loan_purpose, grade_subgrade

🎯 Target: loan_paid_back → (1 = Paid Back, 0 = Defaulted)

🔍 Exploratory Analysis

Higher credit scores strongly correlate with timely repayments.

Debt-to-income ratio and interest rate are major risk indicators.

Borrowers with stable employment tend to have higher repayment probability.

🧩 Model Workflow

Preprocessing: OneHotEncoding + Scaling with ColumnTransformer

Model: Logistic Regression

Evaluation Metrics:
Accuracy → 0.90
Precision (1) → 0.91
Recall (1) → 0.97
AUC → 0.91

📈 Insights & Results

✅ Borrowers with higher income and lower DTI ratio are least likely to default.
📉 High interest rates and larger loan amounts increase default likelihood.
💡 The model can support loan approval and risk mitigation strategies in finance.

🏁 Summary

Built a loan payback classification model achieving:
90% Accuracy
0.91 AUC
High recall for identifying reliable borrowers

📊 Business Impact: Enables lenders to make data-driven loan decisions and reduce default risk.
