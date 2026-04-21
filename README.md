# 🚲 Bike Sales Data Analysis - Excel Dashboard

## 📌 Project Overview
This project focuses on analyzing the demographic and financial factors that influence customer decisions to purchase a bike. An end-to-end data analysis pipeline was executed using **Microsoft Excel**, moving from raw, messy data to a clean, interactive dashboard. The dashboard provides actionable insights into high-conversion customer profiles, enabling data-driven marketing and sales strategies.

## 🛠️ Tools Used
* **Microsoft Excel**: Data Cleaning, Data Transformation, Pivot Tables, Pivot Charts, Slicers, and Interactive Dashboard Design.

## 📂 Dataset Details
The dataset contains demographic and socioeconomic information about various individuals and indicates whether or not they purchased a bike. 
* **Key Columns:** `Marital Status`, `Gender`, `Income`, `Children`, `Education`, `Occupation`, `Home Owner`, `Cars`, `Commute Distance`, `Region`, `Age`, and `Purchased Bike`.

## ⚙️ Project Workflow

### 1. Data Cleaning & Transformation (Working Sheet)
* **Standardization:** Replaced abbreviations in the `Marital Status` (M/S $\rightarrow$ Married/Single) and `Gender` (M/F $\rightarrow$ Male/Female) columns for better readability.
* **Formatting:** Converted the `Income` column to a standard currency format.
* **Feature Engineering:** Created a new `Age Brackets` column using nested `IF` statements to group continuous age data into distinct categories (e.g., *Adolescent, Middle Age, Old*).
* **Duplicate Removal:** Identified and removed duplicate records to ensure data integrity.

### 2. Data Processing (Pivot Tables)
Created multiple Pivot Tables to aggregate data and uncover hidden trends:
* **Average Income per Purchase:** Comparing the average income of individuals who bought a bike vs. those who didn't, split by gender.
* **Customer Commute Distance:** Analyzing how the distance a customer commutes daily impacts their likelihood of buying a bike.
* **Customer Age Brackets:** Evaluating which age demographic makes up the majority of the customer base.

### 3. Interactive Dashboard Creation
Designed a dynamic and visually appealing dashboard using **Pivot Charts**. Integrated **Slicers** to allow users to filter the data interactively based on:
* Marital Status
* Region (Europe, North America, Pacific)
* Education Level

## 📊 Key Insights Derived
1. **Income Factor:** There is a direct correlation between higher average income and the likelihood of purchasing a bike, particularly among male customers.
2. **Age Demographics:** **Middle-aged professionals** represent the largest and most frequent buyer segment compared to adolescent and older age brackets.
3. **Commute Distance:** Individuals with shorter commute distances (especially **0-1 miles**) are significantly more likely to purchase a bike, whereas the purchase rate drops sharply for those with a commute greater than 5 miles.

## 🚀 How to Use This Repository
1. Download the `Bikes_Sales_ExcelDashboard.xlsx` file.
2. Open the file in Microsoft Excel.
3. Navigate to the **"Dashboard"** worksheet.
4. Use the **Slicers** on the side to filter the dashboard visuals by Region, Marital Status, and Education to explore different customer segments.

---
*Created by [Jayant Singh Khanna](https://github.com/Jayantsinghkhanna)*
