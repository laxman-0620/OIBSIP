# Predicting House Prices with Linear Regression

## Objective
Build and evaluate a linear regression model that predicts house prices based on area, location,
number of rooms, and age — covering the full pipeline from data cleaning through to model
interpretation.

## Tech Stack
Python, pandas, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## What this covers
- EDA: null check, descriptive statistics, price distribution
- Feature selection reasoning (markdown discussion)
- Missing value handling and One-Hot Encoding of categorical features
- Correlation heatmap
- 80/20 train/test split
- Linear Regression model training
- Evaluation: MSE, RMSE, R² score
- Actual vs. predicted scatter plot
- Residual plot
- Coefficient analysis
- Bonus: Ridge and Lasso regularised model comparison

## How to run
1. `pip install -r requirements.txt`
2. Open `House_Price_Prediction.ipynb` in VS Code or Jupyter
3. Select a Python 3.9+ kernel
4. Run all cells

If you have a real dataset (e.g. Ames Housing from Kaggle), place it at `data/housing.csv` and
re-run — the notebook will use it automatically instead of the generated sample. Real column names
will likely differ, so minor adjustments to feature names may be needed.

## Outputs
- `outputs/price_distribution.png`
- `outputs/correlation_heatmap.png`
- `outputs/actual_vs_predicted.png`
- `outputs/residual_plot.png`
- `outputs/coefficient_analysis.png`
