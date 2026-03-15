Python | Power BI | Data Analysis | EDA

## Olist E-commerce Marketplace Analysis
Data analysis of the Olist Brazilian e-commerce dataset using Python, SQL, and Power BI to uncover sales, customer, and logistics insights.

## Project Overview
This analysis examined the Olist Brazilian E-commerce dataset, containing over 100,000 transactions from sellers and customers across Brazil. To interperated the meaning of the data includes data cleaning, exploratory data analysis (EDA), and a Power BI dashboard.

**Business Questions**

The objective of this analysis was to explore the Olist marketplace dataset to answer several key business questions:

• Which product categories generate the highest revenue on the platform?

• Which regions contribute the most to overall marketplace revenue?

• What payment methods do customers prefer when making purchases?

• Does delivery performance affect customer purchasing behavior?

• Are logistics factors such as freight cost influenced by package weight?

• How has revenue changed over time as the marketplace has grown?

• Which sellers generate the most revenue across the platform?


## Data Set
Original Dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

My Cleaned Data: https://github.com/adunmeye/olist-ecommerce-analysis/blob/main/data/olist_dataset_clean.csv.zip

## Tools Used

1. Python
2. Pandas
3. Matplotlib
4. Seaborn
5. Power BI
6. Jupyter Notebook

## Key Insights
- The **Bed Bath Table** category generated the largest share of revenue, contributing to **8.79% of total sales**.
- Freight costs show little correlation with package weight, suggesting shipping prices are influenced by additional factors such as distance or logistics provider pricing. 
- Customers are heavily concentrated in a few key states, particularly **São Paulo (SP)**, which represents the largest customer base.
- The state of **Paraíba (PB) purchases a higher average price per item**, in comparison to other key states.
- Credit cards are the most commonly used payment method, indicating strong customer preference for this payment type.
- Sellers located in **São Paulo (SP)** generate approximately **66% of Olist’s total marketplace revenue**. 
- Customers across most states frequently **purchase Health & Beauty Products**, making it one of the most consistently popular product categories nationwide.

## Business Recommendations
- Implement targeted **seasonal marketing campaigns** during lower-performing months to stabilize revenue fluctuations. 
- Explore **strategic warehouse placement** or logistics hubs closer to high-volume regions such as  Sāo Paulo(SP) to reduce delivery times.
- Expand the availability of **higher-value product categories** to increase average order value and marketplace profitability.
- Evaluate opportunities to optimize freight costs, as the majority of shipping prices aggregate around **R$20**, indicating potential efficiency improvements in logistics operations.

## Project Workflow

### 1st: Data Cleaning

Cleaned and standardized the dataset using Python and Pandas.

Tasks included:
* Removing null values
* Converting date fields
* Creating derived features (delivery time, order month)

Notebook:
Final visuals will be uploaded shortly._placeholder_(01_data_cleaning.ipynb)

### 2nd: Exploratory Data Analysis

Performed statistical analysis and visualization to identify patterns.

Examples:

* Revenue trends over time
* Customer geographic distribution
* Product category performance
* Freight cost relationships

Notebook:
🚧 Dashboard visualizations are currently being refined.
Final visuals will be uploaded shortly._placeholder_(02_exploratory_data_analysis.ipynb)

### 3rd: Power BI Dashboard

Created an interactive dashboard presenting business insights.

Pages include:

* Executive Overview
* Sales Analysis
* Customer Insights
* Logistics Performance

Screenshots available in:
🚧 Dashboard visualizations are currently being refined.
Final visuals will be uploaded shortly.placholder(dashboard/)

## Repository Structure

- data
- notebooks
- images
