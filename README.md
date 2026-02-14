Credit Card Fraud Detection – Assignment Report
1. Assignment Overview
This project uses the Credit Card Fraud Detection dataset from Kaggle to build and evaluate machine learning models for identifying fraudulent transactions. The dataset is highly imbalanced, with fraudulent transactions being rare compared to legitimate ones. 
The dataset size is large enough and can not be uploaded in github. 
Objectives:
Preprocess and balance the dataset.
Train multiple machine learning models.
Evaluate models using metrics beyond accuracy (Precision, Recall, F1, MCC, AUC).
Deploy the best-performing model using Streamlit.
Share results and workflow via GitHub.
Observations:
Logistic Regression, Naive Bayes, and Random Forest achieved perfect AUC (1.0), showing excellent discrimination between fraud and non-fraud.
Random Forest slightly outperformed others in Recall (1.0), capturing all fraudulent cases, though Precision dipped slightly (0.99).
All models achieved nearly identical performance, confirming effective preprocessing and feature engineering.
MCC values (~0.99) indicate strong balanced performance across classes.

Visualizing predictions and performance metrics interactively.

This project demonstrates that multiple machine learning models can achieve near-perfect fraud detection when trained on the Kaggle dataset. Random Forest stands out slightly due to its perfect recall, making it a strong candidate for deployment where missing fraudulent cases is unacceptable. The Streamlit app and GitHub repository ensure reproducibility and accessibility for further experimentation.

