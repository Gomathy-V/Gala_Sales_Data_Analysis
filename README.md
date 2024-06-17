# Gala sales data Analysis

### Project Overview

This project aims to analyze the critical supply chain issue related to the stocking of perishable grocery items at Gala Groceries. The main challenge lies in balancing inventory levels to avoid both overstocking and understocking. The objective is to identify key factors and provide actionable insights to optimize their inventory management practices, reduce waste, and improve customer satisfaction.

### Data Sources

- Dataset: This dataset, provided by `Cognizant Artificial Intelligence job simulation` Program through `Forage`. The dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each transaction such as product details, customer type, price, quantity, total cost, and payment method at Gala Groceries.

#### Dataset - `sales_data.csv`

|Column Name|Description|
|-----------|-----------|
|transaction_id| A unique identifier for each transaction|
|timestamp| The date and time when the transaction occurred|
|product_id| A unique identifier for each product sold|
|category| The category of the product|
|customer_type| The type of customer|
|unit_price| The price per unit of the product|
|quantity| The number of units sold for this product within this transaction|
|total| The total amount payable by the customer|
|payment_type| The method of payment used in the transaction|

### Tools

- Programming Language: Python
- IDE/Code Editor: Jupyter Notebook
- Libraries
  - `pandas`
  - `matplotlib`
  - `seaborn`

### Data Cleaning / Preparation
- In the initial data preparation phase, we performed the following tasks:

   - Familiarizing with data and inspected data.
   - Data cleaning and formatting.
   - Exploratory Data Analysis
   - Performed an exploratory data analysis to visualize and analyze the trends.

### Exploratory Data Analysis
- Performed an exploratory data analysis to visualize and analyze the supply chain issue and inventory management practices.

#### EDA involved exploring the data in such a way that:

- Analyze the distribution of features.
- Identify Movements and Regularities.
- Visualize correlations between features.
- Examine demographic breakdowns and their impact on departure rates.
- Explore methods to minimize waste and enhance customer satisfaction.

### Findings

- Products with lower unit prices generally experience higher sales frequency than those with higher unit prices.
- Customers at a grocery store typically make numerous low-value transactions and occasionally make a transaction of high value.
- Fruits and vegetables dominate the purchase patterns, followed by various food categories like packaged foods and baked goods. 
- Cash is the preferred payment method, while the other payment types (credit card, e-wallet, and debit card) have fairly similar usage frequencies.
- 11 AM, 4 PM, and 6 PM are peak times for transactions, while 1 PM, 3 PM, and 5 PM are the quieter periods.

### Recommendations

- Pricing strategies that attract price-sensitive customers should be implemented, including promotions, discounts on bulk purchases, and value packs for commonly purchased items.
- Loyalty programs should be implemented to reward frequent visits/purchases, and personalized service with incentives should be offered for high-value transactions.
- Packaged foods and baked goods should be expanded, and personal care and pet products should be strategically promoted to enhance sales and customer engagement.

