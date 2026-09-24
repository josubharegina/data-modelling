# SuperStore Sales Analysis – Power BI Dashboard

## 📊 Project Overview

This project is an interactive **SuperStore Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes sales, profit, orders, customers, products, and regional performance to provide meaningful business insights through interactive visualizations and KPIs.

## 🎯 Objectives

* Analyze overall sales and profit performance.
* Identify high-performing and low-performing products.
* Analyze sales by region, state, and category.
* Understand customer and order trends.
* Track key business performance indicators.
* Create an interactive dashboard for business decision-making.

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculations
* **Data Modeling** – Relationships between tables
* **Microsoft Excel / CSV** – Data source

## 📁 Dataset

The project uses the **SuperStore dataset**, which contains information about:

* Orders
* Customers
* Products
* Categories and sub-categories
* Sales
* Profit
* Quantity
* Discounts
* Shipping
* Regions and locations

## 📌 Dashboard Features

### 1. Sales Overview

Provides a high-level view of business performance using KPIs and charts.

Key metrics include:

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Average Sales

### 2. Product Analysis

Analyzes product and category performance.

Includes:

* Sales by Category
* Profit by Category
* Sub-category performance
* Top-performing products
* Low-performing products

### 3. Regional Analysis

Analyzes geographical performance using:

* Sales by Region
* Profit by Region
* State-wise performance
* Regional comparisons

### 4. Customer & Order Analysis

Provides insights into customer and order behavior.

Includes:

* Customer sales
* Order trends
* Quantity analysis
* Customer performance

## 📈 Key Power BI Concepts Used

* Data Import
* Data Cleaning
* Power Query
* Data Modeling
* Relationships
* DAX Measures
* Calculated Columns
* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Pie/Donut Charts
* Slicers
* Filters
* Interactive Visualizations

## 🧮 Example DAX Measures

```DAX
Total Sales = SUM(SuperStore[Sales])

Total Profit = SUM(SuperStore[Profit])

Total Quantity = SUM(SuperStore[Quantity])

Total Orders = DISTINCTCOUNT(SuperStore[Order ID])

Profit Margin = 
DIVIDE([Total Profit], [Total Sales], 0)
```

> Adjust the table and column names according to the actual names in your Power BI model.

## 🔍 Business Insights

The dashboard can be used to identify:

* Which categories generate the highest sales.
* Which products contribute the most profit.
* Which regions perform strongly or poorly.
* Sales and profit trends over time.
* Products with high sales but low profitability.
* Areas where discounts may affect profitability.

## 📂 Project Files

```text
SuperStore-PowerBI/
│
├── SuperStore_T2.pbix
└── README.md
```

## 🚀 How to Use

1. Download or clone this repository.
2. Open `SuperStore_T2.pbix` using **Power BI Desktop**.
3. Refresh the dataset if required.
4. Use the available slicers and filters to explore the dashboard.
5. Interact with the visualizations to analyze sales and profitability.

## 👩‍💻 Author

**Pradeepa D**
BCA Student | Aspiring Data Analyst / App Developer

### Skills Demonstrated

**Power BI | DAX | Power Query | Data Analysis | Data Visualization | Data Modeling**
