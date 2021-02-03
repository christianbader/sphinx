# Mycelia documentation

## Requirements

- Python 3.8

## Setup

It's recommended to create a virtualenv inside the project folder:

    $ python -m venv env
    $ source env/bin/activate

Make sure **pip** and **wheel** are up to date:

    $ (env) python -m pip install -U pip wheel
    $ (env) pip install -r requirements.txt

## Build the docs:

    $ (env) make html
