# Coffee Orders Data Analysis - May 5 2025

## Overview

This project involved analyzing a small dataset of coffee orders for an online store from 2019 till 2022 . The goal was to understand sales trends by identifying the top-selling coffee type, top customers, and sales by each country.  The analysis was performed using Microsoft Excel.
## Dataset

The dataset used in this project is named `coffeeOrdersData.xlsx` and contains 3 tables named:

* **Orders:** This table contains the number of orders places from 2019 - 2022 and contains the Order ID, Date, Customer ID, Product ID and Quantity. This is where the cleaning and analysis was performed.
* **Customers:** This table contains the information about the Customers including their customer ID, Name, Email, Phone number, Loyalty card and full address.
* **Products:** This is the table that has the information about the products in stock such as the Product ID, Coffee type, Roast type, Size, Unit price, and Profit.

The dataset was created for this exercise.

## Analysis Steps

The following steps were taken to analyze the data:

1.  **Data Cleaning:**
    * Checked for and removed any duplicate rows. 
	* Handled the missing values in the orders table such as the customer name, email, country and loyalty cards using the XLOOKUP function.
	* Used index match to get the dynamic values for coffee type, roast type, size and unit price.
	* Used custom formatting to change date from mm-dd-yyyy format to dd-mmm-yyyy, to change the size values to one decimal place and add kg, and to add currency to the price and sales numbers.
2.  **Descriptive Statistics:**
    * Got the sales by multiplying unit price by the quantity sold to each customer
    * Used multiple IF statements to populate the coffee type names with the full name not the abbreviation
    * Converted the orders table to an actual table to make it easier to create 3 pivot tables named TotalSales, Country and Top5Customers. 
3.  **Basic Visualization:**
    * Created a bar chart to visualize the top 5 customers and the total sales by country. 
    * Created a line chart to visulaize the total sales over time.
    * Inserted a timeline to filter the sales by the year
	* Inserted a slicer for the roast type name, size and loyalty card to filter the total sales 

## Key Findings

Based on the analysis, some key findings include:

* The total sales from 2019 till 2022 is 45,134
* The most popular coffee type was Excelsa which had total sales of $12306 and the least popular was the Robusta which sold at $9005 total sales
* The USA has the highest number of sales across all the countries at $35639, and the lowest was the United Kingdom at $2799

## Files Included

* `coffeeOrdersData.xlsx`: The raw dataset used for the analysis.
* `coffeeOrdersDataDayo.xlsx` : The Excel file containing the formulas, calculations, and charts.
* `README.md`: This file, providing an overview of the project.

## Tools Used

* Microsoft Excel


## Author

* Dayo Akerele
* https://www.linkedin.com/in/dayo-akerele/
* https://github.com/adedosa

---