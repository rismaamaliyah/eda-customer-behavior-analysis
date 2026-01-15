# EDA - Customer Behavior Analysis

## Project Overview

This project analyzes customer purchasing behavior in an e-commerce dataset to identify revenue patterns, customers concentration, and retention issues. The analysis focuses on understanding how revenue is distributed across customers and orders, and how business decisions can be informed through data-driven insights.

## Dataset

- **Source**: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Scope**: Orders, customers, and payment transactions
- **Key Fields**:
    - customers_unique_id
    - order_id
    - order_purchase_timestamp
    - payment_value

## Key Business Questions

- How is revenue distributed across customers?
- Do a small number of customers contribute disproportionately to revenue?
- What does order value distribution look like?
- How strong is customer retention?

## Key Analysis & Visualizations

### Order Value Distribution
This charts shows that order values are heavily right-skewed with significant high-value outliers.
![Order Value Distribution](images/order_value_distribution.png)

### Top Customers by Revenue
A small group of customers contributes disproportionately to total revenue.
![Top Customers Revenue](images/top_customers_revenue.png)

### Revenue Concentration (Pareto Analysis)
The top percentage of customers contributes the majority of total revenue.
![Revenue Pareto](images/pareto_revenue.png)

## Key Insights

- Revenue is highly concentrated among a small group of customers.
- Approximately 10-20% of customers generate the majority of total revenue.
- Monitor high-value transactions for fraud detection or potential enterprise opportunities.
- Segment customers based on spending behavior for targeted marketing strategies.

## Business Recommendations

- Introduce loyalty or retention programs to convert one-time buyers into repeat customers.
- Reduce revenue concentration risk by targeting mid-value customers with personalized offers.
- Monitor high-value transactions for fraud detection or potential enterprise opportunities.
- Segment customers based on spending behavior for targeted marketing strategies.

## Tech Stack

- **Python**: pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**
- **GitHub** for version control and documentation

## How to Run
1. Clone this repository:
```bash
git clone https://github.com/rismaamaliyah/eda-customer-behavior-analysis.git
```

2. Install required libraries:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook
```
