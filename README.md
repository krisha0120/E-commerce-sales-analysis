# E-commerce Sales and Customer Analysis

## Project Overview

This project analyzes historical e-commerce transaction data to identify sales trends, top-performing products, and customer purchasing behavior using Python and SQL.

## Objectives

* Clean and prepare transaction data for analysis.
* Calculate revenue and analyze monthly sales trends.
* Identify top-performing products and important markets.
* Examine repeat-customer purchasing behavior.
* Generate business recommendations from the analysis.

## Dataset

* **Source:** [UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online%2Bretail)
* **Period:** December 2010 – December 2011
* **Original records:** 541,909
* **Data includes:** Invoice numbers, product codes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

## Tools and Technologies

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* SQLite and SQL
* Jupyter Notebook

## Project Workflow

1. **Data loading:** Loaded the Online Retail dataset into Pandas.
2. **Data cleaning:** Removed cancelled invoices and records with non-positive quantities or unit prices.
3. **Feature engineering:** Calculated revenue as quantity multiplied by unit price and extracted the month from invoice dates.
4. **Exploratory data analysis:** Examined revenue trends, product performance, customer behavior, and country-level sales.
5. **SQL analysis:** Used SQLite queries to calculate total revenue, order counts, and other business metrics.
6. **Business recommendations:** Used the results to identify potential product, customer-retention, and market opportunities.

## Key Analyses

* Total revenue and number of orders
* Monthly revenue trends
* Top 10 products by revenue
* Revenue by country
* Repeat-customer analysis

## Key Findings

Add the final values from your notebook here:

* Total cleaned revenue: £10,666,684.54
* Total valid transactions: 530104
* Total orders: 19,960
* Top 10 products' share of revenue: 10.82%
* Repeat-customer percentage: 65.58%

## Business Recommendations

* Monitor high-revenue products to support inventory planning.
* Analyze repeat-customer behavior to improve customer retention.
* Compare country-level sales to identify promising markets.
* Track monthly revenue to support business planning.

## How to Run

1. Install Python and VS Code with the Jupyter extension.
2. Download the dataset from the UCI repository.
3. Place `Online Retail.xlsx` in the project folder.
4. Open `ecommerce_analysis.ipynb` in VS Code.
5. Select your Python kernel and run the notebook cells in order.

## Project Structure

* `Online Retail.xlsx` — Original dataset
* `ecommerce_analysis.ipynb` — Python analysis notebook
* `sales_cleaned.csv` — Cleaned dataset exported from Python
* `ecommerce_analysis.db` — SQLite database containing the sales table
* `README.md` — Project documentation

## Limitations

* The dataset covers 2010–2011 and may not reflect current retail behavior.
* Customer-level analysis excludes records with missing CustomerIDs.
* Revenue is not the same as profit because costs are not included.

## Author

Krisha S
