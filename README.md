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

python manage.py migrate
python manage.py runserver
```


## Link to the Project

[It company task manager project deployed to Render](https://it-manager-project.onrender.com/)

You may use such credentials:

Username: usertest

Password: user12345
