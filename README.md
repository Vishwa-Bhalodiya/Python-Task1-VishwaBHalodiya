# SuperAdmin Django Project with CSV Export 📊

A Django project with an enhanced **SuperAdmin** interface that allows administrators to **export saved data in CSV format** directly from the admin panel.

---

## Features

- Full **Django admin interface** for managing data.
- **Export selected records as CSV** via admin action.
- Supports dynamic data export for any model.
- Easy setup and superuser creation.

---

## Requirements

- Python 3.x
- Django 4.x (or compatible)

---

## Setup & How to Run
Step 1: Navigate to the Project Directory
```bash
cd "C:\Users\Your_Path\SuperAdmin for Django final\SuperAdmin for Django\mysite"
```
- Make sure to replace "Your_Path" with the correct path where your Django project is located on your system.

Step 2: Install Required Dependencies
```bash
pip install django
```

Step 3: Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
Step 4: Create SuperAdmin
```bash
python manage.py createsuperuser
```
- Enter Username, Email, and Password.

Step 5: Run the Development Server
```bash
python manage.py runserver
```
Step 6: Access the Admin Panel
- Open your browser and go to:
`
http://127.0.0.1:8000/admin
`

Login with the superuser credentials.

