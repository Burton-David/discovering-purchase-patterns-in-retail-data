# Association Rules Mining Project
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Burton-David/discovering-purchase-patterns-in-retail-data/HEAD?urlpath=https%3A%2F%2Fgithub.com%2FBurton-David%2Fdiscovering-purchase-patterns-in-retail-data%2Fblob%2Fmain%2Fnotebooks%2Fassociation_rules_analysis.ipynb)
## Overview
This project demonstrates the application of Association Rules Mining techniques to discover interesting patterns in retail purchase data. Using the Groceries Market Basket dataset, we explore customer purchase behavior and identify meaningful product associations that can drive business value.

## Project Structure
```
association_rules_mining/
│
├── data/
│   ├── raw/         # Original, immutable data
│   └── processed/   # Cleaned, transformed data
│
├── notebooks/       # Jupyter notebooks for analysis
│
├── images/         # Visualizations and figures
│
└── README.md       # Project documentation
```

## Setup
1. Clone this repository
2. Download the Groceries Market Basket dataset
3. Install required dependencies:
   ```
   pip install pandas numpy mlxtend plotly
   ```

## Data
The project uses the Groceries Market Basket dataset, which contains real-world retail transaction data. Each record represents a shopping transaction with the items purchased in that transaction.

## Analysis
The analysis includes:
- Data preprocessing and transformation
- Frequent itemset mining using the Apriori algorithm
- Association rules generation and evaluation
- Visualization of key patterns and insights

## Results
Key findings and visualizations can be found in the Jupyter notebook within the `notebooks` directory.
