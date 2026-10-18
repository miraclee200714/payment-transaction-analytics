# Payment Transaction Analytics

## Project Overview
This project analyzes 1,000 synthetic payment transactions using Python, SQL, Pandas, NumPy, SQLite, and Matplotlib. It explores transaction success rates, payment method performance, and monthly payment volume trends.

## Business Questions
1. What percentage of payments succeeded or failed?
2. Which payment method had the highest observed failure rate?
3. How did successful payment volume change over time?
4. What additional data would help investigate payment failures?

## Technologies Used
- Python
- SQL and SQLite
- Pandas and NumPy
- Matplotlib
- Google Colab
- GitHub

## Key Findings

| Metric | Result |
|---|---|
| Total Transactions | 1,000 |
| Successful Transactions | 849 |
| Failed Transactions | 151 |
| Payment Success Rate | 84.90% |
| Payment Failure Rate | 15.10% |
| Digital Wallet Failure Rate | 17.88% |
| Bank Transfer Failure Rate | 15.29% |
| Card Failure Rate | 12.12% |
| Highest Complete-Month Payment Volume | August 2026: $28,568.61 |

## Technical Approach
1. Generated 1,000 reproducible synthetic payment transactions.
2. Explored data types and checked for missing values.
3. Calculated transaction success and failure rates using Python.
4. Created an SQLite database and analyzed transactions with SQL.
5. Compared payment failure percentages by payment method.
6. Created Matplotlib charts and analyzed monthly successful payment volume.
7. Validated transaction IDs, payment amounts, statuses, and Python/SQL calculations.

## Technical Challenge
One challenge was learning how to execute SQL queries within a Python notebook. I resolved this by storing SQL queries as multiline Python strings and executing them through Pandas and SQLite. This helped me understand how SQL and Python work together in a data analysis workflow.

## Business Recommendations
- Collect payment decline codes and failure reasons before investigating root causes.
- Monitor transaction success rates and failure rates across payment methods.
- Analyze transaction counts and average payment amounts alongside monthly payment volume.

## Limitations
This project uses randomly generated synthetic data for educational purposes. Observed differences between payment methods do not demonstrate real-world reliability or identify the causes of payment failures. September is an incomplete month.

## How to Run
1. Open Payment_Transaction_Analysis.ipynb in Google Colab.
2. Run all notebook cells in order.
3. Review the SQL results, visualizations, validation checks, and business findings.

## Skills Demonstrated
Python, SQL, data manipulation, data visualization, data validation, analytical problem-solving, and business reporting.

