# DRF Backend API
> Django Rest framework backend API server which has to implement Celery and Docker.

## Setup

The following steps will walk you thru installation on a Mac. Linux should be similar.
It's also possible to develop on a Windows machine, but I have not documented the steps.
If you've developed Django apps on Windows, you should have little problem getting
up and running.

### Dependancies
###### Prerequisites

- Python 3.8.9 
- PostgreSQL 13.2
- Django 3.2
- Docker

Then you will go to config folder and rename `db_config.sample` to `db_config.py`

Create virtualenv in your system then follow the commends:
```` virtualenv venv --python=python3.8 ````

If you successfully create the virtualenv then activate:
```source venv/bin/activate```


After that you may run `requirements.txt` file following the command:
```angular2html
pip install -r requirements.txt
./manage.py migrate
./manage.py runserver
```

##### If you run the the project Docker, please follow the instructions in this self-learning guide.
```base
docker-compose run drfbackend
docker-compose build
docker-compose up
```

There are two branch here.

```
git branch
```
* Master
* ModelsRelationShip-API
