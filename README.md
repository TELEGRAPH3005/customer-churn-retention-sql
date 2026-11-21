# Customer Churn & Retention Analysis (SQL)

## Project Overview

This project analyzes a subscription-based business using SQL to understand revenue performance, subscription activity, customer behavior, and retention.

The goal is to use SQL queries to extract meaningful business insights and identify opportunities to improve customer retention and revenue performance.

## Tools & Technologies

- SQL (SQLite)
- Python
- Pandas
- Google Colab

## Dataset

The project uses a sample subscription dataset containing three relational tables:

- **Customers:** Customer information.
- **Subscriptions:** Subscription plans, prices, and statuses.
- **Payments:** Payment transactions, dates, and payment statuses.

## Business Questions

1. How much total revenue does the business generate?
2. How does revenue change month to month?
3. Which subscription plans generate the most revenue?
4. How many subscriptions are active or cancelled?
5. Which customers generate the most revenue?
6. What percentage of customers return in consecutive months?
7. How does customer retention change over time?

## SQL Skills Demonstrated

- SELECT, WHERE, ORDER BY
- GROUP BY and aggregate functions
- INNER JOIN
- CASE WHEN
- Common Table Expressions (CTEs)
- Subqueries
- Window functions: RANK() and LAG()
- Date functions
- Customer retention calculations

## Key Findings

### Customer Retention

- January to February retention: **100%** (3 out of 3 customers).
- February to March retention: **83.33%** (5 out of 6 customers).
- Retention decreased by **16.67 percentage points** between the two periods.

These results indicate that one February-active customer did not make a successful payment in March.

## Business Recommendations

- Investigate why customers stop making successful payments.
- Monitor cancellation rates across subscription plans.
- Identify and focus on high-value customers.
- Monitor monthly revenue and retention trends.
- Consider customer engagement and subscription renewal strategies.

## Conclusion

This project demonstrates how SQL can be used to analyze subscription revenue, customer behavior, churn, and retention. The analysis translates query results into business insights that can support better decision-making.

## Limitations

This project uses a small sample dataset of 8 customers. The findings demonstrate SQL analysis techniques and should not be interpreted as statistically representative of a large customer population.
