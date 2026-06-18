# 📈 Linear Regression — Sales Prediction

Predicts sales revenue based on advertising spend using Simple Linear Regression.

## Tech Stack
- Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

## What It Does
- Generates a synthetic ad spend vs. sales dataset
- Trains a Linear Regression model
- Evaluates with MAE, MSE, RMSE, R²
- Plots regression line & residual analysis
- Predicts sales for custom ad spend inputs

## Run It
Open `linear_regression_sales.py` in **Google Colab** and run all cells top to bottom. No installs needed.

## Model Output
```
Equation: Sales = β₀ + β₁ × Advertising_Spend
```
R² ≈ 0.97 — model explains ~97% of variance in sales.

## Project Structure
```
├── linear_regression_sales.py   # Main notebook
├── scatter_ad_vs_sales.png      # EDA scatter plot
├── regression_line.png          # Regression line plot
└── residual_analysis.png        # Residual diagnostics
```
