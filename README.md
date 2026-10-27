E-Commerce Sales & Profit Analytics — Practice Dataset

Files:
- orders.csv: 47 order records (including one cancelled order)
- customers.csv: 12 customer records
- products.csv: 10 product records

Join keys:
- orders.customer_id = customers.customer_id
- orders.product_id = products.product_id

Important definitions:
- Treat only order_status = 'Delivered' as completed sales for primary KPIs.
- gross_sales = quantity * unit_price
- discount_amount = gross_sales * discount_pct
- net_revenue = gross_sales - discount_amount
- product_cost = quantity * unit_cost
- profit = net_revenue - product_cost

Notes:
- This is a synthetic practice dataset, not real company data.
- discount_pct is stored as a decimal (e.g. 0.10 means 10%).
- Use order_date for time-series analysis.
