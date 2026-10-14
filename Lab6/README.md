# Ecommerce Customers - Linear Regression

This is my ARTI308 Lab 6 project. I used Linear Regression to predict how much a customer spends in a year (`Yearly Amount Spent`).

## What I did
1. Loaded and explored the data (500 customers, no missing values).
2. Removed the text columns (Email, Address, Avatar).
3. Split the data into 60% training and 40% testing.
4. Trained a Linear Regression model and tested it.

## Results
- R² = 0.9855
- MAE = 7.74
- RMSE = 9.69

The model is very good. Length of Membership and Time on App have the biggest effect on spending, and Time on Website has almost no effect.

## How to run
Open the notebook in Google Colab, upload `Ecommerce_Customers.csv`, then click Runtime > Run all.
