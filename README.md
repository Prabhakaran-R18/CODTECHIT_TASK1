# CODTECHIT_TASK1

## Name: Prabhakaran R

## Domain: Machine Learning

## Intern ID : CT08ETY

## Company: CODTECHIT SOLUTIONS

## Project: Linear Regression on Housing Prices

## Project Overview:

## Objective:
The goal of the project is to build a predictive model using Linear Regression to estimate housing prices based on various influential factors. This project demonstrates the application of machine learning in solving real-world regression problems, specifically in the housing market.

## Dataset:

## dataset link : [housing.csv](https://github.com/user-attachments/files/18254708/housing.csv)


The dataset used contains housing-related features such as:
RM: Average number of rooms per dwelling.
LSTAT: Percentage of lower status of the population.
MEDV: Median value of owner-occupied homes (target variable).
PTRATIO: Pupil-teacher ratio by town.

These features were chosen to predict the MEDV, which represents the median house prices.

## Key Steps:

## Data Loading and Exploration:

The dataset is loaded using Pandas, and its structure is analyzed using .info() to understand the column details and data types.

## Feature Selection:

Selected the features RM, LSTAT, and PTRATIO as input variables and the MEDV column as the target variable.

## Data Splitting:

Split the dataset into training and testing subsets using train_test_split, with 75% of the data for training and 25% for testing. A random state of 6 ensures reproducibility.

## Model Training:

Used the LinearRegression model from sklearn to fit the training data, learning the relationship between the selected features and the target variable.

## Prediction:

Generated predictions on the test dataset using the trained model.

## Accuracy Evaluation:

Used the accuracy_score metric to evaluate the model's performance. Predictions and actual values were rounded to integers to ensure compatibility with the accuracy metric.

## Challenges and Learnings:

This project showcased how Linear Regression can be applied to solve regression problems in real-world scenarios.
Challenges included selecting the right features and ensuring the model generalizes well to unseen data.

## Results:

The accuracy score provides a quantitative measure of the model's performance in predicting housing prices.

## Future Improvements:

Explore additional features in the dataset to improve model accuracy.
Experiment with feature scaling and polynomial regression for better results.

## PROJECT RESULTS :

![tone1](https://github.com/user-attachments/assets/c7ea4b81-4479-49b9-8ee0-74e7cce5f971)

![tone2](https://github.com/user-attachments/assets/ebc5f1c2-f0cc-45ef-ada9-247941a61007)

![tone3](https://github.com/user-attachments/assets/136aa187-45f5-4e60-9f20-633a41e0b024)

![tone4](https://github.com/user-attachments/assets/9ebfe3f9-d1af-4029-a37f-6e53ab32500c)

![tone5](https://github.com/user-attachments/assets/288d6497-5646-4d98-b608-b74a39f108ef)





Consider other regression models like Ridge Regression or Random Forest Regressor for comparison.
