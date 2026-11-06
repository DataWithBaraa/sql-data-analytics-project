# SQL Data Analytics Project

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@datawithbaraa) [![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=udemy&logoColor=white)](https://www.udemy.com/course/sql-for-exploratory-data-analysis-eda-real-world-project/) [![Website](https://img.shields.io/badge/datawithbaraa.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.datawithbaraa.com) [![License](https://img.shields.io/github/license/DataWithBaraa/sql-data-analytics-project?style=for-the-badge&color=2EA043)](LICENSE) [![Stars](https://img.shields.io/github/stars/DataWithBaraa/sql-data-analytics-project?style=for-the-badge&color=F5B301)](https://github.com/DataWithBaraa/sql-data-analytics-project)

The materials of the data analytics project: the data, every query from the videos, and the project roadmap.

⭐ If this project helps you, star the repository so other learners can find it too.

You explore a sales database step by step, then go deeper with trends, segments and two full reports.

**New here? Open the setup guide in the `00_setup` folder.** It walks you through installing SQL Server and creating the database, on Windows and Mac, with the fixes for the common errors.

```
sql-data-analytics-project/
├── 00_setup/                        the setup guide, and the one-click Docker start for Mac
├── 01_datasets/                     the data, as a backup and as CSV files
│   ├── DataWarehouseAnalytics.bak   the database, ready to restore
│   └── csv-files/                   the same data, to build the database yourself
├── 02_docs/                         the project roadmap and notes
└── 03_scripts/                      the queries, in the order of the videos
    └── 00_init_database.sql         builds the database from the CSV files
```

Get the database in one of two ways:

- Restore `01_datasets/DataWarehouseAnalytics.bak` in SSMS. It needs SQL Server 2022 or newer.
- Or run `03_scripts/00_init_database.sql`. It builds the database from the CSV files in `C:\sql\sql-data-analytics-project\01_datasets\csv-files\`.

The videos show the folders without numbers: `datasets` there is `01_datasets` here, `scripts` is `03_scripts`.

<details>
<summary><b>The chapters of both videos</b>: the minute in the video and the script of each one</summary>

**Exploratory data analysis** ([the video](https://youtu.be/6cJ5Ji8zSDg))

| # | Chapter | Video | Script |
|--:|:--|:--|:--|
| 1 | Intro | [0:00:00](https://youtu.be/6cJ5Ji8zSDg?t=0) |  |
| 2 | What is EDA? | [0:00:41](https://youtu.be/6cJ5Ji8zSDg?t=41) |  |
| 3 | Download Project Materials | [0:01:58](https://youtu.be/6cJ5Ji8zSDg?t=118) | [the setup guide](00_setup) |
| 4 | Dimensions & Measures | [0:06:09](https://youtu.be/6cJ5Ji8zSDg?t=369) |  |
| 5 | #1 Database Exploration | [0:11:03](https://youtu.be/6cJ5Ji8zSDg?t=663) | [01_database_exploration.sql](03_scripts/01_database_exploration.sql) |
| 6 | #2 Dimensions Exploration | [0:14:20](https://youtu.be/6cJ5Ji8zSDg?t=860) | [02_dimensions_exploration.sql](03_scripts/02_dimensions_exploration.sql) |
| 7 | #3 Date Exploration | [0:18:08](https://youtu.be/6cJ5Ji8zSDg?t=1088) | [03_date_range_exploration.sql](03_scripts/03_date_range_exploration.sql) |
| 8 | #4 Measures Exploration | [0:23:22](https://youtu.be/6cJ5Ji8zSDg?t=1402) | [04_measures_exploration.sql](03_scripts/04_measures_exploration.sql) |
| 9 | #5 Magnitude Analysis | [0:31:54](https://youtu.be/6cJ5Ji8zSDg?t=1914) | [05_magnitude_analysis.sql](03_scripts/05_magnitude_analysis.sql) |
| 10 | #6 Ranking Analysis | [0:43:05](https://youtu.be/6cJ5Ji8zSDg?t=2585) | [06_ranking_analysis.sql](03_scripts/06_ranking_analysis.sql) |
| 11 | What is Next? | [0:50:01](https://youtu.be/6cJ5Ji8zSDg?t=3001) |  |

**Advanced analytics** ([the video](https://youtu.be/2jGhQpbzHes))

| # | Chapter | Video | Script |
|--:|:--|:--|:--|
| 1 | Intro | [0:00:00](https://youtu.be/2jGhQpbzHes?t=0) |  |
| 2 | What is Data Analytics Project? | [0:00:46](https://youtu.be/2jGhQpbzHes?t=46) |  |
| 3 | Download Project Materials | [0:02:07](https://youtu.be/2jGhQpbzHes?t=127) | [the setup guide](00_setup) |
| 4 | #1 Changes Over Time Analysis | [0:06:39](https://youtu.be/2jGhQpbzHes?t=399) | [07_change_over_time_analysis.sql](03_scripts/07_change_over_time_analysis.sql) |
| 5 | #2 Cumulative Analysis | [0:14:42](https://youtu.be/2jGhQpbzHes?t=882) | [08_cumulative_analysis.sql](03_scripts/08_cumulative_analysis.sql) |
| 6 | #3 Performance Analysis | [0:22:32](https://youtu.be/2jGhQpbzHes?t=1352) | [09_performance_analysis.sql](03_scripts/09_performance_analysis.sql) |
| 7 | #4 Part-To-Whole Analysis | [0:34:56](https://youtu.be/2jGhQpbzHes?t=2096) | [10_part_to_whole_analysis.sql](03_scripts/10_part_to_whole_analysis.sql) |
| 8 | #5 Data Segmentation | [0:42:19](https://youtu.be/2jGhQpbzHes?t=2539) | [11_data_segmentation.sql](03_scripts/11_data_segmentation.sql) |
| 9 | #6 Build Customer Report | [0:58:08](https://youtu.be/2jGhQpbzHes?t=3488) | [12_report_customers.sql](03_scripts/12_report_customers.sql) |
| 10 | #7 Build Product Report | [1:17:21](https://youtu.be/2jGhQpbzHes?t=4641) | [13_report_products.sql](03_scripts/13_report_products.sql) |
| 11 | Commit Code in GitHub | [1:20:58](https://youtu.be/2jGhQpbzHes?t=4858) |  |

The sketches of the project: [Project_Notes_Sketches.pdf](02_docs/Project_Notes_Sketches.pdf).

</details>

---

## 🗺️ What you build

![The project roadmap](02_docs/Project%20Roadmap.png)

The project has two parts, and the scripts follow them:

- **Exploratory data analysis**, scripts `01` to `06`: you get to know the data, from the tables and dates to the big numbers and the top performers.
- **Advanced analytics**, scripts `07` to `13`: you go deeper with trends, running totals, performance, part-to-whole and segments. Two reports close the project, one for customers and one for products.

---

## 🏆 Share your build

Finished the project? Add this badge to the top of your own README, so others can find the original project too.

[![Built with Data With Baraa](https://img.shields.io/badge/Built_with-Data_With_Baraa-F5B301?style=for-the-badge)](https://github.com/DataWithBaraa/sql-data-analytics-project)

```text
[![Built with Data With Baraa](https://img.shields.io/badge/Built_with-Data_With_Baraa-F5B301?style=for-the-badge)](https://github.com/DataWithBaraa/sql-data-analytics-project)
```

Then show your build to the others in [Discussions, Show and tell](https://github.com/DataWithBaraa/sql-data-analytics-project/discussions/categories/show-and-tell).

---

## 🎓 Learn with me

Watch on YouTube, or take the guided version with a certificate on my Academy or Udemy.

| Course | YouTube | My Academy | Udemy |
|:--|:--|:--|:--|
| **SQL** | [Full course](https://youtu.be/SSKVgrwhzus) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe) | [Full Package](https://www.datawithbaraa.com/course/sql-full-course-for-beginners) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/1087406/the-sql-handbook) | [SQL Bootcamp](https://www.udemy.com/course/the-complete-sql-bootcamp-30-hours-go-from-zero-to-hero/?referralCode=D20781228C2EB8B98339) · [SQL for Analytics](https://www.udemy.com/course/sql-mastery-for-data-analytics-and-business-intelligence/) |
| **Python** | [Full course](https://youtu.be/Rq5gJVxz55Q) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZGfFl2ANI_zISzNp257Lwn) | [Full Package](https://www.datawithbaraa.com/course/the-ultimate-python-mastery) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/998313/the-python-handbook) | [Python Bootcamp](https://www.udemy.com/course/the-complete-python-bootcamp-13hours-go-from-zero-to-hero/?referralCode=776491A4119FF8AF41CA) |
| **Tableau** | [Full course](https://youtu.be/K3pXnbniUcM) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZJqrKcUUCWCWPYCrlcVm9v) | [Full Package](https://www.datawithbaraa.com/course/tableau-ultimate-full-course-for-beginners) | [Tableau Course](https://www.udemy.com/course/the-tableau-ultimate-course-from-zero-to-hero/?referralCode=6544726FDC491A6B25EC) · [Chart Masterclass](https://www.udemy.com/course/the-tableau-ultimate-chart-masterclass-63-tableau-charts/) |
| **Power BI** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZge4KDGqGtqgiuVuhVZWzu) | | |
| **Databricks** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZWchr-GE5iPPBmOjiffK6O) | | |

Materials on my website: [SQL](https://www.datawithbaraa.com/wiki/sql) · [Python](https://www.datawithbaraa.com/wiki/python) · [Tableau](https://www.datawithbaraa.com/wiki/tableau) · [Power BI](https://www.datawithbaraa.com/wiki/power-bi)

### The SQL projects

| Project | YouTube | Materials | Udemy |
|:--|:--|:--|:--|
| **Data Warehouse** | [Watch](https://youtu.be/9GVqKuTVANE) | [Repository](https://github.com/DataWithBaraa/sql-data-warehouse-project) | [Building a Modern Data Warehouse](https://www.udemy.com/course/building-a-modern-data-warehouse-data-engineering-bootcamp/) |
| **Exploratory Data Analysis** | [Watch](https://youtu.be/6cJ5Ji8zSDg) | this repository | [SQL for Exploratory Data Analysis](https://www.udemy.com/course/sql-for-exploratory-data-analysis-eda-real-world-project/) |
| **Advanced Data Analytics** | [Watch](https://youtu.be/2jGhQpbzHes) | this repository | |

More on YouTube: [Data projects](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7) · [Data careers](https://www.youtube.com/playlist?list=PLNcg_FV9n7qah95jp-aPtysu7kFCbg7hd)

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/baraa-khatib-salkini/) [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gsVJbMxKcA) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/datawithbaraa/) [![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@datawithbaraa) [![Newsletter](https://img.shields.io/badge/Newsletter-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://www.blog.datawithbaraa.com) [![Notion Roadmaps](https://img.shields.io/badge/Notion_Roadmaps-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.com/@datawithbaraa)

## 🛡️ License

[MIT](LICENSE). Use it, change it, share it, with attribution.

## 🌟 About me

Hi, I'm **Baraa Khatib Salkini**. I spent years in enterprise data engineering and built one of the largest lakehouses at Mercedes-Benz. Today I teach data full-time at **Data With Baraa**: visually, step by step, from zero to hero.
