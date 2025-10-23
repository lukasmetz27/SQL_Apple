# SQL_Apple

## Advanced SQL Analysis of Apple Retail Sales Data

This project demonstrates advanced SQL techniques on a dataset of over 1 million rows from Apple retail sales. It highlights the ability to solve real-world business problems, optimize query performance, and extract actionable insights from large-scale datasets.

⸻

### Table of Contents
- Project Overview
- Database Schema
- Skills Highlighted
- Key Business Questions Solved
- Performance Optimization

⸻

### Project Overview

The goal of this project is to analyze Apple retail sales data to provide insights on:
- Store performance across regions and countries
- Product trends over time
- Warranty claims and customer service efficiency

By leveraging advanced SQL features, the project addresses real-world business challenges while demonstrating efficient data processing techniques for large datasets.


### Database Schema

The database consists of five main tables:

<img width="1297" height="734" alt="Bildschirmfoto 2025-10-23 um 15 02 16" src="https://github.com/user-attachments/assets/5f9bdd03-e1ef-495e-af51-ec4c031d6d81" />
<br/>


| Table     | Description     |
|-------------|-------------|
| stores      | Apple retail store information (store ID, name, city, country)    |
| category    | Product categories (category ID, category name)      | 
| products      | Apple product details (product ID, name, launch date, price)    |
| sales    | Sales transactions (sale date, store ID, product ID, quantity)      | 
| warranty    | Warranty claims (claim date, repair status)      |

<br/>

### Skills Highlighted
- Performance Optimization: Created indexes to significantly improve query execution speed
- Window Functions: Used for running totals, ranking, and growth analysis
- Complex Joins & Aggregations: Integrated multiple tables to derive meaningful insights
- Data Segmentation: Analyzed trends across different timeframes, regions, and categories
- Correlation Analysis: Explored relationships between variables such as product price and warranty claims

⸻

### Key Business Questions Solved
- Which stores have the highest sales performance?
- What are the top-selling and least-selling products per country and year?
- What percentage of warranty claims were completed or rejected per store?
- How do product categories perform relative to price and sales trends?
- What insights can be drawn from warranty claim patterns to improve customer satisfaction?

⸻

### Performance Optimization
- Implemented indexes on frequently joined columns to reduce query execution time
- Leveraged CTEs and subqueries for modular and readable SQL
- Optimized aggregations and window functions to handle millions of rows efficiently
