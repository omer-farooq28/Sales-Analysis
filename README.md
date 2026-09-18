# Sales Analysis

A beginner-friendly Exploratory Data Analysis (EDA) project on a supermarket sales dataset using Python, Pandas, and Matplotlib. The project analyzes sales performance, customer behavior, product categories, regions, and shipping methods to generate simple, easy-to-understand business insights.

---

## Project Overview

This project focuses on exploring supermarket sales data to answer basic business questions such as:

- Which products generate the highest sales?
- Which customer segments contribute the most revenue?
- Which regions perform best?
- How do sales change over time?
- Which shipping mode is used the most?

This is a beginner-level project, so it sticks to simple Pandas operations (like `groupby`, `sum`, `mean`) and basic Matplotlib charts (`plt.bar`, `plt.plot`) rather than advanced plotting or analysis techniques.

---

## Project Structure

```text
Supermarket-Sales-Analysis/
│
├── dataset/
│   └── supermarket_data.csv
│
├── notebook/
│   └── Supermarket_Sales_Analysis.ipynb
│
├── screenshots/
│   ├── 01_dataset_preview.png
│   ├── 02_data_cleaning.png
│   ├── 03_sales_analysis.png
│   ├── 04_monthly_sales.png
│   ├── 05_sales_by_region.png
│   └── 06_top_products.png
│
├── README.md
└── requirements.txt
```

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning

- Loaded the dataset
- Checked data types
- Checked for missing values
- Checked for duplicate records
- Converted date columns to proper date format

### 2. Exploratory Data Analysis

The notebook includes:

- Basic Sales KPIs (Total Sales, Total Orders, Unique Customers, etc.)
- Monthly Sales Trend
- Sales by Category
- Sales by Sub-Category
- Sales by Region
- Sales by Customer Segment
- Top Products
- Top Customers
- Ship Mode Analysis

---

## Key Insights

- Identified monthly sales trends.
- Compared sales across product categories.
- Analyzed regional sales performance.
- Evaluated customer segment contributions.
- Identified top-selling products.
- Compared shipping modes based on sales.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Supermarket-Sales-Analysis.git
```

Navigate to the project directory:

```bash
cd Supermarket-Sales-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebook/Supermarket_Sales_Analysis.ipynb
```

---

## Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Perform sales forecasting.
- Implement customer segmentation using machine learning.
- Add profitability analysis.
- Create interactive visualizations using Plotly.
