# ALX Travel App

A Django-based travel booking application.

## Setup

1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate venv: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Seed database: `python manage.py seed`
7. Run server: `python manage.py runserver`

## Models

- **Listing**: Properties available for booking
- **Booking**: Guest reservations
- **Review**: Guest reviews and ratings

## Seeding

The application includes a management command to populate the database with sample data:

```bash
python manage.py seed