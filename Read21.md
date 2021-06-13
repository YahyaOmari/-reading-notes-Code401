# Django Models

### What is Django Models?
- Django model is the built-in feature that Django uses to create tables, their fields, and various constraints. In short, Django Models is the SQL of Database one uses with Django.

### Why we use models in Django?
- Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms

### How do Django models work?
- Django's models provide an Object-relational Mapping (ORM) to the underlying database. When you create a model, Django executes SQL to create a corresponding table in the database  without you having to write a single line of SQL. Django prefixes the table name with the name of your Django application.

### Model Primer

- Models are usually defined in an application’s models.py file.

- They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata.