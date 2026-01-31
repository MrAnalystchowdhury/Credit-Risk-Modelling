📊 Credit Risk Analysis & Loan Default Prediction


🔍 Project Overview

This project analyzes loan and borrower data to understand why some borrowers default and others don’t, and to build a model that can predict the probability of default (PD) — similar to how banks assess credit risk before approving loans.
The goal was not just accuracy, but interpretability and business relevance, so that results can actually support lending decisions.



🧠 What I Was Trying to Understand

I focused on three key questions:

Which borrower characteristics increase default risk?
How strongly do income, loan size, interest rate, and credit history affect repayment?
Can we predict default in a way that is explainable to decision-makers?



📂 Data Understanding

The dataset contains:

Borrower information (income, employment length, home ownership)
Loan details (loan amount, interest rate, term)
Credit behavior (credit history length, delinquencies)
Final outcome: default vs non-default
Not all columns were useful.
I removed identifiers, post-loan leakage variables, and irrelevant metadata, keeping only features that would be known at the time of loan approval — just like in real banking practice.



⚙️ Methodology

Data Cleaning

Handled missing values
Removed irrelevant and duplicate columns
Standardized numeric features

Exploratory Analysis

Compared default vs non-default borrowers
Checked how risk changes with income, interest rate, and loan size
Identified high-risk borrower patterns

Modeling

Built an interpretable Logistic Regression model
Compared it with a Random Forest for performance
Evaluated using ROC-AUC, confusion matrix, and classification report



📈 Key Insights

Higher interest rates are strongly associated with higher default risk
Low income + large loan amount significantly increases probability of default
Borrowers with shorter credit history default more often
Certain loan purposes (e.g., small business, medical) show elevated risk



🏦 Real-World Application

This project can be used for:

Loan approval screening
Risk-based pricing (higher interest for higher Probability of Default)
Early warning systems for potential defaults
Credit policy analysis



🛠 Tools & Skills Used

Python (Pandas, NumPy, Scikit-Learn)
Credit Risk Thinking (Probability of Default modeling)
Model Evaluation & Interpretation



📂 Dataset:
👉 https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014

🔗 Google collab notebook:
👉 https://colab.research.google.com/drive/1eBjiXLSTroS36ovf1pNQIYmX2M63h-Mv?usp=sharing

📁 Porfolio:
👉 https://www.datascienceportfol.io/mranalystchowdhury/projects/2



I’m actively building real-world analytics projects and seeking Data Analyst opportunities where I can apply structured thinking, SQL, and BI tools to support data-driven decision-making.



#DataAnalytics
#DataAnalyst
#SQL
#PowerBI
#Python
#AnalyticsMindset
#PortfolioProject
#CreditRiskModelling

I’m actively building real-world analytics projects and seeking Data Analyst opportunities where I can apply structured thinking, SQL, and BI tools to support data-driven decision-making.


hashtag#DataAnalytics hashtag#DataAnalyst hashtag#SQL hashtag#PowerBI hashtag#AnalyticsMindset hashtag#PortfolioProject
