# 📊 E-Commerce Sales & Time-Series Analysis
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Data%20Analysis-Pandas-red)](https://pandas.pydata.org/)
[![Visualization](https://img.shields.io/badge/Visualization-Seaborn%2FMatplotlib-orange)](https://seaborn.pydata.org/)

## 🎯 Overview
This project performs an end-to-end exploratory data analysis (EDA) and feature engineering on e-commerce transaction data. The analysis tracks 3,500 records to uncover business growth patterns, seasonal sales trends, and product profitability metrics from 2022 to early 2025.

The project transitions from raw transaction logs to a strategic business report, identifying peak shopping days and high-margin product categories to optimize marketing and inventory management.

## 🛠️ Tech Stack
- **Data Handling:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Analysis Type:** Time-Series Analysis & Feature Engineering

## 📈 Pipeline Phases

### 1. Data Cleaning & Feature Engineering
To move beyond basic reporting, several high-value features were engineered:
* **Profit Metrics:** Created `Profit_Margin_Pct` and `Unit_Profit` to evaluate which products drive actual wealth vs. just revenue.
* **Temporal Features:** Extracted `Month`, `Day_of_Week`, and `Is_Weekend` from raw `Order Date` timestamps to track consumer behavior.
* **Operational Logic:** Calculated `COGS` (Cost of Goods Sold) and `Order_Intensity` to categorize order volumes and operational expenses.

### 2. Time-Series Analysis
A deep dive into the 3-year timeline of the dataset:
* **Growth Tracking:** Implemented cumulative sum functions to track the journey to a **$10 Million revenue milestone**.
* **Seasonality:** Isolated weekly cycles to identify "Peak" vs "Trough" shopping days using the `Day_of_Week` feature.
* **Trend Comparison:** Overlayed Monthly Sales vs. Profit lines to verify margin consistency during high-volume periods.

### 3. Business Logic & Observations
* **The "MVP" (Laptop):** Identified as the primary driver for both sales volume and profit margins.
* **Weekend Surge:** Discovered that **Sunday** is the highest-performing day (>$1.6M), indicating a consumer-heavy shopping pattern.
* **Efficiency King (Camera):** Isolated as a low-cost, high-volume "Low-Risk Winner" due to low unit costs and steady demand.

## 🏆 Key Results
* **Cumulative Revenue:** Successfully hit the **$10,000,000** milestone by January 2025.
* **Profit Stability:** Confirmed that despite sales peaks (near **$400k/month**), profit margins remain stable, indicating healthy cost control.
* **Actionable Insight:** Identified **Wednesday** as the primary "Slump Day," providing a data-backed opportunity for mid-week promotional interventions.

## 📂 Repository Structure
* `E-Commerce Dataset.ipynb`: The complete Python workbook containing all code, engineering, and visualizations.
* `ecommerce_sales_data.csv`: The primary dataset containing 3,500 transaction records.
* `requirements.txt`: Necessary libraries to reproduce the analysis environment.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

**Prashant Shukla**  
📧 Email: prashantshukla8851@gmail.com
💼 LinkedIn: [Prashant Shukla](https://www.linkedin.com/in/prashant-shukla-58ba19373) 

**Project Link:** [https://github.com/pr4sh4nt-shukla/E-Commerse-Sales-Insights](https://github.com/pr4sh4nt-shukla/E-Commerse-Sales-Insights)

---

⭐ **If you found this project helpful, please consider giving it a star!** ⭐
