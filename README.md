# Python-Regression-linear-and-multy-linear-

## Project Overview
This repository contains Python Jupyter Notebooks demonstrating regression models, specifically Simple Linear Regression and Multiple Linear Regression. It demonstrates how to prepare data, train models, and make predictions on real-world datasets such as employee salaries and startup profits.

## Tech Stack
- **Programming Language**: Python 3
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-Learn (sklearn)
- **Environment**: Jupyter Notebook

## Key Implementation Details
- **Simple Linear Regression (`linear regression .ipynb`)**:
  - Uses `Salary_Data.csv` to model the linear relationship between years of experience (independent variable) and salary (dependent variable).
  - Trains a Scikit-Learn `LinearRegression` model and visualizes the best-fit line over training/test data points.
- **Multiple Linear Regression (`Multi linear regression.ipynb`)**:
  - Uses `50_Startups.csv` to predict company profit based on R&D Spend, Administration, Marketing Spend, and State.
  - Implements one-hot encoding for categorical variables (State column) and trains a multi-variable linear regression model.
