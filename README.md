# Predicting Social Personality
[![Kaggle Badge](https://img.shields.io/badge/Kaggle-Loan_Approval_Prediction-brightgreen)](https://www.kaggle.com/competitions/playground-series-s5e7/overview)

# Table of Contents
* [Project Overview](#project-overview)
* [Motivation](#motivation)
* [Data Description](#data-description)
* [Technology](#technology)
* [Methodology](#methodology)
* [Results](#results)
* [Conclusion](#conclusion)


# Project Overview
This project was developed as part of [Kaggle's Predict the Introverts from the Extroverts competition](https://www.kaggle.com/competitions/playground-series-s5e7/overview), where the goal was to build a model to predict loan approvals based on applicant data. The competition provided a rich dataset that enabled the application of various machine learning techniques.
The objective is to analyze and use historical data on previous loan applications, including attributes like income, loan amount, and applicant demographics, to identify key patterns that influence loan approval decisions. 
By building an accurate prediction model, the project seeks to streamline loan approval processes and support financial institutions in making data-driven decisions.

# Motivation
Loan approval decisions play a critical role in financial services, impacting both individuals' access to credit and lenders' risk management. 
Automating the loan approval process with a reliable predictive model can lead to faster decision making, risk mitigation and enhanced financial inclusion.
Through this project, we explore various machine learning techniques to build a robust model that can classify loan applications as "Approved" or "Rejected" with high accuracy, benefiting both lenders and applicants.

# Data Description
Source: https://www.kaggle.com/competitions/playground-series-s4e10/data

Size: 100K records and 13 features

* id: Unique identifier for each loan application.
* person_age: The applicant's age.
* person_income: How much money the applicant makes per year.
* person_home_ownership: Whether the applicant owns a home or not.
* person_emp_length: How many years the applicant has been working.
* loan_intent: The reason the applicant needs the loan.
* loan_grade: A score showing how reliable the applicant is in paying back loans.
* loan_amnt: The amount of money the applicant wants to borrow.
* loan_int_rate: The interest rate charged on the loan.
* loan_percent_income: What percentage of the applicant's income will go to loan payments.
* cb_person_default_on_file: Shows if the applicant has ever failed to pay back a loan.
* cb_person_cred_hist_length: How long the applicant has had a credit history
* loan_status: Shows if the loan is approved or rejected.

# Technology
* **Programming Language**: Python 3.10
* **Libraries**: Pandas, NumPy, Scikit-Learn
* **Tools**: Jupyter Notebook
* **Platform**: Google Colab

# Methodology
* **Data Collection**: Gathered data from Kaggle 
* **Data Cleaning**: No missing and duplicate values
* **Exploratory Data Analysis (EDA)**: Analyzed data distributions, correlations.
* **Feature Engineering**: Created additional features using encoding, normalized data.
* **Model Selection**: Developed Random Forest, Decision Tree, KNN and Logistic Regression.
* **Model Tuning**: Used GridSearchCV for hyperparameter optimization.
* **Evaluation**: Primary evaluation criteria is AUC ROC curve. Also evaluated on the basis of accuracy, precision and recall.

# Results
After experimenting with four different machine learning models, the final selected model achieved a ROC AUC score of 0.94 on the test set, indicating a strong ability to distinguish between approved and rejected loan applications. 
This model outperformed the others in terms of both accuracy and consistency, demonstrating high predictive power.

Key evaluation metrics for the selected model are as follows:
* **ROC AUC Score**: 0.94028
* **Accuracy**: 94.018%
* **Precision**: 94.336
* **Recall**: 94.018

# Conclusion
The loan approval prediction project successfully identified an optimal model that achieved an impressive ROC AUC score of 0.94. 
Through thorough experimentation with multiple models and feature engineering, this final model demonstrated the best performance and proved capable of supporting decision-making processes in the loan approval pipeline. 
This solution has the potential to help financial institutions streamline loan evaluations, reduce manual review time, and enhance risk management. 
Future improvements could involve further tuning of hyperparameters, exploring additional features, and increasing the score using a deep learning model.

