# API Reference

## Views

### employee_list

- URL: `/`
- Method: `GET`
- Description: Displays a list of all employees.

### employee_detail

- URL: `/employee/<int:pk>/`
- Method: `GET`
- Description: Displays the details of a specific employee.

### employee_create

- URL: `/employee/new/`
- Method: `GET`, `POST`
- Description: Creates a new employee.

### employee_update

- URL: `/employee/<int:pk>/edit/`
- Method: `GET`, `POST`
- Description: Updates an existing employee.

### employee_delete

- URL: `/employee/<int:pk>/delete/`
- Method: `GET`, `POST`
- Description: Deletes an existing employee.
