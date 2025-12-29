# UniFeeSync – University Fee Management Backend

Developed a backend service for a restricted-access hostel fee system using Django REST Framework. Implemented JWT-based authentication with tiered user roles, where privileged users manage onboarding through CSV uploads and regular users access their own records securely. Designed APIs around structured data validation and controlled access, keeping the platform usage limited to authorized institutional members.

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
