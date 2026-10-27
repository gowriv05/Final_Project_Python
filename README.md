# In-Vehicle Coupon Acceptance Analysis

## Project Overview
This project analyzes customer behavior related to in-vehicle coupon acceptance. The objective is to understand which factors are associated with customers accepting or rejecting coupons while travelling.

The analysis uses Python for data cleaning, exploratory data analysis (EDA), and visualization. A Power BI dashboard is designed to present the key findings interactively.

## Problem Statement
Customers receive different types of coupons while travelling under different conditions. However, not all customers accept the coupons they receive.

This project explores customer demographics, travel conditions, coupon types, and other factors to understand coupon acceptance behavior.

## Objectives
- Analyze overall coupon acceptance and rejection.
- Explore acceptance patterns across different coupon types.
- Understand the relationship between weather and coupon acceptance.
- Analyze customer and travel-related characteristics.
- Present key insights through visualizations and a Power BI dashboard.

## Dataset
**Dataset Name:** In-Vehicle Coupon Recommendation

**Source:** UCI Machine Learning Repository

The dataset contains information about coupon types, driving conditions, customer demographics, travel details, and coupon acceptance.

**Target Variable:**
- `Y = 1`: Coupon accepted
- `Y = 0`: Coupon not accepted

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Power BI

## Data Cleaning and Preprocessing
The following preprocessing steps were performed as required by the dataset:
- Inspected the dataset structure and data types.
- Identified and handled missing values.
- Checked for duplicate records.
- Removed columns with excessive missing values where appropriate.
- Prepared the cleaned dataset for exploratory data analysis.

## Exploratory Data Analysis
The analysis explores the following areas:

1. Overall coupon acceptance and rejection.
2. Coupon acceptance by coupon type.
3. Coupon acceptance under different weather conditions.
4. Customer demographic patterns.
5. Travel-related factors associated with coupon acceptance.
6. Relationships between selected numerical variables.

Visualizations were created using Matplotlib and Seaborn to identify patterns in the data.

## Power BI Dashboard
An interactive Power BI dashboard was developed to summarize the analysis.

**Key Performance Indicators (KPIs):**
- Total Coupons
- Accepted Coupons
- Coupon Acceptance Rate

**Visualizations:**
- Accepted vs. Rejected Coupons
- Acceptance Rate by Coupon Type
- Acceptance Rate by Weather

**Interactive Slicers:**
- Coupon: Filter the dashboard by coupon type.
- Passenger: Filter the dashboard by passenger category.

These slicers allow users to explore coupon acceptance patterns for different coupon types and passenger categories.
<img width="1380" height="777" alt="Screenshot 2026-10-23 211400" src="https://github.com/user-attachments/assets/8fff438f-d932-4324-a4e4-2729db128b43" />


## Key Findings
The project examines which coupon types and customer or travel characteristics are associated with coupon acceptance.

The final findings should be based on the actual results from the Python analysis and Power BI dashboard.

## Business Insights
The analysis can help businesses:
- Understand customer coupon acceptance behavior.
- Identify coupon types worth examining for targeted promotions.
- Explore how travel conditions relate to coupon acceptance.
- Develop more personalized coupon marketing strategies.

## Limitations
- The analysis is based on the available dataset.
- The results describe associations and do not prove that a particular factor causes coupon acceptance.
- Findings may not represent every customer or real-world driving situation.

## Future Enhancements
- Explore customer segments and their coupon preferences.
- Evaluate model performance using suitable classification metrics.

## Conclusion
This project uses Python-based exploratory data analysis and Power BI visualization to investigate factors associated with in-vehicle coupon acceptance. The findings can support a better understanding of customer behavior and help inform data-driven coupon marketing strategies.

## Author
Gowri V

**Skills Demonstrated:** Python, Pandas, NumPy, Data Cleaning, Exploratory Data Analysis, Data Visualization, Power BI
