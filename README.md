# Bike-Sales-Data-Analysis-Dashboard
# 🚲 Bike Sales Data Analysis & Interactive Dashboard

## 📌 Project Overview
This project is an end-to-end Data Analysis portfolio piece built entirely in **Microsoft Excel**. 
The goal of this project is to analyze the purchasing behavior of bike store customers based on various demographic factors such as income, age, gender, commute distance, and education. 

The final output is an interactive and dynamic dashboard that allows stakeholders to easily filter and extract actionable business insights.

## ⚙️ Data Cleaning & Transformation (ETL)
To ensure the accuracy and reliability of the insights, the raw dataset underwent a rigorous data preparation phase:
- **Data Cleansing:** Identified and removed all duplicate records to prevent skewed data and inaccurate metrics.
- **Data Transformation (Feature Engineering):** 
  - Created a new calculated column for **"Age Brackets"** (categorizing customers into *Adolescent, Middle Age, and Old*). This transformation was crucial for creating cleaner, more readable, and practically useful visualizations compared to plotting individual ages (which ranged from 25 to 89).
  - Standardized categorical variables (e.g., standardizing marital status and gender abbreviations into full words for better readability).

## 📊 Dashboard Features & Visualizations
The dashboard is highly interactive, utilizing **Excel Slicers** to allow dynamic filtering. 

### 🎛️ Interactive Filters (Slicers)
Users can slice the data dynamically using three main filters:
1. **Marital Status** (Married / Single)
2. **Region** (Europe / North America / Pacific)
3. **Education** (Bachelors / Graduate Degree / High School / Partial College / Partial High School)

### 📈 Key Visualizations
- **Average Income per Purchase (Bar Chart):** Compares the average income of customers who purchased a bike vs. those who didn't, segmented by gender.
- **Customer Commute Distance (Line Chart):** Illustrates the relationship between the distance customers commute (0-1 Miles to More than 10 Miles) and their likelihood to purchase a bike.
- **Customer Age Brackets (Line Chart):** Highlights which age demographic (Adolescent, Middle Age, Old) drives the most sales.
- **Detailed Customer Age 25-89 (Line Chart):** A granular view of purchase counts across exact customer ages.

## 🛠️ Tools & Technologies Used
- **Microsoft Excel**
- **Data Cleaning Tools** (Remove Duplicates, Find & Replace)
- **Functions & Formulas** (Nested `IF` statements for Age Brackets)
- **Pivot Tables & Pivot Charts** (For data aggregation and visualization)
- **Slicers** (For interactive dashboard capabilities)

## 🚀 How to Use This Project
1. Download the `Bike_Sales_Project.xlsx` file from this repository.
2. Open the file in Microsoft Excel.
3. Navigate to the **"Dashboard"** sheet.
4. Click on the Slicers (Marital Status, Region, Education) on the left side to interact with the charts and see how customer demographics affect bike sales dynamically.

## 🖼️ Dashboard Snapshot
<img width="1221" height="667" alt="Dashboard_Screenshot" src="https://github.com/user-attachments/assets/f5d1bed7-2426-477e-aa95-66df5c86c1e9" />


------------------------------------------------------------
*If you find this project interesting, feel free to reach out or connect with me!*
