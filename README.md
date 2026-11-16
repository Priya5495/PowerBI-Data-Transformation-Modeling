
# Power BI – Data Transformation & Data Modeling

## Project Overview

This project focuses on data preparation, transformation, data cleaning, aggregation, and data modeling using Microsoft Power BI and Power Query Editor.

The project uses an E-commerce Sales dataset consisting of three related datasets:

- List of Orders
- Order Details
- Sales Target

The objective is to prepare and organize the datasets, perform data transformations, combine related information, and establish relationships between tables.

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- Data Modeling
- Data Transformation

## Dataset Description

**1. List of Orders**
- Order ID
- Order Date
- Customer Name
- City
- State
- Category
- Amount
- Profit

**2. Order Details**
- Order ID
- Category
- Sub-Category
- Quantity
- Amount
- Profit

**3. Sales Target**
- Category
- Month of Order Date
- Target

## Project Tasks & Implementation

### 1. Data Import
- Imported three CSV datasets into Power BI.
- Used Power Query Editor for data preparation.

### 2. Data Transformation
- Restricted List of Orders to the first 500 rows.
- Changed Order Date to Date format.
- Changed Amount and Target to Fixed Decimal Number.
- Applied Proper Case formatting to Customer Name.

### 3. Custom Column Creation
- Created Location by combining City and State.
- Created Profit Margin using Profit / Amount.
- Created Profit Status using conditional logic:
  - Loss
  - Break-Even
  - Profit

### 4. Data Merging
- Merged List of Orders and Order Details using Order ID.
- Created a new merged query named Orders Data.

### 5. Data Quality
- Checked missing values across datasets.
- Identified and checked duplicate records.
- Applied appropriate data-quality checks.

### 6. Sorting and Filtering
- Sorted Order Date in descending order.
- Applied a State filter to analyze Tamil Nadu orders.

### 7. Data Aggregation
Created summary queries for:
- Count of Order ID
- Average Profit by Category
- Total Amount by Sub-Category
- Total Target by Month of Order Date

### 8. Data Modeling
Established relationships between:
- List of Orders and Order Details using Order ID.
- Order Details and Sales Target using Category.

## Key Skills Demonstrated

- Data Import and Preparation
- Data Cleaning
- Power Query Transformations
- Custom Columns
- Conditional Columns
- Data Merging and Joins
- Grouping and Aggregation
- Data Quality Validation
- Relationship Management
- Data Modeling

## Project Files

- `PowerBI Assignment1.pbix` – Power BI project file.
- `PowerBI Assignment1 Documentation.pdf` – Assignment documentation with screenshots and explanations.
- `Dataset/` – Original CSV datasets 
## Learning Outcome

Through this assignment, I gained practical experience in using Power BI and Power Query Editor to transform, clean, combine, aggregate, and model e-commerce sales data.

This project helped strengthen my foundational Data Analytics and Business Intelligence skills.

---

**Project Type:** Data Analytics – Power BI Assignment 1  
**Module:** Data Analytics Module 2  
**Tool:** Microsoft Power BI
