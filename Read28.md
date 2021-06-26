# API Deployment

### django-environ

Environment variables are the perfect place to store settings. This app gives a well-functioning API for reading values from environment variables or text files, handful type conversion.

### What is API deployment?

- Frameworks can be used to deploy data APIs from CSVs and databases, content from documents, or custom code resources that allow access to more complex objects. An API proxy does not deploy an API, but can take existing SOAP or XML- RPC resources and transform them into more common RESTful APIs with JSON formats.

### How do I deploy a Python API?

**Assuming that Python and Pip are installed in your machine, lets start by creating a application folder, I call it is python-service-deployment.**

    - Step 1: Virtual Environment 
    - Step 2: Configure python Interpreter 
    - Step 3: Flask-RESTful 
    - Step 4: Build REST API
    - Step 5: Make it Heroku ready and deploy

### Django Settings: Best practices

- Keep settings in environment variables.
- Write default values for production configuration (excluding secret keys and tokens).
- Don’t hardcode sensitive settings, and don’t put them in VCS.
- Split settings into groups: Django, third-party, project.
- Follow naming conventions for custom (project) settings.

