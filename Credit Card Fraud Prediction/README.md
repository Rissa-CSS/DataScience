# Credit Card Fraud Prediction

## Description

**Skill(s): Machine Learning**

This project leverages a pre-processed dataset, where features have been transformed and reduced to numerical values through Principal Component Analysis (PCA). The objective is to analyze transactional data and assess the likelihood of fraud. Various machine learning models are applied, including Logistic Regression, Linear Discriminant Analysis (LDA), and Gaussian Naive Bayes, to evaluate and compare their effectiveness in identifying potentially fraudulent transactions. The use of PCA enhances model performance by reducing dimensionality, helping to focus on the most important features for fraud detection.


## Dataset

This [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) was obtained from Kaggle.

### Attributes
- Time (float): PCA transformation of time of transaction.
- V1 - V28 (float): PCA transformation of banking features
- Amount (float): PCA transformation og transaction amount.
- Class (integer): 1 or 0 determining if the transaction is fraudulent or not.
