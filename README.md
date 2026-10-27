# GreenPie

A Django e-commerce web app for groceries. Users can browse and search products, manage a cart, check out, view past orders, reschedule deliveries, and apply promotions. It also has signup, login and profile pages.

## Tech

- Python, Django
- SQLite
- HTML templates

## Run it

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Then open http://127.0.0.1:8000/. On Windows, run `set DJANGO_SETTINGS_MODULE=greenpie.settings` first.

## Tests

```bash
python manage.py test
```
