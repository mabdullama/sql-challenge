# sql-challenge

### Background

I have been hired as a new data engineer at Pewlett Hackard (a fictional company). My first major task is to do a research project about people whom the company employed during the 1980s and 1990s. The purpose of this project is designing the tables that hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. Then I’ll perform data modeling, data engineering, and data analysis.

### Data Modeling

This project includes a data modeling phase where we design the database structure and relationships using an Entity-Relationship Diagram (ERD). The ERD provides a visual representation of the database schema, showing the entities (tables) and their relationships.
The ERD model, generated using Quick DBD, illustrates the relationships and attributes of the entities in our database.

![ERD_Diagram](https://github.com/mabdullama/sql-challenge/blob/main/ERD_Diagram.png)

### Data Engineering
The data engineering phase consit of two steps:
1. Create table schemas "table_schema.sql" for the six provided CSV files, create primary keys, foreign keys, and constraints. Verify primary key uniqueness and utilize composite keys when needed.
2. Import the CSV data into the corresponding SQL tables mapping the columns. 

### Data Analysis
This part we create the "queries.sql" which performs the queries to analysie the databse and extract the following information:

1. List the following details of each employee: employee number, last name, first name, gender, and salary.
2. List employees who were hired in 1986.
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.
4. List the department of each employee with the following information: employee number, last name, first name, and department name.
5. List all employees whose first name is "Hercules" and last names begin with "B."
6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.













