# Tweetika

A clean and modern Django-based social posting app where users can register, log in, and share short posts with optional images. This project demonstrates core web development skills in Python, Django, authentication, forms, database modeling, and responsive UI design.

## 🌟 Project Overview

Tweetika is a simple microblogging application inspired by the concept of short social updates. It showcases how to build a full Django web app with:

- User registration and authentication
- CRUD operations for posts
- Image upload support
- Bootstrap-powered UI
- SQLite database integration

## 🚀 Features

- Register new users
- Log in and log out securely
- Create, edit, and delete tweets
- Upload a photo with each post
- Display posts in a timeline-like feed
- Use Django forms and model validation
- Build reusable templates and a polished layout

## 🛠️ Tech Stack

- Python
- Django 6.0.7
- SQLite
- Bootstrap 5
- Pillow for image handling
- HTML, CSS, and JavaScript

## 🧠 Skills Demonstrated

This project reflects strong development skills in:

- Django project and app architecture
- Model-View-Template (MVT) design pattern
- Database modeling with Django ORM
- Creating and handling forms
- Authentication and authorization
- URL routing and view logic
- Working with media files and uploads
- Building reusable templates and layout structure
- Clean project organization and maintainable code

## 📁 Project Structure

```text
Tweetika/
├── requirements.txt
├── twitter/
│   ├── manage.py
│   ├── db.sqlite3
│   ├── media/
│   ├── static/
│   ├── templates/
│   ├── tweet/
│   └── twitter/
```

## ⚙️ Installation and Setup

### 1) Clone the repository

```bash
git clone <your-repo-url>
cd Tweetika
```

### 2) Create a virtual environment

#### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3) Install dependencies

```bash
pip install -r requirements.txt
```

### 4) Apply database migrations

```bash
python manage.py migrate
```

### 5) Create a superuser (optional)

```bash
python manage.py createsuperuser
```

### 6) Run the development server

```bash
python manage.py runserver
```

Then open your browser at:

```text
http://127.0.0.1:8000/
```

## 🐍 Django Setup Notes

If you are setting up Django from scratch, the basic workflow is:

```bash
pip install django
django-admin startproject twitter
cd twitter
python manage.py startapp tweet
python manage.py migrate
python manage.py runserver
```

## 📌 How to Use the App

1. Open the homepage.
2. Register a new account.
3. Log in to your account.
4. Create a tweet with optional photo upload.
5. Edit or delete your posts from the feed.

## 🧪 Development Notes

This project is a great example of a beginner-friendly but practical Django application. It covers the full flow from database design to user interaction and UI presentation.

## ✨ Why This Project Stands Out

- Simple and easy to understand
- Built with real-world Django patterns
- Includes authentication and media handling
- Demonstrates both backend and frontend integration
- Shows strong fundamentals in Python web development

## 👨‍💻 Author

Built as a personal Django project to strengthen backend development, full-stack thinking, and clean code practices.
