FROM python:3.8.5

RUN pip install --upgrade pip
RUN pip install Django
RUN pip install django-prometheus

COPY . /app

WORKDIR /app

RUN python manage.py migrate

