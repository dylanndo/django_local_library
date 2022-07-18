# locallibrary
Mozilla Django Tutorial

## Dev Setup
* `brew install poetry`
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
