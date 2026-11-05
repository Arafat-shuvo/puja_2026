# Django CRUD Operations

A beginner-friendly Django web application demonstrating the four fundamental CRUD (Create, Read, Update, and Delete) operations using Python, Django, HTML, CSS, and SQLite.

## Overview

This project demonstrates how to build a simple database-driven web application using the Django framework. It allows users to create, view, update, and delete records through an intuitive web interface.

The project is designed to help beginners understand Django's core concepts, including models, views, URL routing, templates, database migrations, and ORM operations.

## Features

- **Create:** Add new records to the database.
- **Read:** Retrieve and display existing records.
- **Update:** Edit and modify existing records.
- **Delete:** Remove records from the database.
- **Database Integration:** Manage application data using SQLite.
- **Django Admin:** Manage database records through the built-in admin interface.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Programming |
| Django | Web Framework |
| HTML5 | Page Structure |
| CSS3 | Styling |
| SQLite | Database Management |
| Bootstrap | Responsive UI (if applicable) |

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
git clone https://github.com/Arafat-shuvo/crud.git
```

### 2. Navigate to the Project Directory

```bash
cd crud
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install django
```

### 6. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

### 8. Open the Application

Visit the following URL in your web browser:

```text
http://127.0.0.1:8000/
```

## Learning Objectives

Through this project, you will learn:

- Django project and app structure.
- Creating and managing Django models.
- Performing CRUD operations using Django ORM.
- Handling HTTP requests with views.
- Configuring URL routing.
- Rendering dynamic HTML templates.
- Managing database migrations.
- Using the Django Admin Panel.

## Future Improvements

- Implement user authentication and authorization.
- Add search and filtering functionality.
- Integrate pagination.
- Improve UI with Bootstrap.
- Add form validation and error handling.
- Implement Django REST Framework APIs.

## Author

**Md. Arafat Hossain**

GitHub: [@Arafat-shuvo](https://github.com/Arafat-shuvo)

---

If you find this project helpful, consider giving it a ⭐ on GitHub!
