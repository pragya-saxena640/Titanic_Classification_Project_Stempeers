# Titanic_Classification_Project
Class: Summer Machine Learning Class 2025 (STEMPEERS)
Instructor: Bhishan Poudel
Programmer: Pragya Saxena
Date: 2025-08-05

# Project Info
- In my project, I built 3 models, which were logistic regression, decision tree, and random forest
- I uttilized the sci-kit learn classifier for the titanic data classification
- We have used the module Pandas for data analysis
- The goal for this project was to determine if the ML model I built
  can accuratlty predict whether the passnegers would surive or not
  
# Data preparation
* I used relevant data in the csv file, which were the columns pclass, sex, age, fare, sibsp, parch
* I dropped andy rows that had missing data
* The categorical column ‘Sex’ was converted into numerical values: male as 0 and female as 1.

# Accuracy and analysis
* All 3 models were fairly accurate, with its accuracy score being around 74%-78%
* I used an confusion matrix for the logistic regression

# Improvement
* Although all the models were pretty accurate, all of their accuracy scores were around the same, so I can improve it by adding feature engineering which is selecting, creating, and transforming features to better the models accuracy
* Instead of dropping the rows that had missing data, I could've filled it with the median age
* I could've used feature scaling, which improves convergence and performance in logistic regression
