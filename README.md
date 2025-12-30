🏦 Loan Approval Prediction (Machine Learning)
An end-to-end Machine Learning project to predict loan approval using structured financial data, with a focus on reducing risky approvals.

📌 Objective

Predict whether a loan should be Approved (1) or Rejected (0) using a binary classification model.

⚙️ Approach

Manual encoding for binary features (Yes/No, Male/Female)

One-Hot Encoding for multi-class categorical feature

ML Pipeline to avoid data leakage

Logistic Regression model

📊 Features Used

Numerical: age, income, loan amount, interest rate, loan-to-income ratio, credit score

Binary: gender, previous loan default

Categorical: loan intent

📈 Evaluation

Confusion Matrix

Precision, Recall, F1-Score

Key insight: Credit score and loan-to-income ratio strongly influence approval decisions.

🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib
