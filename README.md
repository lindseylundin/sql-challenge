# SQL Homework - Employee Database: A Mystery in Two Parts


## Background

Research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

Design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:

1. Data Engineering
2. Data Analysis

## Instructions

#### Data Modeling

- Inspect the CSVs and sketch out an ERD of the tables. 

   ![image](https://user-images.githubusercontent.com/75588830/109763550-39e24700-7bc0-11eb-95d8-3676c6b8e157.png)


#### Data Engineering

- Create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

- Import each CSV file into the corresponding SQL table. 

#### Data Analysis

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

      ![image](https://user-images.githubusercontent.com/75588830/109764123-1bc91680-7bc1-11eb-9b8e-62c15ea0df7d.png)


2. List first name, last name, and hire date for employees who were hired in 1986.

      ![image](https://user-images.githubusercontent.com/75588830/109764302-621e7580-7bc1-11eb-84be-4545fd1220f9.png)


3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
      
      ![image](https://user-images.githubusercontent.com/75588830/109764417-824e3480-7bc1-11eb-8782-49e04071b65a.png)


4. List the department of each employee with the following information: employee number, last name, first name, and department name.

      ![image](https://user-images.githubusercontent.com/75588830/109764459-91cd7d80-7bc1-11eb-890a-3d45e03c98be.png)


5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

      ![image](https://user-images.githubusercontent.com/75588830/109764496-9eea6c80-7bc1-11eb-8c8b-b432daf2942a.png)


6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

      ![image](https://user-images.githubusercontent.com/75588830/109764518-aad62e80-7bc1-11eb-9092-7b4ebce33d1b.png)


7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

      ![image](https://user-images.githubusercontent.com/75588830/109764558-b6c1f080-7bc1-11eb-8a18-46ba79795ac8.png)


8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

      ![image](https://user-images.githubusercontent.com/75588830/109764604-c5100c80-7bc1-11eb-97a4-b8c2b0120ac0.png)

