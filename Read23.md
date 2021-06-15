# Django Custom User

### Should you create a custom user model in Django?

- It's highly recommended to set up a custom User model when starting a new Django project. Without it, you will need to create another model (like UserProfile ) and link it to the Django User model with a OneToOneField if you want to add new fields to the User model.

### How do I create a custom user in Django?

1. Create a new app. This will hold your custom user model.
2. Create the Custom User Model in models.py.
3. Create the User model manager.
4. Update settings module (settings.py ):
5. Create the Forms for Register, Change, and Admin-Level 
6. Create.
7. Update the Django Admin.
8. Challenge.

### How do I authenticate a custom user in Django?

- Authentication backends provide an extensible system for when a username and password stored with the user model need to be authenticated against a different service than Django's default. You can give your models custom permissions that can be checked through Django's authorization system.