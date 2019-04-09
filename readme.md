## About This Example

The example is following this tutorial:-
[http://v1k45.com/blog/modern-django-part-1-setting-up-django-and-react](http://v1k45.com/blog/modern-django-part-1-setting-up-django-and-react)

## How to setup Dev environment

Start react at localhost:3000
-> cd django-react
-> cd frontend
-> npm install
-> npm start

Start dango to read react at localhost:3000
-> cd django-react
-> python3 -m venv venv
-> . venv/bin/activate
-> pip3 install -r requirements.txt
-> python manage.py runserver

## How to setup Production environment
react build
-> cd django-react
-> cd frontend
-> npm install
-> npm run build

Start dango to read react build
-> cd django-react
-> python3 -m venv venv
-> . venv/bin/activate
-> pip3 install -r requirements.txt
-> python manage.py runserver --settings=ponynote.production_settings