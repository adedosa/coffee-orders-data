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
	* Handled the missing values in the orders table such as the customer name, email and country using the XLOOKUP function.
	* Used index match to get the dynamic values for coffee type, roast type, size and unit price.
	* Used custom formatting to change date from mm-dd-yyyy format to dd-mmm-yyyy, to change the size values to one decimal place and add kg, and to add currency to the price and sales numbers.
2.  **Descriptive Statistics:**
    * Got the sales by multiplying unit price by the quantity sold to each customer
    * Used multiple IF statements to populate the coffee type names with the full name not the abbreviation
    * [e.g., "Identified the most popular product by counting the occurrences of each product using the `COUNTIF` function."]
3.  **Basic Visualization:**
    * [Describe the charts you created and their purpose, e.g., "Created a bar chart to visualize the total sales for each product."]
    * [e.g., "Generated a line chart to show the trend of daily sales over the month."]
    * *(You can even mention the Excel features you used to create these charts)*

## Key Findings

Based on the analysis, some key findings include:

* [State your first key insight, e.g., "The total sales for January 2025 were $[amount]."]
* [State your second key insight, e.g., "The most popular product was '[Product Name]', accounting for [percentage]% of total sales."]
* [State your third key insight, e.g., "There was a noticeable increase in sales during the second week of January."]
    * *(List 2-3 significant observations from your analysis)*

## Files Included

* `[YourFileName.csv or YourFileName.xlsx]`: The raw dataset used for the analysis.
* `[YourFileName_Analyzed.xlsx]` (Optional): The Excel file containing the formulas, calculations, and charts.
* `README.md`: This file, providing an overview of the project.

## Tools Used

* Microsoft Excel

## Next Steps (Optional)

* [Suggest potential next steps or further analysis, e.g., "Further analysis could involve segmenting customers based on their purchase history." or "Exploring the reasons behind the sales peak in the second week."]

## Author

* [Your Name]
* [Your GitHub Profile Link (Optional)]

---