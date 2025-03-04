# Setup

## Prerequisites

- Python 3.x
- Django
- MySQL

## Installation

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

## Building the Documentation

1. Install MkDocs and the Material theme:
    ```sh
    pip install mkdocs-material
    ```

2. Serve the documentation locally to preview it:
    ```sh
    mkdocs serve
    ```

3. Open your web browser and navigate to `http://127.0.0.1:8000/` to view the documentation.

4. To build the static site:
    ```sh
    mkdocs build
    ```

5. To deploy the documentation to GitHub Pages:
    ```sh
    mkdocs gh-deploy
    ```
