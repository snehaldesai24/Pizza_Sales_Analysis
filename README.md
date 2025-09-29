# 🍕 Pizza Sales Analysis Dashboard (PowerBI + SQL + Python)

## 📌 Overview  
This project delivers an **end-to-end sales analytics solution** for a pizza restaurant by combining:  
- **SQL** for data transformation & KPI calculations  
- **Python** for data cleaning, exploratory analysis & automation  
- **Power BI** for dashboard design & interactive visualization  

The analysis uncovers top- and bottom-performing products, sales trends, and revenue drivers—helping guide **menu optimization, marketing strategies, and staffing decisions**.
---

## 🛠 Technologies Used  
- **SQL** – Data cleaning, transformation, and KPI calculation  
- **Power BI** – Dashboard design, data visualization, and interactive analytics  
- **Python (Pandas, Matplotlib, Seaborn, Jupyter)** – Data preprocessing, EDA, and statistical analysis
---

## 📂 Dataset Details  
**File:** `pizza_sales.csv` – Full transactional sales data  

**Key Columns:**  
- `pizza_id` – Unique row ID  
- `order_id` – Order number  
- `pizza_name_id` – Internal pizza code  
- `quantity` – Pizzas sold per line item  
- `order_date` – Transaction date (DD-MM-YYYY)  
- `order_time` – Time of order (HH:MM:SS)  
- `unit_price` – Price per pizza  
- `total_price` – Quantity × Unit price  
- `pizza_size` – S, M, L, XL, XXL  
- `pizza_category` – Classic, Supreme, Veggie, Chicken  
- `pizza_name` – Menu display name  

---

## ❓ Problem Statement  
1. Identify best- and worst-selling pizzas by revenue, quantity, and orders.  
2. Discover peak sales days and months for staffing & promotions.  
3. Optimize the menu based on sales performance.  
4. Enable data-driven marketing and inventory management.  
5. Automate insights using **Python scripts** for reproducibility.  

---

## 📊 KPIs  

| KPI | Value | Description |
| --- | --- | --- |
| **Total Revenue** | 817.86K | Total sales from all orders |
| **Average Order Value (AOV)** | 38.31 | Revenue per order |
| **Total Pizzas Sold** | 49,574 | Units sold |
| **Total Orders** | 21,350 | Unique orders |
| **Avg. Pizzas/Order** | 2.32 | Average items per order |
| **Busiest Days** | Friday & Saturday | Peak sales days |
| **Peak Months** | May, July | Highest order volume |
| **Top Category** | Classic | Most revenue & sales |
| **Top Size** | Large | Best-selling size |

---

## 💡 Key Insights from Power BI Dashboard  

- **Top Seller (Revenue):** Thai Chicken Pizza  
- **Top Seller (Quantity):** Classic Deluxe Pizza  
- **Worst Seller:** The Brie Carre Pizza  
- **Category & Size:** Classic + Supreme contribute over 50% of revenue; Large pizzas dominate sales.  
- **Peak Periods:** Fridays, Saturdays, and months of May & July see the highest demand.  
- **Top 5 by Revenue:** Thai Chicken, Barbecue Chicken, California Chicken, Classic Deluxe, Spicy Italian.  
- **Bottom 5 by Revenue:** Spinach, Mediterranean, Green Garden, The Brie Carre, and others.  

---

## 📈 Power BI Dashboard Features  

1. **Sales Trend Analytics** – Daily, monthly, and yearly revenue trends.  
2. **Product Performance Analysis** – Top & bottom 5 pizzas by multiple metrics.  
3. **Category & Size Distribution** – Revenue breakdown by pizza type & size.  
4. **KPI Cards** – Key performance indicators displayed prominently.  
5. **Interactive Filters** – Slice data by category, size, or time period.

### 🔹 Python (EDA & Automation)  
- Data cleaning & preprocessing with **Pandas**  
- Exploratory analysis with **Matplotlib & Seaborn**  
- Time-series sales trend plots  
- Automated KPI summary reports in Jupyter Notebook  
- Export of **cleaned datasets** for Power BI  

---

## 📦 Files Included  

- `pizza_sales.csv` – Full dataset  
- `Pizza_Sales.sql` – SQL scripts for KPIs & metrics  
- `Pizza_Sales_Analysis.ipynb` – Python notebook for data cleaning & EDA  
- `Pizza Sales Analysis Result.pdf` – Business problem & SQL+Python approach  
- `Pizza_Sales_Dashboard.pbix` – Power BI dashboard file  

---

## 🚀 How to Use  

1. **Run SQL Scripts** – Use `Pizza_Sales_SQL_Queries.sql` in MySQL to prepare KPI datasets.  
2. **Load Data into Power BI** – Import processed data and connect to SQL if needed.  
3. **Explore the Dashboard** – Interact with filters and visuals to uncover insights.  

