# oauth_backend

Basic backend to allow users to login with Google account. Uses Django Web Framework for backend, MongoDB for DB stack, and django-allauth for login implementation via Google account.

## Getting Started

The setup assumes that MongoDB and Python has been preinstalled on the system, alongside the virtualenv package.
After cloning the repo, set up a Python `virtualenv` , activate and run the following script:

`python -m pip install -r requirements.txt`

to install the required Python packages.

Afterwards, run Django migrations and start the server:

```
python .\manage.py migrate
python .\manage.py runserver
```
Login interface can be accessed from `localhost:8000`, by default.
