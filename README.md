# traffic-revenue-analysis-powerbi
**Overview**

This project is a Power BI dashboard built using an E-commerce dataset. The goal of the dashboard is to analyze traffic, conversion, and revenue performance in an e-commerce setting and identify patterns that can help improve business outcomes.

**Dataset**

The data used in this project comes from the Maven Analytics Data Playground (Toy Store E-commerce Database).

Note: The dataset is not included in this repository. It can be accessed directly from the Maven Analytics platform.

**Objective**

The main objective of this project is to understand how users move through the e-commerce funnel and how that impacts revenue. The analysis focuses on:

Tracking revenue and order trends over time

Understanding conversion behavior

Identifying drop-offs in the customer journey

Comparing performance across devices and traffic sources

Evaluating product-level profitability and risks

**Tools Used**

Power BI

DAX

Excel (for data preparation)

**Data Model**

The dashboard is built on a relational data model that connects multiple tables representing different stages of the e-commerce process.

**Key tables include:**

**Orders:** Contains order-level information such as revenue, timestamps, and product references

**Order Items:** Links individual products to orders and captures pricing details

**Website Sessions:** Tracks user visits, device type, and traffic sources

**Website Pageviews:** Captures page-level interactions

**Products:** Stores product-related information

**Order Item Refunds:** Tracks refunds issued for specific items

**Date Table:** Enables time-based analysis

These tables are connected to represent the full flow from user sessions to purchases and post-purchase activity.

**Data Model Preview**

<img width="1756" height="565" alt="datamodel" src="https://github.com/user-attachments/assets/4bfc1868-17c0-4e8b-9438-74e6ed99abdd" />

The model follows a structured relationship design to support efficient filtering and aggregation across metrics.

**Dashboard Breakdown**

The dashboard is structured into the following sections:

**KPI Overview:** Revenue, Orders, Average Order Value, Conversion Rate, Profit, and Sessions

**Trend Analysis:** Monthly revenue and conversion trends

**Customer Funnel:** Tracking the journey from session to purchase

**Segmentation:** Performance by device type and traffic source

**Product Analysis:** Revenue, profit, and refund behavior by product

**Key Insights**

Revenue shows strong overall growth, with a significant portion coming from the later months of the year

Mobile conversion rate is noticeably lower than desktop, indicating potential friction in the mobile experience

A large percentage of users drop off before completing a purchase, especially between product view and add-to-cart stages

Some products have high refund rates, which negatively impacts profitability


**Recommendations**

Improve the mobile user experience to increase conversion rates

Optimize product pages to reduce drop-offs in the funnel

Investigate high-refund products to identify possible issues

Leverage seasonal trends to plan targeted marketing campaigns

**Dashboard Preview**

Dashboard 1 (Filtered View – 2014)

<img width="1282" height="724" alt="dashboard-1" src="https://github.com/user-attachments/assets/8448adcf-27ab-4fe0-a892-32ccc41d3a44" />

Dashboard 2 (Filtered View – 2013)

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/667778e7-5f1b-4b4f-813e-2b04fdc4c3bc" />

**How to Use**

Download the Power BI file from this repository

Open it using Power BI Desktop

Use the available filters (such as year selection) to explore different views

**Files in this Repository**

readme.md - Project documentation

datamodel.png – Data model image

dashboard-1.png – Dashboard screenshot 2014

dashboard-2.png – Dashboard screenshot 2013

## Power BI File

The `.pbix` file exceeds GitHub's upload limit and is hosted on Google Drive instead.

 [Download the .pbix file from Google Drive](https://drive.google.com/drive/folders/1UJroqLq5bPhQe_nrwlDEkoZS9hxYn-lg?usp=sharing)

**About This Project**

This project focuses on analyzing e-commerce performance and translating data into actionable business insights using Power BI.
