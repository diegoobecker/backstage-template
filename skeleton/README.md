##{{cookiecutter.destination.repo}}

### A simple Python application with [Flask](https://flask.palletsprojects.com/en/2.0.x/quickstart/#a-minimal-application) and running with [Docker](https://docs.docker.com/language/python/)

#### To run this example, follow the below steps:

```bash
git clone {{"https://" + cookiecutter.destination.host + "/" + cookiecutter.destination.owner + "/" + cookiecutter.destination.repo}}
cd {{cookiecutter.destination.repo}}
docker-compose up
```
