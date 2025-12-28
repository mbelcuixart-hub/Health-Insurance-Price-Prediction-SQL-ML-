# Health-Insurance-Price-Prediction-SQL-ML-
Health Insurance Charges Prediction
Project Overview

This project demonstrates how to explore, analyze, and predict health insurance charges using a combination of SQL for data exploration and Machine Learning (ML) for predictive modeling. The dataset contains personal characteristics of individuals, such as age, sex, BMI, number of children, smoking status, and region, along with their insurance charges.

The main goals of this project are:

Explore the dataset using SQL queries to understand key factors affecting insurance charges.

Visualize important trends and relationships in the data.

Build and evaluate machine learning models to predict insurance costs based on individual characteristics.

Dataset

Source: insurance.csv

Columns:

age: Age of the insured person

sex: Gender (male/female)

bmi: Body Mass Index

children: Number of children/dependents

smoker: Whether the person smokes (yes/no)

region: Residential area

charges: Annual health insurance charges (target variable)

Requirements

Python 3.x

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

sqlite3

Project Structure

Data Loading and Preparation

Load the CSV dataset with pandas.

Create an in-memory SQLite database for SQL queries.

Data Exploration with SQL

Run multiple SQL queries to explore average charges, distributions, and group statistics.

Example queries:

Average charges by smoker status

Average charges by region

Charges greater than a certain value

Categorize BMI

Counts of individuals by sex and smoking status

Data Visualization

Visualize distributions and relationships using matplotlib and seaborn.

Examples:

Histogram of charges

Boxplots comparing smokers vs non-smokers

Scatter plots of BMI vs charges

Machine Learning Modeling

Models used:

Linear Regression

Random Forest Regressor

Train/test split for evaluation.

Metrics:

RMSE (Root Mean Squared Error)

R² score

Results

Random Forest achieved better performance than Linear Regression (RMSE ≈ 4,587, R² ≈ 0.86).

Important factors: smoking status, BMI, and age.

Conclusions

SQL can be used to explore data quickly and generate insights.

Random Forest is recommended for accurate predictions.

This project can help insurance companies set personalized premiums and help customers compare options.

How to Run

Clone the repository.

Ensure insurance.csv is in the working directory.

Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn


Run the notebook or Python script.

Explore SQL queries and ML predictions interactively.

License

This project is open-source and available for educational purposes.
