**Credit Card Fraud Detection**

**Overview**

This project aims to develop a fraud detection system using machine learning techniques, specifically logistic regression, to identify fraudulent transactions in credit card data. The dataset used for this project is obtained from Kaggle, specifically from the MLG - ULB dataset repository. The dataset contains transactions made by credit cards in September 2013 by European cardholders, and it presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

**Dataset**

The dataset can be accessed from the following link: (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

**Features**

Time: Time elapsed between the transaction and the first transaction in the dataset (in seconds).
V1-V28: Anonymized features obtained using PCA.
Amount: Transaction amount.
Class: Target variable representing whether the transaction is fraudulent (1) or legitimate (0).
Project Structure

creditcard.csv: The dataset file.

**Results**

The logistic regression model achieved an accuracy of 94.53% on the training data and 94.92% on the test data.

**Conclusion**

This project demonstrates the implementation of a fraud detection system using logistic regression. The model shows promising results in identifying fraudulent transactions, which can be further improved and integrated into real-world financial systems to prevent fraudulent activities.
