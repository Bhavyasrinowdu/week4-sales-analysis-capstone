# Week 4 Sales Analysis Capstone

## Project Overview

This project analyzes sales data to understand sales performance across different segments, countries, products, years, and months.

Python was used for data cleaning, analysis, visualization, and regression modeling. Microsoft Excel was used for PivotTables and charts, and Power BI was used to create a sales dashboard.

## Objectives

- Clean and prepare the sales dataset.
- Analyze sales performance across different segments.
- Compare sales across countries and products.
- Analyze yearly and monthly sales trends.
- Create visualizations to understand sales performance.
- Build a simple linear regression model to predict sales.
- Create a sales dashboard using Power BI.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Microsoft Excel
- Power BI
- Jupyter Notebook

## Dataset

The dataset contains sales information including:

- Segment
- Country
- Product
- Discount Band
- Units Sold
- Manufacturing Price
- Sale Price
- Gross Sales
- Discounts
- Sales
- COGS
- Profit
- Date
- Month Number
- Month Name
- Year

The dataset contains 700 records and 16 columns.

## Data Cleaning

The following data cleaning steps were performed using Python:

- Checked the dataset structure.
- Checked for missing values.
- Removed duplicate records.
- Filled missing values in the Discount Band column.
- Converted the Date column into date format.
- Standardized column names.
- Saved the cleaned dataset as `cleaned_sales.csv`.

## Data Analysis

Sales were analyzed based on different categories.

### Sales by Segment

Sales were grouped by segment to identify which customer segment generated the highest sales.

### Sales by Country

Sales were grouped by country to compare sales performance across different countries.

### Sales by Product

Sales were grouped by product to identify the best-performing products.

### Sales by Year

Sales were analyzed by year to understand yearly sales performance.

### Monthly Sales

Monthly sales were analyzed to identify sales trends and high-performing months.

## Regression Analysis

A simple Linear Regression model was created using:

- Input: Units Sold
- Target: Sales

The dataset was divided into training and testing sets.

The model was evaluated using:

- Mean Absolute Error (MAE)
- R² Score

An Actual vs Predicted Sales graph was also created to compare the model predictions with actual sales values.

## Key Findings

- Government is the highest-performing sales segment.
- Paseo is the highest-selling product.
- Mexico has the lowest sales among the analyzed countries.
- 2014 has significantly higher sales compared to 2013.
- October has the highest monthly sales.

## Recommendations

- Focus more on the Government segment.
- Continue promoting high-performing products such as Paseo.
- Improve sales strategies in Mexico.
- Study the factors that contributed to the strong performance in 2014.
- Plan marketing campaigns around high-performing months.

## Excel Analysis

Microsoft Excel was used to create PivotTables and charts for:

- Sales by Segment
- Sales by Country
- Sales by Product
- Sales by Year
- Monthly Sales

## Power BI Dashboard

A Power BI dashboard was created to visualize:

- Sales by Segment
- Sales by Country
- Sales by Product
- Sales by Year
- Monthly Sales

The dashboard provides a visual overview of sales performance and makes it easier to identify trends and high-performing areas.

## Project Files

- `cleaned_sales.csv` – Cleaned sales dataset
- `sales_analysis_and_visualization.ipynb` – Python data cleaning, analysis, visualization, and regression model
- `Sales_Analysis.xlsx` – Excel PivotTables and sales analysis
- `Sales_Analysis_Dashboard.pbix` – Power BI sales dashboard
- `final report.docx` – Project report

## Conclusion

The sales analysis provided useful insights into the company's sales performance. The analysis showed differences in sales across segments, countries, products, years, and months.

Python, Excel, and Power BI were used to clean, analyze, visualize, and understand the sales data. The findings and recommendations can help identify strong-performing areas and support better sales strategies.
