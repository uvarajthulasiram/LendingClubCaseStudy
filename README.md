# Lending Data Analysis

## Overview
This project involves analyzing the dataset of a leading lending company to identify risks and provide actionable insights. The analysis aims to highlight key patterns, identify risky applicants, and offer recommendations to mitigate credit loss.

## Objective
- Analyze the dataset to identify risks and issues in borrower's patterns.
- Create a detailed case study document outlining the risks and observations.
- Provide actionable recommendations based on the analysis.

## Dataset
- **Rows:** 39,717
- **Columns:** 111 (reduced to 34 after data cleaning)

## Data Preprocessing
1. **Irrelevant Columns Removed:** Dropped columns like `id`, `member_id`, and `desc` as they do not contribute to risk analysis.
2. **Null Values Handled:** Removed columns with more than 50% null values and rows with critical missing data.
3. **Derived Features Added:** Created columns for credit health, income levels, and date components.
4. **Outliers Managed:** Used the IQR method to handle extreme values in `loan_amnt` and `annual_inc`.

## Analysis
### Univariate Analysis
- [ToDo]

### Bivariate Analysis
- [ToDo]

## Tools and Libraries
- **Python:** Data analysis and visualization
- **Libraries:**
  - `Pandas` for data manipulation
  - `NumPy` for numerical operations
  - `Matplotlib` and `Seaborn` for visualization

## Results and Recommendations
- [ToDo]