# Retail - Loyalty Program Analysis
Project portfolio : Analyzing loyalty programs in retail business units

## 1. Business Understanding
Home World is a company engaged in retail building materials. Each customer has a membership card, where to join the loyalty program you can subscribe for $ 20 / month. The program includes discounts, special offers and gifts.

Objective :

**A. Loyalty Program Analysis :**

  - Assess changes in average purchase size for each cohort for loyalty program members/non-members.
  - Assess purchase frequency for loyalty program members/non-members.
      
**B. Hypothesis Testing :**

  - Test the hypothesis that the average purchase size is higher for loyalty program members than for non-members.
  - Formulate statistical hypotheses about the data from the data set and test them.
   
**C. Summary :**
    
  - Provide conclusions from the results of data analysis.
  - Provide solutions or suggestions based on the results of the analysis.

## 2. Data Understanding
There are 2 datasets namely `retail_dataset_us.csv` and `product_codes_us.csv`. This dataset includes the following columns:

Dataset `retail_dataset_us.csv`:

- `purchaseId` — A unique identification number for each purchase transaction.
- `item_ID` — A unique identification number for each item purchased in a transaction.
- `purchasedate` — The date and time the purchase transaction was made.
- `Quantity` — The number of items purchased in one transaction.
- `CustomerID` — A unique identification number for each customer.
- `ShopID` — A unique identification number for each retail store.
- `loyalty_program` — Indicates whether the customer is a member of the loyalty program or not.

Dataset `product_codes_us.csv`:

- `productID` — A unique identification number for each product.
- `price_per_one` — Price per unit (units) of the product.

## 3. Data Preparation
In this process, we prepare data so that it is easier to analyze. Some of the steps we take are :

- Fix Column Name
- Remove Duplicated
- Handling Missing Values
- Convert Data Types

## 4. Exploratory Data Analysis
