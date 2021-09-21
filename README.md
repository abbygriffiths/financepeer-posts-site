# Posts App

A simple posts application that uses the Django User authentication framework to implement login and registration.
Allows users to post simple text posts.

# Requirement
- Python 3
- Django

# Steps to Deploy
- `git clone` the repository to your local machine
- Run `python manage.py makemigrations` followed by `python manage.py migrate` to create database tables
- From the root directory of the project, run `python manage.py runserver`
- Navigate to URL `http://localhost:8000` to see the app

# Routes
- `/`
    - Root page. Shows all the existing 
- `/accounts/register`
    - Form to sign up a new user account
- `/post/:id:/`
    - Detailed view of post id *:id:*
- `/user/:username`
    - Get all posts created by user *:username:*
- `/admin`
    - HACK: Django admin panel. Currently only way of adding posts :/

# Caveats
- FIXME: Adding posts requires going into admin panel
- TODO: Uploading posts as JSON 
- No React.js yet ;-;