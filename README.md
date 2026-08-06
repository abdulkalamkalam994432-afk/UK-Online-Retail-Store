# UK Based Online Retail Store - Sales Analysis

This is a small project where I analyzed sales data from a UK based online retail store using Python. I used pandas for cleaning the data and matplotlib/seaborn for the visualizations.

## About the dataset

The dataset is called `Sales Transaction v.4a.csv` and has these columns:

- TransactionNo
- Date
- ProductNo
- ProductName
- Price
- Quantity
- CustomerNo
- Country

(Dataset is from Kaggle, not included in this repo - you can search "UK Online Retail Sales Transaction" to find it)

## What I did

- Loaded the csv into pandas
- Checked for null values and dropped them
- Checked for duplicate rows and removed them
- Found total customers, total products, total orders, and average quantity per order
- Made a bunch of charts to explore the data:
  - Top 10 best selling products
  - Top 10 customers by number of orders
  - Pie chart of top 5 products
  - Price vs Quantity scatter plot
  - Price distribution histogram
  - Box plot for prices
  - Stem plot for best sellers
  - Step chart for average prices
  - Monthly sales trend line chart

## Libraries used

- pandas
- numpy
- matplotlib
- seaborn

## How to run

1. Download the dataset and put it in the same folder as the notebook
2. Change the file path in the first cell to match where your csv is
3. Run the cells in order

## Notes to self

- file paths are still hardcoded to my laptop, need to fix before sharing
- monthly sales chart needs Date to be converted with pd.to_datetime and Revenue column needs to be created (Price * Quantity) - forgot to add that cell
