# EMPLOYEE_TURNOVER
Employee Turnover Prediction using Logistic Regression &amp; Regularization 

📌 Project Overview

Employee attrition is one of the biggest challenges faced by modern organizations. High employee turnover leads to increased recruitment costs, project delays, loss of skilled talent, and reduced productivity.

This project was developed for TalentCore Pvt. Ltd., a multinational company experiencing a rising number of employee resignations. The objective is to build an intelligent Machine Learning system that predicts whether an employee is likely to leave the company based on job-related and personal factors.

The solution focuses on building a baseline Logistic Regression model and improving its performance using L1 (Lasso) and L2 (Ridge) Regularization, followed by a detailed comparison to recommend the best-performing model.

🎯 Problem Statement

The HR department wants to predict employee attrition using various employee attributes such as:

Age

Job Satisfaction

Salary

Work-Life Balance

Training Hours

Bonuses

Years at Company

Performance Rating

Overtime

Other work-related factors

The target variable is:

0 → Employee Stays

1 → Employee Leaves

Since the output is binary, this is a Binary Classification Problem.

📊 Dataset Description

Total Rows: 900

Total Features: 15

Target Variable: Attrition

Reflects realistic corporate workforce scenarios

Contains both numerical and categorical variables

The dataset simulates real-world employee metrics in a corporate environment.

🛠️ Project Implementation Steps
1️⃣ Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Train-Test split

2️⃣ Baseline Model

Implemented Logistic Regression to establish baseline performance.

3️⃣ Model Improvement

Applied:

L1 Regularization (Lasso) – Feature selection capability

L2 Regularization (Ridge) – Reduces overfitting by shrinking coefficients

4️⃣ Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC-AUC Score

Special focus was given to Recall, as missing potential resignations can significantly impact the company.

📈 Results & Insights

The baseline Logistic Regression provided a solid starting point.

L1 Regularization helped eliminate less important features.

L2 Regularization improved generalization performance.

The final recommendation is based on evaluation metrics and model stability.

Regularization helped reduce overfitting and improved prediction consistency on unseen data.

💡 Business Impact

This predictive system enables HR teams to:

Identify high-risk employees early

Take proactive retention actions

Improve employee engagement strategies

Reduce recruitment and training costs

Enhance workforce planning

By leveraging AI-driven insights, TalentCore Pvt. Ltd. can make data-driven HR decisions.

🚀 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

📌 Conclusion

This project demonstrates how Logistic Regression combined with Regularization techniques can effectively solve real-world employee attrition problems. The approach ensures model interpretability, performance optimization, and business relevance.
