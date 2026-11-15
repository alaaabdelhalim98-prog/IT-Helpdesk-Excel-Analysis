# 📊 IT Helpdesk Ticket Analysis (Excel)

## 📌 Project Overview
This project analyzes an IT Helpdesk dataset containing **152 support tickets** to evaluate team workload, resolution efficiency, and customer satisfaction using Microsoft Excel.

## 🛠️ Tools & Excel Functions Used
* **Data Aggregation & Filtering:** `COUNTA`, `SUM`, `AVERAGEIF`
* **Data Summarization:** Pivot Tables
* **Data Visualization:** Pivot Charts (Column Charts)

## ❓ Business Questions & Key Findings
1. **What is the total number of IT tickets?**
   * **Answer:** 152 tickets (calculated using `COUNTA`).
2. **What is the average customer satisfaction rating for resolved tickets?**
   * **Answer:** 3.86 / 5 (calculated using `AVERAGEIF`).
3. **What is the total number of hours spent resolving tickets?**
   * **Answer:** 893 hours (calculated using `SUM`).
4. **Which support agent handled the highest workload?**
   * **Answer:** **Tamer Saeed** with 13 tickets (analyzed via Pivot Table & Column Chart).
5. **What is the most common IT problem reported?**
   * **Answer:** **Data Request** with 29 tickets, followed by **Hardware Issue** with 27 tickets (analyzed via Pivot Table & Column Chart).

## 📂 Workbook Structure
1. **`Helpdesk Data`**: Raw dataset along with summary KPI calculations and functions.
2. **`Agent Workload`**: Pivot Table and Column Chart analyzing ticket distribution per support agent.
3. **`Issue Types`**: Pivot Table and Column Chart highlighting the most frequent IT issues.
