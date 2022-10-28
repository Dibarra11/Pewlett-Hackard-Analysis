# Pewlett Hackard Analysis


## Overview

Pewlett Hackard provided us with an extensive database of employees, and they need to determine how many employees are close to retirement. In addition, they want to determine how many vacancies will need to be filled in the coming years. Finally, based on the findings, Pewlett Hackard will determine how many employees could receive a retirement package.

## Results

Based on the following four tables, we obtain the desired information for employees retiring soon.

### The table 1 

It shows employees who were born between the years 1952 and 1955.

![image](Resources/1.png)

![image](Resources/1-1.png)

### Table 2 

Utilizing the DISTINCT ON function, we removed the employee names whose names are repeated on the table.

![image](Resources/2.png)

### Table 3

Shows the number of employees possibly retiring by the department. The ORDER BY function displayed the count column in descending order.

![image](Resources/3.png)

### Table 4

Indicates employees born after 1965 and meet the criteria to be in the mentorship program. The DISTINCT ON function was utilized to sort the result of the table

![image](Resources/4.png)

![image](Resources/4-1.png)

## Summary

The analysis shows that there is a possibility that 72,458 employees will retire. 
  25,916 Senior Engineer
  24,926 Senior Staff
  9,285 Engineer
  7,636 Staff
  3,603 Technique Leader
  1,090 Assistant Engineer
  2 Managers

- How many employees are qualified to be in the mentorship program to train the new generation

  There are 1549 employees eligible for the mentoring program.
  
  Additional queries that could determine the outcome of the retiring workforce of Pewlett Hackard
  
  Employees' gender and Salary

  
  ![image](Resources/5.png)
  
  ![image](Resources/5-1.png)
  

