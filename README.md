# Festival Sales Analysis
This project explores customer purchasing behavior during the Diwali season using a real-world dataset. It involves data cleaning, preprocessing, and detailed exploratory data analysis (EDA) using Python libraries like pandas, matplotlib, and seaborn.
## Objective
To understand the impact of various customer demographics and categories on festival sales, and to identify key trends such as:

(i) Which product categories perform best during festivals?

(ii) Which age groups and occupations are the most active buyers?

(iii) What is the regional distribution of sales and orders?

(iv) How do gender and marital status affect purchasing decisions?
## Dataset
The dataset used (Diwali Sales Data.csv) contains 11,251 records and 15 columns. After cleaning, 13 relevant columns were retained, including:
User ID,Customer Name,Product ID,Gender,Age Group,Age,Marital Status,State,Zone,Occupation,Product Category,Orders,Amount.
## Steps
### 1. Data Cleaning
(i) Removed blank and irrelevant columns.

(ii) Handled null values in the Amount column.

(iii) Converted data types where needed.

(iv) Renamed columns for clarity.

(v) Replaced numeric codes in marital status with readable labels.
### 2. Exploratory Data Analysis (EDA)
(i) Demographic Analysis:

Distribution of customers by gender and age group.

Marital status vs. spending behavior.

Occupational distribution of customers.

(ii) Geographical Analysis:

Zone-wise and state-wise sales and orders.

Region-wise preference for product categories.

(iii) Category-Wise Insights:

Top-selling product categories.

Most popular items by age group and region.

Spending patterns across different customer segments.

(iv) Customer Insights:

Top 5 customers by number of orders and total spending.

Most common occupations and states among high-value customers.

Spending frequency histogram to identify common spending ranges.
## Tools Used
(i) Python (pandas, matplotlib, seaborn)

(ii) Jupyter Notebook for analysis and visualization
