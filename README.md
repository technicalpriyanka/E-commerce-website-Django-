# E-commerce-website-Django-
An e-commerce website is a digital platform designed to facilitate the buying and selling of goods and services online. It allows businesses to showcase their products, manage inventory, and provide a seamless shopping experience to customers

Steps to buils e cpmmerce website:

Step 1: Install virtualenv
pip install virtualenv 
python -m virtualenv venv
venv\Scripts\activate
deactivate
python --version

Step 2: Start project with Django
pip install django
django-admin startproject shopping

Step 3:create file urls.py and views.py to catch the request
can pass the response from HttpResponse

Step 4: Serve html page
create html page and data into it.

Step 5: Create Superuser
python manage.py create superuser 
python manage.py makemigrations
python manage.py migrate
and set the credentials username, email and password

Step 6: Create product models and category products
get product in admin cart
