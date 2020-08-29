# Basic Django application


## Functionality

- Log in
    - via username & password
    - via email & password
    - via email or username & password
    - with a remember me checkbox (optional)
- Create an account
- Log out
- Profile activation via email
- Reset password
- Remind a username
- Resend an activation code
- Change password
- Change email
- Change profile
- Multilingual: English, Russian, and Simplified Chinese


## Set & Run the project:

### Install dependencies:

```
pip install -r requirements.txt
```


### Configure the settings:

1. Edit `app/conf/development/settings.py` if you want to develop the project.

2. Edit `app/conf/production/settings.py` if you want to run the project in production.

### Apply migrations

```
python manage.py migrate
```

### Collect static files (only on a production server)

```
python manage.py collectstatic
```

### Running

#### A development server

```
python manage.py runserver
```

### Linting:

```
make lint
```
