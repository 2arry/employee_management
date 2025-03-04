# Employee Management System

This is a simple Employee Management System built with Django. It allows you to perform CRUD (Create, Read, Update, Delete) operations on employee records.

## Features

- List all employees
- View employee details
- Add a new employee
- Edit an existing employee
- Delete an employee

## Setup

### Prerequisites

- Python 3.x
- Django
- MySQL

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/2arry/employee_management.git
    cd employee_management
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up the MySQL database:
    - Create a database named `employee_db`.
    - Update the database settings in `employee_management/settings.py` with your MySQL credentials.

5. Apply the migrations:
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

6. Create a superuser to access the Django admin interface:
    ```sh
    python manage.py createsuperuser
    ```

7. Run the development server:
    ```sh
    python manage.py runserver
    ```

8. Open your web browser and navigate to `http://127.0.0.1:8000/` to access the application.

## Usage

### Employee List

- The main page displays a list of all employees.
- You can add a new employee by clicking the "Add New Employee" link.
- Each employee has links to view details, edit, and delete.

### Employee Detail

- Click on an employee's name to view their details.

### Add/Edit Employee

- Fill out the form to add or edit an employee.
- Click "Save" to submit the form.

### Delete Employee

- Click the "Delete" link next to an employee to delete them.
- Confirm the deletion on the next page.

## Admin Interface

- Navigate to `http://127.0.0.1:8000/admin/` and log in with the superuser credentials.
- You can manage employees from the admin interface as well.

## License

This project is licensed under the MIT License.
