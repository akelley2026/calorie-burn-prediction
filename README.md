# Data 300 Final Project – Predicting Calorie Burn

## Overview
This project focuses on predicting the number of calories burned during a workout using a large-scale fitness dataset. By leveraging personal attributes, workout characteristics, and nutritional data, we build a regression model to estimate caloric expenditure for new workout scenarios.

## Dataset
- Source: Kaggle (Smart Fitness & Nutrition Analytics Dataset)
- Observations: 20,000 individuals
- Features: 50+ variables including:
  - Demographics (age, gender, BMI)
  - Workout metrics (duration, heart rate, frequency)
  - Nutritional intake (macros, calories, water intake)

## Objective
The goal of this project is to:
- Predict **Calories Burned** (continuous target variable)
- Identify which factors most influence caloric expenditure
- Evaluate model performance on unseen data

## Methods
- Data cleaning and preprocessing
- Feature engineering (e.g., BMI calculations, macro distributions)
- Exploratory Data Analysis (EDA)
- Regression modeling

## Tools Used
- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn

## Key Insights
- Workout duration and heart rate metrics are strong predictors of calorie burn
- Body composition (BMI, fat percentage) plays a significant role
- Nutritional intake has a measurable but secondary effect compared to workout intensity

## Files
- `FinalProject.ipynb` – Full analysis, EDA, and modeling workflow

## Authors
- Andrew Kelley  
- Zach Deitch  
- Yuquing Wang
