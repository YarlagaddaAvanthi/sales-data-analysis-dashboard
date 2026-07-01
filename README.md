# Sales Data Analysis & Dashboard

This project analyses a Kaggle sample sales dataset and builds an end-to-end sales dashboard using Python (pandas) and Tableau.

## Dataset

- Source: Kaggle Sample Sales Data.
- Contains order-level information such as order date, product line, customer, country, quantity, and sales amount.

## Tools

- Python (pandas, matplotlib, seaborn) for data cleaning and KPI analysis.
- Tableau for interactive sales dashboard.
- VS Code / Jupyter Notebook for development.

## Project Steps

1. Imported the raw dataset (`sales_data_sample.csv`) and inspected structure.
2. Cleaned the data and created derived fields (Year, Month, Year-Month, Revenue).  
3. Calculated key KPIs:
   - Total sales.
   - Monthly sales trend.
   - Sales by product line.
   - Top customers by sales.
   - Sales by country.
4. Built Tableau worksheets:
   - Monthly Sales Trend.
   - Top Product Lines.
   - Top 10 Customers.
   - Sales by Country.
5. Combined them into a Tableau dashboard.

## Files in this repository

- `sales_analysis.ipynb` – Python notebook for cleaning, KPIs, and visualizations.
- `sales_data_sample.csv` – original Kaggle dataset (if license permits; otherwise link to Kaggle).[web:1]
- `cleaned_sales_data.csv` – cleaned dataset used for the dashboard.
- `sales_analysis_dashboard.twbx` – Tableau workbook containing the dashboard.
- `dashboard_screenshot_*.png` – images of the Tableau dashboard.

## How to run

1. Clone or download this repository.
2. Open `sales_analysis.ipynb` in VS Code or Jupyter Notebook and run all cells.
3. Open `sales_analysis_dashboard.twbx` in Tableau Desktop/Public to explore the interactive dashboard.
