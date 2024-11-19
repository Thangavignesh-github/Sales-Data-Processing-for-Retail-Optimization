# Sales Data Pipeline and Visualization Project

## Overview
This project involves creating an end-to-end data pipeline for sales data analysis using Azure Data Factory, Azure Data Lake Storage, and Power BI for visualization. The project focuses on data ingestion, transformation, cleaning, and visualization of meaningful insights from the sales data.

---

## Key Features
1. **Data Pipeline Implementation**: Automated data ingestion, transformation, and storage using Azure Data Factory and Azure Data Lake Storage.
2. **Data Cleaning and Transformation**: Preprocessing steps to handle missing values, outliers, and duplicates, with custom transformations for insights like Total Sales, Average Order Value, and Sales by Product and Location.
3. **Secure Data Handling**: Masking and hashing PII data (e.g., credit card numbers) for secure processing.
4. **Interactive Visualizations**: Dashboards in Power BI for real-time business insights, including Sales Trends, Regional Performance, and Product Contributions.

---

## Tools and Technologies
- **Azure Data Factory (ADF)**: For automating data ingestion and transformation workflows.
- **Azure Data Lake Storage (ADLS)**: For storing raw, cleaned, and transformed datasets.
- **Power BI**: For building interactive and insightful dashboards.
- **PySpark**: For advanced data transformations and analytics.

---

## Key Insights
- **Total Sales**: 34.10K - Highlights the overall performance of the business.
- **Average Order Value (AOV)**: 2.62K - Reflects transaction efficiency.
- **Sales by Product**: Laptops and Phones contribute significantly to total sales.
- **Sales by Location**: Regional distribution of sales emphasizes New York as the top-performing region.
- **Sales Growth Over Time**: Steady growth from 2020 to 2022 highlights a positive trend.

---

## Challenges and Solutions
- **Handling Missing Data**: Filled non-critical missing values with defaults while dropping rows with critical missing fields.
- **PII Security**: Implemented masking and hashing techniques for sensitive credit card data.
- **Data Outliers**: Applied thresholds to filter unrealistic sales values and ensure data integrity.
- **Visualization Design**: Organized the Power BI dashboard with clear, concise visualizations for stakeholders.

---

## Folder Structure
├── Data │ ├── raw-data/ │ ├── cleaned-data/ │ └── transformed-data/ ├── Scripts │ ├── data_ingestion.py │ ├── data_cleaning.py │ ├── data_transformation.py ├── Visualizations │ └── PowerBI_Dashboard.pbix ├── README.md