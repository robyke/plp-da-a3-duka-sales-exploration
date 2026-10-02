# Duka Electronics H1 Sales Exploration

## Project Summary

This project explores Duka Electronics sales data for January to June 2026. The analysis looks at branch performance, product performance, weekday and weekend sales, monthly revenue and Premium online orders using pandas and NumPy.

## Questions Answered

1. Which branches generated the most revenue and the most orders?
2. Which products generated the most revenue and sold the most units?
3. How do weekday and weekend sales compare?
4. Which month had the highest and lowest revenue?
5. How many Premium online orders came from Nairobi and Mombasa, and how much revenue did they generate?

## How to Regenerate the Data

Run `python generate_data.py`.

This creates `duka_sales.csv` using the fixed random seed `2026`.

## How to Run the Notebook

Open `duka_sales_exploration.ipynb` in Google Colab or Jupyter Notebook and run all cells from top to bottom.

## Executive Summary

- Duka Electronics generated **KES 71,792,500** in total revenue from **1,000 orders** during the first half of 2026.
- Nairobi was the strongest branch, producing **KES 26,106,100** from **376 orders**.
- Laptops generated the most product revenue at **KES 41,535,000**, while Tablets sold the most units at **691 units**.
- April was the best revenue month at **KES 13,518,300**, which was **24.0% higher** than June, the weakest month at **KES 10,903,400**.
- Premium online orders from Nairobi and Mombasa totaled **83 orders** and generated **KES 10,218,000** in revenue.
