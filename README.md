# Credit-Card-Data-Analysis-Insights

## 📌 Project Overview

This project focuses on analyzing credit card customer data to understand spending behavior, repayment patterns, and profitability for the bank. The analysis helps identify high-value customers, spending trends, and potential risk areas.

---

## 🎯 Objective

The goal of this project is to:

* Analyze customer spending and repayment behavior
* Identify profitable and high-risk customers
* Understand trends across time, city, and product categories
* Generate insights to support data-driven business decisions

---

## 📂 Dataset Description

The dataset consists of three main tables:

* **Customer Acquisition** → Customer details (age, city, credit limit, etc.)
* **Spend Data** → Transaction-level spending information
* **Repayment Data** → Customer repayment records

---

## 🧹 Data Cleaning & Preprocessing

* Replaced invalid age values (age < 18) with mean age
* Adjusted spend values exceeding credit limit
* Capped repayment values at customer credit limit
* Converted date columns into proper datetime format

---

## 📊 Exploratory Data Analysis (EDA)

* Total and monthly spending analysis
* Monthly repayment trend analysis
* Customer-level performance evaluation
* Category-wise and city-wise spending insights
* Top customers based on repayment

---

## 📈 Key Business Insights

* High credit limit customers contribute significantly to total spending
* A gap between spending and repayment indicates potential risk customers
* Spending patterns show seasonal trends across months
* Certain cities dominate overall transaction volume
* Top customers contribute a major share of revenue (Pareto effect)
* Middle-aged customers are the most active spenders
* Bank profitability depends on interest earned from outstanding balances

---

## 📊 Visualizations

* Monthly spending trend 📈
* City-wise spending comparison 🏙️
* Product category analysis 🛍️
* Top customer contribution charts

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas
* Matplotlib

---
NOTE-
Due to data privacy and institutional restrictions, the dataset used in this project cannot be shared publicly.
