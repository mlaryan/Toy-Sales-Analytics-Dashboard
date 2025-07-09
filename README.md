
# 📊 Business Performance Analysis of Toy Products Across Stores in Mexico

![Alt text](![Alt text](chart.png)

### 📌 Project Overview:
- This project focuses on analyzing a toy business operating across multiple stores in Mexico, selling a wide variety of toy products. The aim is to uncover insights about product sales, profitability, and inventory usage, using Power BI and Python.

### 🎯 Problem Statement:
The business faced key challenges such as:
- Overstocking of underperforming products
- Unbalanced sales across product categories
- Underutilized high-margin items
- Understand Products with high profit margins but low sales volum
- Inventory inefficiencies (e.g: high stock but low sales)

### To tackle these, the analysis spans across stores, categories, and time, providing insights on:
- 📈 Sales and profit trends
- 📦 Inventory inefficiencies
- 🧠 Pricing strategies
- 🏆 Top-performing product categories by store
- 🔎 High-margin products with low sales

### 🧰 Tech Stack:
- Python (Pandas, NumPy, Matplotlib, Seaborn), Power BI, Jupyter Notebook

### 🧹 Data Cleaning Process:
- Loaded raw data using pandas
- Explored the structure using .info(), .describe(), and .isnull().sum()
- Visualized outliers and decided to retain them, since they may reflect real-world business anomalies or exceptional events
- Handled nulls and type mismatches, particularly in Date columns
- Ensured relational consistency across Sales, Products, Inventory, and Stores tables
