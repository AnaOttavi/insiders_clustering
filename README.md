# Insiders Clustering

Project from Data Science Community, mentoring by Meigarom Lopes.

The business problem is selecting customers to create a loyalty program called Insiders.
A UK-based online retail store has captured the sales data for different products for the period of one year (Nov 2016 to Dec 2017). The organization sells gifts primarily on the online platform. The customers who make a purchase consume directly for themselves. There are small businesses that buy in bulk and sell to other customers through the retail outlet channel.



# 1. Business Problem.
Find significant customers for the business who make high purchases of their favourite products. The organization wants to roll out a loyalty program, called Insiders, to the high-value customers after identification of segments.

**Dataset Description** : https://www.kaggle.com/vik2012kvs/high-value-customers-identification

Attribute:     Description

InvoiceNo:      Invoice number (A 6-digit integral number uniquely assigned to each transaction)
 
StockCode :     Product (item) code

Description :   Product (item) name

Quantity :      The quantities of each product (item) per transaction

InvoiceDate:    The day when each transaction was generated

UnitPrice:      Unit price (Product price per unit)

CustomerID:     Customer number (Unique ID assigned to each customer)

Country :       Country name (The name of the country where each customer resides)

# 2. Business Assumptions.

- Indicate customers who will be part of a loyalty program called Insiders.
- What are the main characteristics of these customers?: Ticket, bascket size, high LTV, churn probability,high TVC prevision, purchasing propensity, age, location.
- How many customers will be part os this group?
- RFM model (recency, frequency,, monetary): sorted data to have a RFM Score.

# 3. Solution Strategy

**Data Description:** rename columns, check NA values, change types.

**Feature Engineering:** recency, frequency, monetary, gross revenue.

**Model Training:** K-Means

**Cluster Analysis:** Visualization Inspection, UMAP -t-SNE

**Feature Engineering:** create new attributes based on the original variables using mindmap hypothesis.

**Exploratory Data Analysis (EDA):** univariate and bivariate analysis. Space studt with PCA, UMAP, t-SNE, Tree-Based Embedding

**Hyperparameter Fine Tunning:** Within-Cluster Sum os Square (WSS) and Silhouette Score.

Step 08. Model training:

Step 09. Cluster Analysis:

Step 10. Deploy to Production:

# 4. Top 3 Data Insights
Hypothesis 01:

True/False.

Hypothesis 02:

True/False.

Hypothesis 03:

True/False.

# 5. Machine Learning Model Applied
# 6. Machine Learning Modelo Performance
# 7. Business Results
# 8. Conclusions
# 9. Lessons Learned
# 10. Next Steps to Improve
# LICENSE
# All Rights Reserved - Comunidade DS 2021
