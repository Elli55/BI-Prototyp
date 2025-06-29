# Sylter Fisch GmbH – Business Intelligence Prototype

This repository contains a prototype Business Intelligence (BI) solution developed as part of a case study for the module **Business Intelligence I (DLMIWBI01)**. The project was created to simulate a BI application for a fictional fast-food fish company with over 400 branches across Germany.

 Objective

The goal of this prototype is to analyze sales data and develop an interactive BI dashboard that supports decision-making for marketing, sales, and logistics teams.

 Contents

- Extraction of operational data from:
  - POS systems (sales transactions)
  - ERP systems (product and stock information)
  - Excel sheets (campaign metadata)
- ETL Process using Python (Google Colab)
- Data cleaning and transformation
- Data modeling using Star Schema
- Interactive Power BI dashboard

# Included Files

- `verkaufsdaten.csv` – Sample sales data
- `produkte.csv` – Product master data
- `kampagnen.csv` – Marketing campaigns
- `filialen.csv` – Branch metadata
- 'SyltFisch.ipynb` – Python script for cleaning and preparing the data
- `dashboard_screenshots/` – Screenshots of the final Power BI report

 📊 Dashboard Features

- Page 1: Key KPIs (net/gross revenue, basket size, MoM growth)
- Page 2: Product performance by time and category
- Page 3: Geographical comparison of store performance
- Page 4: Campaign effectiveness (with campaign flags, discounts, and top products)

 Disclaimer

This is a **personal learning project** and **does not contain any original exam or copyrighted content** from IU Internationale Hochschule. It is based on fictional data and serves educational and demonstrational purposes only.

 Technologies Used

- Python (Pandas, NumPy)
- Google Colab
- Power BI Desktop
- CSV flat files
- Talend Open Studio (mentioned for ETL context)

