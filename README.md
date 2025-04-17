# Sales Data Analysis Project

## Overview
This project analyzes sales data for electronic products stored in a SQLite database. It performs various SQL queries to extract insights about sales performance and visualizes the results using matplotlib.

## Features
- Database setup and sample data insertion
- Comprehensive SQL queries for sales analysis
- Data visualization with bar charts, pie charts, and heatmaps
- Detailed insights about product performance and revenue trends

## Technical Components
- **Database**: SQLite with a sales table containing product information, quantities, prices, and dates
- **Data Processing**: Pandas for SQL query results manipulation
- **Visualization**: Matplotlib and Seaborn for generating charts

## SQL Queries Included
- Total sales summary by product
- Revenue generation analysis
- Product performance metrics (quantity sold, average price)
- Time-based analysis (daily, monthly revenue)
- Best-selling products identification

## Visualizations
The project generates several visualization charts:
1. Revenue by product (bar chart)
2. Revenue by product with conditional coloring (green for high revenue)
3. Revenue share by product (pie chart)
4. Monthly revenue heatmap
5. Top revenue generating products (sorted bar chart)
6. Total quantity sold per product
7. Daily revenue trend

## Key Findings
1. **Top Revenue Drivers**: Laptops, Monitors, and Smartphones lead in revenue
2. **Underperforming Products**: Routers, Printers, and Mice have minimal revenue impact
3. **Value vs. Volume Gap**: Laptops generate highest revenue with few units sold
4. **Monthly Product Shifts**: January favors laptops/smartphones, February shows strong monitor sales
5. **Revenue Trend**: Peak in early January, spike in mid-February, followed by decline
6. **Bundling Opportunity**: Potential for bundling high-volume accessories with high-value items

## Installation & Usage
To run this project:
1. Ensure Python is installed with pandas, matplotlib, and seaborn libraries
2. Connect to an SQLite database named "sales_data.db"
3. Execute the provided code in sequence

## Future Improvements
- Add predictive analytics for future sales trends
- Implement interactive dashboards
- Include geographical sales analysis
- Add customer segmentation analysis
