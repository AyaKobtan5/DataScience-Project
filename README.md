#  Global Superstore Sales & Profit Analysis

##  Project Overview

This project explores the **Global Superstore dataset**, a comprehensive retail dataset containing customer orders across multiple regions, product categories, and customer segments.  
It aims to uncover key business insights through **data cleaning, exploratory analysis, and visualizations**, helping to answer critical questions such as:

- Which product categories and subcategories drive the most revenue and profit?
- How do sales and profits change over time (monthly or seasonal trends)?
- Which markets and customer segments are most profitable?
- Are there categories with high sales but low profitability?

##  Objectives

The main goal of this project is to analyze **sales and profit patterns** to identify business opportunities and challenges. Specifically:

- Evaluate top-performing products and regions  
- Detect seasonal sales trends  
- Visualize correlations between key financial metrics  
- Build an interactive dashboard for data-driven decision making  

##  Tools & Libraries

This analysis was conducted using **Python** in a **Jupyter/Google Colab Notebook** with the following libraries:

| Category          | Libraries Used                        |
|------------------|--------------------------------------|
| Data Analysis     | pandas, numpy                         |
| Visualization     | matplotlib, seaborn, plotly           |
| Environment       | Jupyter Notebook / Google Colab       |

##  Project Workflow

###  Dataset Preparation
- Imported and cleaned the dataset (`Global_Superstore2.csv`)  
- Handled duplicates, missing values, and formatted columns  
- Converted date fields into datetime objects  

###  Exploratory Data Analysis (EDA)
- Generated summary statistics  
- Checked missing data and unique values  
- Calculated correlations between numerical columns  

### Data Visualization
Created clear, insightful charts using **Matplotlib** and **Seaborn**:

- **Bar Chart** – Total Sales by Category  
- **Line Chart** – Monthly Sales Trend  
- **Pie Chart** – Sales Distribution by Segment  
- **Heatmap** – Correlation between Sales, Profit, Discount, and Quantity  

###  Dashboard Creation (Interactive)
Using **Plotly**, an interactive dashboard was built that includes:

- Total Sales and Profit by Category  
- Top 10 Products by Sales and Profit  
- Monthly Sales & Profit Trends  
- Correlation Heatmap of Key Metrics  

##  Insights

- Technology leads in total sales; Office Supplies maintain stable profit.  
- Sales and profit peak during holidays; some months show reduced profit due to discounts.  
- Smartphones dominate sales, but high-end copiers yield the highest profit.  
- Sales and profit are strongly correlated, while discounts slightly lower profit.  

##  Key Insights Summary

- **Top Categories:** Technology dominates sales and profit  
- **Seasonality:** Clear spikes in end-of-year performance  
- **Profitability:** Some products have high sales but lower margins  
- **Correlations:** Discounts negatively impact profits  

##  Recommendations

- Focus on high-performing categories and profitable products  
- Review discount policies to maintain healthy margins  
- Align marketing and inventory planning with seasonal demand peaks
