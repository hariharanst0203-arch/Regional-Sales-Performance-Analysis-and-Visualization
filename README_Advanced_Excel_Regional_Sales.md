# 📊 Regional Sales Performance Analysis – Advanced Excel Dashboard

## 📌 Project Overview

**Regional Sales Performance Analysis** is an interactive **Advanced Excel dashboard** developed to analyze sales, profitability, quantity sold, discounts, product categories, and regional performance.

The dashboard transforms sales data into business-ready insights using Excel-based data analysis, PivotTables, charts, slicers, formulas, and interactive dashboard design.

## 🎯 Business Objective

The project aims to help stakeholders quickly understand:

- Regional sales performance
- Product-category performance
- Total quantity sold
- Profitability
- Average discount patterns
- Sales contribution by region and category
- Region × Category performance

## 🛠️ Tools & Excel Features Used

| Tool / Feature | Purpose |
|---|---|
| **Microsoft Excel** | Dashboard development and analysis |
| **PivotTables** | Data aggregation and analysis |
| **Charts / PivotCharts** | Data visualization |
| **Slicers** | Interactive filtering |
| **Excel Formulas** | KPI and analytical calculations |
| **Data Cleaning** | Data preparation |
| **Dashboard Design** | Interactive business reporting |

## 📊 Dashboard Components

The dashboard contains:

- Total Sales Amount by Region
- Average Discount Value by Category
- Total Quantity Sold by Category
- Average Sales by Region
- Total Profit by Category
- Total Sales Amount by Region & Category
- Region slicer
- Product Category slicer

## 📈 Key Metrics

### Total Sales Amount by Region

| Region | Total Sales |
|---|---:|
| **East** | 2,595,496.48 |
| **North** | 2,539,669.00 |
| **South** | 2,494,411.28 |
| **West** | 2,480,206.93 |

**Observation:** East records the highest displayed regional sales, while West records the lowest.

### Total Quantity Sold by Category

| Product Category | Quantity Sold |
|---|---:|
| **Furniture** | 21,743 |
| **Clothing** | 21,567 |
| **Sports** | 20,537 |
| **Electronics** | 20,361 |
| **Groceries** | 18,583 |

**Observation:** Furniture has the highest displayed quantity sold, while Groceries has the lowest.

### Total Profit by Category

| Product Category | Total Profit |
|---|---:|
| **Clothing** | 856,347.49 |
| **Furniture** | 835,080.32 |
| **Electronics** | 803,657.96 |
| **Sports** | 797,005.36 |
| **Groceries** | 739,605.38 |

**Observation:** Clothing generates the highest displayed profit, while Groceries generates the lowest.

### Average Discount

Average discount is compared across:

- Clothing
- Electronics
- Furniture
- Groceries
- Sports

The displayed values are approximately **24.5–25.2**, with Furniture showing the highest displayed average discount.

## 🌍 Regional Analysis

The dashboard compares four regions:

- East
- North
- South
- West

The regional analysis makes it possible to identify sales leaders and compare the contribution of each region.

## 🛒 Category Analysis

Five product categories are analyzed:

- Clothing
- Electronics
- Furniture
- Groceries
- Sports

Each category is evaluated using sales, quantity, profit, and average discount, providing a broader view of product performance.

## 📊 Sales by Region & Category

The second visualization compares **Total Sales Amount by Region & Category**.

It enables users to evaluate:

- Which region performs best within each category
- Category-level regional differences
- Strong and weak regional-category combinations
- Opportunities for targeted sales improvement

## 🎛️ Interactive Features

The dashboard includes slicers for:

### Region
- East
- North
- South
- West

### Product Category
- Clothing
- Electronics
- Furniture
- Groceries
- Sports

Changing the slicer selections dynamically filters the relevant dashboard analysis.

## 💡 Key Business Insights

