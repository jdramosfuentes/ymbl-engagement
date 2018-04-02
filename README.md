# ymbl-engagement
Engagement application for YMBL Austin members

## Setting up the environment
1. Clone this repository - `git clone https://github.com/jdramosfuentes/ymbl-engagement.git`
2. Install virtualenv - `pip install virtualenv`
...We use `virtualenv` to isolate Python environments and libraries
3. Create a new virtual environment - `virtualenv venv` 
4. Install dependencies - `pip install django`, `pip install djangorestframework`
5. Run migrations - `python manage.py migrate`