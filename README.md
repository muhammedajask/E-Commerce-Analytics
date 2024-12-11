# E-Commerce Analytics Project

This project involves analyzing the sales and profit data of an e-commerce store using Python in a Jupyter Notebook. The analysis is based on the dataset **SampleSuperstore.csv**, which contains various details about sales, products, and customer segments.

## Libraries Used
- **Pandas**: For data cleaning and manipulation
- **Plotly**: For generating interactive visualizations

## Project Overview

In this analysis, we explore several key business questions to gain insights into the store's sales and profits. The following analyses were performed:

1. **Monthly Sales Calculation**: Identifying which month had the highest and lowest sales.
2. **Sales by Product Category**: Analyzing sales across different categories and identifying the highest and lowest performing categories.
3. **Sales Analytics by Sub-Category**: Analyzing the sales performance at the sub-category level.
4. **Monthly Profit Analysis**: Analyzing the monthly profit from sales and identifying which month had the highest profit.
5. **Profit by Category & Sub-Category**: Analyzing profit performance by category and sub-category.
6. **Sales and Profit by Customer Segment**: Breaking down sales and profits by customer segments.
7. **Sales and Profit Ratio by Customer Segment**: Analyzing the ratio of sales to profit by customer segment.

## Dataset

The dataset used in this project is **SampleSuperstore.csv**, which contains the following columns:

- Row ID
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

### Data Cleaning Process

1. **Null Values**: No null values were found in the dataset, so no imputation was necessary.
2. **Data Types**: The **Order Date** and **Ship Date** columns were converted to the correct data types for proper analysis.
3. **New Columns Added**: To analyze the data by month, the following columns were added:
   - **Order Year**
   - **Order Month**
   - **Day of Week**

## How to Use

1. Download the dataset: [SampleSuperstore.csv](./SampleSuperstore.csv)
2. Download the Jupyter Notebook: [E-Commerce Analysis.ipynb](./E-Commerce%20Analysis.ipynb)
3. Open the Jupyter Notebook and run the cells to see the analysis and visualizations.


