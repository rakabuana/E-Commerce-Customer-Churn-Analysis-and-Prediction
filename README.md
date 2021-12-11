# E-Commerce Customer Churn Analysis and Prediction with Logistic Regression

This Repository Contains:
- Dataset
- Source Code

Original Data Source: https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

# Background
In every business, in this case e-commerce, getting customers and keeping them is the goal of the company, therefore, it is very important to prevent customers who no longer want to use our e-commerce (churn), in prevention, companies can provide coupons discount to attract the customer's interest to keep using our e-commerce.

# Problem Identification
## 1. Problem Definition
In e-commerce, having many customers is one of the targets in achieving business, therefore, it is very unfortunate if there are customers who do not use our e-commerce anymore (churn), and then, the company must find ways to retain customers who will do churn, and most importantly, the target customers who will churn must be right.

## 2. Business Objectives
to be achieved is to get a prediction system that can be used to find out which customers will churn and the factors that occur.

## 3. Data Requirement
We want to predict which customers will churn and find out what influences customers to churn based on the features in our dataset (e.g., complaints, tenure, PreferredLoginDevice, PreferredPaymentMode, CityTier, etc.) to make predictions.

## 4. Analytic Approach
### a. Machine Learning Techniques
The machine learning approach that is applied this time is supervised learning in the form of classification problems. The system will predict a predetermined label (churn).

### b. Risk
risk of incorrectly predicting which customers will churn and which will not:

- marketing budget loss
When the marketing team gives promo coupons to customers who are predicted to churn, but it turns out that the customers we predict will not churn, then the money spent to give promo coupons to customers who will not churn will be wasted.

- future business income loss
when we correctly predict customers who will churn, then we can maintain future business income.
when we wrongly predict customers who will churn, then we will lose future business income.

#### Performance Measure
The performance measures used to evaluate the ML model are recall and accuracy score

## 5. Action
business users can use the prediction results to further improve service to customers, and provide promo coupons for customers who will churn so that we don't lose income

## 6. Value
This project will maintain income and avoid losing customers, because now business users can give promo coupons only to customers who are predicted to churn. it can also keep customers using the e-commerce.

# Data Understanding and Data Preparation
We import the dataset, created new features, and we created EDA, handling missing value with median, and choosing relevant features to be used for modelling

# Modeling
We use Logistic Regression for this model because this model is one of the models that we are familiar with, and we did hyperparameter tuning on this model, and we got good accuracy results.

# Evaluation
We have got 80% for recall score, accuracy for test set is 80%, and in confusion matrix, we've got 152 for True Positive, 38 for True Negative, 753 for False Positive, and 183 for False Negative
