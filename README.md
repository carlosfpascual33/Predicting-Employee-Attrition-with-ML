# Predicting-Employee-Attrition-with-ML
Application of Machine Learning Algorithm to predict employee attrition (binary variable indicating if an employee leaves the company unexpectedly, generally related to burnout).

Preprocessing and models were combined through pipelines, and several models were compared to check for the best performace in a cross validation environment, namely KNN classifier and Tree classifier models. Hyperparameters optimization (HPO) was performed for each of them on the train data before comparing the models. Also, different preprocessings of the data were applied, namely Min-Max Scaling and Standard Scaling. A dummy classifier was also implemented to compare against a baseline.

The main library used for the project is sklearn.
