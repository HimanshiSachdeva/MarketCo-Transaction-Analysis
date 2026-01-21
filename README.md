# MarketCo Transaction Analysis

This repository contains the analysis and report for **MIS784 Assignment 1**, where I analyzed customer behavior and sales performance for **MarketCo**, an omnichannel retailer.

## Project Overview

The assignment utilizes historical shopping data from MarketCo and applies **marketing analytics techniques** such as **RFM (Recency, Frequency, Monetary)** analysis to gain insights into customer behavior, product sales, and sales channel effectiveness.

## Data

The dataset contains information on transactions, including:
- **InvoiceNo**: Unique transaction identifier.
- **StockCode**: Product code (SKU).
- **Quantity**: Number of units sold.
- **UnitPrice**: Price per unit.
- **Discount**: Discount applied on the transaction.
- **SalesChannel**: Sales channel (e.g., online, in-store).
- **UserID**: Unique customer identifier.

## Analysis Performed

1. **Best-selling Product**: The product with the highest total sales quantity.
2. **Highest Return Rate**: The product with the highest return rate.
3. **Most Applied Discounts**: The product with the highest total discount applied.
4. **Unique Customers by Sales Channel**: Count of distinct customers for each sales channel.
5. **RFM Value Scores**: Recency, Frequency, and Monetary value scores for customers.
6. **Customer Segmentation**: Customers grouped into quintiles for each RFM metric.

## Findings & Insights

- **Best-selling Product**: The most popular product was `T-shirt (StockCode SKU_1114)` with 88 units sold.
- **Highest Return Rate**: The `Notebook (StockCode SKU_1921)` had a return rate of 1.0, signaling potential quality or expectation issues.
- **Most Applied Discounts**: The `USB Cable (StockCode SKU_1679)` received the highest discounts.
- **Sales Channel Insights**: The online channel led with the most unique customers, highlighting its importance in the overall sales strategy.
  
## Recommendations

1. **Loyalty Program**: Introduce a **tiered loyalty program** to retain high-value customers and incentivize repeat purchases.
2. **Product Quality Control**: Investigate the high return rates for the `Notebook` and improve the product description, quality, or customer expectations.

## Files in this Repository:

- **MIS784_A1_224850909_Report.docx**: The written report detailing the findings and recommendations.
- **MIS784_A1_224850909_Query.docx**: The SQL queries used for data analysis.
- **AT1_MIS784_dataset_updated.csv**: The dataset containing MarketCo’s transaction data.
