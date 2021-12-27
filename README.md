# Supervised Machine Learning Homework - Predicting Credit Risk

A machine learning model is to be  built that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

This data is used to create machine learning models to classify the risk level of given loans. Specifically, the Logistic Regression model and Random Forest Classifier is compared on this dataset.



### Retrieve the data

An entire year's worth of data (2019) is used to predict the credit risk of loans from the first quarter of the next year (2020).

Note: these two CSVs have been undersampled to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk. To get a truly accurate model, special techniques need to be used on imbalanced data. Undersampling is one of those techniques. Oversampling and SMOTE (Synthetic Minority Over-sampling Technique) are other techniques that are also used.

## Following steps are followed:

#### Preprocessing: Convert categorical data to numeric

#### Fit a LogisticRegression model and RandomForestClassifier model

#### Revisit the Preprocessing: Scale the data

