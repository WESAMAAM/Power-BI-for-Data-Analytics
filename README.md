# Power BI Data Analytics Portfolio

## About This Project
This repository highlights my work and progress after completing a comprehensive 8-hour course on Power BI for Data Analytics. The projects here demonstrate my ability to take raw data, clean it, model it, and turn it into interactive, easy-to-understand visual dashboards. The main focus of the data used in these projects is the data science job market, helping job seekers understand trends, salaries, and required skills.

## Course Overview
The course I completed is **"Power BI for Data Analytics - Full Course for Beginners"** by Luke Barousse. It is a complete guide that goes from the very basics to advanced features of Power BI.

* **Part 1 (Fundamentals):** Focused on importing data, basic data cleaning, and creating standard visuals (bar charts, line charts, maps) to build a basic dashboard.
* **Part 2 (Advanced):** Focused on using Power Query for deep data transformation (ETL process) and using DAX (Data Analysis Expressions) for creating custom measures and complex data models (like a star schema).
* > <img src="images/Screenshot 2026-09-25 151502.png" alt="Basic Data Jobs Dashboard" width="700">

## My Dashboards
During the course, I built two main dashboards. I have published both to the web so anyone can interact with them.

### 1. Basic Data Jobs Dashboard (Project One)
This first dashboard was built using the fundamental skills learned in the first half of the course. The goal was to solve a problem for data science job seekers by providing a single place to see market trends.

* **What it shows:**
  * Total count of data jobs available.
  * Average yearly and hourly salaries.
  * Which countries have the most job postings (using a map visual).
  * The top data jobs and how many postings don't require a degree.
* **Link to view:** [Click here to open Project One](https://app.powerbi.com/view?r=eyJrIjoiNTUzZjExNWUtNjE4OC00Yzc1LWJlYzYtMTA1ZTlkMzZmNjdkIiwidCI6IjRlNTViNTkzLTIzYWItNDNiNC05ZGJhLTNmNGQ4YmQyOGI0MyIsImMiOjl9)

**Dashboard Screenshot:**
> *(Please replace `placeholder1.png` with your actual image path)*
> <img src="placeholder1.png" alt="Basic Data Jobs Dashboard" width="700">

### 2. Advanced Data Jobs Dashboard (Project Two)
This is the upgraded, final version of the dashboard. It uses a more complex data model (star schema) and advanced DAX formulas. This version provides much deeper insights, especially regarding the specific skills required for different jobs.

* **What it shows (Upgrades):**
  * **Skill Analysis:** Shows the top requested skills (like Python, SQL, AWS) and what percentage of job postings require them.
  * **Salary vs. Skills:** A scatter plot showing if jobs that require more skills actually pay a higher salary.
  * **Interactive Parameters:** Users can switch the view to see data by Job Title, Country, Company, or Skill using interactive buttons.
  * **Dynamic KPIs:** Key Performance Indicators that update based on what the user selects.
  * **Dark Mode Design:** A cleaner, more professional look focused on key metrics.
* **Link to view:** [Click here to open Project Two](https://app.powerbi.com/view?r=eyJrIjoiMGJjNzYxZWEtYTkzZi00M2I3LWEzOGUtZWVmZTVlMmEzNTQ0IiwidCI6IjRlNTViNTkzLTIzYWItNDNiNC05ZGJhLTNmNGQ4YmQyOGI0MyIsImMiOjl9)

**Dashboard Screenshot:**
> *(Please replace `placeholder2.png` with your actual image path)*
> <img src="placeholder2.png" alt="Advanced Data Jobs Dashboard" width="700">

## Key Skills Demonstrated
Through building these two dashboards, I have learned and applied the following skills:

* **ETL (Extract, Transform, Load):** Using **Power Query** to clean messy data, change data types, split columns, replace values, and merge/append different data tables.
* **Data Modeling:** Moving from simple flat tables to building a **Star Schema** with Fact and Dimension tables, and managing relationships (one-to-many, filtering directions).
* **DAX (Data Analysis Expressions):** Writing explicit measures for calculations (like `CALCULATE`, `DIVIDE`, `COUNTROWS`), creating conditional columns, and understanding row, query, and filter contexts.
* **Data Visualization:** Choosing the right charts (bar, column, line, scatter, maps, cards, matrices) to answer specific business questions without cluttering the screen.
* **Interactive Features:** Adding slicers, buttons, bookmarks, and field parameters to allow users to customize what data they see.

## Tools Used
* Power BI Desktop
* Power Query Editor
* DAX Language

## Conclusion
This project was a great hands-on experience. Moving from the first basic dashboard to the final advanced version showed me the real power of Power BI. I learned that having a clean data model and using DAX allows for much deeper analysis, like finding the exact relationship between the skills you have and the salary you can expect.
