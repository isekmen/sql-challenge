# SQL Challenge

# Background
Your major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. 

This Challenge is divided into three parts:
1. Data Modeling
2. Data Engineering
3. Data Analysis


# Instructions

## Data Modeling
Inspect the CSVs and sketch out an Entity Relationship Diagram of the tables. You can use a tool like [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com).

## Data Engineering
* Use the information you have to create a table schema for each of the six CSV files.

  * Remember to specify data types, primary keys, foreign keys, and other constraints.
  * For the primary keys check to see if the column is unique, otherwise create a [composite key](https://en.wikipedia.org/wiki/Compound_key). Which takes to primary keys in order to uniquely identify a row.
  * Be sure to create tables in the correct order to handle foreign keys.

* Import each CSV file into the corresponding SQL table.

## Data Analysis
Once you have a complete database, do the following:

1. List the employee number, last name, first name, sex, and salary of each employee.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, first name.

4. List the department number for each employee along with that employee's employee number, last name, first name, and department name.

5. List first name, last name, and sex for each employees whose first name is "Hercules" and whose last names begins with the letter "B."

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

# Hint
To avoid errors, import the data in the same order as the corresponding tables got created. And, remember to account for the headers when doing the imports.

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.