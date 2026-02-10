# Da_ETL14
# Retail Data ETL Pipeline (Google Colab)

## Dataset Columns
InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Folder Structure
raw/        → original dataset  
processed/  → cleaned dataset  
output/     → analytics-ready tables  

## ETL Steps
1. Download raw CSV from Kaggle
2. Load data into Pandas
3. Remove duplicates and missing CustomerID
4. Standardize column names and datatypes
5. Create derived metrics (revenue, margin)
6. Generate business flags (high-value, bulk orders)
7. Split data into customers, orders, products
8. Export outputs as CSV / SQLite
9. Validate row counts before and after transformation

## Tools Used
- Python (Pandas)
- Google Colab
- SQLite
