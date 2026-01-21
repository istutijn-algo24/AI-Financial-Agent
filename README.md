# AI Financial Coach Agent with Google ADK 💰

The **AI Financial Coach** is a personalized financial advisor powered by Google's ADK (Agent Development Kit) framework. This app provides comprehensive financial analysis and recommendations based on user inputs including income, expenses, debts, and financial goals.

## Features

- **Multi-Agent Financial Analysis System**
    - Budget Analysis Agent: Analyzes spending patterns and recommends optimizations
    - Savings Strategy Agent: Creates personalized savings plans and emergency fund strategies
    - Debt Reduction Agent: Develops optimized debt payoff strategies using avalanche and snowball methods

- **Expense Analysis**:
  - Supports both CSV upload and manual expense entry
  - CSV transaction analysis with date, category, and amount tracking
  - Visual breakdown of spending by category
  - Automated expense categorization and pattern detection

- **Savings Recommendations**:
  - Emergency fund sizing and building strategies
  - Custom savings allocations across different goals
  - Practical automation techniques for consistent saving
  - Progress tracking and milestone recommendations

- **Debt Management**:
  - Multiple debt handling with interest rate optimization
  - Comparison between avalanche and snowball methods
  - Visual debt payoff timeline and interest savings analysis
  - Actionable debt reduction recommendations

- **Interactive Visualizations**:
  - Pie charts for expense breakdown
  - Bar charts for income vs. expenses
  - Debt comparison graphs
  - Progress tracking metrics


## CSV File Format

The application accepts CSV files with the following required columns:
- `Date`: Transaction date in YYYY-MM-DD format
- `Category`: Expense category
- `Amount`: Transaction amount (supports currency symbols and comma formatting)

Example:
```csv
Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00
```

A template CSV file can be downloaded directly from the application's sidebar.
