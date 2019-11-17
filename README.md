# django-whale
A Djanjo stack docker image. 

### To install an app: 
`docker-compose run web django-admin startproject <nameOfProjectRoot> .`

### Updates: 
Replace in `<root>/settings.py`: 
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```
