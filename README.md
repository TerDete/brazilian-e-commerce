# Brazilian E-commerce Big Data Project

🔍 **Project Description**
- Built an ETL pipeline to process e-commerce transaction data, handling over **100,000 records** across multiple datasets.
- Collected raw data and stored it in **HDFS**, then processed the data using **Spark (PySpark)**, and finally loaded the clean data into **PostgreSQL**.
- The final dataset is ready for **analysis and reporting**.

This project simulates a real-world Big Data pipeline built on top of the [Brazilian E-commerce dataset (Olist)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).  
It is divided into 2 roles:

🛠 **Data Engineer (on Ubuntu VM)**: 
- Ingest raw data into HDFS
- Clean and transform data using Apache Spark
- Load transformed data into PostgreSQL

📊 **Data Analyst (on Windows)**: 
- Visualize using Power BI

## 🧱 Project Architecture

![Architecture](Images/archi.png)

## 📂 Project Structure
```bash
├── Data/               - Dataset files
├── Images/             - Include images
├── Notebooks/          - Jupyter Notebooks for processing (PySpark)
├── Visualizations/     - Charts and dashboards (Power BI)
└── README.md           
```
## ⚙️ ETL Pipeline (Data Engineer)
- Data ingested from CSV → HDFS
- Cleaned & transformed using Apache Spark
- Loaded to PostgreSQL data warehouse
## 📊 Dashboard (Data Analyst)
- Visualization with Power BI Desktop

## 📈 Visualizations
1. Monthly Revenue in 2018

![Monthly Revenue](Visualizations/monthly_revenue_2018.png)

2. Top 10 Best-Selling Products

![Top 10 Products](Visualizations/top_10_best_selling_products.png)

3. Revenue by Product

![Revenue by_Product](Visualizations/product_revenue_share.png)

## 🛠️ Tools and Technologies
- HDFS
- Apache Spark (PySpark)
- PostgreSQL
- Power BI
- Jupyter Notebook
- Linux
- Git
