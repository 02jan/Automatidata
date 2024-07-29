# Predicting taxi fares 
**Disclaimer:** This project was part of the Google Advanced Data Analytics Specialisation on Coursera, and was completed with their guidance.

## Overview
The goal of this project was to build a multiple linear regression model to predict taxi fares using existing data that was collected over the course of a year. The project utilized dataset created for pedagogical purposes. The final linear regression model performed with a $R^2$ of 0.87, MAE of 2.13, MSE of 12.66 and RMSE of 3.70.

## Business Understanding
Automatidata works with its clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs. Automatidata is consulting for the New York City Taxi and Limousine Commission (TLC) to develop a linear regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered.

## Data Understanding
This project's dataset was created for pedagogical purposes. It consisted of 22699 rides and 17 features.

## Modeling and Evaluation
A linear regression model with 6 features was used to determine which feature is the most important to predict taxi fares. The below plot shows that mean_duration was the feature with the greatest weight in the model's final prediction. The final linear regression model performed with a $R^2$ of 0.87, MAE of 2.13, MSE of 12.66 and RMSE of 3.70.

![image](https://github.com/user-attachments/assets/fb5bc3db-093c-474d-8767-6122e718c391)

## Conclusion
New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. This model can benefit TLC by quoting reasonable taxi fares for their prospective passengers, allowing them to make a more informed decision whether to ride with them or not.
