# Sales Performance Analysis — Power BI

## 📊 Project Overview

This project presents an interactive **Sales Performance Dashboard** built using Microsoft Power BI.

The dashboard analyzes sales performance across different **countries, products, customer segments, and years**, while providing key business metrics such as total sales, gross sales, COGS, profit, and average sales.

The goal of this project is to transform raw sales data into an interactive dashboard that can support business performance analysis and decision-making.

---

## 🎯 Project Objectives

- Analyze overall sales performance
- Compare sales across different countries
- Analyze sales performance by product
- Compare different customer segments
- Track sales performance across years
- Analyze units sold by country
- Monitor gross sales, COGS, and profit
- Provide interactive filtering for business analysis

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Visualization**

---

## 📁 Dataset

The project uses an Excel-based sales dataset containing information related to:

- Country
- Product
- Segment
- Year
- Sales
- COGS
- Gross Sales
- Profit
- Units Sold
- Other sales-related attributes

The dataset contains sales information across multiple countries, products, customer segments, and years.

---

## 🔄 Data Preparation

The data was imported into Power BI and prepared for analysis using **Power Query**.

Key steps included:

- Importing the Excel dataset
- Reviewing and validating data types
- Cleaning and transforming the dataset
- Preparing fields for visualization
- Creating calculated measures using DAX
- Building the Power BI data model for analysis

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Sales | 118.73M |
| Total COGS | 102M |
| Total Gross Sales | 128M |
| Total Profit | 16.89M |
| Average Sales | 169.61K |

---

## 📈 Dashboard Analysis

### 1. Total Sales by Country

A column chart compares total sales across countries, helping identify the countries contributing the most to overall sales.

### 2. Sales by Year and Segment

A line chart analyzes sales trends across years for different customer segments.

### 3. Gross Sales vs Total Sales

A donut chart provides a comparison between gross sales and total sales.

### 4. Sales by Product

A pie chart shows the contribution of different products to total sales.

### 5. Units Sold by Country

A bar chart compares the number of units sold across different countries.

### 6. Interactive Filters

The dashboard includes slicers for:

- Country
- Segment

These filters allow users to interactively explore the sales data.

---

## 💡 Key Insights

- Total sales generated in the dataset are approximately **118.73M**.
- Total profit is approximately **16.89M**.
- The dataset contains sales information across five countries.
- Sales performance varies across different customer segments.
- Product-level analysis shows differences in contribution to total sales.
- Country-level analysis helps identify markets with higher sales and unit volumes.
- The dashboard allows users to dynamically filter the analysis by country and customer segment.

---

## 🖼️ Dashboard Preview

![Sales Performance Dashboard](Dashboard/sales_dashboard.png)

---

## 📂 Project Structure

```text
Sales-Performance-Analysis-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── sales_dashboard.pbix
│
├── Dataset/
│   └── sample_data.xlsx
│
└── Dashboard/
    └── sales_dashboard.png
