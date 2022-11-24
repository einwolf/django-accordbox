# Django with react

Setup Webpack Project with Django

https://python-webpack-boilerplate.rtfd.io/

https://www.accordbox.com/blog/definitive-guide-django-and-webpack/

## Django commands

```bash
# Django setup
django-admin startproject djaccord
python manage.py webpack_init
# Use default of [frontend]

# Django dev
python manage.py migrate
python manage.py runserver 0.0.0.0:8000
```

## Nodejs commands

```bash
# Nodejs setup
# Install npm into frontend directory
cd djaccord/frontend
npm install

# Run nodejs in watch mode
npm run watch
```

## Django urls

http://127.0.0.1:8000/

## Nodejs urls

http://127.0.0.1:8080/
