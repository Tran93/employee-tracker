#Employee tracker

## Description

In this application, I've created a CMS that stores employees data by ID, roles department, and salary. I also added functionality to update the role. I think particular application, I used the Inquirer and mysql packages

Before you start this application make sure you do the following commands:

Clone the repository from GitHub
Install node.js
Run npm install to install dependencies. Dependencies include mysql, console.table, express, inquirer, and jest.
Run mysql -u root -p to start the database connection.
Updated connection.js file with your own mysql user password.
Create the database by running the command: source db/schema.sql.
Seed the database by running the command: source db/seeds.sql.

## User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 
```

## Video Demonstration
https://drive.google.com/file/d/1ZoWsi3pH086MM9V0MbfIYRtv32h5fE_I/view

## Screenshot

The following video shows an example of the application being used from the command line:


