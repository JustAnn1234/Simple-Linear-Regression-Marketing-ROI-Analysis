# Simple Linear Regression – Marketing ROI Analysis

## Project Overview
This project performs an end-to-end Simple Linear Regression analysis using Python and `statsmodels` to evaluate the impact of different marketing budget allocations (TV, Radio, Social Media) on Sales. The final model identifies the optimal marketing channel to maximize corporate ROI.

## Key Findings
* **Primary Driver:** `TV` advertising has a textbook-perfect correlation (~0.999) with `Sales`.
* **ROI Impact:** Every $1 increase in TV advertising spend yields a **$3.56 increase** in revenue.
* **Model Accuracy:** The final OLS model explains **99.9%** of the variance in Sales.

## Repository Structure
* `regression_analysis.ipynb`: The core Jupyter Notebook containing all data cleaning, EDA, OLS model output, and diagnostic assumption plots.
* `marketing_and_sales_data_evaluate_lr.csv`: The clean marketing dataset used for the project.
* `README.md`: Project summary and setup instructions.

## Environment Setup & Installation
To run the notebook locally, clone this repository and install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
