# Deloitte Australia Data Analytics Virtual Experience (Forage)

This repository contains my work completed as part of the **Deloitte Australia Data Analytics Virtual Experience** program on Forage.

## Project Tasks

1. **Task 1 – Machine Downtime Analysis using Tableau**
2. **Task 2 – Gender Pay Equality Classification using Excel**

---

## 🔹 Task 1: Machine Downtime Analysis (Tableau)

### Objective
- Identify the factory with the highest machine downtime.
- Identify the device type contributing most to downtime in that factory.

### Work Completed
- Imported the provided JSON telemetry dataset into Tableau.
- Created a calculated field **Unhealthy** (10 minutes downtime per unhealthy record).
- Built bar charts for factory and device type analysis.
- Created a dashboard combining both charts.
- Applied factory selection as a filter so the device chart updates dynamically.

### Result
- **Daikibo Factory Seiko (Osaka)** had the highest downtime.
- **LaserWelder** had the highest downtime in that factory.

### Files
- `Task-1-Tableau/Screenshot/Task_1_Tableau_Dashboard.png` – Tableau dashboard screenshot
- `Task-1-Tableau/Result/Task_1_Final_Result.png` – final result image
- `Task-1-Tableau/Result/Task_1_Result.md` – result summary

### Tool Used
- Tableau Public

---

## 🔹 Task 2: Gender Pay Equality Classification (Excel)

### Objective
Classify each job role based on its Equality Score (-100 to +100) into:
- Fair
- Unfair
- Highly Discriminative

### Work Completed
- Added a new column named **Equality Class**.
- Used the following Excel formula:
  `=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))`
- Applied the formula to all rows in the dataset.

### Files
- `Task-2-Excel/Screenshot/Task_2_Result_Preview.png` – preview screenshot of the Excel result
- `Task-2-Excel/Result/Gender_Pay_Equality_Classification.xlsx` – completed Excel result
- `Task-2-Excel/Result/Task_2_Result.md` – classification result summary

### Tool Used
- Microsoft Excel

---

## 📌 Skills Practiced
- Creating calculated fields in Tableau
- Building bar charts and dashboards
- Applying filters in Tableau dashboards
- Writing conditional formulas in Excel (IF, ABS)
- Following business instructions to solve structured tasks

## 👤 Author
**Himanshu Gupta**

Deloitte Australia Data Analytics Virtual Experience (Forage)
