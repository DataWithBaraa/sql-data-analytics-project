# 📊 SQL Data Analytics Project  

A **comprehensive SQL Exploratory Data Analysis (EDA) project** that demonstrates how to explore, analyze, and derive insights from relational databases.  
This project is designed for **data analysts, BI professionals, and learners** who want hands-on SQL practice.  

The repository contains structured SQL scripts that cover:  
- 🔍 Database exploration  
- 📑 Dimensions & attributes analysis  
- 📆 Date/time-based exploration  
- 📈 Measures & metrics calculations  
- ⚖️ Magnitude comparisons across categories  
- 🏆 Ranking & performance analysis  

---

## 🎯 Project Overview  

This project is inspired by practical SQL workflows where data exploration leads to **actionable insights**.  

It demonstrates three main types of SQL analytics projects:  
1. 🏗️ **Data Warehousing** – Structuring and organizing raw data.  
2. 🔎 **Exploratory Data Analysis (EDA)** – Asking questions and uncovering patterns. *(Focus of this repo)*  
3. 📊 **Advanced Analytics** – Business-driven queries (trends, comparisons, segmentation, reports).  

---

## 🗂️ Dataset & Setup  

To run this project, you can set up the database in **SQL Server** in three ways:  
1. ⚡ **Executing Scripts** – Run `init_database.sql` to create schema & tables.  
2. 📂 **Importing CSVs** – Use SQL Server’s *Import Flat File* wizard.  
3. 💾 **Restoring Backup** – Use the provided `.bak` file to restore the database.  

Tables used:  
- 👤 `DimCustomer` (customer details, demographics, location)  
- 📦 `DimProduct` (product details, categories, cost)  
- 🛒 `FactSales` (sales transactions, quantities, revenue, dates)  

---

## 🧠 Core Concept: Dimensions & Measures  

Understanding the dataset is easier if you separate fields into **Dimensions vs Measures**:  
- 🧩 **Dimensions** → Descriptive attributes (Country, Category, Product, Dates, Gender).  
- 🔢 **Measures** → Numeric values that can be aggregated (Sales Amount, Quantity, Cost, Age).  

This classification is the foundation of almost every analytical query.  

---

## 🛣️ Project Roadmap  

The project follows **six structured steps** for analysis:  

1. 🔍 **Database Exploration** → Inspect tables, columns, metadata.  
2. 🧩 **Dimensions Exploration** → Explore unique values (countries, categories, products).  
3. 📆 **Date Exploration** → Identify time ranges (first/last orders, customer age).  
4. 📊 **Measures Exploration** → Aggregate metrics (sales, quantities, averages).  
5. ⚖️ **Magnitude Analysis** → Compare measures across dimensions (sales by category, revenue by country).  
6. 🏆 **Ranking Analysis** → Identify top/bottom performers (best products, loyal customers, worst sellers).  

---

## 📝 Example Queries  

Here are some representative queries from the project:  

- 📑 **List all tables in the database**  
```sql
SELECT * FROM information_schema.tables;
