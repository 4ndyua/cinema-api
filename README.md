# Cinema API
API service for cinema management written on Django REST Framework

## Installing from GitHub
Install PostgresSQL and create db
```
git clone https://github.com/4ndyua/cinema-api.git
cd cinema_API
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py runserver
```
## Run with docker
Docker should be installed
```
docker-compose build
docker-compose up
Getting access
create user on /api/user/register/
get access token on /api/user/token/
```
## Features
- Documentation is located at /api/doc/swagger/
- Managing orders and tickets
- Creating movies with genres, actors
- Creating cinema halls
- Adding movie sessions with associated cinema hall
- Filtering movies and movie sessions
