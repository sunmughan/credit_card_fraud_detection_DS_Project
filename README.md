# Credit Card Fraud Detection
![](https://32gss3htucqd.wpcdn.shift8cdn.com/wp-content/uploads/2020/07/codeair-1.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

This repository contains Credit card fraud detection algorithm using machine learning techniques in python.

**Credit Card Fraud Detection**: With a lot of people, banks and online retailer being a victim of credit card fraud, a model detecting whether the transaction is fraud or not can help in saving a huge amount of money.

**Dataset**: The dataset has been obtained from kaggle. This dataset contains 284807 rows and 30 numeric columns and one class that specifies whether the transaction is fraudulent or not. The values of columns V1-V28 in the dataset may be result of a PCA(Principal Component Analysis) Dimensionality reduction to protect user identities and sensitive information. There are no missing values in the dataset.

**Algorithm**: The algorithm used in this dataset is Random Forest algorithm. For model improvement normalization and SMOTE techniques (to handle imbalanced data) were used.

**Visualisation**: The library used for visualizing the data, confusion matrix etc. is seaborn.
This code is prepared using Jupyter Notebook.

### Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

### Data
The datasets contains transactions made by credit cards in September 2019-2020 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 586 frauds out of 1048576 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

The dataset can be downloaded from the kaggle website which can be found at "https://www.kaggle.com/mlg-ulb/creditcardfraud".

### Inspiration
Identify fraudulent credit card transactions.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

### Acknowledgements
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project
