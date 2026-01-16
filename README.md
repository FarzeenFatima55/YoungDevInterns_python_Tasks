# DevInterns Python Tasks

This repository contains Django-based tasks for the DevInterns program. Follow the steps below to set up and run the project locally on your machine.

---

## 1. Clone the Repository

```bash
git clone https://github.com/FarzeenFatima55/Devinterns_python_Tasks.git
cd Devinterns_python_Tasks
```

---

## 2. Create a Virtual Environment

```bash
python -m venv .venv
```

---

## 3. Activate the Virtual Environment (Windows)

```bash
.venv\Scripts\activate
```

> After activation, you should see `(.venv)` in your terminal.

---

## 4. Install Django

```bash
pip install django
```

---

## 5. Database Setup

Create migration files:

```bash
python manage.py makemigrations
```

Apply migrations to the database:

```bash
python manage.py migrate
```

---

## 6. Create Superuser (Admin Account)

```bash
python manage.py createsuperuser
```

Follow the prompts to set a username, email, and password.

---

## 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and go to:

```
http://127.0.0.1:8000/
```

To access the Django admin panel:

```
http://127.0.0.1:8000/admin/
```

---

## Notes

* Make sure Python is installed and added to your system PATH.
* Always activate the virtual environment before running the project.
* This project uses Django’s default SQLite database.

---

Happy Coding 🚀
