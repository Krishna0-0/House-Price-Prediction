# 🏠 House Price Prediction using XGBoost

This project predicts house prices using the **Boston Housing Dataset** and the **XGBoost Regressor** model. It uses advanced regression techniques and data visualization for performance analysis.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7.0-orange)

## Overview

- Data source: Boston Housing Dataset
- Model used: XGBoost Regressor
- Metrics: R² Score and Mean Absolute Error
- Tools: Python, scikit-learn, XGBoost, Matplotlib, Seaborn

## Dataset Description

The **Boston Housing Dataset** contains information collected by the U.S. Census Service concerning housing in the area of Boston, Massachusetts. It has been widely used as a benchmark dataset in regression tasks.

Each record in the dataset describes a Boston suburb (506 total samples), with **13 numerical/categorical features** and **1 target variable**:

| Feature   | Description |
|-----------|-------------|
| `CRIM`    | Per capita crime rate by town |
| `ZN`      | Proportion of residential land zoned for lots over 25,000 sq.ft. |
| `INDUS`   | Proportion of non-retail business acres per town |
| `CHAS`    | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| `NOX`     | Nitric oxide concentration (parts per 10 million) |
| `RM`      | Average number of rooms per dwelling |
| `AGE`     | Proportion of owner-occupied units built prior to 1940 |
| `DIS`     | Weighted distances to five Boston employment centers |
| `RAD`     | Index of accessibility to radial highways |
| `TAX`     | Full-value property-tax rate per $10,000 |
| `PTRATIO` | Pupil-teacher ratio by town |
| `B`       | \( 1000(Bk - 0.63)^2 \), where Bk is the proportion of Black residents by town |
| `LSTAT`   | % lower status of the population |

The target variable is:
- `price` = median value of owner-occupied homes in $1000s

> **Note**: While widely used, this dataset has limitations in terms of fairness, inclusivity, and recency. Avoid using it in production-grade models without deeper review.

> 📎 Dataset source: [StatLib CMU - Boston Housing](http://lib.stat.cmu.edu/datasets/boston)

## Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

## Model Evaluation

- Training R² Score: ~0.999
- Testing R² Score: ~0.88
- Mean Absolute Error: ~2.4

Visualizations show the alignment between actual and predicted prices.

