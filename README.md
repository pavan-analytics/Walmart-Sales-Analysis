# Walmart-Sales-Analysis
# Walmart Data Analysis: End-to-End SQL + Python + Power BI Project

## Project Overview

This project is a comprehensive data analysis solution designed to extract valuable business insights from Walmart sales data. We utilize Python for data processing, SQL for querying, and Power BI for visualization. The project is structured to help data analysts develop skills in data cleaning, feature engineering, SQL querying, and dashboard creation.

---

## Project Steps

### 1. Set Up the Environment
- **Tools Used**: Visual Studio Code (VS Code), Jupyter Notebook, Python, MySQL, Power BI
- **Goal**: Create a structured workspace with organized project folders for smooth development and data handling.

### 2. Download and Prepare Walmart Sales Data
- **Data Source**: Kaggle’s Walmart Sales Dataset
- **Dataset Link**: [Walmart Sales Dataset](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
- **Storage**: Save the raw data in the `data/` folder for easy access.

### 3. Install Required Libraries
```bash
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2 openpyxl matplotlib seaborn
```

### 4. Load and Explore the Data
- **Initial Exploration**: Use Pandas functions like `.info()`, `.describe()`, and `.head()` to understand data distribution and structure.

### 5. Data Cleaning (Python)
- **Remove Duplicates**
- **Handle Missing Values**
- **Fix Data Types**
- **Format Currency Values**
- **Validate Data Consistency**

### 6. Feature Engineering
- **Create a `Total Amount` Column**: `total_amount = unit_price * quantity`
- **Enhance Dataset**: Add calculated fields for efficient analysis.

### 7. Load Data into MySQL
- **Set Up MySQL Connection**
- **Create Tables Using SQLAlchemy**
- **Insert Cleaned Data into MySQL**
- **Verify Data Using SQL Queries**

### 8. SQL Analysis: Business Problem Solving
- **Revenue Trends**: Identify sales growth across different time periods.
- **Best-Selling Products**: Determine top-selling categories and items.
- **Branch Performance**: Analyze sales by location.
- **Payment Preferences**: Find out which payment methods customers prefer.
- **Customer Behavior**: Study peak sales periods and rating patterns.

### 9. Power BI Dashboard
- **KPIs**: Total Sales Revenue, Total Quantity Sold, Average Customer Rating, Total Transactions
- **Visuals**: Sales Trend, Top Selling Products, Branch Performance, Payment Distribution, Customer Ratings
- **Slicers**: Date Range, Product Category, Branch, Payment Method
- **Title**: "Walmart Sales Analysis Dashboard"

### 10. Project Documentation & Publishing
- **Store SQL Queries in `mysql_queries.sql`**
- **Jupyter Notebook Analysis in `WalMart.ipynb`**
- **Power BI Dashboard File: `WalMart Sales Analysis Dashboard.pbix`**
- **Upload to GitHub with a README file**

## Results and Insights
- **High-Revenue Branches**: Identify best-performing locations.
- **Best-Selling Products**: Analyze which categories drive the most revenue.
- **Customer Preferences**: Understand peak shopping times and payment trends.
- **Operational Improvements**: Recommend stock and pricing adjustments based on sales performance.

## Future Enhancements
- Automate the data pipeline for real-time insights.
- Integrate with additional data sources.
- Improve dashboard interactivity with drill-through analysis.


## Acknowledgments
- **Data Source**: Kaggle’s Walmart Sales Dataset
- **Inspiration**: Walmart’s business case studies on sales optimization.

