Online Retail II – Sales Analysis & Customer Insights

📌 Project Overview

This project analyzes the Online Retail II transactional dataset from a UK-based online retail business. The goal is to explore sales patterns, product performance, customer activity, country-wise transactions, and time-based trends using Microsoft Excel and Pivot Tables.

The project focuses on transforming raw transaction data into meaningful business insights that can support sales and customer analysis.

📸 Project Dashboard

Excel dashboard created for the Online Retail II sales analysis project.

📊 Dataset

The dataset contains transactions from a UK-based, registered, non-store online retailer that mainly sells unique all-occasion giftware. Many customers are wholesalers.

Dataset: Online Retail II

Time period: December 1, 2009 – December 9, 2011

Records: Approximately 1.07 million transaction line items

Source: UCI Machine Learning Repository

Kaggle: https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

UCI: https://archive.ics.uci.edu/dataset/502/online+retail+ii

Dataset Columns

Column

Description

Invoice

Unique transaction/invoice number

StockCode

Product/item code

Description

Product name

Quantity

Number of items purchased

InvoiceDate

Transaction date and time

Price

Unit price in GBP

Customer ID

Unique customer identifier

Country

Customer's country

Note: Invoice numbers beginning with C represent cancellations in the original dataset.

🎯 Project Objectives

Analyze overall retail transaction patterns

Identify high-performing products based on quantity sold

Compare activity across countries

Analyze sales-related values by year and month

Identify high-value customers

Understand seasonal patterns in transaction activity

Build Excel Pivot Tables for business reporting

Convert raw transaction data into useful business insights

🛠️ Tools & Technologies

Microsoft Excel

Pivot Tables

Excel formulas

Data cleaning and transformation

Data aggregation

Business/Data Analysis

🔍 Analysis Performed

1. Product Analysis

The project uses Pivot Tables to identify products with high sales quantities and understand product-level performance.

Examples from the analysis include products such as:

3 BLACK CATS W HEARTS BLANK CARD

FUSCHIA/GREEN STRIPE WOOLLY BLANKET

CHAMPAGNE TRAY BLANK CARD

CAT WITH SUNGLASSES BLANK CARD

2. Country-wise Analysis

Country-level analysis was performed to understand where transactions were concentrated.

The workbook includes country-wise summaries such as:

Number of product descriptions/transactions

Price totals

Country-level product activity

The United Kingdom represents the largest transaction volume in the dataset, consistent with the dataset's origin as a UK-based retailer.

3. Year-wise Analysis

The project compares aggregated price values across years:

Year

Aggregated Price Value

2009

~198,309

2010

~2,526,013

2011

~2,127,799

Important: These figures are the workbook's aggregated Price values. They should not be interpreted as total revenue unless revenue has been explicitly calculated as Quantity × Price.

4. Monthly Analysis

Monthly aggregated values were analyzed to identify periods with higher transaction value.

The workbook indicates particularly high aggregated values in:

November

December

October

March

June

September

December has the highest aggregated Price value in the current workbook analysis.

5. Customer Analysis

The project also includes customer-level analysis to identify customers associated with higher aggregated sales values.

This can be extended into RFM (Recency, Frequency, Monetary) analysis for customer segmentation.

📈 Key Business Questions

This project can help answer questions such as:

Which products have the highest sales quantities?

Which countries generate the most transaction activity?

How does transaction value change across years?

Which months show higher sales-related activity?

Which customers have the highest aggregated purchase values?

Which products and countries should receive closer business attention?

Are there seasonal patterns in retail transactions?

The raw dataset is not required to be committed to GitHub. It can be downloaded from the Kaggle or UCI source linked above.

🚀 How to Use

Download the dataset from Kaggle or UCI.

Open the Excel analysis workbook.

Review the cleaned/organized transaction data.

Explore the Pivot Tables.

Filter by:

Country

Product

Year

Month

Customer

Use the summaries to identify business trends and patterns.

💡 Future Improvements

The project can be extended by adding:

Interactive Excel dashboard

KPI cards for total orders, customers, products, and sales

Revenue calculation using Quantity × Price

RFM customer segmentation

Customer retention analysis

Cohort analysis

Product profitability analysis

Sales forecasting

Python-based exploratory data analysis

Power BI dashboard

Interactive charts and visualizations

📚 Data Source & Citation

The dataset was originally published through the UCI Machine Learning Repository as the Online Retail II dataset.

Citation:

Chen, D. (2012). Online Retail II [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5CG6D

Dataset license: CC BY 4.0

👤 Author

Shibin Jouhar

This project was created as a data analysis portfolio project using Excel and the Online Retail II dataset.
