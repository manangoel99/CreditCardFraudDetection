# CreditCardFraudDetection
-------------------------------

This is an implmentation of the [Kaggle challenge](https://www.kaggle.com/mlg-ulb/creditcardfraud).
The dataset is obtained from it.

The `Fraud Detection.ipynb` notebook contains analysis of the data in terms of class imbalance as well as correlation of fraud with timestamp and with amount.

Random Forest and Decision Trees are first trained for classification since they are not as prone to overfitting and give high F1 score, precision and recall. Further experiments are done to address the class imbalance by undersampling the negative samples but this proved to make the performance worse.