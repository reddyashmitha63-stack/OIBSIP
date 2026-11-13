Customer Segmentation Analysis

About the Project

This project is part of my Oasis Infobyte (OIBSIP) Data Analytics Internship – Task 2.

The main aim of this project is to analyze e-commerce customer data and group customers based on their purchasing behavior. I used RFM Analysis and the K-Means Clustering algorithm to identify different types of customers.

Dataset

Dataset: E-commerce Data

Source: Kaggle – E-commerce Data

The dataset contains information such as invoice numbers, customer IDs, purchase dates, quantities, prices, and countries.

Tools and Technologies Used:

Python

Google Colab

Pandas and NumPy

Matplotlib and Seaborn

Scikit-learn

Steps Performed

Loaded the dataset and explored its structure.

Cleaned the data by handling missing values, duplicate records, and invalid entries.

Performed exploratory data analysis to understand sales and customer purchasing patterns.

Calculated RFM values:

Recency: How recently a customer made a purchase.

Frequency: How often a customer made purchases.

Monetary: How much a customer spent.

Standardized the RFM values.

Used the Elbow Method to choose the number of clusters.

Applied K-Means Clustering to group customers.

Visualized the clusters and studied the customer segments.

Suggested marketing strategies based on the results.

Results and Insights

The analysis identified three customer groups:

At-Risk / Inactive Customers: Customers who have not purchased recently and have relatively low spending.

Regular Customers: Customers who purchase more regularly and form the largest customer group.

High-Value / VIP Customers: Customers who purchase frequently and contribute significantly to revenue.

