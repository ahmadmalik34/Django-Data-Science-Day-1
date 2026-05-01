# 🌐 Personal Bio Site

<div align="center">

**Your First Django Project — No Database Required**

[![Django](https://img.shields.io/badge/Django-5.0%2B-darkgreen?style=flat-square&logo=django)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[Features](#-features) • [Installation](#-installation) • [Usage](#-quick-start)

</div>

---

## 🎯 Overview

Your first proper Django project. Learn the MTV pattern, static files, templates, and how to structure a Django app — all without touching a database.

**A three-page personal website built in pure Django.**

---

## ✨ Features

| Feature | Details |
|---------|---------|
| 🏠 **Home Page** | Landing page with introduction |
| 👤 **About Page** | Detailed bio and background |
| 📧 **Contact Page** | Contact information and links |
| 🎨 **Base Template** | Shared layout with Django template inheritance |
| 📱 **Responsive Design** | Works on desktop and mobile |
| ⚡ **No Database** | Pure views returning HTML strings |

---

## 📦 Tech Stack

- **Framework:** Django 5.0+
- **Language:** Python 3.8+
- **Frontend:** HTML5 + CSS3
- **Styling:** Custom CSS with theme variables

---

## 🚀 Quick Start

### Installation

```bash
# Create virtual environment
python -m venv venv

# Activate it
.\venv\Scripts\activate  # Windows
source venv/bin/activate  # macOS/Linux

# Install dependencies
pip install django python-decouple
```

### Run Locally

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 📂 Project Structure

```
Day_1_Personal_Bio_Site/
├── manage.py
├── config/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── portfolio/
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       ├── base.html
│       ├── home.html
│       ├── about.html
│       └── contact.html
└── static/
    └── css/
        └── style.css
```

---

## 🎓 What You'll Learn

✅ Django project vs app structure  
✅ URL routing with `path()` and `include()`  
✅ Function-based views  
✅ Django Template Language (DTL)  
✅ Template inheritance with `{% extends %}`  
✅ Static files and CSS organization  
✅ MTV pattern in action  

---

## 🔧 Customization

### Change Theme Colors

Edit `static/css/style.css` to modify:

```css
:root {
  --primary: #ff7f00;      /* Orange */
  --text: #333333;          /* Dark gray */
  --background: #ffffff;    /* White */
}
```

### Add New Pages

1. Create a view in `portfolio/views.py`
2. Add a URL pattern in `portfolio/urls.py`
3. Create template in `portfolio/templates/`

---

## 📖 Key Concepts

### MTV Pattern
- **M**odel — Database layer (not used here)
- **T**emplate — HTML rendering
- **V**iew — Business logic

### Template Inheritance
Base template provides layout; child templates fill in content.

### URL Routing
Maps URLs to view functions using `urls.py`

---

<div align="center">

**Day 1 of 50 — Django × Data Science Challenge**

Learning Django from scratch.

</div>