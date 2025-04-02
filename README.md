# E-commerce Sales Dashboard

![image alt](https://github.com/PrismaQ/Ecommerce-Analysis/blob/main/Screenshot.png?raw=true)

## Introduction
An interactive Power BI dashboard designed to track and analyze online sales data. It features custom visualizations and filters to explore trends and insights.

## Data Sources
The dashboard uses sample data from `Orders.csv` and `Details.csv`. You can update the source in Power BI with your own Excel or SQL data.

### Orders.csv Information
- **Columns**: orderID, OrderDate, CustomerName, State, City
- **Rows**: 501

### Details.csv Information
- **Columns**: orderID, Amount, Profit, Quantity, Category, Sub-Category, Payment_Method
- **Rows**: 1501

## Methodology

### Data Cleaning
- Reformatted column values for consistency (e.g., date formats, capitalization).
- Created new measures such as total sales, average order value, and profit margins.

### Exploratory Data Analysis
- Analyzed key performance indicators (KPIs) per month.
- Identified the highest profit products.
- Determined top customers based on purchase amounts.
- Analyzed top states with the highest revenue.

## Features
- Interactive bar, pie, and map visualizations
- Custom slicers for dynamic filtering
- Drill-down options for detailed analysis

## License
Licensed under the MIT License. See the `LICENSE` file for details.
