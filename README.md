# Nike_Database_II 
SQL Solutions for Customer and Order Analysis
This repository contains SQL scripts designed to solve various business-related questions, focusing on customer segmentation, order completion rates, revenue analysis, and return rates. Each query is crafted to extract specific insights from the database, providing valuable information for business decision-making.

Queries Overview
Total Customers by State

Count the total number of unique customers by state.
Output: state, total_customer.
Total Completed Orders by State

Count the total number of completed orders by state, with special handling for states like 'California' and missing data.
Output: cleaned_state, total_completed_orders.
Completed Orders by State for Nike Official and Nike Vintage

Count the total number of completed orders by state for both Nike Official and Nike Vintage products.
Output: cleaned_state, total_completed_orders, official_completed_orders, vintage_completed_orders.
Total Revenue and Completed Orders by State

Calculate the total revenue and count the number of completed orders by state for both Nike Official and Nike Vintage products.
Output: cleaned_state, total_completed_orders, official_completed_orders, vintage_completed_orders, total_revenue.
Returned Items and Revenue Analysis by State

Calculate the total revenue, count the number of completed orders, and count the number of returned items by state for both Nike Official and Nike Vintage products.
Output: cleaned_state, total_completed_orders, official_completed_orders, vintage_completed_orders, total_revenue, returned_items_count.
Return Rate and Revenue Analysis by State

Calculate the return rate, total revenue, count of completed orders, and count of returned items by state for both Nike Official and Nike Vintage products.
Output: cleaned_state, total_completed_orders, official_completed_orders, vintage_completed_orders, total_revenue, returned_items_count, return_rate.
Detailed SQL Scripts
The SQL scripts are written to work with a relational database containing tables such as order_items, order_items_vintage, orders, and customers. The queries utilize CTEs (Common Table Expressions), UNION operations, and various SQL functions to combine data from multiple tables and perform calculations to derive the desired insights.
