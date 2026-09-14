# GFC Financial Chatbot

A rule-based financial chatbot prototype built in Python as part of the **BCG GenAI Job Simulation** on Forage.

The chatbot answers predefined financial queries about **Microsoft, Tesla, and Apple** using data extracted from their 10-K filings (FY 2023–2025).

---

## What It Does

- Loads and cleans financial data from a CSV file
- Extracts company, year, and metric type from a user's natural-language query
- Returns accurate, data-backed responses using if/elif/else logic
- Handles unrecognized queries and missing context gracefully


---

## Supported Queries

| Query Type | Example |
|---|---|
| Total Revenue | "What is Microsoft's total revenue in 2025?" |
| Net Income (value) | "What is Tesla's net income in 2025?" |
| Net Income Change | "How has Apple's net income changed?" |
| Operating Cash Flow | "What is Microsoft's operating cash flow in 2025?" |
| Total Assets | "What are Tesla's total assets in 2025?" |
| Total Liabilities | "What are Apple's total liabilities in 2024?" |

**Companies:** Microsoft, Tesla, Apple
**Years:** 2023, 2024, 2025 (defaults to 2025 if not specified)

---

## Dataset

`GFC_Financial_Data.csv` contains the following metrics for each company and year:

- Total Revenue
- Net Income
- Total Assets
- Total Liabilities
- Operating Cash Flow

All figures are in USD millions, sourced from public 10-K filings.

