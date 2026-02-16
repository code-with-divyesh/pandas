## 📊 Quick Commerce Performance Dashboard

An end-to-end Exploratory Data Analysis (EDA) and Interactive Dashboard Project built using Python to analyze quick commerce platforms performance.

This project focuses on revenue trends, customer ratings, delivery efficiency, discount impact, and operational performance.

## 🚀 Project Overview

The goal of this project is to:

Clean and preprocess raw quick commerce data

Handle missing values and outliers

Perform business-focused exploratory data analysis

Calculate operational efficiency score

Build an interactive dashboard with KPI cards using Plotly

## 🛠️ Tech Stack

Python

Pandas – Data cleaning & manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Plotly – Interactive dashboard

## 📂 Dataset Features

The dataset contains:

Order_ID

Company

City

Customer_Age

Order_Value

Delivery_Time_Min

Distance_Km

Items_Count

Customer_Rating

Delivery_Partner_Rating

Discount_Applied

Product_Category

## 🔍 Key Business Questions Solved

1️⃣ Which company has the highest total revenue?

Aggregated total order value per company

Visualized using bar + line chart

2️⃣ Which platform has the highest Average Order Value (AOV)?

Calculated company-wise mean order value

3️⃣ How do customer ratings vary across platforms?

Bar charts

Boxplots

Rating distribution analysis

4️⃣ Does delivery time impact delivery partner ratings?

Correlation analysis

Time binning (Very Fast → Very Slow)

Trend visualization

5️⃣ Most popular category for:

Swiggy Instamart
Age 30–40
City: Mumbai

6️⃣ Which cities should companies expand into?

Based on:

High average rating (≥ 3.5)

Low average delivery time (≤ 15 min)

Above median order volume

7️⃣ Do discounts increase order volume?

Compared revenue vs items count

8️⃣ Which company has best operational efficiency?

Created custom Efficiency Score:

Efficiency = Normalized Orders − Normalized Delivery Time

## 📊 Dashboard Features

Interactive dashboard built using Plotly Subplots including:

Revenue by Company

Average Order Value

Customer Ratings

Operational Efficiency

Average Delivery Time

KPI Cards:

Total Revenue

Total Orders

Average Rating

Top Efficient Company

## 🧠 Data Cleaning Strategy

Removed rows with missing city

Filled Items_Count using mode

Filled Customer_Rating using company-wise mean

Filled Delivery_Partner_Rating using grouped mean + overall mean

Removed extreme outliers (Order_Value > 2500)

Rounded and optimized data types

## 📈 Key Insights

Revenue distribution varies significantly across companies

Faster delivery improves partner ratings

Discounts increase order volume but may reduce revenue per order

Operational efficiency depends on balancing order volume and delivery speed

## ▶️ How to Run

pip install pandas numpy matplotlib seaborn plotly

Then run:

python your_script_name.py

## 📌 Future Improvements

Add predictive modeling

Add time-series analysis

Deploy dashboard using Streamlit

Automate reporting

👤 Author:

Divyesh Gandhi
Aspiring 
Data Analyst

## Thank you..
