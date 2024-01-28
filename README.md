# Django User Management App

## Overview

This Django User Management app is designed to practice using Django custom forms, Django built-in authorization forms, and model creation forms. The app utilizes Django version 5.0.1 and PostgreSQL as the database.

## Features

### Default User Group

- When a user is created, they automatically become a member of the default group.
- Members in the default user group can:
  - View all posts
  - Create posts
  - Delete their own posts

### Moderator (Mod) Group

- Users can be promoted by the admin to the Moderator group.
- Members of the Moderator group inherit all permissions from the default group.
- Additionally, members of the Moderator group can:
  - Delete other users' posts

### Admin Group

- Admins have all the permissions of the Moderator group.
- Admins can also:
  - Ban users

## Installation

1. Make sure you have Python and Django installed.
2. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-django-user-management-app.git

## OR

1. Install dependencies:


2. pip install -r requirements.txt
   Apply migrations:

3. python manage.py migrate
    Run the development server:

4. python manage.py runserver
    Access the app at http://localhost:8000/


## Usage
1. Create a new user through the registration process.
2. The new user is automatically added to the default group.
3. Admins can promote users to the Moderator group.
4. Admins can also perform actions like banning users.

## Technologies Used
Django 5.0.1
PostgreSQL
Contribution
Feel free to contribute by submitting issues or pull requests. Follow the standard GitHub workflow.

License
This project is licensed under the MIT License.