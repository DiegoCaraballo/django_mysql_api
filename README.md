# Example Rest API with Django and MySql

### GET, POST, PUT and DELETE of Companies

#### Database Configuration

In settings.py:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'HOST': 'localhost', # Your server, in my case localhost
        'PORT': '3306',
        'USER': 'user',
        'PASSWORD': 'password',
        'NAME': 'django_api', # DataBase name
        'OPTIONS': {
            'init_command': "SET sql_mode='STRICT_TRANS_TABLES'"
        }
    }
}
```