# Advanced EDA & Feature Engineering

## Project Overview

This project focuses on transforming raw customer data into a clean and machine-learning-ready dataset through advanced exploratory data analysis (EDA) and feature engineering techniques. The objective is to improve data quality by handling missing values, treating outliers, and creating meaningful new features.

## Dataset

Customer Personality Analysis Dataset (marketing_campaign.csv)

## Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle missing values using statistical imputation
* Detect and treat outliers using the IQR method
* Create new predictive features
* Generate a clean dataset for future machine learning applications

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Feature Engineering

The following new features were created:

1. Age
2. Total_Children
3. Total_Spending
4. Total_Purchases
5. Income_Per_Child

## Data Cleaning Techniques

### Missing Value Treatment

* Median Imputation applied on Income column.

### Outlier Treatment

* Interquartile Range (IQR) method used.
* Extreme values capped using Winsorization.

## Visualizations

* Income Distribution
* Spending Distribution
* Income vs Total Spending Scatter Plot
* Correlation Heatmap
* Boxplots for Outlier Detection

## Key Insights

* Customers with higher income tend to spend more.
* Wine purchases contribute significantly to total spending.
* Purchase frequency strongly correlates with customer spending.
* Families with fewer children generally spend more on products.

## Project Structure

├── marketing_campaign.csv
├── cleaned_marketing_campaign.csv
├── Project1_EDA_Feature_Engineering.ipynb
├── README.md

## How to Run

1. Install required libraries

pip install pandas numpy matplotlib seaborn

2. Run the Python notebook or script

python project1.py

## Outcome

A cleaned and feature-engineered dataset ready for machine learning model development.
