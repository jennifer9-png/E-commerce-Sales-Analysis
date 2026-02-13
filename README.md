# ECommerce Sales Analysis (Superstore Dataset)
# Project Overview
This project explores and analyzes e-commerce sales data to uncover trends, performance insights, and business opportunities. 
The analysis focuses on sales over time, category and regional performance, profitability, and top-selling products.
The purpose of this project is to demonstrate entry-level data analyst skills, including data cleaning, exploratory data analysis (EDA), visualization, and insight generation using Python.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
- Source: Kaggle – Sample Superstore Dataset
- Records: 9,994 rows
- Columns: 21
- Key Fields
- Order Date, Ship Date
- Category, Sub-Category
- Sales, Profit, Quantity, Discount
- Region, State, Segment

## Data Preparation
The following steps were performed to prepare the dataset for analysis:
- Converted date columns to datetime format
- Extracted Month-Year for time series analysis
- Checked for missing values
- Selected numeric columns for statistical analysis
  
## Exploratory Data Analysis & Visualizations
### Monthly Sales Trends
Sales trends were analyzed on a monthly basis to identify seasonality and long-term growth patterns.
Key observations:
- Sales show clear seasonal fluctuations.
-January 2019 recorded the highest monthly sales (≈120,000).
- Overall sales increased steadily from 2016 to 2019.

![monthly sales trends](1mages/MonthlySalesTrend.PNG)

### Sales by Category
Total sales were aggregated by product category to compare overall performance.
Key observations:
- Technology generated the highest total sales.
- Furniture showed comparatively lower sales performance.

![sales by category](1mages/totalsalesbycategory.PNG)

### Sales by Sub-Category
Sales were further analyzed at the sub-category level to identify top-performing product groups.
Key observations:
- A small number of sub-categories contribute disproportionately to total revenue.
- Indicates opportunities for focused inventory and marketing strategies.

![sales by sub-category](1mages/totalsalesbysubcategory.PNG)

### Sales by Region
Regional sales performance was analyzed to identify geographic differences in revenue contribution.
Key observations:
- Certain regions significantly outperform others.
- Regional insights can guide distribution and sales planning.

![sales by region](1mages/totalsalesbyregion.PNG)

### Profit Analysis
Profitability was analyzed alongside sales to assess margin performance.
Key observations:
- High sales do not always translate into high profit.
- Some categories generate strong revenue but weaker profit margins.

![profit analysis](1mages/totalprofitbycategory.PNG)

## Key Insights
- Sales increased year-over-year from 2016 to 2019.
- Technology is the strongest performing category by revenue.
- Profitability varies significantly across categories.
- A small group of products drives a large portion of total sales.
- Sales patterns suggest seasonal peaks that can guide strategic planning.

## Conclusion

This project demonstrates the ability to clean and analyze real-world data, identify trends, create meaningful visualizations, and translate data into actionable business insights.
