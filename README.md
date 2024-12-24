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

## Doing further segmented univariate analysis reveal the following,

2. The borrowers with lower grades borrowed more than the one with higher grades
3. The interest rate for those borrowers with lower sub grades are much higher which proves again that the grades are inversely proportional to risk.
4. The customers with lower grades show more disrespectful attitude. This insight is derived from the number of public derogatory records.

### Bivariate Analysis

## Bivariate analysis helps validate assumptions and clarify insights derived from univariate analysis.

1. The first chart on the right shows that borrowers with lower subgrades tend to take larger loans at higher
2. interest rates and default more frequently, leading to a higher number of charged-off loans.
3. The second chart reinforces this observation by illustrating the distribution of loan amounts across different grades.

## Tools and Libraries

- **Python:** Data analysis and visualization
- **Libraries:**
  - `Pandas` for data manipulation
  - `NumPy` for numerical operations
  - `Matplotlib` and `Seaborn` for visualization

## Results and Recommendations

## Positive - Focus on Higher-Grade Customers

1. Prioritize loan offers to customers with credit grades A, B, and C.
2. Explore targeted marketing campaigns to attract high-grade customers within the 6-9 years of employment segment.
3. Consider offering competitive interest rates for high-grade customers to remain competitive while potentially increasing loan volume.
4. Analyze the profitability of this segment while considering the lower interest rates.

## Positive - Incentivize Good Behavior

1. Implement loyalty programs or reward systems for customers with consistently positive payment histories.
2. Educate customers on the importance of maintaining good credit scores and minimizing derogatory records.
3. Offer financial counseling services to assist customers in improving their creditworthiness.
4. Monitor the impact of these incentives on loan approval rates and customer retention.

## Positive - Promote Longer Loan Terms

1. Educate customers on the benefits of longer loan terms, such as lower monthly installments and potential long-term cost savings.
2. Offer flexible loan term options to cater to individual customer needs and financial situations.
3. Clearly communicate the impact of loan term on total interest payments to ensure transparency.
4. Monitor customer satisfaction and repayment rates across different loan terms.

## Positive - Incorporate Debt-to-Income Ratio

1. Implement a robust debt-to-income (DTI) ratio assessment as a key factor in loan approval decisions.
2. Establish clear DTI thresholds for different loan products and risk categories.
3. Develop a scoring system that incorporates DTI along with other relevant credit risk factors.
4. Regularly review and adjust DTI thresholds based on market trends and internal risk assessments.

## Negative - Avoid Over-reliance on Low-Risk Segments

1. Avoid over-concentrating loan portfolios in the low-risk (high-grade) segment, as this may limit overall profitability.
2. Diversify lending strategies to include moderate-risk segments while maintaining appropriate risk controls.
3. Continuously monitor the risk-return profile of the loan portfolio and adjust lending strategies accordingly.
