# Propensity Modeling for an E-Commerce Company 

## Business Objective

Our Client is an early-stage e-commerce company selling various products from daily essentials (such as Dairy & vegetables) to high-end electronics and home appliances. It is a one-year-old company and they are witnessing many people coming to their platform and searching for products but only a few end up purchasing. To increase the number of purchases, the business is planning to send discounts or coupons to users to motivate them to buy. But since it is an early-stage startup, they have only limited funds for this discount campaign. So, they have reached out to us seeking our help in building a model that would predict the purchase probability of eac user in buying a product.

We will be making use of propensity modeling for this. Propensity modeling is a set of approaches to building predictive models to forecast the behavior of a target audience by analyzing their past behaviors. That is to say, propensity models help identify the likelihood of someone performing a certain action. We can then use this likelihood or probability score to create personalized targeting campaigns for the users thus reducing our total cost (targeting only a small set of users) and increasing our ROI.

To help us in predicting the propensity of purchase, we will also make use of RFM Modeling. RFM is a data-driven customer segmentation technique that allows marketers to make informed decisions. RFM stands for Recency, Frequency, and Monetary value each corresponding to some key customer trait. These RFM metrics are important indicators of a customer’s behavior because the frequency and monetary value affect a customer’s lifetime value, and recency affects retention, a measure of engagement.

It empowers marketers to quickly identify and segment users into homogeneous groups and target them with differentiated and personalized marketing strategies. This in turn improves user engagement and retention. With the probability scores from propensity modeling, the marketing team can filter only those users who need the actual push (in terms of discounts or coupons) to make a purchase rather than sending coupons to users who would have bought the product anyway.

## Dataset Information:

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Attribute Information:**

* *InvoiceNo*: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

* *StockCode*: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

* *Description*: Product (item) name. Nominal.

* *Quantity*: The quantities of each product (item) per transaction. Numeric.

* *InvoiceDate*: Invoice Date and time. Numeric, the day and time when each transaction was generated.

* *UnitPrice*: Unit price. Numeric, Product price per unit in sterling.

* *CustomerID*: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

* *Country*: Country name. Nominal, the name of the country where each customer resides.

## Aim:

1. To understand Propensity Modeling
2. To understand RFM Analysis
3. To build a model to predict the purchase probability of each user in buying a product for an e-commerce company with the help of the propensity model

## Tech Stack:

● Language - Python

● Libraries - pandas, sklearn, numpy, seaborn, datetime, matplotlib, missingno

## My Approach :

1. Importing the required libraries and packages
2. Read the CSV file
3. Perform data preprocessing
4. Perform exploratory data analysis
	i. Univariate analysis
	ii. Multivariate analysis
5. Perform RFM Analysis
6. Feature engineering
7. Modeling Data Creation
8. Model building
9. Making predictions

## Code Overview

1. input

2. src

3. output

## Folder description

1. input folder - It contains all the data that we will need for analysis.

    ● A config file, with some basic configuration parameters which can be edited according to your dataset.

    ● A final_customer_data.xlsx file that has 2090 rows of customer transaction data with over nine features.

    ● A final_customer_data_with_RFM_features.csv file that is a merged dataset containing both customer data from final_customer_data.xlsx and
    the extracted RFM values

    ● An ecom_product_data.csv file which is a transnational data set that contains all the transactions occurring between 01/12/2010 and
    09/12/2011 for a UK-based and registered non-store online retail. It is used for explaining how RFM modeling helps us in predicting the
    propensity of purchase.

    ● requirements.txt
    This file will help you install all the packages that are required to run the
    project successfully. You can install these packages using the command
    → pip install -r requirements.txt

2. src folder - It contains the original ipython notebooks for the project.

3. output folder – The output folder contains the model we trained for this data. This
model can be quickly loaded and used for future use and the user need not have
to train all the models from the beginning.
