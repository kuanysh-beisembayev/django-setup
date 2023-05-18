# django-setup

###### Build
```bash
docker-compose build
```

###### Run
```bash
docker-compose up
```

###### Migrate
```bash
docker-compose run django python manage.py migrate
```

###### Make migrations
```bash
docker-compose run django python manage.py makemigrations
```

###### Flake8
```bash
docker-compose run django flake8
```

###### List images
```bash
docker image ls
```

###### List containers
```bash
docker ps
```
