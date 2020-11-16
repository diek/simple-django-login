## What's this repository about?  

An updated version of Vitor Freitas' Django login Example [How to Use Django's Built-in Login System](https://simpleisbetterthancomplex.com/tutorial/2016/06/27/how-to-use-djangos-built-in-login-system.html) at [simpleisbetterthancomplex.com](https://simpleisbetterthancomplex.com).  


## Run this project locally 

### 1. Clone the repository:  

    git clone git@github.com:diek/simple-django-login.git  

### 2. CD into simple-django-login 

### 3. Create and Activate a Venv (for Windows - see Python documentation):  

    python3 -m venv _env  
    source _env/bin/activate  

### 4. Pip install Django and other requirements:  

    (_env)$ pip install --upgrade pip
    (_env)$ pip install -r requirements 


### 5. Rename sample.env to .env 

### 6. Generate a SECRET_KEY and copy/paste to .env
    Run the Django shell:  
    `(_env)$ python3 manage.py shell`  
    `>>> from django.core.management import utils`  
    `>>> utils.get_random_secret_key()`  
    `'83^(ny%q89b5q^r955^!d*lw*pv0t*5-qoiwa1q+d2@+n7nlm@'`  
    

### 3.Run migrations(makemigrations not needed because there are no apps):  

    python manage.py migrate  

### 3. Create a user:

    python manage.py createsuperuser

### 4. Run the server:

    python manage.py runserver

### 5. And open 127.0.0.1:8000/login in your web browser.

