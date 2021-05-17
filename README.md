# Diabetes-Prediction-ML-project

##  Team Members:
1. Abhishk Waghmare D12C 66
2. Baldev Sundarani D12C 62
3. Hitesh Santani D12C 57

# Project Description

## Problem Statement
In this project, the objective is to predict whether the person has Diabetes or not based on various features like Glucose level, Insulin, Age, BMI.
During Model evaluation, we compare various machine learning algorithms on the basis of accuracy_score metric and find the best one.

## Motivation
Diabetes is an increasingly growing health issue due to our inactive lifestyle. If it is detected in time then through proper medical treatment, adverse effects can be prevented. To help in early detection, technology can be used very reliably and efficiently. Using machine learning we have built a predictive model that can predict whether the patient is diabetes positive or not.

## Dataset Used
The data set that has used in this project has taken from the **kaggle** . "This dataset is originally from the **National Institute of Diabetes and Digestive and Kidney Diseases**. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage."
        
## Software/Tools Used
* Jupyter Notebook
   
## Libraries Used
* Numpy
* Pandas
* Scikit-learn
* matplotlib
* seaborn

# Steps followed in the project
1. Descriptive Analysis
2. Data Visualizations
3. Data Preprocessing
4. Data Modelling
5. Model Evaluation
6. Prediction

# Algorithms Implemented
## 1. Naive Baye's algorithm
Naive Bayes is a classification algorithm, which uses Bayes theorem of probability for prediction of unknown class. It uses probability to decide which class a test point belongs to. Naive Bayes is a purely statistical model.

## 2. Random Forest algorithm
Random Forest algorithms are often used for each classification and regression tasks and also it is a type of ensemble learning method. The accuracy level is greater when compared to other algorithms. The proposed model gives the best results for diabetic prediction and the result showed that the prediction system is capable of predicting the diabetes disease effectively, efficiently and most importantly, instantly.

## 3. Logistic Regression algorithm
Logistic Regression is a classification method based on Linear Regression. Logistic Regression should be used for classification not for regression. The target variable can be a binary class or multi-class.Logistic regression is used in the description and analysis of data in order to explain the relationship between one dependent binary variable and one or more independent variables.

# Result and Accuracy
Algorithm | Accuracy
---------- | -----------
Naive Bayes | 75.8
Random Forest | 98.8
Logistic Regression | 77.4

# Conclusion
Among the the Implemented algorithms Random Forest is the most accurate algorith with Accuracy of 98.8%.With Random Forest algorithm we can predict diabetes more effectively and efficiently.

# Future Scope
We can use more different algorithms in the future to increase the accuracy of our model.End to End system can be created for our model using flask/django framework and can be deloyed on Heroku platform.
