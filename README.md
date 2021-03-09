# python-recipe-app-api

**Releases:** 
- https://pypi.org/project/Django/

- SOURCE: https://docs.docker.com/compose/django/

- **Create the Django project:** <br />
docker-compose run web django-admin startproject composeexample . <br />

- **Edit** the *composeexample/settings.py* file: <br />

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```

- **Run**: <br />
docker-compose up <br />
