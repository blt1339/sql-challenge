# sql-challenge
![sql.png](sql.png)

# Background
[Project Details](project_instructions_readme.md)

# Project Information
Inside the EmployeeSQL directory there are the following:

    * data directory - Contains the csv files for import into EmployeeSQL

    * ERA_Setup.xlsx - Contains the information pulled from the CSV files to utilze when creating tables
    * ERA_Setup.txt - Contains the information used to create the ERD Diagram
    * ERA_Diagram.png - A ERA Diagram of EmployeeSQL

    * EmployeeSQL_Creation.sql - contains the SQL to create the tables in the EmployeeSQL database

    * EmployeeSQL_Query.sql - contains the SQL to run the requseted queries on EmployeeSQL database

    * EmployeeSQL_Bonus_Analysis.ipynb - A Jupyter Notebook to perform the bonus analysis using SQLAlchemy 
    * config.py - This file is necessary to execute EmployeeSQL Bonus Analysis.ipynb and must be created using the correct values instead of "".

        user_name = ""
        password = ""
        port_no = ""
        db_name = "EmployeeSQL"

# ERD Diagram
![ERD_Diagram.png](EmployeeSQL/ERD_Diagram.png)

# Bonus Analysis Observations
## The following is the common salaries analysis
![common_salaries.png](EmployeeSQL/images/common_salaries.png)

### Observations
The number of employees in the smaller salary ranges are greater than the number employees in the larger salary range. That is realistic.
But according to statista.com HP did not reach over 300,000 until 2008. Additionally HP Wikipedia mentioned that there were 85,000 employees in 1985. Therefore the total salary records of 300,024 in the 80s and 90s does not seem realistic.

## The following is the average salary per title analysis
![average_salaries_per_title.png](EmployeeSQL/images/average_salaries_per_title.png)

### Observations
There are some things that do not make sense when reviewing this result. Assistant Engineer, Engineer, and Senior Engineer have average salaries that are almost the same. As well Staff and Senior Staff have around the same average salary which should not be the case.

# The indentification of employee 499942
![sql.png](EmployeeSQL/images/employee_499942.png)

# Observations
Given the name of the employee is April Foolsday, the reference to this employee seems to confirm that this assignement was a test.
