# Pewlett-Hackard-Analysis

## Project Overview
Instead of having a large chunk of their workforce retiring, the managers want to introduce a mentoring program: experienced and successful employees stepping back into a part-time role instead of retiring completely. Their new role in the company would be as a mentor to the newly hired folks. 

### Purpose
Purpose of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Resources
- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv and titles.csv

## Results

- The Retirement Titles table contains titles for all employees who are retiring, and we observed that there are 133,776 entries. However, some employees are showing up multiple times as they have switched titles over the years. Once we removed the duplicates by taking the most recent titles of the retiring employees, we created the Unique Titles table to assist with our analysis. We have reduced to 90,398 unique entries in Unique Titles table and we observed that the total number of employees is 300,024 from original Employees.csv data. This confirms the management's concern as 30% of current employees will reach retirement age in near future.

- The Mentoriship Eligibility tab shows that there are 1,549 employees that are eligible to participate in a mentorship program, so there are enough experienced employees to become mentor to the newly hired staff. Management just need to convince 2 to 4% of the retiring employees to participate in mentorship program and they will have enough experienced employees to become mentor to the newly hired staff.

### Retirement Titles
- The Retirement Titles table shows all the titles of employees who were born between January 1, 1952 and December 31, 1955.

![Retirement_Titles](https://github.com/grwon/Pewlett-Hackard-Analysis/blob/master/Resources/retirement_titles.png)   

### Unique Titles
- The Unique Titles table shows all the most recent titles of employees who were born between January 1, 1952 and December 31, 1955.

![Unique_Titles](https://github.com/grwon/Pewlett-Hackard-Analysis/blob/master/Resources/unique_titles.png)   

### Retiring Titles
- The Retiring Titles table shows the number of recent titles of retiring employees.

![Retiring_Titles](https://github.com/grwon/Pewlett-Hackard-Analysis/blob/master/Resources/retiring_titles.png)   

### Mentorship Eligibility
- The Mentorship Eligibility table shows all the current employees who are born between January 1, 1965 and December 31, 1965.

![Mentorship_Eligibility](https://github.com/grwon/Pewlett-Hackard-Analysis/blob/master/Resources/retiring_titles.png)   

### Summary
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    - From the Retiring Titles table, we identified that 90,398 roles will need to be filled as the "silver tsunami" begins to make an impact.
     Below is breakdown by retiring title:
     - 29,414 senior engineers
     - 28,254 senior staff
     - 14,222 engineers
     - 12,243 staff
     - 4,502 technique leaders
     - 1,761 assistance engineers
     - 2 managers

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    - From the Mentorship Eligibility table and the below image, we determined the total count of employees eligible to participate in a mentorship program to be 1,549. When we compared the count of qualified, retirement-ready employees in Retiring Titles table to next generation of Pewlett Hackard employees in the below image. We have enough qualified employees to mentor the next generation of employees, as we only need about 2 to 4 % of experienced employees to mentor the new employees.

![Mentorship_Titles](https://github.com/grwon/Pewlett-Hackard-Analysis/blob/master/Resources/retiring_titles.png)
