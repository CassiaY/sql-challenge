# SQL-challenge  
<font size="3">**Module 9 Challenge**  
**Contributors:** Cassia Yoon  
**Github link:** https://github.com/CassiaY/sql-challenge</font>

## Project Background  
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.  
For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.  
Assignment prompt is found in [module9_assignment.pdf](/module9_assignment.pdf).

## Data Modeling
**Instructions:** Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables.  
![Alt text](/README_files/ERD.png)

## Data Engineering
**Instructions:** Create a table schema for each of the six CSV files.  
See [schema_tables.sql](/EmployeeSQL/schema_tables.sql) file. CSV files are found in the [data folder](/EmployeeSQL/data/). I imported the tables in the following order:  
1. departments
2. titles
3. employees
4. dept_emp
5. dept_manager
6. salaries

## Data Analysis Prompts
See my SQL query codes in [data_analysis_queries.sql](/EmployeeSQL/data_analysis_queries.sql).

1. List the employee number, last name, first name, sex, and salary of each employee.  

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).  
The most common last name was 'Baba' :smiley:

## Resources
- To sketch ERD: https://www.quickdatabasediagrams.com/
- query part of a date: https://www.geeksforgeeks.org/datepart-function-in-sql-server/

# Acknowledgements
I wish to thank our teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
