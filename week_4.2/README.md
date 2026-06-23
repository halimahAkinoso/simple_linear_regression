# Multiple Linear Regression – Multi-Channel Marketing Analysis

## Project Overview

This project uses Multiple Linear Regression to analyze the impact of different marketing channels on sales performance. The analysis investigates how TV, Radio, and Social Media advertising contribute to sales and provides data-driven insights for optimizing marketing budget allocation.

The project was completed using Python and the Statsmodels library, with additional statistical tests and diagnostic plots to validate regression assumptions.

---

## Dataset Description

The dataset contains marketing campaign information and corresponding sales outcomes.

### Variables

| Variable     | Description                                    |
| ------------ | ---------------------------------------------- |
| TV           | TV advertising level (Low, Medium, High)       |
| Radio        | Radio advertising expenditure                  |
| Social Media | Social media advertising expenditure           |
| Influencer   | Influencer category (Nano, Micro, Macro, Mega) |
| Sales        | Sales generated from the campaign              |

### Target Variable

* **Sales** – The dependent variable to be predicted.

### Independent Variables

* TV
* Radio
* Social Media

For regression analysis, the TV advertising levels were encoded numerically:

* Low = 1
* Medium = 2
* High = 3

---

## Analysis Goals

The objectives of this project are to:

1. Perform Exploratory Data Analysis (EDA).
2. Examine relationships between marketing channels and sales.
3. Detect multicollinearity using:

   * Correlation Matrix
   * Variance Inflation Factor (VIF)
4. Build a Multiple Linear Regression model using Ordinary Least Squares (OLS).
5. Evaluate model performance using:

   * R-squared
   * Adjusted R-squared
   * F-statistic
   * Predictor p-values
6. Validate regression assumptions through diagnostic plots:

   * Linearity
   * Normality of Residuals
   * Homoscedasticity
7. Interpret regression coefficients.
8. Generate business recommendations based on analytical findings.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* SciPy

---

## Environment Setup

### Install Required Packages

Run the following command:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

### Verify Installation

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
from scipy import stats
```

---

## Project Workflow

1. Load and inspect the dataset.
2. Clean and preprocess data.
3. Encode categorical variables.
4. Perform exploratory data analysis.
5. Check for multicollinearity.
6. Build the Multiple Linear Regression model.
7. Evaluate model performance.
8. Validate model assumptions.
9. Interpret results and coefficients.
10. Provide actionable business recommendations.

---

## Model Evaluation

The regression model is assessed using:

* Adjusted R-squared
* Coefficient significance (p-values)
* Residual diagnostics
* Variance Inflation Factor (VIF)
* Residual distribution analysis

---

## Business Value

This analysis helps marketing managers:

* Identify the most effective advertising channels.
* Allocate marketing budgets more efficiently.
* Improve return on advertising investment.
* Support strategic decision-making with data-driven insights.

---

## Author

Halimat Ibrahim-Akinoso

Multiple Linear Regression – Multi-Channel Marketing Analysis Project
