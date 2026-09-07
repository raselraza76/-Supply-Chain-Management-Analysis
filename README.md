# 🚚 Supply Chain Management Analysis | Power BI

An interactive Power BI dashboard built to analyze supply chain performance across **inventory, warehouses, transportation, orders, products, and sales**. The project provides a clear view of operational performance and helps identify areas that may need attention.

## 📊 Dashboard Preview

![Supply Chain Dashboard](https://raw.githubusercontent.com/raselraza76/-Supply-Chain-Management-Analysis/main/supplychain.png)



## 🎯 Project Overview

This project focuses on understanding how different parts of a supply chain are performing.

The dashboard brings together sales, inventory, warehouse, transportation, and order data to answer practical business questions such as:

* How efficiently are warehouses being utilized?
* How much inventory is currently available?
* Which categories generate the highest transportation costs?
* What is the current inventory turnover?
* How many orders are fulfilled, pending, or cancelled?
* How are units sold changing over time?
* What could future sales look like?
* How does inventory vary across regions and product categories?

## 🔑 Key KPIs

| KPI                   | Value |
| --------------------- | ----: |
| Warehouse Utilization | 34.08 |
| Days of Inventory     | 15.56 |
| Inventory Turnover    | 23.47 |
| Fulfilled Orders      |   838 |
| Pending Orders        |   248 |
| Cancelled Orders      |   114 |

## 📈 Dashboard Features

### 1. Warehouse Analysis

* Warehouse utilization
* Inventory days
* Inventory turnover
* Warehouse performance overview

### 2. Transportation Analysis

* Transportation cost by category
* Transportation cost by region
* Transportation cost comparison across product categories

### 3. Sales & Forecasting

* Units sold by year
* Historical sales trend
* Future sales forecast up to 2030

### 4. Inventory Analysis

* Inventory by category
* Regional inventory comparison
* Category-wise inventory distribution

### 5. Order & Backorder Analysis

* Fulfilled orders
* Pending orders
* Cancelled orders
* Total backorders by order status

## 🗂️ Dataset

The project uses multiple datasets to create a connected supply chain analysis model.

### `orders.csv`

Contains order and sales information.

**Main columns:**

* OrderID
* CustomerID
* ProductID
* OrderDate
* Quantity
* SalesAmount

### `products.csv`

Contains product master information.

**Main columns:**

* ProductID
* ProductName
* Category
* UnitCost

### `warehouses.csv`

Contains warehouse information.

**Main columns:**

* WarehouseID
* City
* Capacity

### `inventory.csv`

Contains inventory and stock information.

**Main columns:**

* InventoryID
* ProductID
* WarehouseID
* Date
* StockQty

### `transport.csv`

Contains transportation and logistics information.

**Main columns:**

* TransportID
* Mode
* Carrier

## 🔗 Data Model

The datasets are connected using common keys such as:

```text
Products
   │
   ├──────── Orders
   │
   └──────── Inventory
                 │
                 └──── Warehouses

Orders ───────── Transportation
```

The relationships allow the dashboard to analyze supply chain performance from different perspectives.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Cleaning**
* **Data Transformation**
* **Data Visualization**
* **Forecasting**

## 📌 Key Insights

From the dashboard, several useful observations can be made:

* Warehouse utilization is relatively low compared with the available capacity.
* Inventory turnover indicates that stock is moving through the supply chain regularly.
* Transportation costs vary across different categories and regions.
* Most orders are currently fulfilled, while a smaller number remain pending or cancelled.
* Inventory levels differ between categories and regions.
* The sales trend shows changes over time, while the forecast provides an estimate of future unit sales.

## 💡 Business Recommendations

Based on the analysis, businesses could:

* Improve warehouse space utilization.
* Monitor slow-moving inventory more closely.
* Optimize transportation routes and carriers.
* Maintain appropriate stock levels based on demand.
* Investigate pending and cancelled orders.
* Use demand forecasts to improve future inventory planning.
* Compare regional performance to identify opportunities for improvement.



## 🎓 Skills Demonstrated

Through this project, I practiced:

* Data cleaning and transformation
* Data modeling in Power BI
* DAX measures and calculated metrics
* KPI development
* Inventory analysis
* Warehouse analysis
* Transportation analysis
* Sales trend analysis
* Forecasting
* Interactive dashboard design
* Business-focused data visualization

## 🔗 Live Dashboard

🚀 **[View Interactive Power BI Dashboard](https://app.powerbi.com/groups/me/reports/62899d28-7f2e-4c5a-ac1d-f89c48b348bd/36f408c4b7a45889a9c0?ctid=f438d128-033e-45cd-8dde-1ffdce68e24c&experience=power-bi)**

## 👨‍💻 About the Project

This project was created as part of my **Data Analytics portfolio** to practice working with real-world business problems and transform raw supply chain data into an interactive and easy-to-understand Power BI dashboard.

