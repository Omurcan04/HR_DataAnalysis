# HR Data Analysis Project

This project aims to analyze HR data to understand employee turnover and identify factors influencing employee satisfaction and retention. The dataset used in this project contains various features such as satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotion status, department, and salary level.

## Dataset

The dataset used in this project is stored in the `HR_capstone_dataset.csv` file. It contains information about employees' attributes and whether they left the company or not. Here are the details of the columns:

- `satisfaction_level`: Employee satisfaction level (numeric)
- `last_evaluation`: Last evaluation score (numeric)
- `number_project`: Number of projects completed (numeric)
- `average_monthly_hours`: Average monthly hours worked (numeric)
- `time_spend_company`: Time spent at the company in years (numeric)
- `Work_accident`: Whether the employee had a work accident (binary: 0 for No, 1 for Yes)
- `left`: Whether the employee left the company (binary: 0 for No, 1 for Yes)
- `promotion_last_5years`: Whether the employee was promoted in the last 5 years (binary: 0 for No, 1 for Yes)
- `Department`: Department in which the employee works (categorical: sales, accounting, hr, technical, support, management, IT, product_mng, marketing, RandD)
- `salary`: Salary level of the employee (categorical: low, medium, high)

## Analysis Steps

1. **Data Loading and Inspection**: Load the dataset and inspect its structure, check for missing values, and perform basic exploratory data analysis.
2. **Data Cleaning**: Handle any missing values, outliers, or inconsistencies in the data.
3. **Data Visualization**: Visualize the distributions and relationships between different features using libraries such as Pandas, Matplotlib, Seaborn.
4. **Model Building**: Build predictive models to understand factors influencing employee turnover and satisfaction using libraries such as scikit-learn. Evaluate model performance using techniques like cross-validation.
5. **Model Evaluation**: Evaluate model performance and interpret the results to draw actionable insights for HR management.

## Files Included

- `HR_capstone_dataset.csv`: The dataset file containing HR data.
- `HR_Analysis.ipynb`: Jupyter Notebook containing the Python code for data analysis and model building.
- `README.md`: This file providing an overview of the project and instructions for running the code.

## Instructions

To run the analysis code in the Jupyter Notebook, you will need Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost (if using XGBoostClassifier)
