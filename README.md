# sql-data-analytics-project
A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more.
This repository contains SQL queries designed to help data analysts and BI professionals quickly explore, segment, and analyze data within a relational database. Each script focuses on a specific analytical theme and demonstrates best practices for SQL queries.

---
## 🚀 Start here

1. You need SQL Server and SSMS. The course materials carry a setup guide for Windows and Mac: `sql-ultimate-course/00_setup/SETUP GUIDE - read me first.pdf`.
2. Get the `DataWarehouseAnalytics` database in one of two ways. Restore `datasets/DataWarehouseAnalytics.bak` in SSMS (it needs SQL Server 2022 or newer). Or run `scripts/00_init_database.sql`, which creates the database and loads the three gold tables from `datasets/csv-files/`. The script reads them from `C:\sql\sql-data-analytics-project\datasets\csv-files\`: put the files there, or change the three paths.
3. If you built the data warehouse project, you already have the gold layer and can query it directly.
4. The scripts are numbered in the order of the project: `01` to `13`.

`datasets/csv-files/` holds the full output of the data warehouse project, layer by layer: the six bronze tables, the six silver tables, and the gold layer (`dim_customers`, `dim_products`, `fact_sales`, `report_customers`, `report_products`). The project queries use the gold layer only.

---

## ☕ Stay Connected

Let's stay in touch! Feel free to connect with me on the following platforms:

[![YouTube](https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white)](http://bit.ly/3GiCVUE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baraa-khatib-salkini)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.datawithbaraa.com)
[![Newsletter](https://img.shields.io/badge/Newsletter-FF5722?style=for-the-badge&logo=substack&logoColor=white)](https://bit.ly/BaraaNewsletter)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/baraasalkini)
[![Join](https://img.shields.io/badge/Join-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@datawithbaraa)

All Courses and their materials are completely free, and all I ask is your support through subscribing, liking, and commenting on my channel. Your engagement means the world to me and It help the channel!
- ✅ **SQL Full Course:** [Course Link](https://youtu.be/SSKVgrwhzus) | [Download Materials](https://www.datawithbaraa.com/sql-introduction/sql-ultimate-course/) | [GIT Repo](https://github.com/DataWithBaraa/sql-ultimate-course)
- ✅ **Tableau Full Course:** [Course Link](https://www.youtube.com/watch?v=K3pXnbniUcM) | [Download Materials](https://www.datawithbaraa.com/tableau/tableau-thank-you/) | [Public](https://public.tableau.com/app/profile/baraa.salkini/vizzes)

- ✅ **SQL Data Warehouse Project:** [Course Link](https://youtu.be/SSKVgrwhzus) | [Download Materials](https://www.datawithbaraa.com/sql-introduction/advanced-sql-project/) | [GIT Repo](https://github.com/DataWithBaraa/sql-data-warehouse-project)
- ✅ **SQL Exploratory Data Analysis Project:** [Course Link](https://youtu.be/SSKVgrwhzus) | [Download Materials](https://www.datawithbaraa.com/sql-introduction/advanced-sql-analytics-project/) | [GIT Repo](https://github.com/DataWithBaraa/sql-data-analytics-project)
- ✅ **SQL Advanced Data Analysis Project:** [Course Link](https://youtu.be/SSKVgrwhzus) | [Download Materials](https://www.datawithbaraa.com/sql-introduction/advanced-sql-analytics-project/) | [GIT Repo](https://github.com/DataWithBaraa/sql-data-analytics-project)
  
- ✅ **Tableau Sales Project:** [Course Link](https://www.youtube.com/watch?v=dahrmqT5GD4) | [Download Materials](https://datawithbaraa.substack.com/p/access-to-course-materials) | [Public](https://public.tableau.com/app/profile/baraa.salkini/vizzes)
- ✅ **Tableau HR Project:** [Course Link](https://www.youtube.com/watch?v=UcGF09Awm4Y) | [Download Materials](https://datawithbaraa.substack.com/p/access-to-course-materials) | [Public](https://public.tableau.com/app/profile/baraa.salkini/vizzes)
- ✅ **ChatGPT:** [Course Link](https://www.youtube.com/watch?v=LJLNfei4i-c) | [Download Materials](https://datawithbaraa.substack.com/p/access-to-course-materials)

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Baraa Khatib Salkini**, also known as **Data With Baraa**. I’m an IT professional and passionate YouTuber on a mission to share knowledge and make working with data enjoyable and engaging!

Let's stay in touch! Feel free to connect with me on the following platforms:

[![YouTube](https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white)](http://bit.ly/3GiCVUE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baraa-khatib-salkini)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.datawithbaraa.com)
[![Newsletter](https://img.shields.io/badge/Newsletter-FF5722?style=for-the-badge&logo=substack&logoColor=white)](https://bit.ly/BaraaNewsletter)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/baraasalkini)
[![Join](https://img.shields.io/badge/Join-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@datawithbaraa)
