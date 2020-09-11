# food-delivery-web-app-django
> Food Delivery Website built with django
## Installation:

**1.Clone Repo**
```sh
git clone https://github.com/oussama-seme-elayne/food-delivery-web-app-django.git
```
**2.Setup Virtualenv**
```sh
virtualenv env
source env/bin/activate
```
**3.Install Requirements**
```sh
cd requirements.txt
pip install -r requirements.txt
```
**4.Migrate Database**
```sh
python manage.py makemigrations
python manage.py migrate
```
**5.Create User**
```sh
python manage.py createsuperuser
```
**6.Run Server**
```sh
python manage.py runserver
