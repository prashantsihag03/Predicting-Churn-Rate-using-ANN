# Predicting-Churn-Rate-using-ANN
Determining the churn rate of a bank and predicting which of their customers are at high risk of leaving the bank.

# Dataset 
Data set is completely fictional. 
It includes data of 10000 customers of the bank with 14 attributes.

# Goal
Goal is to determine which customers are at a high risk of leaving the bank.

# dependencies
1. Pandas
2. Tensorflow
3. Keras
4. Scikit-Learn

# Working
First i have looked into the dataset and analysed which of the attributes are affecting the customers.
Attributes like customer id and customer name have zero effect on churn rate.

After performing steps like handling of categorical values and feature scaling,  ANN classifier is instantiated and hidden layers are added to the network. 

Fitting the ANN Model to the training set with batch size = 10 and epoch = 100 .

Finally prediction is performed on test set and an accuracy of 86.25% is achieved.
Accuracy is returned in form of confusion matrix.


