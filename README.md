Ладыгина Анастасия Александровна ИД22-2
Блогикум, задание на проверку

Как запустить проект 

1. Создать виртуальное окружение 
`python -m venv venv`
`source venv/Scripts/activate`

2. Скачивание библиотек 

`pip install --upgrade --no-cache-dir Pillow`
`pip install -r requirements.txt`

3. Загрузка исходных данных

`cd blogicum`
`python manage.py migrate`
`python manage.py loaddata ../db.json`
`python manage.py runserver`

