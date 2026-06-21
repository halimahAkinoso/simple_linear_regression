# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview
This project uses Simple Linear Regression with Ordinary Least Squares (OLS) to examine how marketing spend relates to sales performance.

The analysis focuses on:
- exploring the marketing dataset
- visualizing the relationship between advertising spend and sales
- fitting a simple linear regression model
- interpreting R-squared, coefficients, and p-values
- generating diagnostic plots for linearity, normality, and homoscedasticity
- making a business recommendation for marketing budget allocation

## Dataset
The dataset used for this project contains the following variables:
- `TV`
- `Radio`
- `Social_Media`
- `Sales`

For the simple linear regression analysis, `TV` is used as the predictor variable and `Sales` is used as the target variable.

## Project Files
- `marketing_and_sales_data_evaluate_lr.csv`: dataset used for the analysis
- `simple_linear_regression_evaluation.ipynb` or related notebook file: notebook containing the full analysis

## Environment Setup
Make sure Python is installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels jupyter
```

## How to Run the Project
1. Open a terminal in the project folder.
2. Install the required packages.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the regression notebook and run the cells from top to bottom.

## Libraries Used
- `pandas` for data loading and cleaning
- `numpy` for numerical operations
- `matplotlib` for plotting
- `seaborn` for statistical visualizations
- `statsmodels` for OLS regression analysis

## Expected Output
By running the notebook, you should be able to:
- inspect the dataset structure
- visualize relationships between variables
- fit a simple linear regression model
- evaluate model performance
- interpret results in business terms
- recommend a marketing budget strategy based on the findings
