# cmsc408-sp2025-hw8

## Homework 8 - World Bank Indicator Analysis 🌍

---

## 🌍 Overview

This assignment explores the **World Development Indicators (WDI)** database curated by the World Bank. The project emphasizes real-world SQL data analysis, schema exploration, and data cleaning across a large dataset containing both country and regional statistics.

You’ll find insights on country counts, region breakdowns, income distribution, and data inconsistencies using structured SQL queries and **Quarto** to generate a full report.

---

## 📁 Project Structure

cmsc408-sp2025-hw8-ishaamalikk/
│
├── reports/
│   ├── report.qmd         # Quarto notebook with all tasks & queries
│   ├── report.html        # Final rendered report to submit
│   ├── helpers.py         # DB connection/query helpers
│   ├── _quarto.yml        # Metadata config (name, email, etc.)
│
├── .gitignore             # Ignores .env and unnecessary files
├── README.md              # This file

---

## ✅ Topics Covered

- SQL basics: `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`
- SQL joins and filters for non-countries and missing data
- Creating and filtering new tables using `CREATE TABLE ... SELECT`
- Conditional aggregation using `CASE WHEN`
- Nested queries & `CTEs` for calculating region-income percentages
- Cross-tabulation and missing pair detection

---

## 🧠 Key Skills Practiced

- Writing SQL queries for real-world datasets  
- Transforming data with multi-layer filters and groupings  
- Detecting anomalies and cleaning data  
- Generating pivot-style and percentage-based summary tables  
- Updating values conditionally using SQL `UPDATE`  

---

## ▶️ How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-ishaamalikk.git
   cd cmsc408-sp2025-hw8-ishaamalikk

	2.	Install dependencies:

poetry install


	3.	Activate the Poetry environment:

poetry shell


	4.	Render the report:

cd reports
quarto render report.qmd


	5.	✅ Submit report.html to Canvas
✅ Push your repo and submit to Gradescope for autograding

⸻

📝 Reflection

This project sharpened my ability to structure complex SQL queries in an analytical context. I particularly enjoyed working with conditional logic (CASE), and found the region-income breakdowns both challenging and rewarding. Using CTEs gave me a cleaner way to write multi-step transformations — a skill I’ll definitely carry forward.

⸻

💡 Tip to Future Me:
Clean queries are happy queries. Comment your logic, use CTEs, and keep your joins tight.

