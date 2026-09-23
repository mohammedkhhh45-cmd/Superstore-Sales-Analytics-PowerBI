# 📊 Superstore Retail & Sales Performance Dashboard

An interactive, 2-page executive Power BI dashboard analyzing **$2.30M in total sales** across 9,994 orders for the U.S. Superstore (2014–2017). The project delivers key business insights into financial metrics, customer acquisition trends, product profitability, and shipping logistics.

---

## 📈 Dashboard Previews

### Page 1: Executive Overview & Financial Metrics
<img width="1597" height="807" alt="Screenshot 2026-09-24 003206" src="https://github.com/user-attachments/assets/de79d669-5237-43fe-b647-39edc7304021" />


### Page 2: Customer & Shipping Insights
<img width="1442" height="806" alt="Screenshot 2026-09-24 003231" src="https://github.com/user-attachments/assets/bcde5cf1-7dec-4b5e-bdde-6fc00b793a60" />


---

## 🔑 Key Performance Indicators (KPIs)

* **Total Revenue:** $2.30M
* **Total Profit:** $286.40K
* **Cost of Goods Sold (COGS):** $2.01M
* **Total Units Sold:** 38K
* **Total Orders:** 9,994
* **Total Customers:** 794
* **Average Discount Amount:** $56.71
* **Top Revenue Category:** Technology ($145.4K profit)
* **Top Sub-Category:** Copiers

---

## 🛠️ Data Engineering & Custom DAX Modeling

Custom data transformations were applied using Power Query and DAX:

1. **COGS (Cost of Goods Sold):**
   ```dax
   COGS = [Sales] - [Profit]
