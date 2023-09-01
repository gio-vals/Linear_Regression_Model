# Linear Regression Project

This project involves the analysis of data from a fictional Ecommerce company specializing in clothing sales. The company offers in-store style consultations and operates online through a mobile app and website. The primary goal is to assist the company in determining whether to prioritize improving their mobile app or website based on customer data.

## Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Overview

1. Importing Libraries: Import necessary libraries for data analysis and visualization.

2. Data Loading and Inspection: Load the dataset using pandas and inspect its basic properties such as column names, data types, and missing values.

3. Exploratory Data Analysis (EDA): Perform EDA to understand the relationships between various features and the target variable, "Yearly Amount Spent." EDA includes data visualization using scatter plots, joint plots, and pair plots.

4. Linear Regression Model: Train a linear regression model to predict "Yearly Amount Spent" based on selected features. Split the data into training and testing sets using scikit-learn.

5. Model Training: Train the linear regression model on the training data using scikit-learn's LinearRegression class.

6. Model Evaluation: Evaluate the model's performance by calculating various metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the explained variance score (R^2).

7. Residuals Analysis: Analyze the residuals to ensure they are normally distributed, indicating the model's goodness of fit.

8. Conclusion: Summarize the findings and provide insights. The analysis suggests that the mobile app performs better than the website, but the decision to prioritize one over the other depends on the company's strategy.

## Getting Started
Follow these steps:

1. Clone the Repository: Clone this GitHub repository to your local machine.

2. Install Dependencies: Ensure you have the required Python libraries installed. You can install them using the following command:

``````
pip install pandas numpy matplotlib seaborn scikit-learn
``````
- For Jupyter notebooks:
``````
!pip install pandas numpy matplotlib seaborn scikit-learn
``````
3. Data File: Place the provided dataset, named 'Ecommerce Customers,' in the appropriate directory, such as the 'data' folder.

4. Run the Code

## Project Output
The project provides insights into the relationship between customer behavior (such as time spent on the website or app) and the yearly amount spent. It includes visualizations, model training and evaluation, and a conclusion on which one (App or Website) performs better.


