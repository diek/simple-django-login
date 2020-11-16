## What's this repository about?  

An updated version of Vitor Freitas' Django login Example [How to Use Django's Built-in Login System](https://simpleisbetterthancomplex.com/tutorial/2016/06/27/how-to-use-djangos-built-in-login-system.html) at [simpleisbetterthancomplex.com](https://simpleisbetterthancomplex.com).  


## How do I run this project locally?  

### 1. Clone the repository:  

    git clone git@github.com:diek/simple-django-login.git  

### 2. Run migrations(makemigrations is not needed because there are no apps:  

    python manage.py migrate  

### 3. Create a user:

    python manage.py createsuperuser

### 4. Run the server:

    python manage.py runserver

### 5. And open 127.0.0.1:8000/login in your web browser.

