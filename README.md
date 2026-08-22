# data-sql-warehouse-project
Building a modern data warehouse with SQL Server , including ETL process , data modeling and analytic .

# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

* **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
* **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
* **Scope**: Focus on the latest data only; historical data is not required.
* **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

## 📊 BI: Analytics & Reporting (Data Analytics)

### Objective

Develop SQL-based analytics to deliver detailed insights into:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**
* **Customer Segmentation**
* **Key Performance Indicators (KPIs)**

### Deliverables

* SQL scripts for generating analytical reports.
* Queries for customer and product analysis.
* Sales trend and performance analysis.
* Business insights to support data-driven decision-making.

---

## 🛠️ Technologies & Tools

* **SQL Server**
* **SQL**
* **Git & GitHub**
* **Draw.io** for data modeling and documentation
* **CSV** files for source data

---

## 🏗️ Data Architecture

The project follows a modern **Medallion Architecture** consisting of three layers:

### 1. Bronze Layer

The Bronze layer stores raw data imported directly from the source systems.

* ERP source data
* CRM source data
* Raw CSV files
* No major transformations are applied

### 2. Silver Layer

The Silver layer contains cleaned and transformed data.

* Data cleansing
* Data standardization
* Handling missing values
* Removing duplicates
* Data validation
* Business rule implementation

### 3. Gold Layer

The Gold layer contains business-ready data designed for analytics and reporting.

* Fact tables
* Dimension tables
* Star schema
* Aggregated business metrics
* Analytical views

---

## 🏗️ Data Model

The project uses a **Star Schema** consisting of:

### Fact Tables

* `fact_sales`

### Dimension Tables

* `dim_customers`
* `dim_products`
* `dim_dates`

The data model is designed to provide efficient analytical queries and simplify reporting for business users.

---

## 🔄 ETL Process

The ETL pipeline follows these major steps:

1. Extract data from ERP and CRM CSV files.
2. Load raw data into the Bronze layer.
3. Perform data cleansing and transformation.
4. Integrate ERP and CRM data.
5. Load transformed data into the Silver layer.
6. Create business-ready Gold layer tables.
7. Generate analytical queries and reports.

---

## 📈 Analytics & Insights

The analytics layer focuses on answering important business questions such as:

* What are the monthly and yearly sales trends?
* Which products generate the highest revenue?
* Who are the most valuable customers?
* Which product categories perform best?
* How is customer behavior changing over time?
* What are the overall sales and revenue trends?

---

## 📁 Project Structure

```text
Data-Warehouse-and-Analytics-Project/
│
├── datasets/
│   ├── source_erp/
│   └── source_crm/
│
├── docs/
│   ├── data_model.png
│   └── architecture.png
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
└── LICENSE
```

---

## 🚀 Project Workflow

```text
CSV Source Files
       ↓
   Bronze Layer
       ↓
   Silver Layer
       ↓
    Gold Layer
       ↓
 SQL Analytics
       ↓
 Business Insights
```

---

## 🎯 Project Goals

The main goals of this project are:

* Build a scalable data warehouse using SQL Server.
* Practice real-world ETL and data engineering concepts.
* Apply data cleansing and transformation techniques.
* Build a business-friendly data model.
* Develop SQL-based analytical reports.
* Generate meaningful business insights.
* Follow industry best practices for documentation and project organization.

---

## 📋 Business Questions

The project aims to answer the following business questions:

### Customer Analysis

* Who are the top customers by revenue?
* How many customers are active?
* What is the average order value per customer?
* Which customers contribute the most to total sales?

### Product Analysis

* Which products generate the highest revenue?
* Which products have the highest sales volume?
* Which product categories perform best?
* Which products are underperforming?

### Sales Analysis

* What is the total revenue?
* What is the monthly sales trend?
* What is the yearly sales performance?
* How many orders are placed?
* What is the average sales amount per order?

---

## 📊 Key KPIs

The following KPIs are used to evaluate business performance:

* **Total Sales**
* **Total Revenue**
* **Total Orders**
* **Total Customers**
* **Total Quantity Sold**
* **Average Order Value**
* **Customer Revenue**
* **Product Revenue**
* **Monthly Sales Growth**
* **Yearly Sales Performance**

---

## 🧪 Data Quality Checks

Data quality is an important part of the project. The following checks are performed:

* Identify missing values.
* Remove duplicate records.
* Validate data types.
* Check invalid dates.
* Check negative or incorrect sales values.
* Validate customer and product information.
* Identify unmatched records between ERP and CRM.
* Ensure consistency across source systems.

---

## 📚 Documentation

The project includes documentation covering:

* Data architecture
* Data model
* ETL process
* Data sources
* Data quality rules
* Business logic
* Analytical queries
* Business insights

The documentation is designed to help both technical and business stakeholders understand the complete solution.

---

## 💡 Skills Demonstrated

This project demonstrates practical experience in:

* SQL
* SQL Server
* Data Warehousing
* ETL
* Data Cleaning
* Data Transformation
* Data Integration
* Data Modeling
* Star Schema
* Medallion Architecture
* Data Quality
* Exploratory Data Analysis
* Business Intelligence
* KPI Development
* Analytical Reporting
* Git & GitHub

---

## 👨‍💻 About the Project

This project is created as a portfolio project to demonstrate practical skills in **Data Engineering, SQL, Data Warehousing, ETL, Data Modeling, and Data Analytics**.

It showcases the complete journey from raw data ingestion to actionable business insights.

---

## ⭐ If You Find This Project Useful

If you find this project helpful or interesting, feel free to **star ⭐ the repository** and explore the different SQL scripts and documentation.

Thank you for visiting the **Data Warehouse and Analytics Project**! 🚀

