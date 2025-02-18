# Blogicum
 Социальная сеть, где люди могут делиться впечатлениями, опытом в путешествиях и в различных других интересах.
## Инструменты|стек
 Были использованы следущие инструменты:
  - python 3.9
  - Django 3.2.16
  - HTML
## Как работать с проектом
 1. создайте и активируйте виртуальное окружение
    python -m venv venv
    source venv/bin/activate # Для Linux/MacOS
    venv\Scripts\activate # Для Windows
 2. обновите и установите все зависимости pip 
    py -m pip install --upgrade pip
    pip install -r requirements.txt 
 3. из директории \blogicum проведите миграции и запустите  проект 
    py manage.py migrate
    py manage.py runserver
## Автор
https://github.com/ilnaral