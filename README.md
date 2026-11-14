# Customer Churn Analysis

## Project Overview

Customer churn is one of the major challenges faced by subscription-based businesses. It refers to the situation in which customers discontinue their subscriptions or stop using a company's services.

This project focuses on analyzing customer churn patterns to understand why customers leave, which customer segments experience higher churn, and how businesses can improve customer retention.

Using Python, SQL, Pandas, NumPy, Matplotlib, and Seaborn, this project explores customer demographics, subscription details, monthly charges, and customer support interactions to identify meaningful patterns and actionable business insights.

## Project Objectives

- Calculate overall customer churn and retention rates.
- Identify customer segments with higher churn rates.
- Analyze churn across subscription plans, contract types, and geographical locations.
- Evaluate customer revenue, average revenue per user (ARPU), and revenue at risk.
- Examine the relationship between customer support interactions, escalations, and churn.
- Visualize important trends and relationships using statistical charts.
- Generate actionable business recommendations to improve customer retention.

## Dataset Description

The analysis uses three interconnected datasets stored in SQLite (`customer_churn_analysis.db`):
1. **Customer Data:** Customer ID, name, gender, date of birth, state, and country.
2. **Subscription Data:** Subscription type, plan type, contract details, monthly charges, renewal dates, cancellation dates, and churn records.
3. **Customer Support Data:** Complaint dates, escalation records, CSAT scores, and customer feedback comments.

## Tools and Technologies

- **Python** – Data analysis and manipulation
- **Pandas & NumPy** – Data cleaning, transformation, and statistical calculations
- **SQLite** – Relational database storage and querying
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis and reporting

## Project Structure

```text
├── Customer_Churn_Analysis.ipynb    # Main Jupyter Notebook analysis
├── Customer_Churn_Analysis.html     # HTML export of the notebook
├── Customer_Churn_Analysis.pdf      # PDF export of the final report
├── customer_churn_analysis.db       # SQLite database containing raw tables
├── exported_churn_data_analysis.csv # Exported processed analysis dataset
├── .gitignore                       # Ignored files
└── README.md                        # Project documentation
```

## How to Run

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd Customer_Churn_Analysis
   ```
2. Install required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Churn_Analysis.ipynb
   ```
