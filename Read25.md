# Django REST Framework and Docker

### What is Django REST framework?

- Django REST framework is a powerful and flexible toolkit for building Web APIs. The Web browsable API is a huge usability win for your developers. Authentication policies including packages for OAuth1a and OAuth2. Serialization that supports both ORM and non-ORM data sources.

### What is difference between Django and Django REST framework?

- Django is the web development framework in python whereas the Django Rest Framework is the library used in Django to build Rest APIs.
- Django Rest Framework is especially designed to make the CRUD operations easier to design in Django.

### Why Django REST framework is used?

- Django Rest Framework lets you create RESTful APIs: A way to transfer information between an interface and a database in a simple way. They created the structure using HTML and CSS, and then used an API to populate each article.

### What is docker in Django?

- Docker is a containerization tool used for spinning up isolated, reproducible application environments. This piece details how to containerize a Django Project, Postgres, and Redis for local development along with delivering the stack to the cloud via Docker Compose and Docker Machine.

### How does Django integrate with Docker?

- Quickstart: Compose and Django
    1. Create an empty project directory.
    2. Create a new file called Dockerfile in your project directory.
    3. Add the following content to the Dockerfile .
        - **syntax=docker/dockerfile:1**
        - FROM python:3
        - ENV PYTHONUNBUFFERED=1
        - WORKDIR /code
        - COPY requirements.txt /code/
        - RUN pip install -r requirements.txt
        - COPY . /code/
    4. Save and close the Dockerfile .
    5. Create a requirements.txt in your project directory.
    6. Add the required software in the file.
        - Django>=3.0,<4.0
        - psycopg2-binary>=2.8
    7. Save and close the requirements.