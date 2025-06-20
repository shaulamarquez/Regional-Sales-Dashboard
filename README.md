# Sales Beverages Regional Dashboard (2021-2023)
Dataset: [Sales Beverage Data](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales/data)

## Overview

This dataset was created to simulate realistic sales patterns in the beverage industry, highlighting important factors like regional preferences, seasonal fluctuations, and customer segmentation. It features both Business-to-Business (B2B) and Business-to-Consumer (B2C) transactions, making it adaptable for a variety of analytical purposes.

## Project Highlights:
- Built an interactive dashboard tailored to FMCG marketing use cases.

- Processed and checked if the data is cleaned with over 17 million records using Microsoft SQL Server.

- Visualized clean, structured data in Microsoft Power BI, focusing on actionable insights.

This project is an overview of a yearly revenue of 14 regions in Germany from 2021 - 2023:

- Baden-Wurttemberg
- Brandenburg
- Hessen
- Schleswig-Holstein
- Mecklenburg-Vorpommern
- Thüringen
- Saarland
- Sachsen-Anhalt
- Nordrhein-Westfalen
- Bremen
- Thuringen
- Rheinland-Pfalz
- Hamburg
- Niedersachsen
- Sachsen
- Berlin
- Baden-Württemberg
- Bayern

It includes the in-depth look of the following:
- Total Revenue
- Month over Month growth 
- Year over Year growth
- Revenue Comparison: This Year vs Last Year
- Revenue per Product Category
- Top 10 Regions by Revenue
- Top 5 and Bottom 5 Product Category by Revenue

## Dashboard
![image](https://github.com/user-attachments/assets/219feb86-ba96-48d3-957a-6f42cb352791)


## Data Dictionary
- Order_ID - Unique identifier for each order. Groups multiple products within the same order.
- Customer_ID - Unique identifier for each customer, distinguishing individual buyers.
- Customer_Type - Indicates whether the customer is B2B (business-to-business) or B2C (business-to-consumer).
- Product - The name of the product purchased, such as "Coca-Cola" or "Erdinger Weißbier".
- Category - The product category, such as "Soft Drinks" or "Alcoholic Beverages".
- Unit_Price - The price per unit of the product.
- Quantity - The number of units purchased for the specified product in the order.
- Discount - The discount applied to the product (e.g., 0.1 for 10%). Discounts are only given to B2B customers.
- Total_Price - The total price for the product after applying discounts.
- Region - The region of the customer, such as "Bayern" or "Berlin".
- Order_Date - The date when the order was placed.

## Tools Used:
- Microsoft SQL Server (Processed and Checked the Data)

- Microsoft Power BI (Data Visualization and Reporting)

- DAX (Calculated Metrics)

## Executive Summary

- In 2022, revenue grew by 3.9%, rising from $380,046,646.92 in the previous year to $394,859,780.08. The upward trend continued in 2023 with a 1.75% increase, reaching a total revenue of $401,774,736.35.
- A seasonal trend is observed, with a significant decrease in revenue during February, likely due to consumers tightening their budgets after the holiday season. Despite this dip, revenue increased by 3.83% in 2022 and by 3.46% in 2023, indicating overall growth.
- Alcoholic beverages led in sales among all product categories. In 2021, total sales reached $294,552,989.91, with 542,175 orders. This increased by 3.98% in 2022, totaling $306,266,344.48, with 544,028 orders. In 2023, sales continued to grow by 1.54%, reaching $310,978,585.33, with 541,678 orders.
- The best-selling alcoholic beverage in 2021 was Veuve Clicquot, generating $65,695,352.92 in sales. In 2022, sales increased by 3.63%, reaching $68,082,230.28, and continued to rise by 1.06% in 2023, totaling $68,804,315.22.
- The lease selling products are Krombacher, Vittel, Mezzo Mix, Volvic and Warsteiner. With an average of 4.81% increased in 2022 and continued to grow with 1.61% in 2023.
- The best performing region in terms of revenue from 2021 to 2023 was Hamburg.

    - In 2021, total revenue reached $26,632,671.79, with 66,828 orders and 671 customers.

    - In 2022, revenue increased by 3.90% to $27,671,554.16, with 67,584 orders and the same number of customers.

    - In 2023, revenue further increased by 1.79%, totaling $28,166,546.03, with 67,046 orders and 671 customers.

Despite minor fluctuations in order volume, Hamburg consistently maintained strong revenue growth across all three years.

