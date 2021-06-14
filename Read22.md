# Django CRUD and Forms

### How do you get crud in Django?
**To create a Django application that performs CRUD operations, follow the following steps.**
1. Create a Project. $ django-admin startproject crudexample.
2. Create an App. $ python3 manage.py startapp employee. 
3. Project Structure. 
4. Database Setup. 
5. Create a Model. 
6. Create a ModelForm.
7. Create View Functions.
8. Provide Routing.

### What is CRUD operations Django?

**CRUD can be best explained as an approach to building a Django web application. In general CRUD means performing Create, Retrieve, Update and Delete operations on a table in a database. Let's discuss what actually CRUD means ..**
  
- Create – create or add new entries in a table in the database. 

- Retrieve – read, retrieve, search, or view existing entries as a list(List View) or retrieve a particular entry in detail (Detail View)
- Update – update or edit existing entries in a table in the database
- Delete – delete, deactivate, or remove existing entries in a table in the database

### HTML Forms

- The form is defined in HTML as a collection of elements inside <form>...</form> tags, containing at least one input element of type="submit".

"form action="/team_name_url/" method="post"

    <label for="team_name">Enter name: </label>
    <input id="team_name" type="text" name="name_field" value="Default name for team.">
    <input type="submit" value="OK">
"/form"

- action: The resource/URL where data is to be sent for processing when the form is submitted. If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.

- method: The HTTP method used to send the data: post or get.

1. The POST method should always be used if the data is going to result in a change to the server’s database because this can be made more resistant to cross-site forgery request attacks.
2. The GET method should only be used for forms that don’t change user data (e.g. a search form). It is recommended for when you want to be able to bookmark or share the URL.
