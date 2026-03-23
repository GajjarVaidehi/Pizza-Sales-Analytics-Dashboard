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

## 📈 Dashboard Visualizations & Insights


### 🏠 Dashboard Overview

![home_page](https://github.com/user-attachments/assets/24fc9dab-5cd6-4317-84a2-d091f21eb6a0)

**Highlights:**

* Total Revenue: 817.86K
* Total Orders: 21,350
* Avg Order Value: 38.31

---

### 📅 Daily Trend for Total Orders

![daily_trend_for_total_orders](https://github.com/user-attachments/assets/8ef41872-0847-4ebf-9dbb-7fc14e56b011)


**Visual Type:** Stacked Column Chart

**Description:**
Shows the number of orders placed on each day of the week.

**Business Questions Answered:**

* Which days generate the most orders?
* When should staffing be increased?

**Insights:**

* Peak orders occur on **Friday and Saturday**
* Lower activity during early weekdays

---

### 📆 Monthly Trend for Total Orders

![monthly_trend_for_total_orders](https://github.com/user-attachments/assets/4a132392-654c-4993-a81c-0b9ea6f2b290)


**Visual Type:** Area Chart

**Description:**
Displays total orders across different months.

**Business Questions Answered:**

* What are the seasonal trends in sales?
* Which months perform best?

**Insights:**

* Highest sales in **January and July**
* Noticeable dip during **September–October**

---

### 🍕 Percentage of Sales by Pizza Category

![percentage_of_sales_by _pizza_category](https://github.com/user-attachments/assets/4d4bef67-1d40-408b-9a08-067e5cb38d08)


**Visual Type:** Donut Chart

**Description:**
Represents contribution of each pizza category to total revenue.

**Categories:**

* Classic
* Chicken
* Veggie
* Supreme

**Business Questions Answered:**

* Which category drives the most revenue?

**Insights:**

* **Classic pizzas dominate sales**
* Other categories contribute evenly

---

### 📏 Percentage of Sales by Pizza Size

![percentage_of_sales_by_pizza_size](https://github.com/user-attachments/assets/c588b7a6-743d-4278-b073-55e164494acd)


**Visual Type:** Donut Chart

**Description:**
Shows revenue distribution by pizza size.

**Sizes:**

* Small, Medium, Large, XL, XXL

**Business Questions Answered:**

* Which size is most preferred?

**Insights:**

* **Large pizzas generate the highest revenue**
* Smaller sizes contribute less

---

### 🍕 Total Pizzas Sold by Pizza Category

![total_pizzas_sold_by_pizza_category](https://github.com/user-attachments/assets/eec1a124-de98-4abf-9113-689a0ce5f825)


**Visual Type:** Funnel Chart  

**Description:**  
This chart shows the total number of pizzas sold for each pizza category, such as Classic, Chicken, Supreme, and Veggie.

**Business Questions Answered:**
- Which pizza category is sold the most?
- Which category has the highest customer demand?

**Insights:**
- The **Classic** category has the highest quantity sold, showing strong customer demand.
- Other categories such as **Chicken**, **Supreme**, and **Veggie** contribute less in comparison.
- This chart helps in demand planning, stock management, and category-level promotions.

---

### 🥇 Top 5 Pizzas by Revenue

![top_5_pizzas_by_revenue](https://github.com/user-attachments/assets/b2528cdd-b60e-4309-afb2-ad0acb133581)


**Visual Type:** Stacked Bar Chart

**Description:**
Displays top-performing pizzas based on total revenue.

**Business Questions Answered:**

* Which products generate the most income?

**Insights:**

* High-performing pizzas should be promoted
* Ideal candidates for upselling and combo offers

---

### 🔻 Bottom 5 Pizzas by Revenue

![bottom_5_pizzas_by_revenue](https://github.com/user-attachments/assets/8fadef68-94b4-4282-9054-5cc8fb21b6ec)


**Visual Type:** Stacked Bar Chart

**Description:**
Shows lowest-performing pizzas in terms of revenue.

**Business Questions Answered:**

* Which products are underperforming?

**Insights:**

* Some items may need removal or improvement
* Opportunity to redesign menu strategy

---

### 📦 Top 5 Pizzas by Quantity Sold

![top_5_pizzas_by_quantity](https://github.com/user-attachments/assets/cce00a07-734b-4f09-bfcb-3a5a87bc4df8)


**Visual Type:** Stacked Bar Chart

**Description:**
Ranks pizzas based on number of units sold.

**Business Questions Answered:**

* Which pizzas are most popular?

**Insights:**

* High demand items may not always generate highest revenue
* Important for inventory planning

---

### 🔻 Bottom 5 Pizzas by Quantity Sold

![bottom_5_pizzas_by_quantity](https://github.com/user-attachments/assets/3351245e-c215-4746-ad73-5dd6610cf70e)


**Visual Type:** Stacked Bar Chart

**Description:**
Displays least sold pizzas.

**Insights:**

* Indicates low customer preference
* Candidates for removal or rebranding

---

### 🧾 Top 5 Pizzas by Total Orders

![top_5_pizzas_by_total_orders](https://github.com/user-attachments/assets/af0af87f-6a64-4c5e-b386-2c19b07ea9d6)


**Visual Type:** Stacked Bar Chart

**Description:**
Shows pizzas with the highest number of orders.

**Insights:**

* Frequently ordered items can be used in combo deals
* Indicates strong customer preference

---

### 🔻 Bottom 5 Pizzas by Total Orders

![bottom_5 _pizzas_by_total_orders](https://github.com/user-attachments/assets/42d7b660-69ef-4c6c-aa3b-a0f2edaa6e76)


**Visual Type:** Stacked Bar Chart

**Description:**
Shows pizzas with the least number of orders.

**Insights:**

* Low engagement products
* May need pricing or recipe adjustments

---

### ⭐ Best & Worst Sellers Summary

![best_worst _seller_page](https://github.com/user-attachments/assets/ec957306-32e2-463e-aa49-ff6d5c196a8d)


**Visual Type:** Summary Dashboard

**Description:**
Combines top and bottom performers across:

* Revenue
* Quantity
* Orders

**Insights:**

* **Top Performers:**

  * Thai Chicken Pizza (Revenue)
  * Classic Deluxe Pizza (Orders & Quantity)
* **Worst Performers:**

  * Brie Carre Pizza (consistently low)

---

## 🧠 Overall Business Insights

* 📈 Sales peak during weekends
* 📅 Strong seasonal trends (Jan & July)
* 🍕 Classic pizzas dominate revenue
* 📦 Large pizzas are most preferred
* ⚠️ Some pizzas consistently underperform

---

## 📌 Conclusion

This dashboard enables stakeholders to:

* Monitor performance in real-time
* Identify high and low-performing products
* Make data-driven decisions for pricing, marketing, and operations

---

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

⭐ **If you found this useful, don’t forget to star the repo!**
