# Python Django Blog Website ✅

A simple, self-contained blog application built with Django. It supports user registration and authentication, creating and managing posts (including images and audio attachments), searching and filtering posts, and a Django admin backend for site administration.

---

## 🚀 Project Overview

This repository is a complete Django blog project that demonstrates a typical blog feature set:

- User sign up, sign in, and profile management
- Create, edit, delete posts with images and audio
- Search and category-based filtering
- Contact form and basic site pages
- Admin site for managing users and posts

Key files and folders:

- `manage.py` — Django project entry point
- `requirements.txt` — Python dependencies
- `myproject/` — Django project settings and configuration (`settings.py`, `urls.py`)
- `myapp/` — Main application (models, views, templates)
- `templates/` — HTML templates (e.g. `index.html`, `post-details.html`)
- `static/` — Static assets (CSS, JS, images)
- `media/` — Uploaded media (images and audio)
- `db.sqlite3` — Default SQLite database (for development)

---

## 🛠️ Technology Stack

- Python 3.x
- Django
- HTML, CSS, JavaScript
- SQLite (default development DB)

---

## ✅ Features

- Registration and authentication
- Create, read, update, delete (CRUD) posts
- Image and audio uploads per post (see `media/posts/`)
- Search and category result pages
- Contact form and profile pages
- Admin interface for site management

---

## 💻 Local Setup (Windows)

1. Clone the repository:

   git clone <repo-url>
   cd Python-Django-Blog-Website

2. Create and activate a virtual environment (PowerShell):

   python -m venv .venv
   .\.venv\Scripts\Activate.ps1

   (Or for cmd.exe: `.venv\Scripts\activate.bat`)

3. Install dependencies:

   pip install -r requirements.txt

4. Apply migrations and create a superuser:

   python manage.py migrate
   python manage.py createsuperuser

5. Run the development server:

   python manage.py runserver

Open http://127.0.0.1:8000/ in your browser.

---

## ⚙️ Configuration & Environment

- For development, the project uses `settings.py` in `myproject/`.
- To keep secrets out of version control, set a `DJANGO_SECRET_KEY` environment variable and set `DEBUG=False` for production.
- Uploaded media is served from the `media/` directory (configured in `settings.py`).

---
