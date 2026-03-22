# 🍕 Pizza Sales Analytics Dashboard

### Power BI + SQL Server | End-to-End Data Analysis Project

---

## 📌 Project Overview

This project showcases an **interactive Pizza Sales Dashboard** built using **Power BI**, with backend data stored and analyzed in **SQL Server**.

The objective is to transform raw transactional data into **actionable business insights**, helping stakeholders understand:

* Sales performance
* Customer ordering behavior
* Product performance (best & worst sellers)
* Time-based trends

---

## 🎯 Business Problem

A pizza business wants to:

* Track overall sales performance 📊
* Identify peak sales periods 📅
* Understand customer preferences 🍕
* Optimize menu and pricing strategy 💡

This dashboard provides a **data-driven solution** to these challenges.

---

## 🛠️ Tech Stack

| Tool              | Purpose                            |
| ----------------- | ---------------------------------- |
| Power BI          | Dashboard creation & visualization |
| SQL Server (SSMS) | Data storage & querying            |
| Excel / CSV       | Data source                        |
| DAX               | Data modeling & calculations       |

---

## 📁 Project Structure

```bash
├── data/
│   ├── pizza_sales.csv
│   ├── pizza_sales_excel_file.xlsx
│
├── sql/
│   └── PIZZA SALES SQL QUERIES.docx
│
├── dashboard/
│   └── Pizza_Sales.pbix
│
├── images/
│   ├── home_page.png
│   ├── best_worst_seller_page.png
|   ├── KPIs.png
│   ├── daily_trend_for_total_orders.png
│   ├── monthly_trend_for_total_orders.png
│   ├── percentage_of_sales_by _pizza_category.png
│   ├── percentage_of_sales_by_pizza_size.png
│   ├── total_pizzas_sold_by_pizza_category.png
│   ├── top_5_pizzas_by_revenue.png
│   ├── top_5_pizzas_by_quantity.png
│   ├── top_5_pizzas_by_total_orders.png
│   ├── bottom_5_pizzas_by_revenue.png
│   ├── bottom_5_pizzas_by_quantity.png
│   ├── bottom_5 _pizzas_by_total_orders.png
│
└── README.md
```

---

## 🧾 Dataset Description

The dataset contains pizza sales transactions with the following fields:

* Order ID
* Order Date
* Pizza Name
* Pizza Category (Classic, Chicken, Veggie, Supreme)
* Pizza Size (Small, Medium, Large, XL, XXL)
* Quantity
* Total Price

---

## 📊 KPI Analysis

![KPIs](https://github.com/user-attachments/assets/71fe8d6d-6d92-4763-900d-041deb3c503a)


### 🔹 Total Revenue

* **Definition:** Total income generated from sales
* **Formula:** `SUM(total_price)`
* **Business Value:** Measures overall business performance

---

### 🔹 Average Order Value (AOV)

* **Definition:** Average revenue per order
* **Formula:** `Total Revenue ÷ Total Orders`
* **Business Value:** Indicates customer spending habits

---

### 🔹 Total Pizzas Sold

* **Definition:** Total number of pizzas sold
* **Formula:** `SUM(quantity)`
* **Business Value:** Reflects demand

---

### 🔹 Total Orders

* **Definition:** Number of unique orders
* **Formula:** `COUNT(DISTINCT order_id)`
* **Business Value:** Tracks business volume

---

### 🔹 Average Pizzas Per Order

* **Definition:** Average pizzas in each order
* **Formula:** `Total Quantity ÷ Total Orders`
* **Business Value:** Helps identify upselling opportunities

---

📄 Full SQL queries used for KPI calculation:
👉 

---

## 📈 Dashboard Visualizations & Insights

---

### 🏠 Dashboard Overview

![Dashboard](images/dashboard_home.png)

**Highlights:**

* Total Revenue: **817.86K**
* Total Orders: **21,350**
* Avg Order Value: **38.31**

---

### 📅 Daily Trend Analysis

![Daily Trend](images/daily_trend.png)

**Description:**
Displays total orders/revenue across weekdays.

**Insights:**

* Peak sales occur on **Friday & Saturday evenings**
* Weekends contribute significantly to revenue

---

### 📆 Monthly Trend Analysis

![Monthly Trend](images/monthly_trend.png)

**Description:**
Shows monthly variation in sales.

**Insights:**

* Highest sales in **January & July**
* Drop observed during **September–October**

---

### 🍕 Sales by Pizza Category

![Category](images/category_sales.png)

**Description:**
Revenue contribution by category.

**Insights:**

* **Classic pizzas generate the highest revenue**
* Balanced distribution across categories

---

### 📏 Sales by Pizza Size

![Size](images/size_sales.png)

**Description:**
Revenue distribution by pizza size.

**Insights:**

* **Large pizzas dominate sales**
* Smaller sizes contribute less to revenue

---

### 🥇 Top 5 Pizzas by Revenue

![Top Revenue](images/top5_revenue.png)

**Insights:**

* Best-performing products driving revenue
* Ideal for promotions & marketing focus

---

### 🔻 Bottom 5 Pizzas by Revenue

![Bottom Revenue](images/bottom5_revenue.png)

**Insights:**

* Low-performing items
* Candidates for removal or redesign

---

### 📦 Quantity-Based Analysis

![Quantity](images/quantity_analysis.png)

**Insights:**

* High sales volume doesn’t always mean high revenue
* Pricing strategy impacts performance

---

### 🧾 Orders-Based Analysis

![Orders](images/orders_analysis.png)

**Insights:**

* Identifies frequently ordered pizzas
* Helps in combo & bundle strategy

---

### ⭐ Best & Worst Sellers Dashboard

![Best Worst](images/best_worst.png)

**Insights:**

* Top performers:

  * Thai Chicken Pizza (Revenue)
  * Classic Deluxe Pizza (Orders & Quantity)
* Worst performers:

  * Brie Carre Pizza (lowest across metrics)

---

## 🔍 SQL Analysis Approach

* Aggregations: `SUM`, `COUNT`
* Filtering: `WHERE`
* Grouping: `GROUP BY`
* Ranking: `TOP 5`, `ORDER BY`
* Date Functions: `DATENAME`, `MONTH`

---

## 🚀 How to Run This Project

1. Import dataset into SQL Server
2. Execute SQL queries for analysis
3. Load data into Power BI
4. Build dashboard visuals
5. Apply filters (Category, Date range)

---

## 💡 Key Business Insights

* 📈 Revenue peaks during weekends
* 📅 Seasonal spikes in January & July
* 🍕 Classic category dominates sales
* 📦 Large pizzas generate maximum revenue
* ⚠️ Some menu items underperform significantly

---

## 🔮 Future Enhancements

* Real-time data integration
* Forecasting using time-series models
* Deployment on Power BI Service
* Automated ETL pipeline

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork and improve the project.

---

## 📬 Contact

If you liked this project or want to collaborate, feel free to connect!

---

⭐ **If you found this useful, don’t forget to star the repo!**
