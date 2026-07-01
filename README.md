# Real-World Retail Shop Data Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on a real-world retail shop dataset. The objective is to analyze sales performance, identify business trends, and generate meaningful insights using data visualization techniques.

## Dataset
The dataset contains retail sales information with the following attributes:

- Ship Mode
- Segment
- Country
- City
- State
- Postal Code
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

## Objectives
- Perform end-to-end data analysis on a real-world retail dataset.
- Analyze sales, profit, and quantity.
- Compare sales across different categories and regions.
- Identify the best-performing product sub-categories.
- Visualize important business insights.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Analysis Performed
- Data loading and inspection
- Statistical summary
- Missing value analysis
- Category-wise sales analysis
- Region-wise sales analysis
- Sub-category sales analysis
- Sales distribution using pie chart
- Sales vs Profit scatter plot
- Profit comparison by category
- Correlation heatmap
- Business insights and conclusions

## Visualizations
- Bar Chart – Sales by Category
- Bar Chart – Sales by Region
- Bar Chart – Sales by Sub-Category
- Pie Chart – Category-wise Sales Distribution
- Scatter Plot – Sales vs Profit
- Box Plot – Profit by Category
- Correlation Heatmap

## Key Findings
- Technology, Furniture, and Office Supplies contribute significantly to overall sales.
- Sales performance varies across different regions.
- Certain product sub-categories generate much higher sales than others.
- Higher sales do not always result in higher profits because discounts affect profitability.
- Sales, Quantity, and Profit are positively correlated, while excessive discounts can reduce profit.

## Conclusion
The analysis provides valuable insights into retail business performance. It helps identify high-performing product categories, profitable regions, and the impact of discounts on profit. These findings can support better inventory management, pricing strategies, and business decision-making.

## How to Run

1. Install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

2. Place `sales_data.csv` in the project directory.

3. Run the Python script:

```bash
python retail_shop_analysis.py
```
