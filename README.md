# 🎬 Video Streaming Website

A full-stack video streaming platform built with:

- **Backend:** Django  
- **Frontend:** HTML, CSS, Vanilla JavaScript  
- **Database:** PostgreSQL  

Users can browse, and stream videos through a clean and responsive interface.

---

# 🚀 Features

- User Authentication (Register / Login / Logout)
- Video Upload & Streaming
- Django Admin Panel
- PostgreSQL Database
- Static & Media File Handling

---

# 🛠 Tech Stack

- Python 3.x
- Django
- PostgreSQL
- HTML5
- CSS3
- JavaScript (Vanilla)

---

# ⚙️ Installation Guide

## Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

## Create Virtual Environment

```bash
python -m venv venv
```

source venv/bin/activate

## Install Dependencies
```bash
pip install django psycopg2-binary
pip freeze > requirements.txt
```

Or if requirements.txt exists:
```bash
pip install -r requirements.txt
```

## Setup PostgreSQL Database
### Login
```bash
psql -U postgres
```

### RUN:
```bash
CREATE DATABASE videostream_db;
CREATE USER videostream_user WITH PASSWORD 'yourpassword';
ALTER ROLE videostream_user SET client_encoding TO 'utf8';
ALTER ROLE videostream_user SET default_transaction_isolation TO 'read committed';
ALTER ROLE videostream_user SET timezone TO 'UTC';
GRANT ALL PRIVILEGES ON DATABASE videostream_db TO videostream_user;
```

## Project Structure
```bash
video-streaming-site/
│
├── manage.py
├── requirements.txt
├── README.md
│
├── project_name/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── app_name/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│
└── static/
    ├── css/
    ├── js/
    └── videos/
```


