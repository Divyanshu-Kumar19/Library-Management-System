# Library Management System

A simple web-based Library Management System built with Django.

## Tech Stack

- Python
- Django
- SQLite
- HTML (Django Templates)
- CSS + Bootstrap
- JavaScript

## Project Structure

- `LMS/` - Django project folder
  - `manage.py`
  - `db.sqlite3`
  - `library/` - main app (models, views, urls, templates, static files)
  - `LMS/` - project settings and root URL configuration
- `main.py` - additional Python entry/script file in repo root

## Features

- Add and view books
- Add and view students
- Issue book records
- Track issue/return details

## Prerequisites

- Python 3.8+
- pip

## Setup and Run

1. Clone the repository
2. Open terminal at project root (`Library-Management-System`)
3. (Optional but recommended) Create and activate a virtual environment
4. Install dependencies:

```bash
pip install django
```

5. Go to Django project folder:

```bash
cd LMS
```

6. Run migrations (if needed):

```bash
python manage.py migrate
```

7. Start development server:

```bash
python manage.py runserver
```

8. Open in browser:

- http://127.0.0.1:8000/

## Admin Access (Optional)

If you need admin access and no superuser exists:

```bash
python manage.py createsuperuser
```

Then visit:

- http://127.0.0.1:8000/admin/

## Notes

- This project currently uses SQLite (`db.sqlite3`) for local development.
- Static assets and templates are included under the `library/` app.
