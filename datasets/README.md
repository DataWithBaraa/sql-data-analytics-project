# Project datasets

The project runs on the `DataWarehouseAnalytics` database. The project video shows two ways to get it.

1. **Restore the backup** `DataWarehouseAnalytics.bak` in SQL Server Management Studio. The backup was made on SQL Server 2022, so it restores on SQL Server 2022 or newer.
2. **Run the script** `scripts/00_init_database.sql`. It creates the database and loads the three gold tables from `csv-files/` with `BULK INSERT`. The paths in the script point to `C:\sql\sql-data-analytics-project\datasets\csv-files\`. Put the files there, or change the three paths to your folder. The folder must be readable by the SQL Server service, so a folder directly on `C:\` works best.

If you built the data warehouse project before this one, you already have the gold layer and can query it directly.

## The CSV files

`csv-files/` holds the full output of the data warehouse project, layer by layer:

| Layer | Files |
|---|---|
| bronze | the six source tables as loaded |
| silver | the six cleaned tables |
| gold | `dim_customers`, `dim_products`, `fact_sales`, `report_customers`, `report_products` |

The project queries use the gold layer only.
