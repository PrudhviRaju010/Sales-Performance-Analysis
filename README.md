# 📊 Sales Performance Analysis Dashboard

## Project Overview

Developed a **comprehensive interactive Sales Performance Dashboard** using Power BI, SQL, and Excel to analyze sales trends, profit performance, and regional insights. This project demonstrates end-to-end data analysis workflow from data extraction to visualization and business insight generation.

**Duration**: [Project Duration]  
**Tools & Technologies**: Power BI, MySQL, SQL, Excel  
**Dataset Size**: [Number of records] transactions across [Time Period]

---

## 🎯 Business Problem & Objectives

### Problem Statement
Organizations need real-time visibility into sales performance across multiple dimensions (regions, products, time periods) to make data-driven decisions and identify growth opportunities.

### Project Objectives
- ✅ Extract and transform raw sales data from MySQL database
- ✅ Identify top-performing regions and product categories
- ✅ Analyze monthly sales trends and growth patterns
- ✅ Compare profit performance across business segments
- ✅ Create an interactive dashboard for executive decision-making
- ✅ Identify underperforming areas for business improvement

---

## 📁 Dataset Information

| Aspect | Details |
|--------|---------|
| **Data Source** | MySQL Superstore Database |
| **Records** | [Total transaction count] |
| **Time Period** | [Date range] |
| **Key Tables** | Orders, Customers, Products, Regions |
| **Data Quality** | Cleaned and validated for accuracy |

### Data Schema
The project uses a **Star Schema** with the following dimension and fact tables:
- **Fact Table**: Orders (sales transactions)
- **Dimension Tables**: Products, Customers, Regions, Dates

---

## 🔍 Key Analysis Performed

### 1. **Sales Performance Analysis**
- Total sales revenue and order count
- Sales trend analysis (month-over-month, year-over-year)
- Regional sales distribution
- Product category performance

### 2. **Profitability Analysis**
- Profit margin calculation by region
- Loss transactions identification
- Profitable vs. unprofitable segments
- Category-wise profit contribution

### 3. **Customer Analysis**
- Top customers by sales value
- Customer-wise profit contribution
- Regional customer concentration

### 4. **Trend Analysis**
- Seasonal sales patterns
- Growth trend identification
- Performance benchmarking

---

## 📈 Key Findings & Insights

| Finding | Impact | Recommendation |
|---------|--------|-----------------|
| **Top Region Performance** | [Region name] contributes [X]% of total sales | Focus marketing investments in this region |
| **Loss Transactions** | [Number] transactions resulted in loss | Review pricing strategy for these products |
| **Product Performance** | [Product name] is the best-performing category | Increase inventory allocation |
| **Seasonal Pattern** | Sales spike in [Month/Quarter] | Plan inventory and staffing accordingly |
| **High-Value Customers** | Top 10% of customers contribute [X]% of revenue | Implement customer retention programs |

---

## 🛠️ Technical Implementation

### Data Processing (SQL)
```sql
-- Example: Market Star Schema Setup
-- Database: MySQL
-- Tables Created: Orders, Products, Customers, Regions
-- Total Records: [Number] transactions
```

**SQL Queries Used**:
- Data extraction and validation
- Aggregation queries for KPI calculation
- Window functions for trend analysis
- Joins across multiple dimension tables

*See `Market_Star_Schema+Setup.sql` for complete schema and data loading scripts.*

### Dashboard Features (Power BI)

**KPI Cards**:
- Total Sales Revenue
- Total Profit
- Number of Orders
- Profit Margin %

**Interactive Visualizations**:
- Sales by Region (Map/Bar Chart)
- Monthly Sales Trend (Line Chart)
- Profit by Category (Stacked Column Chart)
- Top Products Performance (Table)
- Top Customers by Sales (Horizontal Bar)
- Loss Transactions Summary (Table)

**Filters & Slicers**:
- Date Range Selection
- Region Filter
- Product Category Filter
- Customer Segment Filter

---

## 📊 Dashboard Preview

![Sales Analysis Dashboard](SalesAnalysisDashboard.jpg)

*Interactive dashboard with real-time data updates and drill-down capabilities*

---

## 📂 Files Included

| File | Purpose |
|------|---------|
| `Sales Performance Dashboard.pbix` | Power BI dashboard file with all visualizations |
| `Market_Star_Schema+Setup.sql` | SQL schema setup and data loading scripts |
| `SalesAnalysisDashboard.jpg` | Dashboard screenshot for preview |
| `top_customers.csv` | Top 10 customers by sales value |
| `product_profit.csv` | Profit analysis by product category |
| `loss_transactions.csv` | Transactions with negative profit |

---

## 💡 Skills Demonstrated

### Data Analysis & Visualization
- Data modeling and dimensional schema design
- DAX calculations in Power BI
- Advanced Excel analytics
- Business intelligence reporting

### SQL & Database
- Complex SQL queries and aggregations
- Database design and optimization
- Data validation and cleaning

### Business Acumen
- KPI identification and tracking
- Trend analysis and forecasting
- Executive dashboard design
- Data-driven decision making

---

## 🚀 How to Use This Project

1. **Open Power BI File**: `Sales Performance Dashboard.pbix`
2. **Review SQL Scripts**: Execute `Market_Star_Schema+Setup.sql` to recreate the database
3. **Explore Insights**: Use interactive filters to explore different dimensions
4. **Export Reports**: Generate custom reports for specific regions or time periods

---

## 📚 Technical Stack

```
Frontend: Power BI Desktop
Backend: MySQL Database
ETL: SQL Scripts + Power Query
Analytics: DAX Measures & Calculated Columns
Reporting: Power BI Dashboard
```

---

## 🎓 Learning Outcomes

Through this project, I gained expertise in:
- ✅ Database design and implementation
- ✅ Advanced SQL for complex analytics
- ✅ ETL processes and data transformation
- ✅ Power BI dashboard development
- ✅ Business metrics and KPI definition
- ✅ Data storytelling and visualization best practices
- ✅ Executive reporting and presentation

---

## 📌 Future Enhancements

- [ ] Implement predictive sales forecasting using time series analysis
- [ ] Add profitability analysis with cost breakdown
- [ ] Create drill-through reports for granular analysis
- [ ] Integrate real-time data connections
- [ ] Develop mobile-optimized dashboard views
- [ ] Add clustering analysis for customer segmentation

---

## 📞 Contact & Questions

If you have questions about this project or would like to discuss the analysis, feel free to reach out!

**Repository**: [Sales-Performance-Analysis](https://github.com/PrudhviRaju010/Sales-Performance-Analysis)

---

*Last Updated: May 2026*  
*Project Status: ✅ Complete*
