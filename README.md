# ML-algorithms
Implementating  KNN , SVM , Logistic and Decision Tree for classification.

# AIM:
The task is to perform Churn prediction over a telcom data using any classification model and perform some EDA (Exploratory Data Analysis) to display some statistical information from the data to make it more clear and understandable for predictions.

# Dataset: 
https://github.com/imshreyaa/ML-algorithms/blob/master/Churn.csv

# Approach and implementation 
The idea is to apply SVM , KNN , Decision Tree and Logistic Regression for classification of the users on the basis of the features and then print their Accuracy score.
The dataset contains many features i.e. attributes which may or may not responsible for the Prediction , thus by doing EDA on dataset we found the attributes which contributes more.
After applying various preprocessing techniques (Label Encoding, One hot Encoding) on data we found that it has a very large set of attributes  or features that would probably cause underfitting! , Thus To avoid this we applied PCA on the data , Which would Basically reduce the no. of features and cover most of the variation in the dataset.

To find more about it jump into the notebook : https://github.com/imshreyaa/ML-algorithms/blob/master/Telecom.ipynb
