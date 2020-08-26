# Telecom-Churn-Classification-Problem
This repository utlizes Machine Learning to classify whether a telecom customer based on certain factors is likely to Churn for some another company or not.

Telecommunication companies face a problem of their customers churning for other companies.  The role of churn prediction system is not only restricted to accurately predict
churners but also to interpret customer churn behavior. In this dataset,we look at different scenarios in which customers are most likely to leave their current company. Firstly,
we will do some exploratory analysis and then I will perform Classification algorithms on the data to find out which model performs the best to classify the customers correctly. 

This dataset contains 51047 rows and 58 columns, here I'll be working on a subset of this data with 5000 rows. 

URL :  https://www.kaggle.com/jpacse/datasets-for-churn-telecom

First we deal with missing values and convert categorical columns into nominal columns. Then we find out whether the dataset is balanced or not with respect to the target column.
Since, the dataset is imbalanced, F1 Score would be a better metric to test the performance of the models. 

Here I have tuned the hyperparameters using the best parameters I got using Grid Search and Cross Validation.
