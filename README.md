# Brazilian E-Commerce Sales Analysis (Python + Power BI)

## Overview

This project analyzes sales performance from the **Brazilian Olist e-commerce marketplace** using Python and Power BI. The goal was to understand how revenue, product demand, customer behavior, and delivery performance evolved between **2016 and 2018**.

Using Python, multiple tables from the dataset were cleaned and merged into a single analytical dataset. The results were then visualized in Power BI to build an interactive dashboard highlighting the most important business metrics and trends.

---

## Dataset

Source:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains information about:

* Orders
* Customers
* Products
* Sellers
* Payments
* Reviews
* Delivery timestamps

After cleaning and merging the tables, the final dataset used for analysis included **~99,000 orders across several Brazilian states and product categories.**

---

## Tools Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Power BI

---

## Project Workflow

**Data Preparation**

* Merged multiple datasets into a single master table
* Converted timestamp columns to datetime format
* Created new features such as delivery time and delivery delay
* Translated product category names to English
* Removed unnecessary columns

**Exploratory Analysis**

Python was used to explore questions such as:

* How has revenue changed over time?
* Which product categories generate the most sales?
* Which sellers contribute the most revenue?
* How long do deliveries usually take?
* What payment methods do customers prefer?

---

## Dashboard Highlights

### Key Metrics

* **Total Revenue:** $16.64M
* **Total Orders:** ~99K
* **Average Order Value:** $167.37
* **Average Delivery Time:** 12 days
* **Average Review Score:** 4.02 / 5

---

## Key Insights

* **Health & Beauty** is the highest-revenue product category in the dataset.
* A small number of sellers generate a large share of total revenue, with the top sellers each producing **over $250K in sales**.
* **São Paulo is the largest customer city**, accounting for **~15.5K orders**, more than double the second-ranked city.
* **Credit cards represent roughly 77% of all payments**, showing strong adoption of digital payments.
* Most orders are delivered within **10–15 days**, with the overall average delivery time around **12 days**.

---

## Dashboard Preview

### Executive Overview

![Dashboard](images/dashboard_page1.png)

### Customer & Delivery Insights

![Dashboard](images/dashboard_page2.png)

---

## Repository Structure

```
brazilian-ecommerce-sales-analysis
│
├── notebooks
│   └── olist_data_analysis.ipynb
│
├── powerbi
│   └── brazilian_ecommerce_dashboard.pbix
│
├── images
│   ├── dashboard_page1.png
│   └── dashboard_page2.png
│
├── requirements.txt
└── README.md
```

---

## Author

Ashutosh Jamnal

LinkedIn
https://www.linkedin.com/in/ashutosh-jamnal

GitHub
https://github.com/ashujamnal
