# Credit_card_default_Classification

# Problem Description
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments

# **Steps Performed In This ML(Supervised) Project**
---

Handling dataset with the fundamental steps to unvail the factors :

* Importing Libraries And Loading The Datasets
* Overview Of The Datasets 
    *   Reading & Inspection Of First Dataset
    *   Reading & Inspection Of Second Dataset
    *   Merging both the datasets
    *   Further analysing both the datasets
* Data Wrangling And Processing
    *   Converting Dtype Of Feature
    *   Extracting Date
    *   Combining And Creating Columns
    *   Null Value Treatment
    *   Handling Outliers
* Exploratory Data Analysis
* Key Findings From EDA
* Feature Engineering 
    *   Feature Selection
    *   Multicollinearity
    *   Dependent Variable Transformation
    *   Scaling Numberical Features
    *   Dummification
* ML Model
    *   Train-Test Split
    *   Model Training And Prediction
  * Linear Regression
  * Lasso Regression
  * Ridge Regression
  * Decision Tree Regression
  * Random Forest Regression
  * Gradient Boosting Regression
  * XGboost Regression
    * Feature Importance
* HyperParameter Tuning
* Feature Importance of Best performing Model
* Cross Validating for Hyperparameter Tuned Best Performing model
* Key Findings from Machine Learning
* Conclusions 

# Conclusions 
In our dataset, We used many algorithm like Logistic Regression,Support vector classsifier,decision tree classifier,XGBoost Classifier,Random Forest Classifier.Random Forest was the best performing algorithm as shown below
1. Random Forest Classifier has the best value of accuracy score of 84%
2. Random Forest Classifier has the best value of precision score of 84%
3. Random Forest Classifier has the best value of recall score of 83%
4. Random Forest Classifier has the best value of f1 score of 84%
5. Random Forest Classifier has the best value of Roc_auc score of 84%
6. Random Forest Classifier had average fitting time of 1.67 according to cross validate method of sklearn This proves Random Forest Classifier algorithm has perfectly fitted all the dataset.
