# LAB-6
# Ecommerce Customers Analysis

## Overview

In this lab, I applied data analysis and machine learning techniques on the Ecommerce Customers dataset to understand customer behavior and predict yearly spending.

## Dataset

The dataset includes features such as average session length, time spent on the app and website, length of membership, and yearly amount spent.

## Steps Performed

I started by loading the dataset into a DataFrame using pandas. Then, I explored the data using functions like head(), info(), and describe() to understand its structure.

Next, I performed basic data cleaning and focused only on the numerical features needed for analysis. After that, I selected the relevant features and defined the target variable, which is "Yearly Amount Spent".

I split the data into training and testing sets and trained a Linear Regression model on the training data. Finally, I evaluated the model by analyzing the residuals.

## Model

I used a Linear Regression model to predict customer spending based on behavioral features.

## Results

The model performed well, and the residuals were approximately normally distributed around zero, indicating good prediction accuracy.

## Conclusion

The results show that customer behavior, especially the length of membership, has a strong impact on yearly spending.
