# Django Blog Platform

A full-stack blog application built with Django and server-side rendering. The project is structured across five Django apps with clean separation of responsibilities, backed by a MySQL database and Django AllAuth for authentication.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Django 4.2 (Python 3) |
| Database | MySQL |
| Frontend | Django Templates, HTML, CSS, JavaScript |
| Authentication | Django AllAuth (email and username) |
| Rendering | Server-Side Rendering (SSR) |

---

## Project Structure

| App | Responsibility |
|---|---|
| `core` | Home and about pages |
| `posts` | Post creation, editing, and display |
| `comments` | Comment system linked to posts |
| `blogger` | Author profiles and contact information |
| `accounts` | User registration, login, and logout |

---

## Features

- User registration and authentication via Django AllAuth
- Full CRUD for blog posts
- Comment system linked to individual posts
- Author profiles with images and contact details
- Django admin panel integration
- Session-based messaging for user feedback
- Static and media file configuration

---

## Setup

```bash
# Clone the repository
git clone https://github.com/alirzglshn/blog.git
cd blog

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure MySQL
# Create a database named ALIREZA_BLOG_DB and update credentials in settings.py

# Run migrations and start the server
python manage.py migrate
python manage.py runserver
```

Visit `http://127.0.0.1:8000/`

---

## Folder Structure

```
blog/
├── blog/           # Project configuration (settings, URLs, WSGI, ASGI)
├── core/           # Home and about pages
├── posts/          # Blog post management
├── blogger/        # Author profiles
├── comments/       # Post comments
├── accounts/       # Authentication
├── templates/      # Global HTML templates
├── static/         # CSS, JS, images
└── media/          # Uploaded user content
```

---

## Author

Alireza Golshan — Backend Developer (Django)
