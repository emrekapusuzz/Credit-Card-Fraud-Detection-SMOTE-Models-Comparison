
# Credit Card Fraud Detection-SMOTE-Models Comparison

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fensarbayhan.medium.com%2Fmakina-%25C3%25B6%25C4%259Frenmesi-y%25C3%25B6ntemleri-ile-kredi-kart%25C4%25B1-doland%25C4%25B1r%25C4%25B1c%25C4%25B1l%25C4%25B1%25C4%259F%25C4%25B1-tespiti-34e7e0149ec6&psig=AOvVaw2VwrejHyHEwwxFVC8xkklI&ust=1643365288571000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCNjt8Kfo0fUCFQAAAAAdAAAAABAD)


## Introduction

Credit card fraud is an inclusive term for fraud committed using a payment card, such as a credit card or debit card. The purpose may be to obtain goods or services, or to make payment to another account which is controlled by a criminal. The Payment Card Industry Data Security Standard (PCI DSS) is the data security standard created to help businesses process card payments securely and reduce card fraud.

Credit card fraud can be authorised, where the genuine customer themselves processes a payment to another account which is controlled by a criminal, or unauthorised, where the account holder does not provide authorisation for the payment to proceed and the transaction is carried out by a third party. In 2018, unauthorised financial fraud losses across payment cards and remote banking totalled £844.8 million in the United Kingdom. Whereas banks and card companies prevented £1.66 billion in unauthorised fraud in 2018. That is the equivalent to £2 in every £3 of attempted fraud being stopped. (Wiki)

## About

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## About the Repository

This repository includes my analysis on Credit Card Fraud Detection dataset. The repository includes one notebook;

* Data cleaning, Exploratory data analysis, Feature engineering and selection, Visualizations
* Comparison of different machine learning models and Hyperparameter tuning on models I choose

## Dataset

Dataset taken from kaggle [link](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Thank you for your time.



  
