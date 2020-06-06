# Paytm Payment-Gateway
The process of sending request to the gateway and callback/response of transaction.

<strong>NOTE : Paytm Merchant Account is required.</strong>

    - Paytm Merchant-ID and Paytm Secret-ID is to be added in settings.py

## Steps to install and run in local system:-
* Create a virtual environment ```$python3 -m venv <env_name>```
* Activate virtual environment ```$source <env_name>/bin/activate```
* Install requirements in venv ```$pip install -r requirements.txt```
* Make migrations ```$python manage.py makemigrations```
* Apply migrations ```$python manage.py migrate```
* Create a superuser ```$python manage.py createsuperuser```
* Run the server ```$python manage.py runserver```