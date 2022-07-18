# locallibrary
Mozilla Django Tutorial

https://agile-badlands-17432.herokuapp.com/catalog/

## Dev Setup
* `brew install poetry postgres`
* `poetry init`
* `poetry add Django`
* `ssh-keygen -t rsa -b 2048`
* `git config --global user.name "dylanndo"\ngit config --global user.email "dylan2002do@yahoo.com"`

## Run
```bash
poetry install
poetry shell
which python
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
## Heroku Notes
```bash
poetry export --without-hashes -f requirements.txt --output requirements.txt
git push heroku main
heroku run python  manage.py migrate
heroku run python manage.py createsuperuser
```

add 'agile-badlands-17432.herokuapp.com' to ALLOWED_HOSTS in settings.py