# 📊 Ecommerce Sales Dashboard (Power BI)

An interactive **Power BI dashboard** that analyzes ecommerce order data, covering sales, profit and quantity across states, product categories, customers and shipping modes.

> Built as part of my transition from operations into data analytics, using my background in reporting and process analysis.

## 📸 Dashboard Preview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/196dea66-60f1-41bf-adfc-87af7edabc9c" />
_
## 🎯 What This Dashboard Shows

**KPI cards**
- Total **Sales**
- Total **Profit**
- Total **Quantity** sold

**Filters (slicers)**
- Order Date by **Quarter**
- Product **Category**

**Visuals**

| Visual | What it answers |
|---|---|
| Clustered bar chart | Sales by **State** |
| Donut chart | Quantity sold by **Category** |
| Combo (column + line) chart | **Profit** trend by **Month** |
| Column chart | **Cost** by **Customer Name** |
| Donut chart | Quantity by **Ship Mode** |
| Bar chart | **Profit** by **Sub-Category** |

All visuals respond to the slicers, so you can explore any quarter or category.

## 🗃️ Data Model

- **Table:** `List of Orders`
- **Fields used:** Order Date, Customer Name, State, Category, Sub-Category, Ship Mode, Sales, Profit, Quantity, Cost
- Measures are sums of Sales, Profit, Quantity and Cost, with a date hierarchy (Quarter / Month) on Order Date.

## 👩‍💻 Author

**Bhargavi Vivek**
Operations & Process Analyst moving into IT | SQL · Python · Power BI · Advanced Excel
[GitHub](https://github.com/vivekbhargavi07)
