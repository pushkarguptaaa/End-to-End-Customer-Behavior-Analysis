# Customer Shopping Behavior Analysis  
End-to-End ETL, SQL Analysis, and Power BI Dashboard

This project showcases a complete data analytics pipeline built using **Python**, **SQL**, and **Power BI** to analyze customer shopping behavior.  
Starting from raw CSV data, the workflow includes ETL in Python, structured analysis in SQL Server, and interactive visualization in Power BI.

---

## 📌 Project Overview

The goal of this project is to clean, transform, and analyze customer shopping data to understand:

- Who the high-value customers are  
- Which age groups contribute most to revenue  
- How subscription and discounts affect purchasing  
- What products and categories perform the best  
- Which customer segments (new, returning, loyal) drive business growth  

The final result is an insights-rich Power BI dashboard.

---

## 🛠️ Tech Stack

- **Python (pandas, Jupyter Notebook)** – ETL, cleaning, feature engineering  
- **SQL Server** – Business queries & analysis  
- **Power BI** – Visualization & dashboard  
- **CSV Dataset** – Raw input data  

---


## 🔄 ETL Pipeline (Python)

Performed in Jupyter Notebook using pandas.

### **Data Cleaning**
- Removed nulls and corrected inconsistent records  
- Cleaned and standardized column names (snake_case)  
- Normalized categories  
- Converted datatypes (dates, numerical columns)  
- Removed duplicates  

### **Feature Engineering**
- Created **age groups**  
- Derived **purchase frequency**  
- Labeled **customer segments** (New, Returning, Loyal)  
- Added **revenue**, **discount_used**, and **net_spend** fields  

After cleaning & transformation, the final dataset was exported to SQL Server.

---

## 🧮 SQL Analysis

Executed in SQL Server.

### Key Analysis Performed
- Revenue by age group and gender  
- Spending patterns of subscribers vs non-subscribers  
- Customer segment performance  
- Discount dependency and impact on margin  
- Category-level performance  
- Best-rated and best-selling products  
- High-value discount customers  
- Shipping type performance insights  

All queries are included in the `/sql` folder.

---

## 📊 Power BI Dashboard

The cleaned SQL dataset was imported into Power BI to create an interactive report.

### Dashboard Components
- Revenue & order trends  
- Customer demographics  
- Product & category performance  
- Subscription impact  
- Discount analysis  
- Customer segment performance  

![dashboard preview](/dashboard_screenshot.png)

---

## 📈 Key Insights

- Loyal customers drove the highest revenue  
- Age 31–45 contributed the largest purchase volume  
- Discount-heavy categories showed lower profit potential  
- Subscription members spent significantly more  
- Certain products dominated both revenue and ratings  
- Shipping choices varied by customer type  

---

## 🧠 Skills Demonstrated

- End-to-end ETL pipeline development  
- Python data cleaning & feature engineering  
- SQL for analytical queries  
- Power BI dashboarding  
- Data storytelling  
- Creating actionable business insights  

---

## ▶️ How to Run This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/customer-shopping-behavior.git
