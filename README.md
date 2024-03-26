#Credit Card Fraud Detection Model
This repository contains a logistic regression model implemented in Python to predict credit card fraud transactions. The model is designed to identify fraudulent transactions based on historical data, helping financial institutions detect and prevent fraudulent activities.

Key Features
Data Preprocessing: The dataset is preprocessed to handle missing values, scale numerical features, and encode categorical variables.
Model Training: The logistic regression algorithm is trained on a comprehensive dataset containing labeled transactions (fraudulent or legitimate).
Performance Evaluation: The model's performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score.
Results Analysis: Insights are provided on the model's performance, including important features contributing to fraud detection.

Requirements
Python 3.x
NumPy
pandas
scikit-learn
Matplotlib
Jupyter Notebook (optional)

About the Dataset used : 
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation.
Get the dataset here : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Clone the repository:
git clone https://github.com/SurajS0925/credit-card-fraud-detection.git
