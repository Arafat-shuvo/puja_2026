# Django CRUD Operations

A simple Django web application demonstrating the fundamental CRUD (Create, Read, Update, Delete) operations using Django, Python, HTML, and SQLite.

## Overview

This project demonstrates how to perform basic database operations in Django. Users can add new records, view existing records, update information, and delete records through a simple web interface.

## CRUD Operations

The project covers four fundamental operations:

- **Create:** Add new records to the database.
- **Read:** Display and retrieve existing records.
- **Update:** Modify existing records.
- **Delete:** Remove records from the database.

## Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite
- Bootstrap (if applicable)

## Project Structure

```text
crud/
│
├── manage.py
├── db.sqlite3
│
├── crud/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── app/
    ├── migrations/
    ├── templates/
    ├── models.py
    ├── views.py
    ├── urls.py
    └── admin.py
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/crud.git
```

### 2. Navigate to the Project Directory

```bash
cd crud
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Django

```bash
pip install django
```

### 6. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Learning Objectives

Through this project, I aim to understand:

- Django project and app structure.
- Django Models and database management.
- URL routing and View functions.
- Handling HTTP requests.
- Performing CRUD operations.
- Connecting Django with SQLite.
- Building basic web applications.

## Author

**Md. Arafat Hossain**

GitHub: [Arafat-shuvo](https://github.com/Arafat-shuvo)

---

*This project is developed for learning and practicing Django CRUD operations.*
