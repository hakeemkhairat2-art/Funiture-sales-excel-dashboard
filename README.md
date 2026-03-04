## Furniture Sales Excel Dashboard

Recreated from Freedom Oboh

 ## Overview

This project is a recreation of a Furniture Sales Dashboard originally designed by Freedom Oboh.

The goal of this project was to strengthen my skills in:
 • Data cleaning
 • Power Query transformation
 • Pivot Tables
 • Advanced Excel formulas
 • KPI design
 • Dashboard layout and visual storytelling

Built entirely in Microsoft Excel.

Data Preparation (Power Query)
 1. Imported dataset using Home → Get Data → Transform Data
 2. Corrected data types (Order Date & Ship Date)
 3. Fixed date errors by adjusting Regional Settings (English – United States)
 4. Removed unnecessary columns (Postal Code & Discount)
 5. Converted Sales & Profit to Currency format
 6. Created a custom column for Shipping Duration: Ship Date - Order Date Converted to whole number and added suffix “days”

 7. Extracted Month from Order Date (first 3 letters)
 8. Closed & Loaded cleaned data into Excel

 ## Analysis & Calculations

## Pivot Tables Created For:
 • Total Sales, Profit & Quantity
 • Yearly comparison
 • Monthly Sales Trend
 • Sales by State
 • Top 5 Cities
 • Orders by Shipping Duration (%)
 • Orders by Ship Mode
 • Sales by Sub-Category

## KPI Calculations
 • Linked KPI cards to Pivot Table values
 • Created Current Year & Previous Year comparison

Calculated Year-over-Year %: (Current Year - Previous Year) / Previous

• Custom number formatting for K & M values: [>=1000000]0.0,,"M";[>=1000]0.0,"K";0

• Dynamic YoY indicator: IF(K6>0,"Up ","Down ") & TEXT(ABS(K6),"0%") & " YoY"

## Visualization & Design

Charts Used:
 • Line Chart (Sales Trend)
 • Column Chart
 • Doughnut Chart (Ship Mode)
 • Area Chart (Used instead of Map Chart)

Additional Features:
 • Progress bars created using formulas and cell referencing
 • Dynamic chart titles (INDEX, MATCH, TEXT)
 • Named ranges for cleaner formula management
 • Custom formatting applied using Format Painter
 • Dashboard designed using shapes & layout structuring
 • Gridlines removed for clean UI

## Key Insight
 • Handling regional date errors in Excel
 • Building dynamic KPI cards
 • Creating YoY calculations
 • Designing professional dashboard layouts
 • Turning raw data into business insights

 Credit

This project was recreated for learning purposes.
All design inspiration goes to Freedom Oboh.

## Data Analyst Khairat Hakeem
