# HR Analytics Dashboard (Excel Capstone Project)

##Project Overview

This project focuses on cleaning, transforming, analyzing, and visualizing HR data using Microsoft Excel. The objective was to convert a raw HR dataset into an interactive dashboard this include cleaning and transforming raw HR data into a reliable data, analysis, building interactive Pivot Tables and Pivot Charts, creating an executive HR dashboard and generating actionable business insights.

##Key Findings

-Total Workforce : 150 employees across 6 Departments.
-Overall Attrition Rate: 23%
-Overall Average Salary: ~$84,000
-Average performance Scores are similar between Active and Left Employees, implying others factors drive attrition.

##Insights

The following insights were generated;

**Workforce Distribution**

-The company has 150 employees with an overall attrition rate of 23%, indicating that approximately one out of every five employees has either left or resigned.
-The Information Technology department has the highest number of employees, while the Finance department has the fewest. Despite having a smaller workforce, the Finance department records a lower attrition rate than the Information Technology department, indicating stronger employee retention within the Finance department.

**Salary Analysis**

-The analysis reveals an average employee salary of approximately $84K. Among all departments, the Finance department has the highest average salary, while the Operations department has the lowest average salary.

**Employee Attrition**

-The Operations department records the highest attrition rate, which may suggest challenges such as a heavier workload, increased job demands, or other workplace factors contributing to employee turnover. In contrast, the Human Resources department demonstrates strong employee retention with one of the lowest attrition rates.

**Performance Analysis**

-The performance analysis by employment status indicates that some high-performing employees have either resigned or left the organization. This suggests that employee performance alone does not guarantee retention and highlights the need to investigate other factors influencing employee turnover.

**Bonus Distribution**

-The bonus payout analysis shows that employees within the Achieving performance band receive the highest total bonus payout, indicating that the organization's bonus structure is aligned with employee performance and rewards achievement.


##Recommendations

-Improve employee retention strategies within the Operations department.
-Review salary competitiveness in departments experiencing high attrition.
-Conduct exit interviews to identify reasons for employee turnover.
-Continue rewarding high-performing employees through performance-based incentives.
-Implement continuous HR monitoring using interactive dashboards.

###Data Cleaning Summary

-Data was turned in to a table format and duplicates were removed using the employee ID column.
-Hire date column was formatted into date data type and text to column was used to correct the inconsistency and errors.
-Employment status column was changed into text format and the "Proper" function was used to change the first letters cases.
-The department code column was changed into text format and the upper function was used to change the letter cases
-The performance scores and salary columns were filtered by department code and their averages were calculated to handle the missing values
-The first name column missing values were handled by filtering by department code and the fill down was used.
-"Concatenate" function was used to create the full name column
-Year of service column was created by using the "datedif" function
-Performance band and eligible bonus Columns were created using "ifs" function

