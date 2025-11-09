# 📰 Django Blog

A full-featured blog web application built entirely with **Django** and **server-side rendering (SSR)** — no APIs, no React, no frontend frameworks.  
This project was my **second ever Django project**, built right after my e-commerce site, as a way to strengthen my understanding of **Django’s core backend features**, **templating system**, and **app architecture**.

---

## 🚀 Overview

This is a **blog platform** where users can sign up, log in, write posts, and interact with published content.  
The project is structured around **five Django apps**, each handling a clear part of the system:

| App | Purpose |
|------|----------|
| `core` | Handles main pages like Home and About |
| `posts` | Manages post creation, publishing, and display |
| `comments` | Defines user comments (linked to posts) |
| `blogger` | Displays registered authors and their profiles |
| `accounts` | Manages user authentication (sign up, sign in, sign out) |

Everything is rendered on the server side using **Django Templates**, keeping things fast, simple, and secure — exactly how a traditional Django app should be.

---

## 🧠 What I Learned

This project was a deep dive into Django’s fundamentals:

- Setting up multi-app Django projects  
- Building models, views, and URL routes from scratch  
- Using Django’s built-in authentication system  
- Handling user sessions and messages  
- Managing static & media files  
- Structuring templates for scalable projects  
- Connecting Django to a MySQL database  
- Implementing CRUD operations across multiple apps  

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Backend** | Django 4.2 (Python 3) |
| **Database** | MySQL |
| **Frontend** | Django Templates, HTML, CSS, JS |
| **Auth System** | Django AllAuth (email + username) |
| **Rendering** | 100% Server-Side Rendering (SSR) |
| **Environment** | Development on Ubuntu / Xubuntu |

---

## ⚙️ Features

✅ User Registration & Login (via Django AllAuth)  
✅ Create, Edit, Delete Posts (CRUD)  
✅ Comment System (linked to posts)  
✅ Blogger Profiles with Images & Contact Info  
✅ Responsive Templates (server-rendered)  
✅ Clean URL structure  
✅ Message system for user feedback  

---

## 🗂️ Project Structure


blog/
├── blog/ # Main Django project folder
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
│
├── core/ # Home & about pages
├── posts/ # Blog posts management
├── blogger/ # Blogger profiles
├── comments/ # Comments linked to posts
├── accounts/ # User authentication (sign up, sign in, logout)
│
├── templates/ # Global HTML templates
├── static/ # CSS, JS, images
└── media/ # Uploaded user photos


---

# 1️⃣ Clone the repository
git clone https://github.com/alirzglshn/blog.git
cd blog

# 2️⃣ Create & activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Set up the MySQL database
# (Make sure you have a database named ALIREZA_BLOG_DB and update credentials in settings.py if needed)

# 5️⃣ Run migrations
python manage.py migrate

# 6️⃣ Start the development server
python manage.py runserver

# 7️⃣ Visit the app in your browser
# 👉 http://127.0.0.1:8000/


🧩 Why This Project Matters

This project represents my foundation as a Django developer.
It taught me how to structure large Django projects, connect apps together, handle authentication, and build a dynamic site with zero reliance on external APIs or frontend frameworks.

Everything you see here was done with Django’s core features, proving that I can build full, production-style applications with nothing but backend power.


THANKS FOR VEWING THIS REPOSITORY
