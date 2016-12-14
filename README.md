![Django from scratch](https://guides.nanobox.io/assets/quickstart-icons/django.png)

# Django from scratch

Run a Django app locally, install nothing besides nanobox. 

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-django.git

# cd into the django app
cd nanobox-django
```

## Run the app

```bash
# Run django as you would normally, with Nanobox
nanobox run python manage.py runserver 0.0.0.0:8000
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local django.dev
```

Visit your app at <a href="http://django.dev:8000" target="\_blank">django.dev:8000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where python is installed,
python --version

# your packages are available,
pip list

# and your code is mounted
ls
```

## Now What?
For more details about running django apps with nanobox visit [guides.nanobox.io/python/django/](https://guides.nanobox.io/python/django/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
