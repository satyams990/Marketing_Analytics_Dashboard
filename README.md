# 📊 Marketing Analytics Dashboard \| SQL + Python + Power BI

![Power
BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![SQL
Server](https://img.shields.io/badge/SQL%20Server-Database-CC2927?logo=microsoftsqlserver&logoColor=white)
![Python](https://img.shields.io/badge/Python-NLP-3776AB?logo=python&logoColor=white)

## 📌 Project Overview

This project is an end-to-end **Marketing Analytics Dashboard**
developed for **ShopEasy**, an online retail company facing declining
customer engagement, reduced conversion rates, and increasing marketing
expenses.

The solution integrates **SQL Server**, **Python (NLTK VADER)**, and
**Power BI** to transform raw marketing data into actionable business
insights. It combines customer journey analysis, engagement metrics, and
sentiment analysis to uncover performance gaps and support data-driven
decision making.

------------------------------------------------------------------------

## 🎯 Business Problem

ShopEasy experienced:

-   Declining customer engagement
-   Reduced website conversion rates
-   Increasing marketing costs
-   Large volumes of customer reviews without meaningful analysis

The objective was to build a centralized analytics solution capable of
monitoring marketing performance, understanding customer behavior, and
extracting insights from customer feedback.

------------------------------------------------------------------------

# 🛠️ Project Workflow

## Step 1 --- Data Collection

Marketing data was collected from multiple SQL Server tables:

-   `dim_customers`
-   `fact_customer_journey`
-   `fact_customer_reviews`
-   `fact_engagement_data`

------------------------------------------------------------------------

## Step 2 --- SQL Data Preparation

Performed SQL-based data preparation by:

-   Extracting relevant business data
-   Joining multiple relational tables
-   Cleaning and transforming datasets
-   Removing inconsistencies
-   Building an analytical data model

------------------------------------------------------------------------

## Step 3 --- Python Sentiment Analysis

Customer reviews were enriched using **Python** and **NLTK VADER**.

### Tasks Performed

-   Connected SQL Server using PyODBC
-   Loaded customer reviews
-   Calculated sentiment scores
-   Classified reviews into:
    -   Positive
    -   Negative
    -   Neutral
    -   Mixed Positive
    -   Mixed Negative
-   Generated sentiment buckets
-   Exported enriched dataset for Power BI

### Python Libraries

-   Pandas
-   NLTK
-   PyODBC
-   SQLAlchemy

------------------------------------------------------------------------

## Step 4 --- Power BI Data Modeling

Built a robust Power BI data model using:

-   Star Schema
-   Calendar Table (DAX)
-   Relationships
-   Date Hierarchy

### DAX Features

-   Time Intelligence
-   KPI Calculations
-   Dynamic Measures
-   Interactive Filtering

------------------------------------------------------------------------

## Step 5 --- Dashboard Development

### Executive KPIs

-   Conversion Rate
-   Customer Engagement Rate
-   Average Customer Rating
-   Total Reviews
-   Customer Sentiment

### Conversion Analysis

-   Monthly Conversion Trends
-   Product-wise Conversion
-   Conversion Funnel Analysis

### Customer Engagement

-   Views
-   Clicks
-   Likes
-   Content Performance Analysis

### Customer Feedback

-   Rating Distribution
-   Sentiment Distribution
-   Positive vs Negative Reviews

### Time Intelligence

-   Monthly Analysis
-   Quarterly Analysis
-   Year-over-Year Performance

------------------------------------------------------------------------

# 📈 Key Insights

-   Conversion rates fluctuated across different months, highlighting
    opportunities for optimization.
-   Blog content generated the highest engagement, while overall views
    declined during the second half of the year.
-   Average customer rating remained around **3.7**, below the target
    rating of **4.0**.
-   Sentiment analysis revealed predominantly positive customer feedback
    while identifying areas requiring improvement.
-   Actionable recommendations focused on improving conversion rates,
    customer engagement, and customer satisfaction.

------------------------------------------------------------------------

# 💻 Tech Stack

  Category         Technologies
  ---------------- ----------------------------------
  Database         SQL Server
  Programming      Python
  Libraries        Pandas, NLTK, PyODBC, SQLAlchemy
  Visualization    Power BI
  Query Language   SQL
  Analytics        DAX

------------------------------------------------------------------------

# 🚀 Skills Demonstrated

-   SQL Querying
-   Data Cleaning
-   Data Transformation
-   Relational Database Management
-   Python Automation
-   Natural Language Processing (NLP)
-   Sentiment Analysis
-   Power BI Dashboard Development
-   Data Modeling
-   DAX
-   KPI Design
-   Interactive Reporting
-   Business Intelligence
-   Data Visualization
-   Business Insight Generation

------------------------------------------------------------------------

# 📊 Business Outcome

The dashboard enables marketing teams to:

-   Identify conversion bottlenecks
-   Track customer engagement trends
-   Analyze customer sentiment
-   Improve campaign performance
-   Optimize marketing strategies
-   Support data-driven decision making

------------------------------------------------------------------------

# 📁 Project Structure

``` text
Marketing-Analytics-Dashboard/
│
├── SQL/
│   ├── dim_customers.sql
│   ├── fact_customer_journey.sql
│   ├── fact_customer_reviews.sql
│   └── fact_engagement_data.sql
│
├── Python/
│   └── customer_reviews_enrichment.py
│
├── Power BI/
│   ├── Dashboard.pbix
│   └── Calendar DAX Script.txt
│
├── Presentation/
│   └── Marketing Analytics Presentation.pptx
│
├── Dashboard Screenshots/
│
└── README.md
```

------------------------------------------------------------------------

# ⭐ Project Highlights

-   End-to-End Data Analytics Project
-   SQL + Python + Power BI Integration
-   NLP-based Customer Sentiment Analysis
-   Interactive Business Intelligence Dashboard
-   Marketing KPI Monitoring
-   Executive-Level Reporting
-   Actionable Business Recommendations
