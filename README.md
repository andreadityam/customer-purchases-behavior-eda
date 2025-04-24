# Customer Purchase Behavior EDA

This repository contains a dataset representing simulated customer purchase behavior. The focus of this project is to perform **Exploratory Data Analysis (EDA)** to uncover trends, patterns, and insights within the data.

## Dataset Overview

This dataset includes various customer attributes and purchase behavior features. Below are the key columns in the dataset:

### Column Descriptors:
- **age**: Age of the customer.
- **gender**: Gender of the customer (0 for Male, 1 for Female).
- **income**: Annual income of the customer.
- **education**: Education level of the customer.
- **region**: Region where the customer resides.
- **loyalty_status**: Loyalty status of the customer.
- **purchase_frequency**: Frequency of purchases made by the customer.
- **purchase_amount**: Amount spent by the customer in each purchase.
- **product_category**: Category of the purchased product.
- **promotion_usage**: Indicates whether the customer used promotional offers (0 for No, 1 for Yes).
- **satisfaction_score**: Satisfaction score of the customer.

### File Information:
- **File Format**: CSV
- **Number of Rows**: 100,000
- **Number of Columns**: 12

## Project Overview

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the dataset to extract meaningful insights, visualizations, and statistical summaries that can help understand customer behavior. The analysis will include, but is not limited to:
- Descriptive statistics (mean, median, mode, etc.).
- Data distribution and relationships between key variables.
- Visualizations such as histograms, scatter plots, and heatmaps.
- Analysis of customer demographics and their purchasing patterns.
- Insights on promotion usage and its correlation with purchase amount and frequency.
- Evaluating customer satisfaction levels.

## Data Source

This dataset is sourced from Kaggle:  
[Customer Purchases Behavior Dataset](https://www.kaggle.com/datasets/sanyamgoyal401/customer-purchases-behaviour-dataset)

## Dependencies

The following libraries are used for analysis:
- pandas
- numpy
- matplotlib
- seaborn
- scipy

You can install the dependencies using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scipy
