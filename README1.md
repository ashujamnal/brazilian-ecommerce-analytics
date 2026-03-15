# Brazilian E-Commerce Sales Analysis (Python + Power BI)

## Project Overview

This project analyzes sales performance from the Brazilian Olist e-commerce marketplace.
The objective was to understand how revenue, customer orders, product demand, and delivery performance evolved between **2016 and 2018**.

The analysis combines **Python for data cleaning and exploration** with **Power BI for interactive dashboard visualization**. After merging multiple tables from the dataset, a consolidated dataset containing **~99,000 orders** was created and used for analysis.

The final result is a two-page Power BI dashboard summarizing key business insights related to revenue trends, product categories, sellers, customer locations, delivery times, and payment behavior.

---

## Dataset

Source: Olist Brazilian E-Commerce Dataset
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset includes information about:

* Orders
* Customers
* Products
* Sellers
* Payments
* Reviews
* Delivery timestamps

After cleaning and merging the tables, the final dataset used for analysis contained:

* **~99K orders**
* **~30K sellers**
* **Multiple product categories**
* **Customers across Brazilian states**

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

### 1. Data Cleaning (Python)

Several preprocessing steps were required before analysis:

* Merging multiple tables into a single master dataset
* Converting timestamp columns to datetime format
* Creating new features such as:

  * delivery time
  * delivery delay
  * order year and month
* Translating product categories into English
* Removing columns that were not relevant for analysis

---

### 2. Exploratory Data Analysis

Exploratory analysis was used to answer several business questions:

* How has revenue changed over time?
* Which product categories generate the most revenue?
* Which sellers contribute the most sales?
* How long does delivery usually take?
* What payment methods do customers prefer?

---

## Power BI Dashboard

The final dashboard is divided into **two pages**.

---

# Executive Overview

![Image](https://miro.medium.com/v2/resize%3Afit%3A1200/1%2A2azl1AC_bnE_xhBNTmWajg.jpeg)

![Image](https://dezyre.gumlet.io/images/blog/power-bi-dashboard-examples/E-commerce_Sales_Power_BI_Template.webp?dpr=2.6\&w=376)

![Image](https://media.licdn.com/dms/image/v2/D5622AQE_B5ULWLyOhA/feedshare-shrink_800/B56ZrbHEHDIsAg-/0/1764612656840?e=2147483647\&t=-Nic_5u9uuqGBORrFo4MjEXGkM5LRT8gL77uEabO7Fk\&v=beta)

![Image](https://media.licdn.com/dms/image/v2/D5622AQFwnr9jRd-fxA/feedshare-shrink_800/B56Zt.Utx3HYAo-/0/1767350920271?e=2147483647\&t=-Ttl5cEqMoOplPaax5l4BVEH9Qg4dDBLF7iAN-3MugM\&v=beta)

This page provides a high-level overview of business performance.

Key metrics from the dataset:

* **Total Revenue:** $16.64M
* **Total Orders:** **99K**
* **Average Order Value:** **$167.37**
* **Average Delivery Time:** **12 days**
* **Average Review Score:** **4.02 / 5**

Main visualizations:

**Revenue Trend Over Time**

Revenue increased steadily throughout 2017 and early 2018 before declining toward the end of the dataset period.

**Top Product Categories by Revenue**

Categories such as **Health & Beauty, Watches Gifts, and Bed Bath Table** generate the highest revenue.

**Top Sellers by Revenue**

A small number of sellers generate a large portion of revenue, with the top sellers each generating **over $250K in sales**.

---

# Customer & Delivery Insights

![Image](https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1092600i54D94C0A156FA216?v=v2)

![Image](https://miro.medium.com/1%2A2azl1AC_bnE_xhBNTmWajg.jpeg)

![Image](https://dataflip.co/cdn/shop/files/PowerBIDashboardTemplatesforFoodDeliveryServices_1024x1024.jpg?v=1761398698)

![Image](https://i.imgur.com/PjQMLIp.png)

This page focuses on customer behavior and operational performance.

**Orders Distribution by State**

Orders are concentrated in major Brazilian states, particularly around major urban areas.

**Top Cities by Orders**

The city generating the highest number of orders is:

* **São Paulo — ~15.5K orders**

Followed by:

* Rio de Janeiro (~6.9K)
* Belo Horizonte (~2.8K)
* Brasília (~2.1K)

**Delivery Time Distribution**

Most deliveries occur within **10–15 days**, although a small number of orders experience longer delays.

**Payment Method Distribution**

Customer payment preferences show a strong reliance on digital payments:

* **Credit Card — ~77% of transactions**
* Boleto — second most common
* Voucher and debit card represent a small share

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

## Key Takeaways

Some important observations from the analysis:

* The platform generated **$16.64M in revenue from ~99K orders**
* **Health & Beauty** is the highest-revenue category
* A few sellers contribute a significant portion of sales
* **São Paulo is the dominant city with ~15.5K orders**
* **Credit cards account for roughly 77% of payments**
* Average delivery time is **around 12 days**

---

## Author

Ashutosh Jamnal

LinkedIn
https://www.linkedin.com/in/ashutosh-jamnal

GitHub
https://github.com/ashujamnal
