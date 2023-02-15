# Learning Log

Learning Log is an application that helps you track your learning. It keeps a list of the topics you’re learning about. Whenever you learn something new about a topic, make an entry summarizing what you’ve learned. It is built with Django/Django REST Framework

## Clone the Repository

```
git clone https://github.com/becathey/learning-log-django
```

## Create & Activate a Virtual Environment

In the project directory, create and activate a virtual environment. For example:

```
python3 -m venv .venv
source .venv/bin/activate
```

## Install the Dependencies

To install the dependencies, run:

```
pip install -r requirements.txt
```

## Environment Variables

Create a .env file in root of project, and add a SECRET_KEY:

```
SECRET_KEY='<create-and-add-your-secret-key-here>'
```

The .env file should be added to a .gitignore file to protect your secret key.

## Run the App

To run the app in development mode, run:

```
python manage.py runserver
```

Open [http://localhost:8000](http://localhost:8000) in the browser to view the application.

## Deploy the App

To learn how to make the application production-ready and to deploy it, see the Django documentation:

[https://docs.djangoproject.com/en/4.1/howto/deployment/](How to Deploy Django)