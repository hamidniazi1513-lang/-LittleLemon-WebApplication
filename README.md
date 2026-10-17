# Little Lemon Web Application

## Project Overview
A restaurant web application built using Django and Django REST Framework.

## Features
- Restaurant home page
- Menu page
- Table booking API
- User authentication API
- Django administration panel

## Technologies
- Python
- Django
- Django REST Framework
- SQLite

## API Endpoints

| Endpoint | Description |
|---|---|
| `/restaurant/` | Restaurant home page |
| `/restaurant/menu/` | Menu page |
| `/restaurant/booking/` | Booking API |
| `/restaurant/booking/tables/` | Booking tables endpoint |
| `/auth/` | Authentication API |
| `/auth/users/` | Users endpoint |
| `/admin/` | Django administration |

## Run Locally

1. Install dependencies: `pip install -r readme.txt` only if that file actually contains valid pip requirements; otherwise install the packages listed in your dependency file.
2. Navigate to the folder containing `manage.py`.
3. Run: `python manage.py migrate`
4. Start the server: `python manage.py runserver`

Open `http://127.0.0.1:8000/` in your browser.

**Note:** API endpoints should be verified against the project's URL configuration.
