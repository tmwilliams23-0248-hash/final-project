# Black Friday Sales Dashboard

## 1. Dataset Overview

This dataset contains **100,000 rows** and **18 columns**.

### Columns Included in the Dataset

- transaction_id
- customer_id
- age_group
- gender
- city
- customer_segment
- product_id
- product_category
- original_price
- discount_pct

---

# 2. Data Cleaning Process

## Missing Values Check

Data validation techniques were used to verify the dataset for missing or null values. Prior to data visualization, incomplete records were identified and examined to ensure data accuracy.

## Duplicate Records Check

The `transaction_id`, `customer_id`, and `product_id` columns were checked for duplicate entries. Duplicate customer and product records were considered acceptable because customers can make multiple purchases and products may appear in several transactions.

## Consistency Check

The dataset was reviewed for formatting inconsistencies, particularly in the following columns:

- discount_pct
- original_price
- gender
- city
- customer_segment

Standard formatting techniques were applied to maintain consistency throughout the dataset.

---

# 3. Dashboard Visualizations

| Visualization | Columns Used |
|---|---|
| KPI Cards (Total Sales, Total Customers, Total Orders) | total_sales, customer_id, order_id |
| Total Sales by Payment Method (Horizontal Bar Chart) | payment_method, total_sales |
| Total Product Sales by Category (Horizontal Bar Chart) | product_category, total_sales |
| Count of Product ID by City (Pie Chart) | city, product_id |
| Total Sales by Day (Line Chart) | transaction_date, total_sales |
<img width="904" height="508" alt="image" src="https://github.com/user-attachments/assets/97de63ca-13ed-466c-aa8a-ff3305fa7c9a" />

---

# 4. Insights and Recommendations

- The dashboard recorded approximately **766.99K total sales**, with around **3K customers** and **3K orders**, indicating strong Black Friday sales performance.
- **Electronics** generated the highest sales among all product categories.
- **Mobile Wallet** was the most preferred payment method.
- Several cities showed high customer activity, indicating strong regional demand and sales opportunities.
- The business should prioritize high-performing products, improve digital payment support, and focus marketing efforts on top-performing cities and customer segments.

---

# 5. Conclusion

Since the dataset was already organized and cleaned, the project focused mainly on using **Power BI** for dashboard creation, data visualization, and generating business insights.
