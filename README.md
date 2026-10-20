Comparison of regression models for Premier League player goal totals using Python, scikit-learn, and five-fold cross-validation.
# Premier League Goal Scoring: A Comparison of Regression Models

## Overview
This project compares regression methods for estimating recorded
Premier League player goal totals using age, playing position,
and shots on target.

The aim is to practise preprocessing, exploratory data analysis,
cross-validation, and interpretation of model performance.

## Dataset
- Source: https://www.kaggle.com/code/desalegngeb/english-premier-league-players-statistics/notebook
- File used: dataset - 2020-09-24.csv
- Target variable: Goals
- Features: Age, Position, Shots on target

## Methods
- Exploratory data analysis and visualisation
- Missing-value imputation and categorical encoding
- Five-fold cross-validation
- Mean-prediction baseline
- Linear Regression, Ridge, Lasso, Random Forest,
  and Gradient Boosting
- Additional bagging comparison

## Evaluation
Models are compared using mean squared error and root mean
squared error. Results should be interpreted as comparisons
within this dataset and feature set.

## How to run
1. Download the dataset from the source above.
2. Open premier_league_regression.ipynb in Google Colab.
3. Run the cells in order.
4. Upload the CSV when prompted.

## Limitations
- The analysis estimates recorded goal totals, not future goals.
- Shots on target is closely related to the outcome.
- Missing data and the limited feature set affect interpretation.
- Model comparisons do not establish causal relationships.
- Small differences in average error do not necessarily imply
  a reliable performance advantage.

## Tools
Python, pandas, NumPy, matplotlib, scikit-learn, SciPy,
and Google Colab.
