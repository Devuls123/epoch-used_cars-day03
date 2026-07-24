# epoch-used_cars-day03

# Used Car Price Prediction - EDA, Data Cleaning and Feature Engineering

## Dataset Overview

This project analyzes a Used Car Price Prediction dataset to understand the factors that influence used car prices. The project focuses on Exploratory Data Analysis (EDA), data cleaning, and feature engineering as preparation for future Machine Learning modeling.

## Project Objectives

- Explore the structure of the dataset
- Identify numerical and categorical features
- Analyze missing values and duplicates
- Identify potential outliers
- Clean and preprocess the dataset
- Create meaningful engineered features
- Save the final cleaned dataset for future Machine Learning models

## Data Quality Issues Identified

The following data quality issues were investigated:

- Missing values in selected columns
- Duplicate records
- Inconsistent data types
- Potential outliers in numerical features
- Possible inconsistencies in categorical values

## Data Cleaning Techniques Applied

The following techniques were applied:

- Removed duplicate records
- Handled missing numerical values using median imputation
- Handled missing categorical values using mode imputation
- Corrected inappropriate data types
- Standardized column names
- Investigated and handled potential outliers where necessary

## Feature Engineering

The following features were engineered:

1. **Car Age** – Represents the age of the vehicle.
2. **Mileage per Year** – Measures average annual vehicle usage.
3. **Mileage Category** – Groups vehicles based on mileage.
4. **Age Category** – Groups vehicles according to their age.
5. **Brand** – Extracted the vehicle brand from the car name/model where applicable.

## Five Key Insights

1. Newer vehicles generally have higher resale prices than older vehicles.
2. Higher mileage is generally associated with lower used-car prices.
3. The dataset contains a concentration of vehicles within a specific price range, with some high-priced outliers.
4. Some fuel types are significantly more common than others, indicating differences in market preference.
5. Vehicle characteristics such as age, mileage, fuel type, and transmission can potentially be important features for future price prediction models.

## Files in This Repository

- `task-3.ipynb` – Complete EDA, data cleaning, and feature engineering workflow.
- `cleaned_used_cars.csv` – Final cleaned and feature-engineered dataset.
- `README.md` – Project documentation.

## Future Work

The cleaned dataset can be used to build Machine Learning models for predicting used car prices.
