# Interactive Coffee Sales Excel Dashboard
An interactive Excel dashboard and data analysis project featuring XLOOKUP, INDEX/MATCH, custom formatting, Pivot Tables, and dynamic Slicers.

## Overview
This repository contains an end-to-end Excel portfolio project analyzing historical coffee sales orders across multiple customers, products, and locations. The project demonstrates full data analysis workflows in Microsoft Excel—from data gathering, cleaning, and lookup formulas to pivot table aggregations and creating an interactive executive dashboard.

## Dataset & Files
* **`coffeeOrdersData.xlsx`**: Raw, multi-sheet data containing customer profiles, product details, and sales transaction logs.
* **`coffeeOrdersProject.xlsx`**: Final processed Excel workbook featuring lookup formulas, cleaned tables, pivot charts, dynamic timelines, and the interactive dashboard.

---

## Key Skills & Excel Features Demonstrated

### 1. Data Wrangling & Formulas
* **Lookup Functions (`XLOOKUP` & `INDEX/MATCH`):** Merged customer data (Name, Email, Country) and product details (Coffee Type, Roast, Unit Price) into the main orders dataset across multiple tables.
* **Conditional Logic (`IF` / `NESTED IF`):** Applied conditional logic to calculate roast types and size categories.
* **Calculated Columns:** Computed total sales revenue using dynamic multiplication formulas (`Quantity * Unit Price`).

### 2. Data Cleaning & Standardisation
* **Duplicate Detection:** Identified and removed duplicate records to ensure data integrity.
* **Custom Number & Date Formatting:** Standardised order dates (`YYYY-MM-DD`) and formatted currency values for consistent visualization.
* **Excel Tables (`Ctrl + T`):** Converted raw ranges into structured Excel Tables to enable dynamic data range updating.

### 3. Pivot Tables & Data Visualisation
* Summarised total sales trends over time, sales performance by country, and top customer contributions.
* Formatted Pivot Charts (Line, Bar, and Column charts) with clean, minimal aesthetic styling.

### 4. Interactive Dashboard Construction
* **Dynamic Timelines:** Added a scrollable timeline filter allowing users to filter metrics by month and year.
* **Slicers:** Implemented interactive slicers for coffee roast types, loyalty card status, and product size choices.
* **Slicer Connections:** Linked slicers to multiple Pivot Tables for real-time dashboard updates across all charts.

## Dashboard Preview
<img width="1386" height="778" alt="Screenshot 2026-07-28 054330" src="https://github.com/user-attachments/assets/dfba3684-8730-4136-a553-37445658a9e7" />
