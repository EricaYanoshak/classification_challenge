# Classification Challenge
Creating two classification models to fit the provided data, and evaluate which model, logistic regression or random forest, is more accurate at detecting spam. 

## Installation
The following libraries and dependencies were used to successfully run this project:
- import pandas as pd
- from sklearn.model_selection import train_test_split
- from sklearn.metrics import accuracy_score
- from sklearn.preprocessing import StandardScaler
- from sklearn.linear_model import LogisticRegression
- from sklearn.ensemble import RandomForestClassifier
  
## Description
Tasked with improving the email filtering system for an Internet Service Providers' customers. After being provided with a dataset that contains information about emails, with two possible classifications: spam and not spam, the goal is to take the dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails and filter them out of customers' inboxes. This is completed by creating two classification models, logistic regression and random forest, to fit the provided data, and evaluate which model is more accurate at detecting spam.

## Methodology
1. Split the data into training and testing sets
2. Scale the features
3. Create a logistic regression model
4. Create a random forest model
5. Evaluate the models

## Results
Both models performed very well although the **Random Forest Classifier Model**, with a testing accuracy score of **97%**, outperformed the **Logistic Regression Model’s** testing accuracy score of **93%**.

## References Used
To complete this project, I relied heavily on class notes and activities provided during week 11, 12 and 13.