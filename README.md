# DataStage
**Project Overview**

This project involves creating data marts and performing ETL processes to serve business needs in a retail environment. The main tasks include creating a data mart (*RETAIL_DATA_MART*) from source data, transforming it, and answering business questions based on the transformed data. Additionally, a bonus calculation based on customer profitability is required.

**ETL Process:**

1. **Extract**: Read data from the source system or files.
2. **Transform**: Apply necessary transformations such as converting customer names to uppercase and updating date columns.
3. **Load**: Load the transformed data into the designated data marts (*RETAIL_DATA_MART* and *ACTIVATION_SALES_DATA_MART*).

**Business Needs:**

**Data Mart Creation:**

- *RETAIL_DATA_MART*: Includes transaction details for each customer, product, and stock. Customer names are converted to uppercase, and date columns are displayed instead of using a date dimension table.

**Analysis:**

- *ACTIVATION_SALES_DATA_MART*: Displays transaction counts for each customer at each store and identifies the customer type with the highest profit. Additionally, a bonus calculation is performed based on customer profitability.

**Bonus Calculation:**

The bonus is calculated using the equation: `Annual_Incomek$ * SpendingScore * 100`. Customers who generate profit are eligible for the bonus.
