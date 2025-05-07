# Fashion Retail Sales Dashboard Project

This project showcases an end-to-end Excel-based data analytics dashboard built on fashion retail sales data. It includes data cleaning, transformation, and visualization using pivot charts, slicers, and interactive dashboards.

## Project Overview

* Tools Used: Microsoft Excel
* Key Components:

  * Raw data cleaning and preprocessing
  * Data enrichment (age grouping, currency handling, etc.)
  * Pivot tables and pivot charts
  * Interactive slicers for filters (e.g., channel, month, state, category)
  * Visual graphs for customer segmentation, order trends, and product performance

## Step-by-Step Process

### 1. Data Cleaning

* Imported raw dataset into Excel.
* Removed duplicate and irrelevant rows.
* Standardized column headers.
* Converted date columns to proper date format.
* Split full date into separate columns for Month and Year.
* Added calculated columns like "Age Group" and "B2B" status.
* Ensured numerical values like Amount and Quantity are in consistent format.

### 2. Preparing Clean Data

* Created a new sheet titled "CLEAN DATA" to store cleaned and structured data.
* Verified the consistency of data entries.
* Checked for blank or missing values and addressed them appropriately.

### 3. Creating Pivot Charts

* Selected the cleaned dataset.
* Used the Insert > PivotTable option to create dynamic tables.
* Placed the pivot tables on a new sheet titled "pivot chart".
* Built different pivot tables to summarize:

  * Total revenue by Category
  * Order count by Age Group and Gender
  * Sales by State and Channel
  * Monthly sales trends

### 4. Adding Slicers

* Selected each pivot chart.
* Used the PivotTable Analyze > Insert Slicer tool to add interactive filters.
* Added slicers for:

  * Month
  * Channel
  * Category
  * State
* Connected slicers to multiple pivot tables where appropriate.

### 5. Visual Representation

* Converted pivot tables to pivot charts for better visualization.
* Applied chart types like column charts, pie charts, and bar graphs.
* Customized colors, labels, and legends for clarity.
* Arranged charts and slicers into an interactive dashboard layout.

## File Structure

* PROJECT\_B01\_B02 final.xlsx

  * RAW DATA: Original dataset as received
  * CLEAN DATA: Cleaned and structured version for analysis
  * pivot chart: Contains pivot tables, slicers, and visualizations
  * Sheet1: Miscellaneous or interim data (not used in final analysis)

## Data Columns (CLEAN DATA)

* Order Details: Order ID, Date, Month, Channel, Status, Amount
* Customer Details: Customer ID, Gender, Age, Age Group
* Product Details: Category, Size, Quantity
* Shipping Details: City, State, Country, Postal Code
* B2B: Boolean flag indicating if the transaction was business-related

## Insights

1. Top Sales Channels:

   * Myntra and Amazon were the most frequently used channels.

2. Age Group Distribution:

   * Majority of customers fall under Adult (25-44) age group.
   * Notable purchases from Senior and Teenager groups as well.

3. Monthly Trend:

   * The data mostly centers around December, possibly indicating seasonal or holiday sales.

4. Top Performing Categories:

   * Kurta, Set, and Dress were high-selling categories.

5. Gender Demographics:

   * Predominantly female customers indicating a women-focused fashion line.

6. Geographic Reach:

   * Orders came from diverse states like Punjab, Haryana, Tamil Nadu, and West Bengal.

7. Order Status:

   * Majority marked as Delivered, indicating good order fulfillment rate.

## Visuals

The pivot charts include:

* Sales by Age Group and Gender
* Category-wise Revenue Contribution
* Regional Sales Distribution
* Monthly Sales Trends
* Channel-wise Performance

## How to Use

1. Open the Excel file.
2. Go to the pivot chart sheet.
3. Use slicers (e.g., Month, Channel, Category) to interact with the charts.
4. Explore different demographic and regional segments.

## Data Cleaning Summary

* Removed duplicates and irrelevant entries.
* Converted dates and currency formats.
* Created new columns like Age Group for better analysis.
* Standardized column naming and formats.

## Conclusion

This dashboard is a compact example of how Excel can be used for powerful and interactive business insights, especially in the retail domain. It is perfect for stakeholder presentations and executive reporting.

Feel free to fork this project or use it as a template for similar retail analytics dashboards.
