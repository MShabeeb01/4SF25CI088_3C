# FinTrace: Banking Transaction & Fraud Intelligence
**Milestone 1 – CIE: Data Transformation, Null Value Handling, Insight Generation, and Visualization**

## Overview
This repository contains the analysis of the `indian_banking_transactions.csv` dataset, covering data inspection, cleaning, mean imputation for missing values, statistical analysis using NumPy, and visualizations using Matplotlib and Seaborn.

## Repository Contents
- `01_ProjectApproach.ipynb`: Project formulation, problem statement, and workflow phases.
- `02_Pandas.ipynb`: Data loading, schema inspection, mean imputation for numerical attributes, and column transformations.
- `03_Numpy.ipynb`: Extraction of 1D/2D arrays, descriptive statistics, percentiles, and IQR outlier boundaries.
- `04_Matplotlib.ipynb`: Line plots, bar charts, and transaction distribution histograms.
- `05_Seaborn.ipynb`: Target count plots, category risk bar charts, and feature correlation heatmaps.
- `indian_banking_transactions.csv`: Raw transaction dataset used for analysis.

## Key Outcomes & Insights
1. **Data Cleaning & Imputation:** Addressed null values in `loan_type` and applied mean imputation across continuous numerical attributes (`emi_amount`, `transaction_amount`).
2. **Feature Engineering:** Extracted temporal attributes (`month`, `transaction_hour`) to examine time-based transaction patterns.
3. **Statistical Analysis:** Identified right-skewed transaction amount distributions and isolated outlier boundaries using IQR.
4. **Visual Insights:** Visualized transaction frequencies across payment channels and compared distribution densities between legitimate and fraudulent transactions.