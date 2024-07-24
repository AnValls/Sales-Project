# Sales Analysis Project

## Overview
This project analyzes sales data using Python and pandas. We explore monthly sales trends, total sales per product, and visualize the results.

## Data
The data is stored in a CSV file named `ventas.csv`. It contains the following columns:

- **Fecha**: Date of the sale
- **Producto**: Product name
- **Ingresos**: Revenue from the sale

## Steps Taken
1. **Data Cleaning and Preparation**:
   - Removed rows with missing values.
   - Converted the `Fecha` column to datetime format.

2. **Exploratory Data Analysis (EDA)**:
   - Calculated summary statistics for the `Ingresos` column.
   - Grouped data by product to find total sales per product.
   - Grouped data by month to analyze monthly sales.

3. **Visualizations**:
   - Created a bar plot showing total sales per product.
   - Plotted a line chart to visualize monthly sales trends.

## Results
- **Total sales by product**:
  - Product A: $2200
  - Product B: $3300
  - Product C: $1800

- **Monthly sales**:
  - January 2023: $2500
  - February 2023: $1900
  - March 2023: $2900
