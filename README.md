# Analysis-of-Myntra-Apparel

# Project Overview

This project involves analyzing Myntra's apparel dataset to gain insights into pricing, discounts, ratings, and available sizes. Through data cleaning, preparation, and analysis using Excel functions like `AVERAGEIF`, `COUNTIF`, `XLOOKUP`, and `INDEX & MATCH`, the project provides valuable insights that support strategic decision-making

Dataset Link :  https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

# Problem Statement:

- As a data analyst at Myntra, your task is to analyze apparel-related data to:

Identify pricing trends and discount patterns.

Assess customer ratings and product performance.

Examine size availability and its impact on sales.

These insights will support the management team in making informed decisions to enhance product offerings and sales strategies.

# Project Objectives:

A. Data Cleaning and Preparation

1. Check for duplicate values in your dataset and remove them.

2. Standardize the "DiscountOffer" column to a single format, ensuring all values are uniform.

3. Identify rows where both "DiscountPrice" and "DiscountOffer" are null and fill the "DiscountPrice" with the average discount price    of the respective category.

4. Replace all null values in the "SizeOption" column with the text "Not Available."

B. Data Analysis

1. Calculate the overall average original price for products with ratings greater than 4.

2. Count the number of products with a discount offer greater than 50% OFF.

3. Count the number of products available in size "M."

4. Create a new column to label the products as "High Discount" if the discount offer is greater than 50% OFF, otherwise label them as "Low Discount."

C. Data Retrieval and Lookup

1. Use VLOOKUP/XLOOKUP to find the product brand, price, and rating of the product with Product_id "11226634".

2. Find the "DiscountPrice" for the product with the Product ID "6744434" using the INDEX and MATCH functions.

3. Utilize nested xlookup to find any column’s detail of a product with it’s product id.


Technologies Used:

- Excel for data cleaning, manipulation, and analysis.

- VLOOKUP, XLOOKUP, INDEX, and MATCH functions for efficient data retrieval.

- Data cleaning techniques to enhance dataset quality.


# Project Impact:

By analyzing key factors such as pricing, discounts, ratings, and size availability, this project provides valuable insights to Myntra. These insights will help:

- Optimize pricing and discount strategies for better sales performance.

- Improve product availability based on customer preferences.

- Enhance customer satisfaction through data-driven decision-making.
