# Employee-Tracker-UCLA-Challenge-12
*A command-line application to manage a company's employee database, using Node.js, Inquirer, and MySQL*

### App Screenshot

### App Demo


### Database Schema Desig




### Schema Description

- Department
    - `id`: INT PRIMARY KEY
    - `name`: VARCHAR(30) to hold department name

- Role
    - `id`: INT PRIMARY KEY
    - `title`: VARCHAR(30) to hold role title
    - `salary`: DECIMAL to hold role salary
    - `department_id`: INT to hold reference to department role belongs to

- Employee
    - `id`: INT PRIMARY KEY
    - `first_name`: VARCHAR(30) to hold employee first name
    - `last_name`: VARCHAR(30) to hold employee last name
    - `role_id`: INT to hold reference to employee role
    - `manager_id`: INT to hold reference to another employee that is manager of the current employee. This field may be null if the employee has no manager.

### Instructions on how to run the app

- Add a .env file to the root of the app with the following details

```text
DB_NAME='all_employees'
DB_USER='root'
DB_PW='xxx'
```


