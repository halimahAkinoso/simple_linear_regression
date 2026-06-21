# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview
This project evaluates a Simple Linear Regression model using Ordinary Least Squares (OLS) to examine how TV advertising spend influences Sales.

The notebook covers:
- data loading and inspection
- missing value handling
- descriptive statistics
- visual exploration using histograms, pairplots, and scatterplots
- OLS model building
- assumption checking using residual and Q-Q plots
- interpretation of R-squared, coefficients, and p-values
- a business recommendation for marketing budget allocation

## Dataset
The dataset used in this project contains:
- `TV`
- `Radio`
- `Social_Media`
- `Sales`

For the simple linear regression model:
- predictor variable: `TV`
- target variable: `Sales`

## Files Included
- `simple_linear_regression_evaluation.ipynb`
- `marketing_and_sales_data_evaluate_lr.csv`

## Environment Setup
Install the required libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn statsmodels jupyter
```

## How to Run
1. Open a terminal in the `week_4` folder.
2. Install the required packages.
3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `simple_linear_regression_evaluation.ipynb`.
5. Run the notebook cells from top to bottom.

## Expected Outcome
By running the notebook, you should be able to:
- explore and clean the dataset
- fit a simple linear regression model
- evaluate model assumptions
- interpret the model in business terms
- make a budget allocation recommendation based on the regression results
