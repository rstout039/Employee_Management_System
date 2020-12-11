# Employee_Management_System
I created a app that lets any company be able to manage and view their departments, roles, and employees in their companies. <br>
This app uses the Node, Inquirer, MySQL, and console.table packages, as well as a MySQL database to store employee information. <br>

The following sets of code are needed to develop the departments, roles, and employees: <br>

# Department:

id - INT PRIMARY KEY

name - VARCHAR(30) to hold department name

# Role:

id - INT PRIMARY KEY

title -  VARCHAR(30) to hold role title

salary -  DECIMAL to hold role salary

department_id -  INT to hold reference to department role belongs to

# Employee:

id - INT PRIMARY KEY

first_name - VARCHAR(30) to hold employee first name

last_name - VARCHAR(30) to hold employee last name

role_id - INT to hold reference to role employee has

manager_id - INT to hold reference to another employee that manager of the current employee. This field may be null if the employee has no manager

There is also created a command-line application that does the following:

Add departments, roles, employees

View departments, roles, employees

Update employee roles

Update employee managers

View employees by manager

Delete departments, roles, and employees
