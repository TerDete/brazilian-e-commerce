# Brazilian E-commerce Big Data Project

This project simulates a real-world Big Data pipeline built on top of the [Brazilian E-commerce dataset (Olist)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).  
It is divided into 2 roles:

- 🛠 **Data Engineer (on Ubuntu VM)**: ETL pipeline with HDFS, Apache Spark, PostgreSQL
- 📊 **Data Analyst (on Windows)**: Data visualization with Power BI

---

## 📂 Project Structure
├── Data/             # Raw CSV data
├── Notebooks/        # Jupyter Notebooks
├── powerbi/          # Power BI .pbix file
├── images/           # Screenshots of Power BI dashboard
└── README.md

⚙️ ETL Pipeline (Data Engineer)
Data ingested from CSV → HDFS

Cleaned & transformed using Apache Spark

Loaded to PostgreSQL data warehouse

📊 Dashboard (Data Analyst)
Visualization with Power BI Desktop

🧑‍💻 Tools Used
Storage:	HDFS
Processing:	Apache Spark (PySpark)
Data Warehouse:	PostgreSQL
Visualization:	Power BI