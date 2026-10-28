# Finance Analysis Dashboard | Power BI

## Project Overview

The Finance Analysis Dashboard is an interactive business intelligence project developed using Microsoft Power BI. It analyzes financial transactions, customer behavior, loan exposure, and transaction risk to help stakeholders understand financial performance and identify areas that require attention.

The project follows an end-to-end analytical workflow, including raw data auditing, data cleaning, data modeling, DAX measure development, dashboard design, data validation, and business insight generation.

## Business Objectives

- Analyze overall transaction performance and financial activity.
- Monitor transaction completion, failure, pending, and reversal patterns.
- Understand customer transaction behavior across age groups and genders.
- Compare financial activity across branches, account types, channels, and transaction types.
- Evaluate loan exposure, credit scores, interest rates, and risk levels.
- Identify data quality issues and recommend improvements.

## Tools and Technologies

- **Microsoft Power BI** — Interactive dashboards and data visualization.
- **Power Query** — Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** — Calculated columns, measures, and KPIs.
- **Excel** — Source dataset inspection and preparation.

## Dataset Information

The project uses a synthetic financial transaction dataset created for analytical practice.

- **Raw records:** 20,000
- **Duplicate records removed:** 200
- **Records with invalid transaction dates removed:** 30
- **Final analytical records:** 19,770

The dataset includes transaction dates, customer information, branches, account types, transaction amounts, transaction fees, loan amounts, credit scores, interest rates, transaction statuses, and risk levels.

**Note:** The dataset is synthetic and is not a representation of actual customer or banking transactions.

## Data Cleaning and Transformation

The raw dataset contained missing values, duplicate transaction IDs, inconsistent category labels, invalid dates, incorrect data types, and out-of-range values.

The main cleaning activities included:

- Removed duplicate transaction IDs.
- Removed records containing invalid transaction dates.
- Converted financial and numeric fields to appropriate data types.
- Standardized category values for gender, branch, account type, channel, status, and risk level.
- Validated customer age ranges, credit scores, and interest rates.
- Handled missing values according to the meaning of each field.
- Investigated negative financial values rather than automatically converting them to positive values.

## Key Performance Indicators (KPIs)

The Executive Overview includes the following KPIs:

| KPI | Validated result |
|---|---:|
| Total Transaction Amount | ₹41.66M |
| Total Transactions | 19,770 |
| Average Transaction Value | ₹2,107.45 |
| Total Transaction Fees | ₹455.37K |
| Total Loan Amount | ₹339.64 Cr |
| Average Credit Score | 577.20 |

These values represent the full cleaned dataset with no report filters applied.

## Dashboard Pages

### 1. Home Page
- Project introduction and overview.
- Key project highlights.
- Interactive navigation to all four analytical pages.

### 2. Executive Overview
- Overall financial performance.
- Transaction amount trend by month.
- Transaction status distribution.
- Transaction amount by branch, account type, channel, and transaction type.
- Six headline KPI cards.

### 3. Customer & Transaction Analysis
- Transaction amount by age group.
- Transaction count by gender and age group.
- Average transaction value by age group.
- Transaction count by transaction type.
- Transaction amount by gender.

### 4. Loan & Risk Analysis
- Loan amount distribution by risk level.
- Average loan amount by account type.
- Average interest rate by risk level.
- Average credit score by risk level.
- Total loan amount by branch.
- Transaction status distribution by risk level.

### 5. Insights & Data Quality
- Key business insights.
- Data quality summary.
- Data cleaning activities.
- Business recommendations.

## Key Business Insights

- The cleaned dataset contains 19,770 analytical transaction records, with a total transaction value of approximately ₹41.66 million.
- The 65+ age group recorded the highest transaction count, with 3,790 transactions.
- Low-risk customers account for approximately 66% of total loan exposure, representing the largest share of the loan portfolio.
- Vijayawada recorded the highest total loan exposure among the branches, at approximately ₹377.10 million.

## Business Recommendations

- Monitor loan exposure by branch, especially branches with the highest loan exposure.
- Review higher-risk customer activity and maintain appropriate risk monitoring.
- Investigate failed and pending transactions to identify operational issues and opportunities to improve customer experience.
- Use customer age-group and transaction patterns to inform customer engagement strategies.
- Strengthen data quality controls to reduce duplicate records, invalid dates, and inconsistent categories.

## Project Workflow

1. Define the business problem and objectives.
2. Audit and understand the raw dataset.
3. Clean and transform the data using Power Query.
4. Design the data model.
5. Create calculated columns where required.
6. Develop core and analytical DAX measures.
7. Validate calculations and data quality.
8. Design and build the dashboard pages.
9. Derive business insights and recommendations.
10. Document the project for portfolio presentation.

## Repository Structure

```text
Finance-Analysis-Dashboard/
│
├── README.md
│
├── Dataset/
│   └── Finance_Raw_Dataset.xlsx
│
├── PowerBI File/
│   └── Finance_Analysis_Dashboard.pbix
│
└── Screenshots/
    ├── Home.jpg
    ├── Executive Overview.jpg
    ├── Customer & Transaction Analysis.jpg
    ├── Loan & Risk Analysis.jpg
    └── Insights & Data Quality.jpg
```

## Skills Demonstrated

- Data cleaning and transformation
- Data quality validation
- DAX calculations and KPI development
- Financial data analysis
- Interactive dashboard design
- Data visualization and storytelling
- Business insight generation
- Analytical documentation

## Conclusion

This project demonstrates how raw financial data can be transformed into an interactive Power BI dashboard that communicates transaction performance, customer behavior, loan exposure, and risk-related insights. It combines technical analysis with business-oriented recommendations to support data-informed decision-making.

## Disclaimer

This is an educational portfolio project using synthetic data. The findings are illustrative and should not be interpreted as actual banking performance or financial advice.