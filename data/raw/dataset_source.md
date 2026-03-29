# 📊 Dataset Source

The dataset used in this project is publicly available on Kaggle:

🔗 [https://www.kaggle.com/datasets/YOUR-DATASET-LINK](https://www.kaggle.com/datasets/ssssws/chocolate-sales-dataset-2023-2024)

## 📌 Notes
- The original dataset is not included in this repository due to file size limitations.
- A smaller sample dataset is provided for demonstration purposes.
- To reproduce the analysis:
  1. Download the dataset from the link above
  2. Place it in the `data/raw/` folder
  3. Run the Python notebook

## 📁 The dataset follows a star schema design, commonly used in data warehouses.

1. Sales (Fact Table)
Contains transaction-level sales data.

Columns:

order_id – Unique order identifier
order_date – Date of purchase
product_id – Product identifier
store_id – Store identifier
customer_id – Customer identifier
quantity – Number of items sold
unit_price – Price per unit
discount – Discount applied to the transaction
revenue – Total revenue after discount
cost – Estimated product cost
profit – Profit from the transaction
2. Products
Information about chocolate products.

Columns:

product_id
product_name
brand
category
cocoa_percent
weight_g
3. Stores
Information about retail stores.

Columns:

store_id
store_name
city
country
store_type
4. Customers
Customer demographic information.

Columns:

customer_id
age
gender
loyalty_member
join_date
5. Calendar
Calendar table useful for time-based analysis.

Columns:

date
year
month
day
week
day_of_week
