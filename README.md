# cmsc408-sp2025-hw8

## Homework 8 - World Bank Indicator Analysis 🌍

This project is part of CMSC 408 and focuses on analyzing the World Bank's World Development Indicator (WDI) dataset using SQL. The goal was to extract meaningful insights from a large, structured dataset while practicing advanced SQL concepts.

### 🔎 What This Project Covers
- Connecting to a database using secure credentials and `.env` variables.
- Exploring the WDI dataset using `SELECT`, `WHERE`, `GROUP BY`, and `JOIN` queries.
- Creating new tables based on filtered criteria (e.g., countries only).
- Generating pivot-style summary tables using `CASE WHEN` and aggregation.
- Writing multi-step queries using `CTEs` to calculate percentages and distributions.
- Identifying missing data combinations and correcting data anomalies.

### 🧠 Skills Practiced
- Data filtering and aggregation
- Cross joins and identifying missing relationships
- Conditional logic in SQL (`CASE` statements)
- Percentage calculations using nested queries
- Database table creation and updates

### 📝 Reflection
This assignment helped reinforce how SQL can be used not just for data extraction, but also for shaping and transforming data for insights. It emphasized problem-solving strategies in structured querying, and introduced me to using multiple CTEs for organizing complex logic.

### 🚀 How to Run This
1. Clone the repo
2. Make sure your `.env` file is set with the appropriate database credentials.
3. Open `report.qmd` and run:
   ```bash
   quarto render reports/report.qmd
   ```
4. View the generated `report.html` and submit as needed.

---

💡 _“Remind your future self what you were thinking”_ — probably that writing clean, readable queries makes life a lot easier. 😄
