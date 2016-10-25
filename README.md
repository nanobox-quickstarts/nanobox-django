# Django with Nanobox
This is the companion application for the [Django: Getting Started](https://guides.nanobox.io/python/django/) guide on [guides.nanobox.io](https://guides.nanobox.io) and is pre-configured and ready to run with [nanobox](https://nanobox.io/)!

## Up and Running

``` bash

# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-django.git

# cd into the django app
cd nanobox-django

# start the dev environment
nanobox dev start

# add a convenient way to access your app from the browser
nanobox dev dns add django.nanobox.dev

# console into the dev environment
nanobox dev console

# run the application
python manage.py runserver 0.0.0.0:8080
```

Visit the app from your favorite browser at: `django.nanobox.dev:8080`

## Now What?
For more details about how this works or for more advanced topics related to running Django applications with nanobox visit [guides.nanobox.io/python/django/](https://guides.nanobox.io/python/django/)
