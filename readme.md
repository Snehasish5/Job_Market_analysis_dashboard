# 📊 Job Market & Salary Analysis — Power BI Dashboard

**📌 Project Overview**

This project showcases an interactive **Power BI dashboard** that analyzes global job market trends and salary insights using real-world job data. The dashboard helps identify **in-demand roles, salary patterns, experience-level impact, remote work trends, and location-based compensation differences**.

The project demonstrates end-to-end **Power BI skills**, including data preparation, DAX measures, and business-focused visualization design.


**📂 Dataset**

*File Name:* `salaries_1.csv`
*Type:* CSV (real-world job market data)
*Key Fields Used:*
  - `work_year`
  - `experience_level`
  - `employment_type`
  - `job_title`
  - `salary_in_usd`
  - `company_location`
  - `remote_ratio`
  - `company_size`


**🔄 Data Preparation (Power Query)**

--Imported data using **Get Data → Text/CSV**
--Selected only relevant analytical columns
--Removed null and invalid salary records
--Standardized data types:
--Numeric: salary, year, remote ratio
--Text: job title, experience level, company size, location
--Applied all transformations using **Power Query Editor**


**📐 DAX Measures**

The following measures were created to support analysis:

*DAX:*

--Average Salary = AVERAGE(salaries_1[salary_in_usd])

--Job Count = COUNT(salaries_1[job_title])

--Max Salary = MAX(salaries_1[salary_in_usd])


**📊 Dashboard Visuals**

*The Power BI dashboard includes:*

--Top 10 Most Demanded Job Roles

--Average Salary by Experience Level

--Salary Distribution by Experience Level

--Top 10 Job Locations by Demand

--Top 10 Locations by Average Salary

--Average Salary by Remote Work Ratio

--Salary Trend Over Years

--Top 10 Highest Paying Job Roles


**🎛 Interactivity**

*Dynamic slicers for:*

--Experience Level

--Employment Type

--Company Size

--Remote Ratio

--Hover tooltips enabled across all visuals

--Salary values formatted in USD

--Clean, professional dashboard theme for business use



**📈 Key Insights**

--Senior and executive roles command the highest salaries with higher variability

--Mid-level positions dominate overall job demand

--Remote roles offer competitive or higher pay compared to on-site roles

--Large companies generally provide better compensation for experienced roles

--Salary levels show a consistent upward trend over the years



**🛠 Tools & Technologies**

--Power BI Desktop

--Power Query

--DAX

--Custom Box & Whisker Visual (Power BI AppSource)



**🎯 Use Case**

*This project is ideal for:*

--Data Analyst portfolios

--Business and HR salary analysis

--Interview demonstrations of Power BI skills

--Job market trend exploration