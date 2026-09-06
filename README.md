# San Francisco Employee Compensation Dashboard

## 📊 Overview
An interactive Power BI dashboard analyzing employee compensation data for San Francisco city employees (2011–2014). The dashboard explores base pay trends, overtime impact, and pay differences across job titles and employees.

## 🎯 Objective
To identify patterns in employee compensation — including which job titles earn the most, how overtime pay affects total income, and how average pay evolved over time.

## 🛠️ Tools & Technologies
- **SQL Server** – Used to backfill and store the raw salary dataset
- **Power Query** – Data cleaning and transformation (handling nulls, standardizing job titles, formatting pay fields)
- **Power BI** – Data modeling, DAX measures, and interactive dashboard design

## 🔑 Key Insights
- **Battalion Chief, Fire Suppression** is the highest-paid job title, driven largely by overtime pay rather than base pay alone.
- **Average base pay increased from ~$64K (2011) to ~$70K (2013)**, before declining slightly in 2014.
- Overtime pay makes up a significant share of total compensation for top-earning job titles, especially in fire and emergency services roles.

## 📈 Dashboard Features
- KPI cards: Total job titles, total employees, average base pay
- Trend line: Average base pay by year
- Clustered bar chart: Top 7 job titles by average base pay vs. average overtime pay
- Horizontal bar chart: Top 5 employees by total pay & benefits
- Interactive filters: Employee name, year, job title

## 📸 Dashboard Preview
![Dashboard Screenshot](San_Francisco_Employee%20Compensation%20Dashboard.png)

## 📌 How to View
1. Download the `.pbix` file from this repository
2. Open with Power BI Desktop
3. Explore interactively using the filters at the top
