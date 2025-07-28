# 💼  DS & AI Job Market Analytics Dashboard — Power BI Project

This project is a real-world Job Analytics dashboard built in **Power BI**, using a **JSON dataset sourced from Kaggle**. It analyzes job postings based on company, location, salary, rating, and job type.

---

## 📊 Dashboard Pages

### 🔹 1. Job Market Overview

- ✅ Total Jobs, Average Company Ratings (KPI Cards)
- 📊 Bar Chart: Number of Positions vs Companies
- 🍩 Donut Chart: Most Common Job Titles
- 🌍 Map Visual: Count of Companies by Location, Average Salary (Min/Max), and Position Distribution
- 📐 Average Rating by Job Type

### 🔸 2. Salary Analysis

- 💵 KPIs: Average Minimum and Maximum Salaries (Annualized)
- 📊 **Top 5 Lowest-Paying Jobs** with Company, Role, and Location
- 🏆 **Top 10 Highest Average Salary Roles**
- ⚖️ Scatter Plot: Rating vs Minimum Salary
- ☁️ Word Cloud: Company & Position Names by Location
- 📘 Bar Chart: Average Salary by Position Title

---

## 🔧 Data Transformation Highlights

- Parsed nested JSON using Power Query
- Converted salary strings (hourly/yearly) into unified `SalaryMin_Annual` and `SalaryMax_Annual` values
- Cleaned currency symbols, handled nulls
- No separate "Disclosed/Not Disclosed" column added — only rows with valid salary were modeled

---

## 📁 File Contents

- `Job_Market_Analytics.pbix` – Power BI Dashboard File

---

## 📦 Dataset

Original data was downloaded from Kaggle in `.json` format:
- Includes fields: `company`, `positionName`, `location`, `salary`, `rating`, `jobType`, `description`, etc.

---

## 📎 How to Use

1. Open `Job_Market_Analytics.pbix` in Power BI Desktop
2. Review two report pages: Job Market Overview & Salary Analysis
3. Interact with filters, maps, and slicers to explore job trends

---

## ✨ Author

**Keshav Singh Rajpoot**

Let’s connect on [LinkedIn] www.linkedin.com/in/keshav-singh-rajpoot-b37277242

---

## 🏷️ Tags

`Power BI` • `Kaggle` • `Dashboard` • `Data Cleaning` • `Power Query` • `DAX` • `Job Market Analysis`

