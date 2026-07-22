# 🏡 House Price Prediction using Machine Learning

## Overview

This project predicts house prices using the Ames Housing dataset using Machine Learning. It demonstrates an end-to-end machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature encoding, model training, model evaluation, and feature importance analysis.

The project compares three regression algorithms to determine the best-performing model for predicting house prices.

## Dataset

- Dataset: Ames Housing Dataset
- Target Variable: SalePrice

## Project Workflow

- Data Loading
- Data Exploration
- Data Cleaning
- Missing Value Handling
- Duplicate Value Checking
- Exploratory Data Analysis (EDA)
- Outlier Detection using IQR
- Feature Encoding using One-Hot Encoding
- Correlation Analysis
- Train-Test Split
- Model Training
- Model Evaluation
- Model Comparison
- Feature Importance Analysis

## Machine Learning Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Key Findings

- House prices are right-skewed with a few expensive outliers.
- Higher-quality houses generally have higher sale prices.
- Ground Living Area and Garage Area show a positive relationship with house prices.
- Random Forest achieved the best predictive performance among the three models.
- Feature importance analysis identified the most influential features affecting house prices.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

House-Price-Prediction/
│
├── data/
│   └── Ames_Housing_Project.csv
├── House_Price_Prediction.ipynb
├── requirements.txt
└── README.md

## How to Run

1. Clone this repository.
2. Install the required libraries using:

   pip install -r requirements.txt

3. Open the Jupyter Notebook.
4. Run all cells to reproduce the analysis and model results.

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Regression Analysis
- Machine Learning
- Model Evaluation
- Model Comparison
- Feature Importance Analysis

## Author

Arth Jain

Aspiring Data Scientist | Python | SQL | Machine Learning | Data Analysis