1. **East is the leading region by total sales**, with approximately **2.60M**.
2. **West has the lowest displayed regional sales**, at approximately **2.48M**.
3. **Furniture has the highest quantity sold**, with **21,743 units**.
4. **Groceries has the lowest quantity sold**, with **18,583 units**.
5. **Clothing has the highest displayed total profit**, at approximately **856.35K**.
6. **Groceries has the lowest displayed total profit**, at approximately **739.61K**.
7. **Furniture has the highest displayed average discount**, indicating comparatively higher discount activity.
8. The Region × Category analysis shows that performance varies across regional-category combinations.

> **Note:** These observations are based on the values displayed in the project dashboard and are not official external company statistics.

## 🔄 Data Analysis Workflow

```text
Raw Sales Data
      ↓
Data Cleaning & Preparation
      ↓
Excel Calculations
      ↓
PivotTables
      ↓
Charts / PivotCharts
      ↓
Slicers & Interactive Filters
      ↓
Dashboard Design
      ↓
Business Insights
```

## 🧹 Data Preparation

Typical preparation activities include:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Standardizing region names
- Standardizing product categories
- Validating sales and profit values
- Creating required calculated fields
- Preparing data for PivotTable analysis

## 🧮 Example Excel Calculations

```excel
=SUM(Sales_Amount)
```

```excel
=SUM(Profit)
```

```excel
=SUM(Quantity_Sold)
```

```excel
=AVERAGE(Discount)
```

```excel
=AVERAGE(Sales_Amount)
```

> Adjust the formulas to match the actual column names in the source workbook.

## 📸 Dashboard Preview

### 1. Regional Sales Performance Dashboard

![Regional Sales Performance Dashboard](Screenshot/Dashboard.PNG)

### 2. Sales by Region & Category

![Total Sales by Region and Category](Screenshot/Stacked%20Chart.PNG)

> The `Screenshot` folder must remain in the same repository as `README.md`. The image paths above match the filenames shown in your uploaded dashboard files.

## 📁 Recommended GitHub Repository Structure

```text
Regional-Sales-Performance-Analysis/
│
├── README.md
├── Excel/
│   └── Regional_Sales_Performance_Analysis.xlsx
├── Dataset/
│   └── sales_data.xlsx
└── Screenshot/
    ├── Dashboard.PNG
    └── Stacked Chart.PNG
```

If the source dataset is not licensed for public redistribution, do not upload the raw dataset.

## 🚀 How to Use the Dashboard

1. Download the Excel workbook.
2. Open it using Microsoft Excel.
3. Navigate to the dashboard sheet.
4. Use the **Region** slicer to select a region.
5. Use the **Product Category** slicer to select a category.
6. Review sales, profit, quantity, and discount metrics.
7. Use the Region × Category chart for detailed comparison.
8. Refresh PivotTables when the underlying data is updated.

## 🎓 Skills Demonstrated

- Advanced Microsoft Excel
- Data Cleaning
- Data Analysis
- PivotTables
- PivotCharts / Charts
- Excel Slicers
- Dashboard Development
- KPI Reporting
- Sales Analysis
- Profitability Analysis
- Regional Performance Analysis
- Product Category Analysis
- Interactive Reporting
- Data Visualization
- Business Insight Generation

## 📌 Project Outcome

The final dashboard provides a centralized view of **sales, profit, quantity, discount, regional performance, and product-category performance**.

It demonstrates the ability to transform raw sales data into meaningful KPIs, interactive visualizations, and business insights using **Advanced Excel**.

## 👤 Author

**Hariharan S.**

**Aspiring Data Analyst | MCA Graduate**

**Skills:** Excel • SQL • Power BI • Python • Tableau • Data Analysis

## ⭐ Project Details

| Category | Details |
|---|---|
| **Project Name** | Regional Sales Performance Analysis |
| **Domain** | Sales / Retail Analytics |
| **Project Type** | Data Analytics & Business Intelligence |
| **Primary Tool** | Microsoft Excel |
| **Analysis Focus** | Sales, Profit, Quantity, Discount |
| **Dimensions** | Region & Product Category |
| **Key Features** | PivotTables, Charts, Slicers, Interactive Dashboard |

## 📄 Disclaimer

This project is created for **learning, portfolio, and data analytics demonstration purposes**. The values and insights presented are based on the project dataset and should not be interpreted as official financial or business statistics of any external organization.
