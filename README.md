# Customer-Segmentation-Using-RFM-Analysis
#Project Overview :

This project focuses on analyzing customer purchasing behavior using the RFM (Recency, Frequency, Monetary) model.
The goal is to segment customers into meaningful groups to help businesses design targeted marketing strategies and improve customer retention.

The analysis was performed using the Online Retail Dataset (UCI), which contains real transactional data from an online store.

#Objectives :

- Clean and prepare the dataset

- Calculate Recency, Frequency, and Monetary values for each customer

- Assign RFM scores

- Segment customers based on RFM profiles

- Visualize customer behavior and segment distributions

- Provide marketing insights for each segment
#Dataset :

- Source: UCI Machine Learning Repository

- Content:

Invoice number

Customer ID

Product details

Quantity purchased

Price

Invoice date
# Methodology :
1. Data Cleaning

- Removed duplicates

- Handled missing Customer IDs

- Filtered out negative quantities (cancellations)

- Converted InvoiceDate to datetime format

2. RFM Metrics Calculation

- Recency: Days since last purchase

- Frequency: Number of transactions

- Monetary: Total amount spent

3. RFM Scoring

- Each metric was ranked from 1 to 5
4. Segmentation
- The project includes:

Distribution of RFM scores

Bar chart of customer segments

Heatmap (Recency × Frequency) showing average Monetary value

Total sales trend over time

Country-wise sales summary
#Tech Stack :

- Python, Pandas, NumPy, Matplotlib, Seaborn

