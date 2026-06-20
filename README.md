# Customer Behavior Analysis Project
<img width="1377" height="775" alt="image" src="https://github.com/user-attachments/assets/db8b9098-791c-4c37-ae17-47e85262e882" />


## Overview

The Customer Behavior Analysis Project is an end-to-end data analytics project designed to analyze customer purchasing patterns, spending behavior, subscription trends, product performance, and revenue contribution across different customer segments.

The project demonstrates the complete analytics lifecycle, including data extraction, cleaning, exploratory data analysis (EDA), SQL-based business analysis, dashboard development, and reporting. The objective is to generate actionable business insights that can support decision-making and improve customer engagement strategies.

---

## Dataset

The dataset contains customer transaction and shopping behavior information, including:

### Key Attributes

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

### Dataset Size

* Approximately 4,000 customer records
* Multiple categorical and numerical variables
* Includes data quality issues such as missing values, duplicates, and inconsistent records for data cleaning practice

---

## Tools & Technologies

| Tool             | Purpose                                 |
| ---------------- | --------------------------------------- |
| Python           | Data Cleaning, EDA, Feature Engineering |
| Pandas           | Data Manipulation and Analysis          |
| NumPy            | Numerical Operations                    |
| PostgreSQL       | Data Storage and SQL Analysis           |
| SQLAlchemy       | Database Connectivity                   |
| Power BI         | Dashboard Development and Visualization |
| Jupyter Notebook | Analysis and Documentation              |
| Git/GitHub       | Version Control and Project Sharing     |

---

## Project Workflow

### Step 1: Data Loading

* Imported dataset into Python using Pandas
* Performed initial inspection of data structure
* Validated column names and data types

### Step 2: Data Cleaning

The following data quality checks were performed:

* Missing value identification and treatment
* Duplicate record detection and removal
* Standardization of categorical values
* Data type corrections
* Outlier detection and handling
* Feature creation (Age Groups, Customer Segments)

### Step 3: Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

* Customer demographics
* Revenue distribution
* Product popularity
* Subscription behavior
* Purchase trends
* Category performance
* Customer loyalty patterns

### Step 4: PostgreSQL Integration

* Created PostgreSQL database
* Loaded cleaned dataset into database tables
* Established connection using SQLAlchemy and Psycopg2
* Executed analytical SQL queries

### Step 5: Business Analysis Using SQL

Key business questions answered include:

* Revenue by Gender
* Subscription vs Non-Subscription Revenue
* Top Products by Review Rating
* Discount Impact Analysis
* Customer Segmentation
* Repeat Buyer Analysis
* Product Performance Analysis
* Age Group Revenue Contribution

### Step 6: Dashboard Development

Created an interactive Power BI dashboard to visualize customer behavior and business performance metrics.

### Step 7: Reporting

Compiled insights, findings, and recommendations into a final analytics report.

---

## Dashboard Overview

The Power BI dashboard includes:

### KPI Metrics

* Total Customers
* Average Purchase Amount
* Average Review Rating

### Customer Analysis

* Subscription Status Distribution
* Gender-Based Analysis
* Age Group Analysis

### Revenue Analysis

* Revenue by Category
* Revenue by Age Group
* Revenue Contribution Analysis

### Sales Analysis

* Sales by Category
* Sales by Age Group

### Interactive Filters

* Subscription Status
* Gender
* Product Category
* Shipping Type

---

## Key Insights

Some notable findings from the analysis include:

* Clothing generated the highest revenue among all categories.
* Young Adult customers contributed the highest revenue share.
* A significant portion of customers were non-subscribers.
* Purchase behavior varied across shipping types and product categories.
* Repeat buyers showed a higher tendency toward subscription-based purchasing.

---

## Project Structure

```text
Customer-Behavior-Analysis/
│
├── data/
│   ├── customer_data.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── exploratory_data_analysis.ipynb
│
├── sql/
│   ├── business_queries.sql
│
├── dashboard/
│   ├── Customer_Behavior_Dashboard.pbix
│
├── reports/
│   ├── Customer_Behavior_Report.pdf
│
└── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
cd Customer-Behavior-Analysis
```

### 2. Install Required Libraries

```bash
pip install pandas numpy sqlalchemy psycopg2-binary openpyxl
```

### 3. Run Data Cleaning & EDA

Open Jupyter Notebook and execute:

```bash
jupyter notebook
```

Run:

* data_cleaning.ipynb
* exploratory_data_analysis.ipynb

### 4. Load Data into PostgreSQL

Update PostgreSQL connection details and execute the database loading script.

### 5. Execute SQL Queries

Run the queries available in:

```text
sql/business_queries.sql
```

### 6. Open Power BI Dashboard

Open:

```text
Customer_Behavior_Dashboard.pbix
```

Refresh the data source if required.

---

## Business Value

This project demonstrates practical skills in:

* Data Cleaning
* Data Analysis
* SQL Querying
* Database Integration
* Dashboard Development
* Business Insight Generation
* End-to-End Analytics Workflow

These skills are directly applicable to Data Analyst and Business Analyst roles across industries.

---

## Author

**Souradip Adhikari**

Data Analyst | Business Analyst | SQL | Python | Power BI | PostgreSQL
