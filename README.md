# Employee Management

A small, beginner-friendly command-line application for managing employee records. It demonstrates how to separate a simple text-based interface (`app.py`) from employee business logic (`employee_service.py`).

## Features

- Add employees with an ID, name, and department.
- List all employees.
- Search employees by ID or name.
- List employees in a department (department matching ignores case).
- Change an employee's department.
- Delete an employee.
- Validate required fields and prevent duplicate employee IDs.

## Setup

Install Python 3. The project uses only the Python standard library, so no third-party packages need to be installed.

Download or clone this project, then open a terminal in the project directory.

## Run the application

Run:

```bash
python app.py
```

Use the numbered menu to choose an action. Select **7** to exit.

## Run the tests

Run the unit tests from the project directory:

```bash
python -m unittest -v
```

## Limitations

- Employee records are kept in memory while the application is running. They are cleared when you exit; the application does not save records to a database or file.
- The application is a basic single-user command-line program, without authentication or a graphical interface.
- Search checks employee IDs and names; department filtering is available separately through the menu.

This project is used to demonstrate Git and CI/CD.