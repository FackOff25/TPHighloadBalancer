FROM python:3.8.5

RUN pip install --upgrade pip
RUN pip install Django==3.1.6

COPY . /app

WORKDIR /app

RUN python manage.py migrate

