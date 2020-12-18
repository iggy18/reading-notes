# custom user model

- Django ships with a built-in User model for authentication and if you'd like a basic tutorial on how to implement log in, log out, sign up and so on see the Django Login and Logout tutorial for more.

- However, for a real-world project, the official Django documentation highly recommends using a custom user model instead.

- create and navigate into a dedicated directory called accounts for - our code
- install Django
- make a new Django project called config
- make a new app accounts
- start the local web server.

- `$ cd ~/Desktop`
- `$ mkdir accounts && cd accounts`
- `$ pipenv install django~=3.1.0`
- `$ pipenv shell`
- `(accounts) $ django-admin.py startproject config .`
- `(accounts) $ python manage.py startapp accounts`
- `(accounts) $ python manage.py runserver`

- DO NOT RUN MIGRATE UNTIL AFTER CUSTOM USER MODEL HAS BEEN CREATED

- since you ran startapp you should the user model to the installed apps in the settings folder.

- import abstract user and add a custom user class to the models file.

- touch a forms.py file

- then update admin.py with your customuseradmin class.