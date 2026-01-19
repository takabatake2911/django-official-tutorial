# Django Tutorial (Polls App)

This repository contains a learning project built by following the **official Django tutorial**.

The goal of this project is to understand Django fundamentals such as:
- Project and app structure
- URL routing
- Views and HTTP responses
- Models and database migrations
- Templates and forms
- Django admin

## Tutorial Reference

Official Django documentation:  
https://docs.djangoproject.com/en/6.0/intro/tutorial01/

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/takabatake2911/django-official-tutorial.git
cd django-official-tutorial
````

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the development server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/polls/
```

## Notes

* This project is for **learning purposes only**.
* The implementation closely follows the official Django tutorial.
* The repository structure reflects common Django best practices.

## License

This project is licensed under the MIT License.
