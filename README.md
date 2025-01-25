# USP-Project-
Employee & Department Management System
This project is a simple Employee & Department Management System implemented using a Bash script. The system allows users to manage employee and department records, including operations like adding, viewing, updating, deleting, and searching employee data. Additionally, the system provides functionalities to generate reports based on the employee records.

The project utilizes a basic command-line interface with dialog for user interaction, providing an intuitive and text-based graphical interface for the management operations.

Features
Add Employee: Allows the user to add a new employee with details such as employee ID, name, department, and salary.
Add Department: Enables adding a new department with a unique ID and name.
View Employee Records: Displays all stored employee records.
View Department Details: Displays all department records.
Search Employee Records: Allows searching for employee records by a search term (e.g., name or department).
Update Employee Details: Updates details for an existing employee based on their employee ID.
Delete Employee: Deletes an employee record from the system by employee ID.
Generate Reports: Generates a formatted employee report that can be viewed in the terminal.
Data Files
The system uses two data files to store information:

emp.lst: Stores employee records in the format: emp_id|name|dept|salary.
dept.lst: Stores department records in the format: dept_id|dept_name.
These files are automatically created when the system is initialized, and the data is stored in a simple, human-readable format.

Dependencies
dialog: A command-line utility for creating text-based user interfaces.
Usage
Clone this repository.
Run the script using a Bash shell.
Use the on-screen menu to select and perform actions.
Example
Add an employee:
Enter employee details (ID, name, department, and salary).
The employee will be added to the emp.lst file.
View employee records:
Displays all employees currently in the system.
