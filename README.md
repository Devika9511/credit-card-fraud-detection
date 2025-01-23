# credit-card-fraud-detection
This project is aimed at detecting fraudulent credit card transactions using machine learning models, developed and executed in Google Colab. The objective is to build an efficient predictive model to identify fraudulent transactions.

Project Overview
Credit card fraud detection is essential to minimize financial losses. This project analyzes a dataset of credit card transactions to distinguish between legitimate and fraudulent transactions using machine learning techniques.

Dataset

The dataset is anonymized credit card transaction data with several features, such as transaction time, amount, and more. The target variable is a binary variable that indicates whether the transaction is fraudulent (1) or not (0).

Methodology

Data Preprocessing: Handled missing values, scaled features, and balanced the dataset using techniques such as SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance.

Exploratory Data Analysis (EDA): Explored feature correlations, data distribution, and visualized key patterns in the data.

Model Development: Built and evaluated models such as logistic regression, decision trees, random forests, and gradient boosting.

Model Evaluation: Used metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to evaluate the performance of the model.

This project depends on the following project dependencies:
Python 3.x
Google Colab
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn

Results
The model was able to achieve good accuracy in detecting fraud transactions, hence balancing precision with recall to lower false positives and false negatives.
