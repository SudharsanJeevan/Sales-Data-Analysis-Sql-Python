# 📊 Sales Data Analysis using SQL and Python

## 📌 Project Overview

This project analyzes a retail sales dataset to extract meaningful business insights using SQL for data aggregation and Python (Pandas, Matplotlib, Seaborn) for data analysis and visualization.

The objective is to evaluate:
- Regional sales performance
- Profitability across product categories
- Customer segment contribution
- Impact of discounting on profit

---

## 📁 Dataset

- Dataset: Sample Superstore Dataset  
- Records: 9,000+ rows  
- Features: Sales, Profit, Discount, Category, Region, Customer Segment  

---

## 🛠 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- SQL (SQLite)
- Jupyter Notebook

---

## 🧹 Data Preprocessing

The dataset was examined and prepared before analysis:

- Checked data types using `df.info()`
- Generated summary statistics using `df.describe()`
- Verified missing values using `df.isnull().sum()`
- Checked for duplicate records
- Standardized column names for SQL compatibility

The dataset contained no missing or duplicate values.

---

## 🗄 SQL-Based Analysis

The dataset was loaded into an SQLite database and analyzed using SQL queries with:

- `GROUP BY`
- `SUM()`
- `ORDER BY`
- Aggregation techniques

---

## 📈 Key Business Insights

- The **West region** generates the highest total sales.
- The **Technology category** is the most profitable.
- The **Consumer segment** contributes the largest share of revenue.
- Higher discount levels are strongly associated with reduced profitability.
- Certain sub-categories (e.g., Tables) consistently generate losses.

---

## 📊 Visualization

- Bar charts for categorical comparisons  
- Scatter plot for analyzing Discount vs Profit relationship  

---

## 📂 Project Structure

- sales_data_analysis.ipynb   # Main analysis notebook  
- SampleSuperstore.csv       # Dataset  
- Sales_Data.db              # SQLite database  

---

## 🚀 How to Run

1. Clone the repository  
2. Open the notebook in Jupyter  
3. Run all cells to reproduce results  

---

## 🔗 Project Link

👉 https://github.com/SudharsanJeevan/Sales-Data-Analysis-Sql-Python

---

## 🎯 Conclusion

This project demonstrates:

- SQL-based data aggregation  
- Data cleaning and preprocessing using Pandas  
- Business insight extraction  
- Data visualization for decision-making  

It showcases practical skills required for an entry-level Data Analyst role.

---

## 👤 Author

Sudharsan Jeevan  
Aspiring Data Analyst / Data Scientist
