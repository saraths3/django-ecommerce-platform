# Django E-Commerce Platform

A full-featured e-commerce platform built with Django and Django REST Framework. The project demonstrates session management, CRUD operations, database relationships, and RESTful API development in a practical web application.

---

## Overview

This project was developed as part of an academic assignment to explore core Django concepts, including:

* Session Management
* CRUD Operations
* Database Modeling
* User Management
* REST API Development
* Django Administration

The application provides product management, order processing, user profile management, shopping cart functionality, and API access for products and orders.

---

## Features

| Feature                  | Description                               |
| ------------------------ | ----------------------------------------- |
| Product Management       | Create, view, update, and delete products |
| User Profiles            | Manage customer profile information       |
| Order Management         | Create and manage customer orders         |
| Shopping Cart            | Session-based cart functionality          |
| Recently Viewed Products | Session-based product history             |
| REST API                 | Product and order API endpoints           |
| Admin Panel              | Built-in Django administration support    |

---

## Technology Stack

| Technology            | Usage                |
| --------------------- | -------------------- |
| Python                | Programming Language |
| Django                | Web Framework        |
| Django REST Framework | API Development      |
| SQLite                | Database             |
| HTML                  | Templates            |
| CSS                   | Frontend Styling     |

---

## Installation

### Clone the Repository

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

Linux/macOS:

```bash
source .venv/bin/activate
```

Windows:

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Administrator Account

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

---

## API Endpoints

### Products

| Method | Endpoint                     |
| ------ | ---------------------------- |
| GET    | `/api/products/`             |
| GET    | `/api/products/<id>/`        |
| POST   | `/api/products/add/`         |
| PUT    | `/api/products/update/<id>/` |
| DELETE | `/api/products/delete/<id>/` |

### Orders

| Method | Endpoint                   |
| ------ | -------------------------- |
| GET    | `/api/orders/`             |
| GET    | `/api/orders/<id>/`        |
| POST   | `/api/orders/add/`         |
| PUT    | `/api/orders/update/<id>/` |
| DELETE | `/api/orders/delete/<id>/` |

---

## Project Status

| Module             | Status   |
| ------------------ | -------- |
| Product CRUD       | Complete |
| User Profile CRUD  | Complete |
| Order CRUD         | Complete |
| Session Management | Complete |
| Product API        | Complete |
| Order API          | Complete |

---

## Future Improvements

* Authentication and authorization
* Product categories
* Search and filtering
* Payment gateway integration
* Order tracking
* Product reviews and ratings

---

## License

This project was created for educational and learning purposes.
