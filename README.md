# 🚀 Big Data Analysis Using PySpark  
### Scalable Retail Data Analytics Project

---

## 📌 Project Objective

The objective of this project is to perform scalable big data analysis on a large Online Retail transaction dataset using **PySpark**.  
The goal is to efficiently process large volumes of structured data and extract meaningful business insights to support data-driven decision-making.

---

## Dataset used

- <a href="https://www.kaggle.com/datasets/ahmadsamsulmuarif/online-retailcsv">Dataset</a>



- 📊 Online Retail Transaction Dataset (CSV format)
- Contains:
  - Invoice Number
  - Stock Code
  - Product Description
  - Quantity
  - Unit Price
  - Customer ID
  - Country
  - Invoice Date
- Large structured dataset suitable for distributed processing.

---

## 🎯 Key Performance Indicators (KPIs)

-  Total Revenue Generated  
-  Top-Selling Products  
-  Country-wise Revenue Contribution  
-  Monthly Sales Trends  
-  Top Customers by Purchase Value  
-  Sales Distribution Analysis  

---

## ⚙️ Project Workflow
- Dataset (CSV)
   ↓
- Data Loading (PySpark DataFrame)
   ↓
- Data Cleaning & Preprocessing
   ↓
- Feature Engineering (TotalAmount)
   ↓
- Data Aggregation & Analysis
   ↓
- Scalability Implementation (Repartitioning)
   ↓
- Visualization & Insights

  
---

## 🔄 Process

- Loaded dataset into **PySpark DataFrame**
- Handled missing and inconsistent data
- Removed invalid transactions (negative quantity/price)
- Created new feature:

  - Performed aggregations using `groupBy()` and Spark functions
- Applied repartitioning to demonstrate scalability
- Converted results into Pandas for visualization

---

## 🛠 Tools & Technologies

| Category | Tools Used |
|----------|------------|
| Platform | Google Colab |
| Framework | Apache Spark (PySpark) |
| Language | Python |
| Libraries | PySpark, Matplotlib |

---

## 📊 Project Insights

- 🔹 A small number of products contribute major revenue.
- 🔹 The United Kingdom generates the highest sales.
- 🔹 Monthly sales show noticeable variation.
- 🔹 High-value customers significantly impact total revenue.
- 🔹 Distributed processing improves performance for large datasets.

---

## ⚡ Scalability Demonstration

- Used Spark distributed DataFrame operations  
- Implemented `repartition()` for parallel execution  
- Leveraged Spark’s lazy evaluation mechanism  

---

## 🏁 Conclusion

This project successfully demonstrates scalable big data analytics using **PySpark**.  
By processing large-scale retail data through distributed computing, meaningful business insights were generated efficiently, showcasing the power of Apache Spark in handling big data workloads.

---

## 📌 Future Enhancements

- Implement performance benchmarking  
- Add advanced visual dashboards  
- Apply machine learning models for sales prediction  
- Deploy using Spark cluster environment  

---


