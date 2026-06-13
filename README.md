
# Django E-Commerce Platform

A Django-based e-commerce platform developed to demonstrate session management, CRUD operations, and RESTful API development using Django REST Framework.

## Features

* Product management (Create, Read, Update, Delete)
* User profile management
* Order management
* Shopping cart using Django sessions
* Recently viewed products using Django sessions
* RESTful API for products
* RESTful API for orders
* Django admin integration

## Technologies Used

| Technology            | Purpose             |
| --------------------- | ------------------- |
| Python                | Backend development |
| Django                | Web framework       |
| Django REST Framework | API development     |
| SQLite                | Database            |
| HTML                  | Frontend templates  |
| CSS                   | Styling             |

## Project Requirements

| Requirement              | Status      |
| ------------------------ | ----------- |
| Product CRUD             | Implemented |
| User Profile CRUD        | Implemented |
| Order CRUD               | Implemented |
| Shopping Cart Session    | Implemented |
| Recently Viewed Products | Implemented |
| Product API              | Implemented |
| Order API                | Implemented |
| Django Admin Support     | Implemented |

## Installation

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/django-ecommerce-platform.git
cd django-ecommerce-platform
```

### Create and Activate a Virtual Environment

Linux/macOS:

```bash
python -m venv .venv
source .venv/bin/activate
```

Windows:

```bash
python -m venv .venv
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

### Create an Admin User

```bash
python manage.py createsuperuser
```

### Run the Development Server

```bash
python manage.py runserver
```

The application will be available at:

```
http://127.0.0.1:8000/
```

## API Endpoints

| Method | Endpoint                   | Description        |
| ------ | -------------------------- | ------------------ |
| GET    | /api/products/             | List all products  |
| GET    | /api/products/<id>/        | Retrieve a product |
| POST   | /api/products/add/         | Create a product   |
| PUT    | /api/products/update/<id>/ | Update a product   |
| DELETE | /api/products/delete/<id>/ | Delete a product   |
| GET    | /api/orders/               | List all orders    |
| GET    | /api/orders/<id>/          | Retrieve an order  |
| POST   | /api/orders/add/           | Create an order    |
| PUT    | /api/orders/update/<id>/   | Update an order    |
| DELETE | /api/orders/delete/<id>/   | Delete an order    |

## Screenshots

Screenshots can be added here after project completion.

## License

This project was developed for educational purposes.
