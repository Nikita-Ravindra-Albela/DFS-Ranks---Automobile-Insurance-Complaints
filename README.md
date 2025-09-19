# DFS-Ranks---Automobile-Insurance-Complaints---Capstone
📊 Automobile Insurance Complaints Ranking Dashboard
Power BI Project | BFSI Domain
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------



📝 Overview
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project analyzes automobile insurance complaints data from multiple companies operating in New York State.
The main goal is to identify complaint patterns, company performance, and premium trends, and to create an interactive dashboard that supports decision-making for stakeholders in the Banking, Financial Services, and Insurance (BFSI) sector.

📂 Dataset
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Source: MySQL database project_automobile_insurance

Key Columns:

Company_Name — Name of the insurance company

Filing_Year — Year when the complaint was closed

Upheld_Complaints — Valid complaints confirmed by regulators

Question_of_Fact_Complaints — Complaints pending confirmation

Not_Upheld_Complaints — Withdrawn/invalid complaints

Total_Complaints — Sum of all complaint types

Premiums_Written (in Millions) — Average premiums collected in NYS over two years

Rank — DFS ranking based on complaint ratios

Ratio — Complaint ratio = Upheld complaints ÷ Premiums written

🧮 Analysis Performed
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. 📌 Complaint Diagnostic Report

Total complaints by company

Trend of complaints by year

Complaint ratio (complaints per million dollars of premium)

Identified companies with highest and lowest complaints

2. 💰 Premium Trend Analysis

Total premiums collected by each company

Yearly premium trend analysis

Examined possible reasons behind premium fluctuations
(e.g. changes in claims, regulatory factors, competition)

3. 📈 Comparative Insights

Compared 5+ companies side-by-side on:

Complaints

Premiums

Complaint ratio

Year-wise trends

📌 KPIs & DAX Measures

Company with Highest Complaints

Highest Complaints Count

Company with Lowest Complaints

Company with Highest Premium

Company with Lowest Premium

Average Complaints per Company

Dynamic slicers for Year and Company

📊 Dashboard Features
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Interactive slicers (Company, Year)

KPI cards for key metrics

Bar charts for company-wise performance

Line chart for year-wise complaint trend

Donut chart for fact vs upheld complaints

Complaint ratio comparison

Clean dark-themed design for readability

🛠 Tech Stack

Power BI — Dashboard design, data modelling, DAX

SQL (MySQL) — Data extraction

DAX — Calculated columns and measures

💡 Insights
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Complaint ratio is highest for smaller premium companies, indicating possible service or process issues.

Companies with higher premiums tend to have lower complaint ratios.

Complaint counts have decreased overall since 2010, suggesting improved service quality.

📎 How to Use

Download the .pbix file from this repository.

Open it in Power BI Desktop.

Connect to the dataset if needed and refresh data.

Use slicers to filter by company or year.

🏁 Outcome
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project demonstrates the ability to:

Perform end-to-end BFSI domain analysis

Apply DAX for KPIs

Build an interactive and insight-driven dashboard for business stakeholders

📌 Author
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Nikita Albela
💼 Aspiring Data Analyst | BFSI Domain
📧 nikitaalbela31@gmail.com

🔗 LinkedIn Profile - www.linkedin.com/in/nikita-albela-4194b1164
