# wisdompets
This is a python project built using django framework.

## Files-Do NOT Edit: 
### manage.py
* Runs commands.

### wisdompets/__init__.py
* Tells Python that the folder contains Python files.

### wisdompets/wsgi.py
* Provides a hook for web servers.

## Files-DO Edit: 
### wisdompets/settings.py
* Configures Django.

### wisdompets/urls.py
* Routes requests based on URL.

## To run in local server
* run `python3 manage.py runserver` on root directory. 

## To create a Django app in your Django project
* run `python3 manage.py startapp <nameofyourapp>` on root directory.

## Pieces of a Django App
![Pieces of App](/readme_img/pofapp.png)

## To make Django migrations
* run `python3 manage.py makemigrations` to migrate your created models **!Important**
* Note that you have to put your app in `INSTALLED_APPS = ['appname.apps.AppnameConfig', ...]` <-- like this. 

## To show all Django migrations
* run `python3 manage.py showmigrations`.

## To apply made Django migrations
* run `python3 manage.py migrate`

## To create superuser (admin)
* first navigate to admin.py under your app --> import your model .. see adoptions/admin.py
* run `python3 manage.py createsuperuser`.

## To open interactive python shell with Django initialized
* run `python3 manage.py shell`.

