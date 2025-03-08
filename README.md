# 🛒 Electronics Store Sales Analysis

## 📌 Project Overview
This project analyzes **electronic store sales data** to uncover trends and patterns that drive revenue and customer behavior. Using **Pandas** and **Matplotlib**, we clean, process, and visualize sales data to answer key business questions.

## 📂 Repository Contents
- **`sales_data.csv`** – Raw dataset containing electronic store sales records.
- **`sales_analysis.ipynb`** – Jupyter Notebook for data cleaning, analysis, and visualization.

## 🔍 Data Cleaning Steps
Before analyzing the data, we perform essential **data preprocessing** tasks:
- 🧹 **Removing NaN values** – Drops missing records to ensure data accuracy.
- ❌ **Filtering out invalid entries** – Removes rows that don’t meet logical conditions.
- 🔄 **Converting data types** – Uses `to_numeric`, `to_datetime`, and `astype` to ensure consistency.

## 📊 Key Business Questions Answered
1. 📅 **What was the best month for sales?** – Identifies peak revenue month.
2. 🏙️ **Which city sold the most products?** – Determines high-performing locations.
3. ⏰ **What is the best time for advertisements?** – Suggests optimal ad placement times.
4. 🔗 **Which products are frequently bought together?** – Analyzes bundle purchases.
5. 🛍️ **What is the best-selling product and why?** – Identifies top-performing items.

## 📈 Data Analysis Techniques
To answer these questions, we use various **Pandas & Matplotlib** methods:
- 📌 **Concatenating multiple CSV files** – Uses `pd.concat()` to merge data.
- ➕ **Adding new columns** – Extracting meaningful insights from existing data.
- 📝 **String parsing** – Uses `.str` methods for data manipulation.
- 📊 **Aggregate analysis with `groupby()`** – Summarizing data effectively.
- 📉 **Visualizing trends** – Bar charts, line graphs, and other plots.

## 🛠 Technologies Used
- **Python** – for data processing and analysis.
- **Pandas** – for data manipulation and exploration.
- **Matplotlib & Seaborn** – for data visualization.
- **Jupyter Notebook** – for interactive coding and analysis.

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/NithinKolan/Electronics-Store-Sales-Analysis.git
