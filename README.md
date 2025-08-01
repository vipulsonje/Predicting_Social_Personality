# Predicting Social Personality
[![Kaggle Badge](https://img.shields.io/badge/Kaggle-Predicting_Social_Personality-brightgreen)](https://www.kaggle.com/competitions/playground-series-s5e7/overview)

#Competition Summary

This project was developed as part of [Kaggle's Predict the Introverts from the Extroverts competition](https://www.kaggle.com/competitions/playground-series-s5e7/overview), where the goal was to classify individuals as Introverts or Extroverts based on their social behavior and personality traits.

**Evaluation Metric:** Accuracy  
**Final Accuracy:** 96.86% (0.9686), just 0.2% behind the top submission on the leaderboard.

This was a challenging and insightful competition that allowed me to apply and fine-tune various classification models and ensemble techniques.

# Table of Contents
* [Project Overview](#project-overview)
* [Motivation](#motivation)
* [Data Description](#data-description)
* [Technology](#technology)
* [Methodology](#methodology)
* [Results](#results)
* [Conclusion](#conclusion)


# Project Overview
This project focuses on building a machine learning model to classify individuals as Introverts or Extroverts based on their social behavior and personality traits. Using a rich dataset provided by Kaggle’s July Playground Prediction Competition, I explored various behavioral indicators such as time spent alone, social event attendance, and feelings after socializing.

The goal was to leverage supervised learning techniques to accurately predict personality types, providing insights into how quantifiable social behavior can reflect underlying personality traits.

This work highlights the intersection of psychology and data science, demonstrating how machine learning can assist in understanding complex human characteristics.

# Motivation
* Behavioral Insight through Data Science: Can machine learning identify personality traits based on observable behavior?
* Psychometric & Personality Research: Helps validate or challenge existing psychological theories and bridges psychology and data science to find empirical patterns in personality assessments.

# Data Description
Source: [https://www.kaggle.com/competitions/playground-series-s5e7/data](https://www.kaggle.com/competitions/playground-series-s5e7/data)

Size: 18.5K records and 8 features

* Time_spent_Alone: Hours spent alone daily (0–11).
* Stage_fear: Presence of stage fright (Yes/No).
* Social_event_attendance: Frequency of social events (0–10).
* Going_outside: Frequency of going outside (0–7).
* Drained_after_socializing: Feeling drained after socializing (Yes/No).
* Friends_circle_size: Number of close friends (0–15).
* Post_frequency: Social media post frequency (0–10).
* Personality: Target variable (Extrovert/Introvert).

# Technology
* **Programming Language**: Python 3.10
* **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, xgboost
* **ML Models**: Logistic Regression, Random Forest, SVM, XGBoost, Ensemble models
* **Tools**: Jupyter Notebook
* **Environment**: Google Colab Virtual Environment 
* **Platform**: GitHub

# Methodology
* **Data Collection**: Gathered data from Kaggle 
* **Data Cleaning**: ~9K missing values
* **Exploratory Data Analysis (EDA)**: Analyzed data distributions, correlations.
* **Feature Engineering**: Encoded the categorical features, normalized the data.
* **Model Selection**: Developed Logistic Regression, Random Forest, SVM and XGBoost.
* **Model Tuning**: Used GridSearchCV for hyperparameter optimization.
* **Evaluation**: Primary evaluation criteria is Accuracy. Also evaluated on the basis of precision and recall.

# Results
By analyzing behavioral and survey-based features, multiple classification models were developed and evaluated, including Logistic Regression, Random Forest, SVM, and Gradient Boosting approaches. The final ensemble model achieved an accuracy score of 0.9686 on the test set, indicating a strong ability to predict introverts from the extroverts. 

Key evaluation metrics for the selected model are as follows:
* **Accuracy on Public Leaderboard**: 0.9748
* **Accuracy on Private Leaderboard**: 0.9686

# Conclusion
This project aimed to distinguish between introverts and extroverts using supervised machine learning techniques. 
The final results demonstrated that social personality traits can be predicted with reasonable accuracy based on structured data, highlighting the potential of data-driven approaches in personality assessment. 
Future work could involve expanding the dataset, incorporating text or social media features, or exploring personality dimensions beyond the introvert-extrovert spectrum. 
Future improvements could involve further tuning of hyperparameters, exploring additional features, and increasing the score using a deep learning model.

