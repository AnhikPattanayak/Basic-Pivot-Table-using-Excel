# Basic Excel Pivot Table Project

This project focuses on analyzing sales transaction data to uncover actionable business insights related to revenue trends, regional performance, product demand, and sales representative effectiveness. 

## 🗂️ Dataset Description

The dataset Sales_data.xlxs contains 2 tables of sales data and customer ID information consisting of:
- ### **Table_1: Sales Data**
  - **Num** : Unique sequential identifier for each sales transaction record.  
  - **Date** : Exact date on which the sales transaction occurred.
  - **Month** : Month extracted from the transaction date to analyze monthly trends.
  - **Sales Rep**: Name of the sales representative responsible for the transaction.
  - **Region** : Geographic sales region where the transaction took place.
  - **Customer ID** : Unique identifier linking the sale to a specific customer.
  - **Model** : Product model sold in the transaction (e.g., chair type).
  - **Color** : Color variant of the product sold, useful for product preference analysis.
  - **Item Code** : Unique product code used for inventory and tracking.
  - **Number** : Quantity of units sold in the transaction.
  - **Price / Unit** : Selling price of a single unit before aggregation.
  - **Total** : Total transaction value calculated as Quantity × Price per Unit.

- ### **Table_2: Customer Info**
  - **Customer ID** :	Unique customer identifier used to join customer data with sales data.
  - **Company Name** :	Name of the company or organization purchasing the product.
  - **Representative** :	Primary contact or account manager associated with the customer.

## 🛠️ Methodology

1. Data Preprocessing
  - **Handling Missing Values** : Identified and addressed any missing data in the dataset. 
