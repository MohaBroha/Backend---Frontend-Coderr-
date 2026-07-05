# 🚀 Coderr -- Fullstack Marketplace Platform

> A modern fullstack marketplace platform built with Django REST
> Framework and Vanilla JavaScript.

**Author:** Moha Broha

------------------------------------------------------------------------

# 🌍 Live Demo

-   Frontend: https://coderr.mohabroha.dev
-   API: https://coderr.mohabroha.dev/api/registration/
-   Git urls: https://github.com/MohaBroha/coderr-project

------------------------------------------------------------------------

# 📖 About

Coderr is a fullstack marketplace platform that allows customers and
business users to interact through a modern REST API.

The project was developed from scratch and deployed to a production
Ubuntu server using Gunicorn, Nginx and Cloudflare.

------------------------------------------------------------------------

# ✨ Features

## Authentication

-   Registration
-   Login
-   Token Authentication
-   Customer & Business Accounts

## Marketplace

-   Create Offers
-   Update Offers
-   Delete Offers
-   Search & Filter Offers

## Orders

-   Create Orders
-   Update Status
-   Statistics

## Reviews

-   Business Reviews
-   Rating System

## Profiles

-   Customer Profiles
-   Business Profiles
-   Profile Editing

------------------------------------------------------------------------

# 🛠 Tech Stack

## Frontend

-   HTML5
-   CSS3
-   Vanilla JavaScript

## Backend

-   Python 3.12
-   Django
-   Django REST Framework

## Deployment

-   Ubuntu 24.04
-   Gunicorn
-   Nginx
-   systemd
-   Cloudflare
-   GitHub

------------------------------------------------------------------------

# 🏗 Architecture

``` text
Internet
    │
Cloudflare
    │
Hetzner Ubuntu Server
    │
Nginx
 ├───────────────┐
 │               │
 ▼               ▼
Frontend     Gunicorn
                 │
                 ▼
          Django REST API
                 │
                 ▼
             SQLite Database
```

------------------------------------------------------------------------

# 📂 Project Structure

``` text
Backend---Frontend-Coderr
│
├── README.md
├── backend
│   ├── auth_app
│   ├── profile_app
│   ├── offers_app
│   ├── orders_app
│   ├── reviews_app
│   ├── base_info_app
│   ├── core
│   ├── manage.py
│   ├── requirements.txt
│   └── .env.example
│
└── frontend
    ├── shared
    ├── scripts
    ├── assets
    ├── index.html
    ├── login.html
    ├── registration.html
    ├── offer.html
    └── profile pages
```

------------------------------------------------------------------------

# 🔄 Request Flow

``` text
Browser
   │
Frontend
   │
POST /api/...
   │
Nginx
   │
Gunicorn
   │
Django REST Framework
   │
SQLite
   │
JSON Response
   │
Browser
```

------------------------------------------------------------------------

# ☁ Deployment

1.  Clone repository
2.  Create Python virtual environment
3.  Install requirements
4.  Configure `.env`
5.  Run migrations
6.  Create superuser
7.  Configure Gunicorn
8.  Create systemd service
9.  Configure Nginx
10. Configure Cloudflare
11. Go live

------------------------------------------------------------------------

# 🚀 Local Installation

``` bash
git clone <repository>
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py runserver
```

------------------------------------------------------------------------

# 📡 Main API Endpoints

-   /api/registration/
-   /api/login/
-   /api/profile/
-   /api/profiles/business/
-   /api/profiles/customer/
-   /api/offers/
-   /api/offerdetails/
-   /api/orders/
-   /api/reviews/
-   /api/base-info/

------------------------------------------------------------------------

# 🎯 Learning Outcomes

-   Django REST API Development
-   Authentication & Permissions
-   REST Architecture
-   Ubuntu Server Administration
-   Gunicorn
-   systemd
-   Nginx Reverse Proxy
-   Cloudflare DNS & HTTPS
-   Production Deployment
-   Git & GitHub

------------------------------------------------------------------------

# 🔮 Future Improvements

-   CI/CD with GitHub Actions
-   PostgreSQL
-   Docker
-   Automated Deployment
-   Unit Test Expansion

------------------------------------------------------------------------

# 👨‍💻 Author

**Moha Broha**

GitHub: https://github.com/MohaBroha

------------------------------------------------------------------------

# 📄 License

This project is licensed under the MIT License.
