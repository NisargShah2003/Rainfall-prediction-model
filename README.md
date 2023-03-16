# Rainfall-prediction-model

Introduction:
It is a classification model which gives the output as wether there will be rain tomorrow or not. 
For this I am going to use XGBoost, Logistic Regression, Decision Tree Classifier, Random Forest, CatBoost models.
The dataset taken is weather data from AUS. 
As we know that the rainfall prediction is more imnportant in october to April in Austrelia.So, We are going to focus on this data only.

Data preprocessing:
The classes containing true and False are imbalanced so resample method is used here.
Outliers are removed from the dataset using IQR method.
We have many missing values and datatypes of many columns are different.
To solve this problem,filling values using mode in categorical, median in numerical values is used.
Then Label Encode is used to convert all data into numeric format and then data is standaradized.
For feature selction chi-Square method is used and data is divided into training and testing dataset.

ML Models used:
EvalML (Auto ML) is used for testing different models and get the basic idea of model we should use to get better results.
Then XGBoost, CatBoost, Logistic Regression, Decision Tree Classifier, Random Forest models are performed on the dataset.
Then comparison of the results obtained from every models with one another and conclusion is given.
