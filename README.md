Overview:

This project analyzes and predicts bank customer churn using Python (Machine Learning) and visualizes the results through an interactive Power BI dashboard.
It helps identify at-risk customers and provides insights to improve customer retention strategies.

Project Components:
File	Description
churn.csv	Original dataset containing customer demographics and banking details.
bank_churn_model.ipynb / .py	Python implementation for churn prediction using Random Forest Classifier. Includes preprocessing, training, and probability scoring.
Bank_Churn_PowerBI.pbix	Power BI dashboard visualizing churn rate, high-risk segments, and regional insights.
feature_importance.csv (optional)	Feature importance data exported from the machine learning model.
Tools & Technologies
Purpose	Tool
Data Processing & Modeling	Python (Pandas, Scikit-learn, NumPy)
Visualization & Dashboard	Power BI
IDE / Notebook	Jupyter Notebook
Dataset	Bank Customer Churn (Kaggle)
References:


Dataset Source: Kaggle - Bank Churn Modelling Dataset

Python Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

Visualization Tool: Microsoft Power BI

Machine Learning Model: Random Forest Classifier

Author: thanjaidharani 

Outputs:

churn_scored.csv → Predicted churn probabilities (Churn_Prob) generated from Python.

Power BI Dashboard → Displays Churn Rate, Average Probability, High-Risk Customers, and Key Demographics.

Reference Workflow

Data Preparation: Clean and preprocess data in Python.

Model Training: Train a churn prediction model and generate churn probabilities.

Data Export: Save model output to CSV for Power BI.

Power BI Integration: Import scored dataset → Create measures → Design dashboard layout.

Credits:

Project Developed by Thanjaidharani M

Analysis and Visualization with Python & Power BI

Academic / Reference Use Only