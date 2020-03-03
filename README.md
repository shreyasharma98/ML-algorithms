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

# Theory

In machine learning, support-vector machines (SVMs, also support-vector networks[1]) are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis. Given a set of training examples, each marked as belonging to one or the other of two categories, an SVM training algorithm builds a model that assigns new examples to one category or the other, making it a non-probabilistic binary linear classifier (although methods such as Platt scaling exist to use SVM in a probabilistic classification setting). An SVM model is a representation of the examples as points in space, mapped so that the examples of the separate categories are divided by a clear gap that is as wide as possible. New examples are then mapped into that same space and predicted to belong to a category based on the side of the gap on which they fall.
