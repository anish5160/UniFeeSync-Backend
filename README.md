# UniFeeSync – University Fee Management Backend

A backend service built with Django REST Framework to manage student fee data, authentication, password resets, and CSV-based bulk uploads.

## Requirements
- Python 3.10+
- pip
- virtualenv (optional)

## Setup & Run

# clone the project
git clone https://github.com/anish5160/UniFeeSync-Backend.git
cd UniFeeSync-Backend/src

# create and activate virtual environment (optional but recommended)
python3 -m venv .venv
source .venv/bin/activate    # for mac/linux
# or .venv\Scripts\activate  # for windows

# install dependencies
pip install django djangorestframework

# run migrations
python3 manage.py migrate

# start development server
python3 manage.py runserver
