# Budget_Analysis_Project

Financial Budget Analysis Dashboard (SQL + Exel)
This project analyzes company budget vs. actual spending using SQL and Excel to simulate real-world Financial Analysis.

The goal of this project was to transform raw financial data into actionable insights through a structured data pipeline and dashboard.

Workflow:
  Imported raw CSV data into PostgreSQL
  Cleaned and transformed data using SQL
  Created analytical views for:
  Budget vs. actual variance comparisons
  Rolling 3-month averages
  Month-over-month growth
  Spend breakdown at department-level
  Exported processed data into Excel
  Built an Executive Summary Dashboard to visualize key financial metrics and suggest recommendations

Executive Dashboard Features:
  KPI summary (total spend, average spend, variance)
  Monthly spending trend with rolling average
  Budget vs. actual comparison
  Department-level volatility analysis

Key Insights:
  Spending is heavily concentrated in Engineering (~75%+ of total spend)
  Monthly costs show an overall upward trend across the year
  High volatility in certain departments suggests inconsistent cost behavior
  Several months show meaningful variance from budget, indicating forecasting gaps

Future Recommendations:
  Implement tighter cost controls in high-spend departments (Engineering)
  Standardize forecasting assumptions across departments
  Reduce volatility through improved budget planning and tracking
