# Online Retail II Data Analysis

## Project Overview

This project analyzes retail transaction data to explore sales performance, product popularity, customer spending, and purchasing trends.

Using Python and Pandas for data cleaning and exploratory data analysis (EDA), along with Power BI for interactive visualization, this project transforms retail transaction data into meaningful business insights.

The project focuses on understanding which products generate the most revenue, which customers contribute the most sales, how revenue changes over time, and which countries perform best.

## Tools & Technologies

- **Python** — Data cleaning and analysis
- **Pandas** — Data manipulation and preprocessing
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Exploratory data analysis
- **Power BI** — Interactive dashboards
- **CSV** — Data storage

## Dataset

This project uses the **Online Retail II** dataset, which contains transaction records from a UK-based online retailer.

**Original Dataset:** [Online Retail II – Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

The original dataset contains 1,048,575 rows and 8 columns.

The dataset includes:

- `Invoice` — Invoice number
- `StockCode` — Product code
- `Description` — Product description
- `Quantity` — Quantity purchased
- `InvoiceDate` — Transaction date
- `Price` — Unit price
- `Customer ID` — Customer identifier
- `Country` — Customer's country

The original dataset was downloaded from Kaggle, cleaned and processed using Python and Pandas. The cleaned data was then used for exploratory data analysis and Power BI dashboard development.

**Note:** The original and cleaned CSV files are not included in this repository. You can download the original dataset using the Kaggle link above.

## Project Workflow

### 1. Data Cleaning with Python

Python and Pandas were used to prepare the original transaction data for analysis.

Key steps included:

- Inspecting the dataset structure, dimensions, and data types
- Identifying missing values
- Removing rows containing missing values
- Converting invoice dates to datetime format
- Identifying cancelled invoices
- Excluding cancelled invoices, non-positive quantities, and non-positive prices from the sales analysis
- Calculating revenue using quantity multiplied by unit price
- Creating seasonal categories based on invoice months
- Exporting the cleaned sales data to CSV

The cleaned dataset was then used for further analysis and visualization.

### 2. Exploratory Data Analysis (EDA)

The notebook explores the dataset through business-focused questions, including:

- How does revenue change monthly and yearly?
- Which products generate the most revenue?
- Which products sell the highest quantities?
- Which customers spend the most money?
- Which countries generate the most revenue?
- Which countries have the most unique customers?
- What is the average order value?
- How many invoices involve cancellations or negative quantities?
- Which products sell in high quantities but generate relatively low revenue?
- Which seasons generate the highest revenue?

### 3. Power BI Dashboard

Two interactive Power BI dashboard pages were created to present the analysis.

#### Page 1 — Online Retail Sales Overview

This dashboard provides an overview of overall sales performance and trends.

**Key metrics and visualizations:**

- Total Revenue
- Total Orders
- Unique Customers
- Average Order Value
- Monthly Revenue Trend
- Top 10 Countries by Revenue
- Revenue by Year
- Year, Country, and Product slicers

#### Page 2 — Product & Customer Analysis

This dashboard focuses on product performance and customer spending.

**Key visualizations:**

- Top 10 Products by Revenue
- Top Countries by Customer Count
- Top Customers by Spend
- Product Quantities Sold
- Product, Year, and Country slicers

## Key Business Insights

The following findings are based on calculations performed using the cleaned dataset.

- **Total revenue:** Approximately 17.32 million in the dataset's recorded currency.
- **Transaction volume:** 36,457 unique invoices.
- **Customer base:** 5,860 unique customers.
- **Product variety:** 4,630 unique product codes.
- **Leading market:** The United Kingdom generates approximately 14.34 million in revenue.
- **Top product by revenue:** Regency Cakestand 3 Tier generates approximately 282.51K.
- **Top customer by revenue:** Customer ID 18102 generates approximately 597.34K.
- **Monthly performance:** November has the highest combined monthly revenue, at approximately 2.33 million.
- **Yearly performance:** Revenue decreases from approximately 8.72 million in 2010 to 7.92 million in 2011.

The yearly comparison should be interpreted carefully because 2009 covers only part of the year in this dataset.

## Project Structure

```text
online-retail-data-analysis/
│
├── notebooks/
│   └── online_retail_analysis.ipynb
│
├── powerbi/
│   └── online_retail_dashboard.pbix
│
├── images/
│   ├── dashboard_page1.png
│   └── dashboard_page2.png
│
├── README.md
└── requirements.txt
```

## How to Run This Project

1. Clone or download this repository.
2. Download the original [Online Retail II dataset from Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci).
3. Place the downloaded CSV file in the appropriate location expected by the Jupyter Notebook.
4. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

5. Open `online_retail_analysis.ipynb` in Jupyter Notebook.
6. Run the notebook cells to perform data cleaning and exploratory data analysis.

To explore the interactive dashboards, open the Power BI file located in the `powerbi` folder.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Python programming
- Pandas data manipulation
- Sales and revenue analysis
- Product performance analysis
- Customer spending analysis
- Time-based trend analysis
- Data visualization
- Power BI dashboard development
- Business insight communication

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from cleaning retail transaction data and exploring business questions in Python to creating interactive Power BI dashboards.

It showcases practical skills in data preparation, exploratory analysis, business performance measurement, and data visualization for Data Analyst roles.

## medisa

**Data Analyst Portfolio Project**

