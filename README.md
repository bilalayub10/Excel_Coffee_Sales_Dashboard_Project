# Coffee Sales Dashboard in Excel

## Project Overview

In this project, I transformed raw coffee sales data into an interactive Excel dashboard that provides insightful analytics and visual representations of coffee sales performance. The dataset covers four years (2019, 2020, 2021 & 2022) of coffee orders (sales) data for a coffee store that delivers coffee to three countries: the United States, Ireland, and the United Kingdom.

The dashboard allows users to explore key aspects of coffee sales, track performance over time, and compare data across different countries and periods. With dynamic charts, pivot tables, and interactive filters, this tool offers an intuitive way to visualize and analyze sales trends, helping users make data-driven decisions.

## Project Objectives

The goal of this project was to create an interactive Excel dashboard that provides clear insights into coffee sales performance. Specifically, the objectives of this project were to:

- Display total sales over time through a dynamic chart.          
- Show sales performance by country, highlighting differences across regions.
- Identify the top 5 customers based on total sales.
- Include an interactive timeline to explore sales trends over the four-year period.
- Provide slicers for key variables such as Roast Type Name, Coffee Size, and Loyalty Card status to filter the data dynamically.

## Tools and Technologies

- **Microsoft Excel**: The dashboard was created entirely using Microsoft Excel, utilizing its features like pivot tables, pivot charts, and slicers.

## Data Sources

This project uses three primary [datasets](https://github.com/bilalayub10/Excel_Coffee_Sales_Dashboard_Project/blob/main/coffeeOrdersData.xlsx) to drive the analysis and visualizations in the dashboard:

1. **Orders Data**: Contains detailed information about each coffee order, including order ID, order date, customer ID, product ID and quantity.
  
2. **Customers Data**: Includes information about each customer, such as customer ID, customer name, email, phone number, address, city, country, postcode, and their loyalty card status. 

3. **Products Data**: Provides details on the coffee products, including product ID, coffee type, roast type, size, and unit price.

These datasets were combined and processed within Excel to create the interactive dashboard, enabling dynamic analysis and filtering.

## Data Processing and Analysis

The data processing and analysis for this project involved several key steps to ensure the dataset was well-organized and ready for visualization. The following steps were taken:

1. **Data Integration**: 
   - The **Customers Data** and **Products Data** were combined with the **Orders Data** using Excel functions like `VLOOKUP` and `INDEX-MATCH` to enrich the dataset with additional information about customers and products.

2. **Sales Calculation**: 
   - A new **Sales** column was created by multiplying the **Unit Price** by the **Quantity** for each order, providing a clear view of total sales per transaction.

3. **Data Enrichment**: 
   - Additional columns such as **Coffee Type Name** and **Roast Type Name** were created using the `IF` function to replace abbreviated values in the original columns with their full names. This made it easier to analyze and interpret the data by providing more descriptive information for coffee varieties and roast types.

4. **Data Formatting**:
   - Date and numeric values were properly formatted for consistency and easier analysis.
   - Duplicate entries were identified and removed to ensure the accuracy of the data.
   - The dataset was then converted into a **table** to enable easier data manipulation and ensure consistency across the dataset.

5. **Pivot Table and Chart Creation**:
   - Pivot tables and pivot charts were created to analyze key sales metrics:
     - **Total sales over time**
     - **Sales by country**
     - **Top 5 customers**
   - Formatting was applied to enhance the visual appeal and clarity of these pivot tables and charts.

6. **Interactive Elements**:
   - A **timeline** was inserted to allow users to explore sales trends over different time periods.
   - **Slicers** were added for key variables such as **Roast Type**, **Coffee Size**, and **Loyalty Card status**, making it easier to filter and analyze data dynamically.

7. **Dashboard Creation**:
   - All the pivot charts, timeline, and slicers were combined into a new sheet called the **Dashboard**.
   - The final dashboard was formatted and organized to provide an intuitive, interactive view of the coffee sales data, allowing users to explore the data in a meaningful way. [Click to see Complete Project Excel File](Project (Coffee Sales Dashboard).xlsx)

Below is a screenshot of the finalized coffee sales dashboard created in Excel.

![](https://github.com/user-attachments/assets/02ee361a-9074-4e67-b7f5-715cf3786241)


## Acknowledgments

This project was created with the help of a [tutorial](https://www.youtube.com/watch?v=m13o5aqeCbM) by Mo Chen on his YouTube channel. The tutorial provided valuable guidance in building the coffee sales dashboard using Excel. 






