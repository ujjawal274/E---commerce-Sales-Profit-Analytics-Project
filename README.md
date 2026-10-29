E-Commerce Sales & Profit Analytics — Practice Dataset

Files:
- orders.csv: 47 order records (including one cancelled order)
- customers.csv: 12 customer records
- products.csv: 10 product records

Join keys:
- orders.product_id = products.product_id
- orders.customer_id = customers.customer_id ( *Optional/Additional Customers Analysis* )

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


---
*E-commerce Sales & Profit Analytics Dashboard:*
<img width="1365" height="604" alt="Screenshot 2026-10-27 080955" src="https://github.com/user-attachments/assets/b4a232a3-eed4-49a3-8d70-6b3692592912" />

---
---

*E-commerce Sales & Profit Analytics Final Dashboard:*
<img width="1341" height="548" alt="Screenshot 2026-10-29 170818" src="https://github.com/user-attachments/assets/a7fa38f6-403e-428c-9cc9-cae87f48d7f3" />


---

*Business_Insights(useful_info):*

<img width="722" height="379" alt="Screenshot 2026-10-27 211153" src="https://github.com/user-attachments/assets/2fe7a700-6427-4814-9ea6-a664c4d901b1" />

- Fashion Products ka stock jyada rakhna, Good Quality, Discount dena, Vouchers dena, Goodies dena 
- Insight/useful_info- Business ko har ₹100 ki revenue par lagbhag ₹39.76 profit mil raha hai.(Profit Margin)
  

---


