# Django-boilerplate

## Steps for setup:-
1. Clone this repo.
2. Create virtual environment outside the folder.
    ```python3.7 -m venv env```
    ```source env/bin/activate```
3. Install all the required python modules.
    ```pip install -r requirements.txt```
4. Rename the project name.
5. Files that need to changed if project is renamed.
    ```
        ./django-boilerplate/django-boilerplate/settings.py
                                               /asgi.py
                                               /wsgi.py
                                               /urls.py
        ./django-boilerplate/manage.py
    ```
 6. ```python manage.py makemigrations```
 7. ```python manage.py migrate```
 8. ```python manage.py runserver```
