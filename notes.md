

#### notes

```bash
# build a runtime
nanobox build

# deploy the runtime into the dev environment
nanobox dev deploy

# console into the dev environment
nanobox dev console

# install django
pip install Django

# freeze the pip modules into the requirements.txt
pip freeze > requirements.txt

# generate a django project

# cd into into a tmp dir
cd tmp

# generate the project
django-admin startproject myapp

# cd back into the app dir
cd -

# copy the generated app into our codebase
cp -a /tmp/myapp/* .

# modify sqlite db location (myapp/settings.py)
# os.path.join(BASE_DIR, 'src/db.sqlite3')

# run the development server
python manage.py runserver 0.0.0.0:8080

```
