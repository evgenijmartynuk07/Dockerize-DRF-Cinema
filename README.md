# Cinema API

API service for cinema management written on DRF

## Installing using GitHub

Install PostgresSQL and create your DB

```shell
git clone https://github.com/evgenijmartynuk07/Dockerize-DRF-Cinema.git
cd Dockerize-DRF-Cinema
python -m venv venv

Windows: venv\Scripts\activate
Linux, Unix: source venv/bin/activate

pip install -r requirements.txt

set POSTGRES_HOST=<your db host>
set POSTGRES_DB=<your db name>
set POSTGRES_USER=<your db user>
set POSTGRES_PASSWORD=<your db password>

or you can create .env and set there

python manage.py migrate
python manage.py runserver
```

## Run with Docker

Docker should be installed

```shell
docker-compose build
docker-compose up
```

## Getting Access

Docker should be installed

```shell
Create user -> /api/user/register/
Get access token -> /api/user/token/
```

