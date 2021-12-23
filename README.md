# Binary_classification
Exploring a binary classifier using machine learning. 

# Dependencies
Python >=3.7

pandas ==1.3.5

seaborn ==0.11.2

numpy ==1.21.5

matplotlib ==3.5.1

sklearn >=1.0

# Dataset
train.csv:     used for training and validation in the ratio of 4:1 (3910 records, 57 features, 1 output) 

test.csv:      used for testing purposes ((without Ground Truth) - 691 records, 57 features)

# Generic Approach
Data preprocessing, Feature Selection using Chi2, and machine learning model - Radom Classifier is used.

# Summary of validation performance

Accuracy : 95.50%

Confusion matrix:[[578  16]  [ 28 356]]

We can derive other metrics such as sensitivity, specificity, F1-score from confusion matrix.

# Contents of this repository

Readme file - description of the project and way to use it.

train.csv and test.csv files - datasets

bin_classify.ipynb - A reproducible code that has all details 

A short pictorial reporesentation of methodology followed and the snapshot of binary classification metrics obtained from the validation set is also included in the ipynb file. Use the line "predictions = model.predict(X_test_fs), print(predictions) " to obtain the predictions. Note that the trained model is not saved. To reproduce the results, first train the model using Radom Forest Classifier and then perform testing. 
