# 🧹 Task-1:- Data Cleaning & Preprocessing Project
## 📌 Project Summary
This project demonstrates advanced data cleaning and preprocessing techniques using Pandas and Scikit-learn. The goal is to prepare a raw marketing dataset for downstream machine learning tasks, forming a crucial part of a broader data science pipeline.

## 📂 Dataset Overview
The dataset contains customer information relevant to a marketing campaign. It includes:

Demographics: year_birth, education, marital_status, income

Purchase History: mntwines, mntfruits, mntmeatproducts, etc.

Web & Store Interaction Metrics

Campaign Engagement: Responses to past campaigns, complaints, etc.

## 🔧 Core Tasks
## ✅ Data Cleaning
Renamed all column headers to lowercase_snake_case for consistency

Converted dt_customer to proper datetime format

Cast education and marital_status as categorical features

Imputed or handled missing values appropriately

## ✅ Feature Engineering
Engineered a new feature: customer_days (number of days since enrollment)

Dropped non-informative or redundant fields:

id, dt_customer, z_costcontact, z_revenue

## ✅ Data Export
Final cleaned dataset exported to: processed_data.csv

## 🧪 Libraries & Tools
pandas

numpy
